<p id="demo"></p>

<script>
var i = 0;
var txt = 'Hi, i make things go check my website, k thx bye';
var speed = 50;

function typeWriter() {
  if (i < txt.length) {
    document.getElementById("demo").innerHTML += txt.charAt(i);
    i++;
    setTimeout(typeWriter, speed);
  }
}
</script>