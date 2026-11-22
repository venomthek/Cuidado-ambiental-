# Cuidado-ambiental-
No se solo me pagaron por hacer esto 



<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>Cuidemos el planeta</title>
<style>
:root{
  --bg:#EEF3EC; --surface:#FFFFFF; --ink:#16301F; --muted:#4D6455; --accent:#1F7A4D; --water:#2E7DA6; --line:#C9D8CC;
  box-sizing:border-box; padding-top:env(safe-area-inset-top,0px); padding-bottom:env(safe-area-inset-bottom,0px);
}
@media (prefers-color-scheme: dark){
  :root:not([data-theme="light"]){--bg:#0F1D15; --surface:#172A1E; --ink:#E6F0E8; --muted:#A5BBAA; --accent:#5FD08F; --water:#6DB8DD; --line:#2A4433;}
}
:root[data-theme="dark"]{--bg:#0F1D15; --surface:#172A1E; --ink:#E6F0E8; --muted:#A5BBAA; --accent:#5FD08F; --water:#6DB8DD; --line:#2A4433;}
html{scroll-padding-top:env(safe-area-inset-top,0px);scroll-behavior:smooth}
*,*::before,*::after{box-sizing:border-box}
body{margin:0;background:var(--bg);color:var(--ink);font-family:Georgia,"Times New Roman",serif;line-height:1.65;font-size:18px}
h1,h2,h3,.sans{font-family:"Trebuchet MS","Segoe UI",system-ui,sans-serif}
a{color:var(--accent)}
:focus-visible{outline:3px solid var(--water);outline-offset:3px}
.wrap{max-width:860px;margin:0 auto;padding:0 20px}
header.hero{padding:72px 0 56px}
h1{font-size:clamp(2.4rem,8vw,4.6rem);line-height:1.05;margin:0 0 20px;letter-spacing:-.02em}
.lead{font-size:1.2rem;max-width:34em;color:var(--muted);margin:0 0 28px}
.btn{display:inline-block;background:var(--accent);color:var(--bg);padding:12px 22px;border-radius:8px;text-decoration:none;font-family:"Trebuchet MS",system-ui,sans-serif;font-weight:700}
nav{position:sticky;top:env(safe-area-inset-top,0px);background:var(--bg);border-bottom:1px solid var(--line);z-index:5}
nav .wrap{display:flex;gap:18px;overflow-x:auto;padding-top:12px;padding-bottom:12px}
nav a{white-space:nowrap;text-decoration:none;color:var(--ink);font-family:"Trebuchet MS",system-ui,sans-serif;font-size:.95rem}
section{padding:56px 0;border-bottom:1px solid var(--line)}
h2{font-size:clamp(1.6rem,5vw,2.3rem);margin:0 0 16px}
.facts{display:grid;gap:14px;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));margin-top:24px}
.fact{background:var(--surface);border-left:5px solid var(--accent);padding:16px 18px;border-radius:4px}
.fact b{font-family:"Trebuchet MS",system-ui,sans-serif;font-size:1.7rem;display:block;color:var(--accent)}
.fact:nth-child(2n){border-left-color:var(--water)}
.fact:nth-child(2n) b{color:var(--water)}
.fact span{font-size:.95rem;color:var(--muted)}
.erres{display:grid;gap:12px;grid-template-columns:repeat(auto-fit,minmax(240px,1fr));margin-top:20px}
.erres div{background:var(--surface);padding:18px;border-radius:10px}
.erres h3{margin:0 0 6px;font-size:1.15rem}
.erres p{margin:0;color:var(--muted);font-size:.98rem}
.tabs{display:flex;flex-wrap:wrap;gap:8px;margin:20px 0 14px}
.tabs button{font:inherit;font-family:"Trebuchet MS",system-ui,sans-serif;font-size:.95rem;border:1.5px solid var(--accent);background:transparent;color:var(--ink);padding:8px 16px;border-radius:999px;cursor:pointer}
.tabs button[aria-selected="true"]{background:var(--accent);color:var(--bg)}
.panel{background:var(--surface);padding:20px;border-radius:10px;min-height:150px}
.panel ul{margin:0;padding-left:20px}
.panel li{margin:6px 0}
.pledge{display:grid;gap:10px;margin-top:18px}
.pledge label{display:flex;gap:12px;align-items:flex-start;background:var(--surface);padding:12px 16px;border-radius:8px;cursor:pointer}
.pledge input{width:22px;height:22px;accent-color:var(--accent);margin-top:3px;flex:none}
.meter{height:14px;background:var(--line);border-radius:99px;overflow:hidden;margin:20px 0 8px}
.meter i{display:block;height:100%;width:0;background:var(--accent);transition:width .4s}
#msg{font-family:"Trebuchet MS",system-ui,sans-serif;font-weight:700;margin:0}
footer{padding:36px 0 48px;color:var(--muted);font-size:.95rem}
@media (prefers-reduced-motion:reduce){html{scroll-behavior:auto}.meter i{transition:none}}
</style>
</head>
<body>
<header class="hero"><div class="wrap">
  <h1>Cuidar el ambiente empieza en casa</h1>
  <p class="lead">Nuestro planeta es el único hogar que tenemos. Pequeñas decisiones diarias, repetidas por muchas personas, cambian el futuro del agua, el aire y la vida que nos rodea.</p>
  <a class="btn" href="#compromiso">Haz tu compromiso</a>
</div></header>

<nav aria-label="Secciones"><div class="wrap">
  <a href="#problemas">Problemas</a><a href="#erres">Las 3 R</a><a href="#acciones">Acciones</a><a href="#compromiso">Compromiso</a>
</div></nav>

<main>
<section id="problemas"><div class="wrap">
  <h2>Lo que está en juego</h2>
  <p>La contaminación, el cambio climático y la pérdida de bosques afectan la salud, la comida y el agua de todos. Estas son algunas realidades que explican por qué actuar importa:</p>
  <div class="facts">
    <div class="fact"><b>Calentamiento</b><span>La temperatura global ha subido más de 1 °C desde la era preindustrial por las emisiones de gases de efecto invernadero.</span></div>
    <div class="fact"><b>Plásticos</b><span>Millones de toneladas de plástico llegan cada año a los océanos y dañan a la fauna marina.</span></div>
    <div class="fact"><b>Bosques</b><span>La deforestación reduce la biodiversidad y la capacidad de la Tierra de absorber carbono.</span></div>
    <div class="fact"><b>Agua</b><span>Solo una pequeña parte del agua del planeta es dulce y accesible: cuidarla es cuidar la vida.</span></div>
  </div>
</div></section>

<section id="erres"><div class="wrap">
  <h2>Las 3 R: reducir, reutilizar, reciclar</h2>
  <p>El orden importa: lo mejor es generar menos residuos desde el principio.</p>
  <div class="erres">
    <div><h3>Reducir</h3><p>Compra solo lo necesario y evita productos de un solo uso.</p></div>
    <div><h3>Reutilizar</h3><p>Dale otra vida a frascos, ropa, bolsas y muebles antes de desecharlos.</p></div>
    <div><h3>Reciclar</h3><p>Separa papel, vidrio, metal y plástico, y los residuos orgánicos para compost.</p></div>
  </div>
</div></section>

<section id="acciones"><div class="wrap">
  <h2>Qué puedes hacer</h2>
  <p>Elige dónde quieres actuar:</p>
  <div class="tabs" role="tablist" aria-label="Áreas de acción">
    <button role="tab" aria-selected="true" data-t="casa">En casa</button>
    <button role="tab" aria-selected="false" data-t="agua">Agua</button>
    <button role="tab" aria-selected="false" data-t="mov">Movilidad</button>
    <button role="tab" aria-selected="false" data-t="comunidad">Comunidad</button>
  </div>
  <div class="panel" id="panel" role="tabpanel" aria-live="polite"></div>
</div></section>

<section id="compromiso"><div class="wrap">
  <h2>Tu compromiso</h2>
  <p>Marca lo que te comprometes a hacer esta semana.</p>
  <div class="pledge" id="pledge"></div>
  <div class="meter" role="progressbar" aria-valuemin="0" aria-valuemax="100" aria-valuenow="0" id="bar"><i id="fill"></i></div>
  <p id="msg">Aún no has marcado ninguna acción.</p>
</div></section>
</main>

<footer><div class="wrap">Cuidar el ambiente es tarea de todos. Comparte esta página con tu familia, tu escuela o tu comunidad.</div></footer>

<script>
const data={
  casa:["Apaga luces y desconecta aparatos que no uses.","Lleva bolsas reutilizables y tu propia botella.","Separa los residuos y haz compost con los restos de comida.","Compra productos locales y de temporada."],
  agua:["Cierra el grifo mientras te cepillas los dientes.","Ducha corta: cada minuto ahorrado cuenta.","Repara goteras y fugas cuanto antes.","Riega las plantas temprano o al atardecer."],
  mov:["Camina o usa bicicleta en trayectos cortos.","Prefiere el transporte público o comparte el auto.","Evita encender el motor sin moverte.","Planifica tus salidas para hacer menos viajes."],
  comunidad:["Organiza una jornada de limpieza en tu barrio.","Planta un árbol de especie nativa.","Comparte lo que aprendes con tus vecinos.","Apoya a quienes protegen parques y ríos cercanos."]
};
const panel=document.getElementById('panel');
function show(k){panel.innerHTML='<ul>'+data[k].map(t=>'<li>'+t+'</li>').join('')+'</ul>'}
document.querySelectorAll('.tabs button').forEach(b=>b.addEventListener('click',()=>{
  document.querySelectorAll('.tabs button').forEach(x=>x.setAttribute('aria-selected','false'));
  b.setAttribute('aria-selected','true');show(b.dataset.t);
}));
show('casa');
const pledges=["Llevar mi botella y bolsa reutilizables","Separar mis residuos","Reducir mi tiempo de ducha","Apagar luces y aparatos que no uso","Caminar o usar bici una vez esta semana"];
const box=document.getElementById('pledge'),fill=document.getElementById('fill'),msg=document.getElementById('msg'),bar=document.getElementById('bar');
pledges.forEach(p=>{const l=document.createElement('label');l.innerHTML='<input type="checkbox"><span>'+p+'</span>';box.appendChild(l)});
function update(){
  const n=box.querySelectorAll('input:checked').length,pct=Math.round(n/pledges.length*100);
  fill.style.width=pct+'%';bar.setAttribute('aria-valuenow',pct);
  msg.textContent=n===0?'Aún no has marcado ninguna acción.':n===pledges.length?'¡Excelente! Te comprometiste con todo. El planeta te lo agradece.':'Llevas '+n+' de '+pledges.length+'. ¡Sigue así!';
}
box.addEventListener('change',update);
</script>
</body>
</html>
