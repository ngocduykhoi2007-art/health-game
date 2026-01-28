<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Health Reading Game</title>
<link href="https://fonts.googleapis.com/css2?family=Poppins&display=swap" rel="stylesheet">

<style>
body{
  font-family:Poppins,sans-serif;
  background:#f4f7fb;
  margin:0;
  padding:20px;
}

/* ===== HERO ===== */
.hero{
  background-image:url("https://images.unsplash.com/photo-1505751172876-fa1923c5c528");
  background-size:cover;
  background-position:center;
  border-radius:18px;
  padding:50px 20px;
  margin-bottom:30px;
  text-align:center;
  position:relative;
  box-shadow:0 15px 30px rgba(0,0,0,.25);
}
.hero::before{
  content:"";
  position:absolute;
  inset:0;
  background:rgba(0,0,0,0.55);
  border-radius:18px;
}
.hero h1,.hero p{position:relative;z-index:1}
.hero h1{
  font-size:38px;
  color:#ffeaa7;
  text-shadow:0 4px 8px rgba(0,0,0,.9);
}
.hero p{color:#ecf0f1;font-size:18px}

/* ===== LAYOUT ===== */
.container{
  display:flex;
  gap:20px;
  max-width:1300px;
  margin:auto;
}

.card{
  background:#fff;
  border-radius:14px;
  box-shadow:0 10px 25px rgba(0,0,0,.08);
  padding:22px;
}

/* ===== READING (TO HƠN) ===== */
.reading{
  width:60%;
  height:85vh;
  overflow-y:auto;
  line-height:1.8;
  font-size:16px;
}
.reading p{margin-bottom:16px}

.quiz{width:40%}

.highlight{
  background:#fff3a0;
  padding:2px 4px;
  border-radius:4px;
}

/* ===== QUIZ ===== */
.progress{
  height:10px;
  background:#ddd;
  border-radius:10px;
  overflow:hidden;
  margin-bottom:15px;
}
.progress-bar{
  height:100%;
  width:0%;
  background:#3498db;
}

.option{
  background:#ecf0f1;
  padding:10px;
  border-radius:8px;
  margin-bottom:10px;
}

input[type=text]{
  width:100%;
  padding:8px;
  border-radius:6px;
  border:1px solid #ccc;
}

button{
  background:#2980b9;
  color:#fff;
  border:none;
  border-radius:8px;
  padding:10px 20px;
  font-size:16px;
  cursor:pointer;
  margin-right:10px;
}
button:disabled{background:#bdc3c7}

.feedback{font-weight:bold;margin-top:10px}
.correct{color:#27ae60}
.wrong{color:#e74c3c}
.explain{
  margin-top:8px;
  background:#f0f6ff;
  padding:10px;
  border-radius:8px;
  font-size:14px;
}
</style>
</head>

<body>

<div class="hero">
  <h1>🌍 Health Around the World</h1>
  <p>Reading Comprehension Game – MCQ & Fill in the Blanks</p>
</div>

<div class="container">

<!-- ===== READING (6 ĐOẠN) ===== -->
<div class="card reading">
<h3>The Unhealthiest and Healthiest Countries in the World (Summary)</h3>

<p id="p1">
Different studies measure how healthy countries are in different ways, which often leads to very different results.
According to a study by Clinic Compare, the Czech Republic is ranked as the unhealthiest country in the world.
This ranking is based on high levels of alcohol and tobacco consumption and obesity.
Many of the unhealthiest countries are in Eastern Europe, where smoking is common and increasing among teenagers.
The United States is the only country outside this region in the top ten unhealthiest countries, mainly because
36% of its population is obese.
</p>

<p id="p2">
However, these results should be treated carefully. Clinic Compare also ranked Afghanistan as the healthiest country
because of its low levels of obesity and alcohol consumption, followed by Guinea and Niger.
In reality, these countries face serious health problems.
For example, people in the Democratic Republic of Congo have an average life expectancy of only 53 years,
and many die from diseases that could be treated in wealthier nations.
In Malawi, tuberculosis and HIV are common, while in Mozambique, lack of nutrients is a bigger problem than overeating,
and 30% of the population cannot access health services.
</p>

<p id="p3">
The passage also highlights the importance of environmental factors.
Nepal and Afghanistan, although ranked as healthy by Clinic Compare, are among the most polluted countries in the world.
Air pollution causes around 7 million deaths each year.
In addition to industrial and vehicle pollution, billions of people are exposed to dangerous household air pollution
from cooking with wood, coal or dung.
</p>

<p id="p4">
Other studies use broader criteria.
One study found Spain to be the healthiest country due to its healthy diet, clean air,
active lifestyle and free healthcare system.
</p>

<p id="p5">
Another study, the Global Health Security Index, ranked the USA as the healthiest country
because of its ability to respond effectively to pandemics, even though it has high obesity rates.
</p>

<p id="p6">
Finally, the highest levels of obesity are found in Pacific island countries such as Nauru and Tuvalu.
This is linked to a shift from traditional diets to imported processed foods.
Overall, the passage shows that health rankings depend heavily on the factors being measured
and do not always reflect real living conditions.
</p>
</div>

<!-- ===== QUIZ ===== -->
<div class="card quiz">
<div class="progress"><div class="progress-bar" id="bar"></div></div>
<h3 id="q"></h3>
<div id="opts"></div>

<button id="checkBtn" onclick="check()">Check</button>
<button id="nextBtn" onclick="nextQ()" disabled>Next</button>

<div class="feedback" id="fb"></div>
<div class="explain" id="ex"></div>
</div>

</div>

<script>
const qs=[
{type:"mc",q:"What is the passage mainly about?",
o:["Reasons rich countries are healthier","Effects of pollution","How different surveys reach different conclusions","Global obesity growth"],
a:2,e:"Reach different conclusions = give different results.",h:"p1"},

{type:"mc",q:"Why was the Czech Republic considered the least healthy?",
o:["Infectious diseases","Unhealthy lifestyle habits","Limited medical services","Low life expectancy"],
a:1,e:"Unhealthy lifestyle habits = alcohol, smoking, obesity.",h:"p1"},

{type:"mc",q:"What health issue affects Mozambique more than overeating?",
o:["Insufficient nutrients","Physical inactivity","Alcohol illness","Heart disease"],
a:0,e:"Mozambique suffers more from lack of nutrients.",h:"p2"},

{type:"mc",q:"What message does the author convey about health rankings?",
o:["Always accurate","Depend on criteria","Focus on obesity","Ignore pollution"],
a:1,e:"Health rankings depend on factors measured.",h:"p6"},

{type:"mc",q:"Why was Spain ranked the healthiest country?",
o:["Scientific research","Balanced diet and active lifestyle","Low income gap","High population"],
a:1,e:"Healthy diet + active lifestyle.",h:"p4"},

{type:"fill",q:"Alcohol, tobacco and ________ caused the Czech Republic to rank unhealthiest.",
a:"obesity",e:"Obesity is listed with alcohol and tobacco.",h:"p1"},

{type:"fill",q:"Smoking is increasing among ________ in Eastern Europe.",
a:"teenagers",e:"Teenagers are mentioned directly.",h:"p1"},

{type:"fill",q:"These results should be treated ________.",
a:"carefully",e:"The author warns readers.",h:"p2"},

{type:"fill",q:"Air pollution causes around 7 million ________ each year.",
a:"deaths",e:"Exact number stated.",h:"p3"},

{type:"fill",q:"Pacific island obesity is linked to imported ________ foods.",
a:"processed",e:"Processed foods replace traditional diets.",h:"p6"}
];

let i=0,score=0;

function load(){
document.getElementById("fb").innerText="";
document.getElementById("ex").innerText="";
document.getElementById("nextBtn").disabled=true;
document.getElementById("checkBtn").disabled=false;
document.querySelectorAll(".highlight").forEach(e=>e.classList.remove("highlight"));

const q=qs[i];
document.getElementById("q").innerHTML=q.q;
const o=document.getElementById("opts");
o.innerHTML="";

if(q.type==="mc"){
q.o.forEach((x,j)=>o.innerHTML+=`<div class="option"><input type="radio" name="a" value="${j}"> ${x}</div>`);
}else{
o.innerHTML=`<input type="text" id="ans">`;
}

document.getElementById("bar").style.width=(i/qs.length*100)+"%";
}

function check(){
const q=qs[i];
let ok=false;

if(q.type==="mc"){
const s=document.querySelector('input[name="a"]:checked');
if(!s) return alert("Choose an answer");
ok=(+s.value===q.a);
}else{
ok=(document.getElementById("ans").value.trim().toLowerCase()===q.a);
}

document.getElementById("checkBtn").disabled=true;
document.getElementById("nextBtn").disabled=false;
document.getElementById("fb").innerHTML= ok?"<span class='correct'>✔ Correct</span>":"<span class='wrong'>✘ Incorrect</span>";
document.getElementById("ex").innerText=q.e;
document.getElementById(q.h).classList.add("highlight");
document.getElementById(q.h).scrollIntoView({behavior:"smooth",block:"center"});
if(ok) score++;
}

function nextQ(){
i++;
if(i<qs.length) load();
else{
document.querySelector(".quiz").innerHTML=`<h2>🎉 Finished!</h2><p>Your score: ${score}/${qs.length}</p>`;
document.getElementById("bar").style.width="100%";
}
}
load();
</script>

</body>
</html>
