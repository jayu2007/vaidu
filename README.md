# vaidu
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Happy Girlfriend's Day ❤️</title>

<link rel="stylesheet" href="style.css">

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&family=Dancing+Script:wght@700&display=swap" rel="stylesheet">
</head>

<body>

<div class="hearts"></div>

<section id="home">

<h1>Happy Girlfriend's Day ❤️</h1>

<h2>To My Beautiful Vaidu</h2>

<p class="subtitle">
Distance means so little when someone means so much.
</p>

<button id="openBtn">
Open My Heart 💌
</button>

</section>

<section id="letter" class="hidden">

<h1>My Love Letter</h1>

<div class="card">

<p>

Dear Vaidu ❤️,

Happy Girlfriend's Day.

Thank you for being the best part of my life.

No matter how far apart we are, you'll always have the biggest place in my heart.

Every picture with you is my favorite memory.

Every call with you becomes my favorite moment.

Every day with you is a blessing.

I don't know what tomorrow brings.

But I know one thing.

I want every tomorrow with you.

Thank you for loving me.

Thank you for staying.

Thank you for being YOU.

Forever Yours,

<b>Jayu ❤️</b>

</p>

</div>

<button id="galleryBtn">
Our Memories 📸
</button>

</section>

<section id="gallery" class="hidden">

<h1>Our Beautiful Memories ❤️</h1>

<div class="slider">

<img src="images/1.jpg">

<img src="images/2.jpg">

<img src="images/3.jpg">

<img src="images/4.jpg">

<img src="images/5.jpg">

<img src="images/6.jpg">

<img src="images/7.jpg">

<img src="images/8.jpg">

</div>

<button id="reasonBtn">
Why I Love You ❤️
</button>

</section>

<section id="reasons" class="hidden">

<h1>Reasons Why I Love You ❤️</h1>

<div class="grid">

<div class="box">❤️ Your smile</div>

<div class="box">🌸 Your kindness</div>

<div class="box">✨ Your love</div>

<div class="box">💖 Your cute face</div>

<div class="box">🌷 Your support</div>

<div class="box">🫂 You always make me happy</div>

<div class="box">🌹 You're my safe place</div>

<div class="box">♾️ I choose you forever</div>

</div>

<button id="countBtn">
Countdown ⏳
</button>

</section>

<section id="countdown" class="hidden">

<h1>Our Anniversary</h1>

<h2>17 May ❤️</h2>

<div id="timer"></div>

<a href="https://open.spotify.com/track/5XeFesFbtLpXzIVDNQP22n?si=-seWk-DIRKOZpUUmZnR1ng&utm_source=copy-link"
target="_blank">

<button>

🎵 Play Our Song

</button>

</a>

<button id="finalBtn">

Final Surprise ❤️

</button>

</section>

<section id="end" class="hidden">

<h1>

Forever & Always ❤️

</h1>

<p>

No matter how many miles separate us...

You'll always be my home.

Happy Girlfriend's Day

My Beautiful Vaidu ❤️

Love You Forever

<b>Jayu ❤️</b>

</p>

</section>

<script src="script.js"></script>

</body>

</html>
*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:'Poppins',sans-serif;
scroll-behavior:smooth;
}

body{
background:linear-gradient(135deg,#ffd6e8,#ffeaf4,#fff);
overflow-x:hidden;
color:#333;
}

section{
min-height:100vh;
display:flex;
flex-direction:column;
justify-content:center;
align-items:center;
padding:40px 20px;
text-align:center;
transition:.8s;
}

.hidden{
display:none;
}

h1{
font-family:'Dancing Script',cursive;
font-size:3rem;
color:#ff2d75;
margin-bottom:20px;
}

h2{
font-size:1.7rem;
margin-bottom:15px;
}

.subtitle{
max-width:650px;
font-size:1.1rem;
line-height:1.8;
margin-bottom:30px;
}

button{
background:#ff2d75;
color:white;
border:none;
padding:16px 35px;
font-size:18px;
border-radius:50px;
cursor:pointer;
transition:.3s;
box-shadow:0 10px 25px rgba(255,45,117,.3);
margin-top:25px;
}

button:hover{
transform:translateY(-4px) scale(1.05);
background:#ff0f63;
}

.card{
max-width:800px;
background:white;
padding:35px;
border-radius:25px;
box-shadow:0 15px 40px rgba(0,0,0,.12);
line-height:2;
font-size:18px;
}

.slider{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(230px,1fr));
gap:20px;
width:100%;
max-width:1100px;
margin-top:30px;
}

.slider img{
width:100%;
height:300px;
object-fit:cover;
border-radius:20px;
box-shadow:0 10px 30px rgba(0,0,0,.18);
transition:.35s;
}

.slider img:hover{
transform:scale(1.05);
}

.grid{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(240px,1fr));
gap:20px;
width:100%;
max-width:1000px;
margin-top:35px;
}

.box{
background:white;
padding:25px;
border-radius:20px;
font-size:18px;
font-weight:600;
box-shadow:0 10px 25px rgba(0,0,0,.1);
transition:.35s;
cursor:pointer;
}

.box:hover{
background:#ff2d75;
color:white;
transform:translateY(-6px);
}

#timer{
font-size:2.6rem;
font-weight:bold;
margin:35px 0;
color:#ff2d75;
}

.hearts{
position:fixed;
left:0;
top:0;
width:100%;
height:100%;
pointer-events:none;
overflow:hidden;
z-index:-1;
}

.hearts span{
position:absolute;
bottom:-30px;
font-size:24px;
animation:float 10s linear infinite;
opacity:.75;
}

@keyframes float{

0%{
transform:translateY(0) rotate(0deg);
opacity:0;
}

10%{
opacity:1;
}

100%{
transform:translateY(-120vh) rotate(360deg);
opacity:0;
}

}

#end{
background:linear-gradient(135deg,#ff8eb7,#ffc5dd,#fff0f7);
}

#end p{
max-width:700px;
font-size:22px;
line-height:2;
background:white;
padding:35px;
border-radius:25px;
box-shadow:0 10px 35px rgba(0,0,0,.12);
}

a{
text-decoration:none;
}

@media(max-width:768px){

h1{
font-size:2.3rem;
}

h2{
font-size:1.3rem;
}

.card{
padding:25px;
font-size:16px;
}

button{
width:90%;
}

.slider img{
height:250px;
}

#timer{
font-size:2rem;
}

}