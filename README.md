
Chats
Archived
html css love proposal webpage
5 hours ago
HTML Love Letter Website
5 hours ago
HTML Love Letter Website
5 hours ago
Romantic HTML Page for Yeni
6 hours ago
HTML Love Letter Website Design
6 hours ago
HTML and CSS for Personal Webpage
6 hours ago
<!DOCTYPE html> <html lang="id"> <head> <meta charset="UTF-8"> <meta name="viewport" content="width=device-width, initial-scale=1.0"> <title>Untuk Yeni 💍</title> <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet"> <style> body { font-family: 'Poppins', sans-serif; background: linear-gradient(135deg, #ffd6e0, #ffeaea); margin: 0; padding: 0; display: flex; flex-direction: column; justify-content: center; align-items: center; height: 100vh; text-align: center; color: #333; transition: all 0.5s ease-in-out; }
h1 {
  font-size: 2.5rem;
  color: #ff4d6d;
  margin-bottom: 30px;
  animation: fadeIn 1s ease-in-out;
}
.button-group {
  display: flex;
  gap: 20px;
}
button {
  padding: 15px 30px;
  font-size: 1.2rem;
  border: none;
  border-radius: 30px;
  cursor: pointer;
  transition: all 0.3s;
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.15);
}
#yesBtn {
  background-color: #ff6b81;
  color: white;
}
#noBtn {
  background-color: #a29bfe;
  color: white;
  position: relative;
}
button:hover {
  transform: scale(1.1);
}
.shake {
  animation: shake 0.4s;
}
.bounce {
  animation: bounce 0.5s ease;
}
@keyframes shake {
  0% { transform: translate(0, 0); }
  25% { transform: translate(5px, 5px); }
  50% { transform: translate(-5px, -5px); }
  75% { transform: translate(5px, -5px); }
  100% { transform: translate(0, 0); }
}
@keyframes bounce {
  0% { transform: scale(1); }
  50% { transform: scale(1.3); }
  100% { transform: scale(1); }
}
@keyframes fadeIn {
  from { opacity: 0; }
  to { opacity: 1; }
}
.page2 {
  background: linear-gradient(135deg, #ffd6e0, #ffeaea);
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  height: 100vh;
  padding: 20px;
  animation: fadeIn 1s ease-in-out;
}
.page2 h1 {
  font-size: 2.2rem;
  color: #ff4d6d;
  margin-bottom: 20px;
}
.page2 p {
  font-size: 1.1rem;
  max-width: 600px;
  line-height: 1.7;
  color: #444;
  margin-bottom: 10px;
}
.page2 img {
  width: 150px;
  height: 150px;
  border-radius: 50%;
  object-fit: cover;
  margin-bottom: 20px;
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.2);
}
</style> </head> <body> <h1>Apakah kamu mau menikah denganku?</h1> <div class="button-group"> <button id="yesBtn" onclick="animateYes()">Saya Mau 🤍</button> <button id="noBtn" onclick="moveButton()">Tidak Mau 💔</button> </div>
<audio id="clickSound" src="https://www.soundjay.com/buttons/sounds/button-16.mp3"></audio>
<audio id="backgroundMusic" src="https://www.bensound.com/bensound-music/bensound-sunny.mp3" autoplay loop></audio>

<script> const noBtn = document.getElementById('noBtn'); const yesBtn = document.getElementById('yesBtn'); const clickSound = document.getElementById('clickSound'); function moveButton() { const maxX = window.innerWidth - noBtn.offsetWidth - 20; const maxY = window.innerHeight - noBtn.offsetHeight - 20; const randomX = Math.random() * maxX; const randomY = Math.random() * maxY; noBtn.style.position = 'absolute'; noBtn.style.left = `${randomX}px`; noBtn.style.top = `${randomY}px`; clickSound.play(); noBtn.classList.add('shake'); setTimeout(() => { noBtn.classList.remove('shake'); }, 400); } function animateYes() { yesBtn.classList.add('bounce'); setTimeout(() => { goToPage2(); }, 500); } function goToPage2() { document.body.innerHTML = ` <div class="page2"> <img src="https://via.placeholder.com/150" alt="Foto Kamu"> <h1>HORRE! TUKANG MARAH JADI ISTRIKU 💍</h1> <p>Jangan marah-marah lagi ya sayang 💖</p> <p>Dalam tawa, dalam canda,<br> Dalam sedih, dalam suka,<br> Kamu selalu ada, Yeni tercinta,<br> Menjadi bagian hidupku selamanya.</p> <p>Bersamamu adalah bahagia,<br> Menikahimu adalah doa,<br> Yuk jalani hidup bersama,<br> Tanpa marah, hanya cinta 💞</p> <audio autoplay loop> <source src="https://www.bensound.com/bensound-music/bensound-love.mp3" type="audio/mpeg"> </audio> </div>`; } </script> </body> </html>function goToPage2() {
document.body.innerHTML = `
<div class="page2">
<img src="IMG-20250619-WA0035_1750737271743.jpg" alt="Foto Kamu">
...
