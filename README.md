<h1>🤠 Добро пожаловать на мой ковбойский сайт</h1>

<button onclick="shoot()">🔫 выстрелить</button>

<br><br>

<img 
  id="cowboyGif"
  src="https://media0.giphy.com/media/v1.Y2lkPTZjMDliOTUydWF3bmszY3JjNWk5bzBiYm84b2R2Z3ZhZzF1bjl3eDZtdzh4eXJwZCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/aqDXCH2M1ycEw/giphy.gif"
  style="display:none; max-width:400px;"
  alt="Стреляющий ковбой"
/>

<script>
function shoot() {
  const gif = document.getElementById("cowboyGif");

  // перезапуск гифки каждый раз
  gif.style.display = "none";
  gif.offsetHeight; 
  gif.style.display = "block";
}
</script>
