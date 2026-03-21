<!DOCTYPE html>
<html lang="no">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Den Store Skriveprisen</title>
<link href="https://fonts.googleapis.com/css2?family=Cinzel:wght@400;700;900&family=Cormorant+Garamond:ital,wght@0,300;0,600;1,400&display=swap" rel="stylesheet">
<style>
:root {
  --gold:   #f7d060;
  --gold2:  #e8960a;
  --cream:  #f8f0dc;
  --bg:     #060410;
  --deep:   #10082a;
  --red:    #c0392b;
  --purple: #6c3fa0;
  --teal:   #1a8a7a;
  --blue:   #1a5fa0;
}

* { margin:0; padding:0; box-sizing:border-box; }

body {
  background: var(--bg);
  color: var(--cream);
  font-family: 'Cormorant Garamond', serif;
  min-height: 100vh;
  overflow-x: hidden;
  cursor: default;
}

/* ══════════════════════════════
   SETUP SCREEN
══════════════════════════════ */
#setup {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  min-height: 100vh;
  padding: 2rem 1.5rem 3rem;
  gap: 0;
  background:
    radial-gradient(ellipse at 50% 0%, #2a1060 0%, transparent 60%),
    radial-gradient(ellipse at 20% 80%, #1a0840 0%, transparent 50%),
    var(--bg);
}

.setup-crown {
  font-size: 3rem;
  margin-bottom: 0.3rem;
  animation: float 3s ease-in-out infinite;
}

@keyframes float {
  0%,100% { transform: translateY(0); }
  50%      { transform: translateY(-8px); }
}

#setup h1 {
  font-family: 'Cinzel', serif;
  font-size: clamp(1.6rem, 5vw, 3rem);
  font-weight: 900;
  color: var(--gold);
  text-align: center;
  letter-spacing: 0.06em;
  text-shadow:
    0 0 30px rgba(247,208,96,0.5),
    0 0 80px rgba(247,208,96,0.2);
  margin-bottom: 0.4rem;
  line-height: 1.2;
}

.setup-divider {
  width: 180px;
  height: 1px;
  background: linear-gradient(90deg, transparent, var(--gold), transparent);
  margin: 0.8rem auto 1.4rem;
}

#setup p {
  color: rgba(248,240,220,0.5);
  font-size: 1.05rem;
  font-style: italic;
  text-align: center;
  margin-bottom: 2rem;
}

.category-block {
  width: 100%;
  max-width: 500px;
  margin-bottom: 1rem;
}

.cat-label {
  font-family: 'Cinzel', serif;
  font-size: 0.72rem;
  letter-spacing: 0.18em;
  text-transform: uppercase;
  margin-bottom: 0.35rem;
  padding-left: 0.3rem;
  display: flex;
  align-items: center;
  gap: 0.5rem;
}

.cat-dot {
  width: 8px; height: 8px;
  border-radius: 50%;
  flex-shrink: 0;
}

input[type="text"] {
  width: 100%;
  background: rgba(255,255,255,0.05);
  border: 1px solid rgba(247,208,96,0.25);
  border-radius: 6px;
  padding: 0.7rem 1rem;
  color: var(--cream);
  font-family: 'Cormorant Garamond', serif;
  font-size: 1.1rem;
  outline: none;
  transition: border-color 0.25s, background 0.25s;
}

input[type="text"]:focus {
  border-color: var(--gold);
  background: rgba(255,255,255,0.08);
}

input[type="text"]::placeholder { color: rgba(248,240,220,0.25); }

#startBtn {
  margin-top: 1.5rem;
  background: linear-gradient(135deg, var(--gold2), var(--gold), var(--gold2));
  background-size: 200% 100%;
  color: #1a0a00;
  font-family: 'Cinzel', serif;
  font-size: 1rem;
  font-weight: 700;
  letter-spacing: 0.14em;
  text-transform: uppercase;
  border: none;
  border-radius: 8px;
  padding: 0.9rem 3.5rem;
  cursor: pointer;
  transition: transform 0.15s, box-shadow 0.15s, background-position 0.4s;
  box-shadow: 0 4px 28px rgba(247,208,96,0.3);
}

#startBtn:hover {
  transform: translateY(-2px) scale(1.02);
  box-shadow: 0 8px 40px rgba(247,208,96,0.5);
  background-position: right center;
}

/* ══════════════════════════════
   CEREMONY SCREEN
══════════════════════════════ */
#ceremony {
  display: none;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  min-height: 100vh;
  padding: 2rem;
  position: relative;
  overflow: hidden;
  background:
    radial-gradient(ellipse at 50% 40%, #1a0a38 0%, transparent 65%),
    var(--bg);
}

/* Starfield */
.stars { position:fixed; inset:0; pointer-events:none; z-index:0; }
.star {
  position:absolute; background:white; border-radius:50%; opacity:0;
  animation: twinkle var(--d) var(--delay) infinite;
}
@keyframes twinkle {
  0%,100% { opacity:0; }
  50%      { opacity:var(--bright); }
}

/* Curtain flash on reveal */
#flashOverlay {
  position: fixed; inset:0; z-index:50;
  background: white;
  opacity: 0;
  pointer-events: none;
  transition: opacity 0.05s;
}

#stage {
  position: relative;
  z-index: 10;
  text-align: center;
  max-width: 760px;
  width: 100%;
}

/* Progress dots */
#progressDots {
  display: flex;
  gap: 0.5rem;
  justify-content: center;
  margin-bottom: 2.5rem;
}

.prog-dot {
  width: 10px; height: 10px;
  border-radius: 50%;
  border: 1px solid rgba(247,208,96,0.4);
  background: transparent;
  transition: background 0.4s, border-color 0.4s, transform 0.3s;
}

.prog-dot.done {
  background: var(--gold);
  border-color: var(--gold);
}

.prog-dot.active {
  background: rgba(247,208,96,0.4);
  border-color: var(--gold);
  transform: scale(1.3);
}

/* Big show title */
#showTitle {
  font-family: 'Cinzel', serif;
  font-size: clamp(1.4rem, 4vw, 2.4rem);
  font-weight: 900;
  color: var(--gold);
  letter-spacing: 0.06em;
  opacity: 0;
  transform: translateY(16px);
  transition: opacity 0.9s, transform 0.9s;
  text-shadow: 0 0 50px rgba(247,208,96,0.4);
  margin-bottom: 0.3rem;
}

#showTitle.visible { opacity:1; transform:translateY(0); }

#showLine {
  width: 240px;
  height: 1px;
  background: linear-gradient(90deg, transparent, var(--gold), transparent);
  margin: 0.6rem auto 2.5rem;
  opacity: 0;
  transition: opacity 0.8s 0.3s;
}
#showLine.visible { opacity:1; }

/* Category announcement */
#categoryAnnounce {
  opacity: 0;
  transform: translateY(10px);
  transition: opacity 0.6s, transform 0.6s;
  margin-bottom: 2rem;
}
#categoryAnnounce.visible { opacity:1; transform:translateY(0); }

#catLabel {
  font-family: 'Cinzel', serif;
  font-size: 0.75rem;
  letter-spacing: 0.22em;
  text-transform: uppercase;
  color: rgba(248,240,220,0.45);
  margin-bottom: 0.4rem;
}

#catName {
  font-family: 'Cinzel', serif;
  font-size: clamp(1.5rem, 4.5vw, 2.6rem);
  font-weight: 700;
  letter-spacing: 0.04em;
  line-height: 1.15;
}

/* Step hint */
#stepHint {
  font-size: 0.85rem;
  color: rgba(248,240,220,0.3);
  letter-spacing: 0.14em;
  text-transform: uppercase;
  font-style: italic;
  margin-bottom: 2.5rem;
  min-height: 1.2em;
  transition: opacity 0.3s;
}

/* Drum roll */
#drumIndicator {
  opacity: 0;
  transition: opacity 0.3s;
  margin-bottom: 2rem;
  display: flex;
  align-items: center;
  justify-content: center;
  gap: 0.7rem;
  font-family: 'Cinzel', serif;
  font-size: 0.75rem;
  letter-spacing: 0.2em;
  text-transform: uppercase;
  color: var(--gold);
}
#drumIndicator.visible { opacity:1; }

.drum-dot {
  width: 9px; height: 9px;
  background: var(--gold);
  border-radius: 50%;
}
@keyframes drumPulse {
  0%,100% { transform:scale(1); opacity:0.35; }
  50%      { transform:scale(1.7); opacity:1; }
}
.drum-dot.beating { animation: drumPulse 0.16s infinite; }
.drum-dot:nth-child(2).beating { animation-delay:0.05s; }
.drum-dot:nth-child(3).beating { animation-delay:0.10s; }

/* Winner reveal */
#winnerArea {
  opacity: 0;
  transform: scale(0.8) translateY(20px);
  transition: opacity 0.7s cubic-bezier(.17,.84,.44,1), transform 0.7s cubic-bezier(.17,.84,.44,1);
}
#winnerArea.visible {
  opacity:1;
  transform: scale(1) translateY(0);
}

#winnerLabel {
  font-family: 'Cinzel', serif;
  font-size: 0.8rem;
  letter-spacing: 0.22em;
  color: rgba(248,240,220,0.4);
  text-transform: uppercase;
  margin-bottom: 0.3rem;
}

#winnerName {
  font-family: 'Cinzel', serif;
  font-size: clamp(2.6rem, 9vw, 5.5rem);
  font-weight: 900;
  color: var(--cream);
  text-shadow:
    0 0 20px rgba(247,208,96,0.8),
    0 0 60px rgba(247,208,96,0.35),
    0 0 120px rgba(247,208,96,0.15);
  line-height: 1.1;
  margin-bottom: 0.6rem;
  animation: none;
}

@keyframes shimmer {
  0%,100% { text-shadow: 0 0 20px rgba(247,208,96,0.8), 0 0 60px rgba(247,208,96,0.35), 0 0 120px rgba(247,208,96,0.15); }
  50%      { text-shadow: 0 0 40px rgba(247,208,96,1), 0 0 100px rgba(247,208,96,0.6), 0 0 160px rgba(247,208,96,0.3); }
}

#winnerName.shimmering {
  animation: shimmer 1.5s ease-in-out infinite;
}

#trophyRow {
  font-size: 2.8rem;
  opacity: 0;
  letter-spacing: 0.2rem;
  transition: opacity 0.5s 0.4s;
}
#trophyRow.visible { opacity:1; }

/* Burst ring on reveal */
@keyframes burstRing {
  0%   { transform:scale(0.3); opacity:0.9; }
  100% { transform:scale(3);   opacity:0; }
}

.burst-ring {
  position: fixed;
  width: 200px; height: 200px;
  border-radius: 50%;
  border: 3px solid var(--gold);
  top: 50%; left: 50%;
  transform: translate(-50%, -50%) scale(0.3);
  pointer-events: none;
  z-index: 40;
  animation: burstRing 0.8s ease-out forwards;
}

/* Next button */
#nextBtn {
  margin-top: 2.5rem;
  background: transparent;
  border: 1px solid rgba(247,208,96,0.35);
  color: var(--gold);
  font-family: 'Cinzel', serif;
  font-size: 0.8rem;
  letter-spacing: 0.16em;
  text-transform: uppercase;
  padding: 0.75rem 2.5rem;
  border-radius: 40px;
  cursor: pointer;
  opacity: 0;
  transition: opacity 0.4s, background 0.2s, transform 0.15s;
  display: none;
}
#nextBtn.visible { opacity:1; }
#nextBtn:hover { background:rgba(247,208,96,0.1); transform:translateY(-1px); }

/* Fireworks canvas */
#fireworkCanvas {
  position: fixed; inset:0;
  pointer-events: none;
  z-index: 5;
}

/* Click hint */
.click-anywhere {
  position: fixed;
  bottom: 1.5rem;
  left: 50%;
  transform: translateX(-50%);
  font-size: 0.72rem;
  color: rgba(248,240,220,0.22);
  letter-spacing: 0.16em;
  text-transform: uppercase;
  z-index: 20;
  pointer-events: none;
  animation: blink 2.5s infinite;
}
@keyframes blink {
  0%,100% { opacity: 0.3; }
  50%      { opacity: 0.8; }
}

/* ══════════════════════════════
   FINAL SCREEN
══════════════════════════════ */
#finalScreen {
  display: none;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  min-height: 100vh;
  text-align: center;
  padding: 2rem;
  position: relative;
  z-index: 10;
  background:
    radial-gradient(ellipse at 50% 30%, #1a0a38 0%, transparent 60%),
    var(--bg);
}

#finalScreen h2 {
  font-family: 'Cinzel', serif;
  font-size: clamp(1.4rem, 4vw, 2.6rem);
  font-weight: 900;
  color: var(--gold);
  margin-bottom: 0.5rem;
  text-shadow: 0 0 40px rgba(247,208,96,0.35);
  letter-spacing: 0.06em;
}

#finalSubtitle {
  font-style: italic;
  color: rgba(248,240,220,0.4);
  margin-bottom: 2.5rem;
}

.final-list { list-style:none; display:flex; flex-direction:column; gap:1.1rem; }

.final-list li {
  display: flex;
  align-items: baseline;
  gap: 0.7rem;
  opacity: 0;
  transform: translateX(-24px);
  animation: slideIn 0.6s forwards;
  background: rgba(255,255,255,0.03);
  border: 1px solid rgba(247,208,96,0.12);
  border-radius: 8px;
  padding: 0.8rem 1.4rem;
}

.final-list li .fi-emoji { font-size: 1.5rem; }
.final-list li .fi-cat {
  font-family: 'Cinzel', serif;
  font-size: 0.72rem;
  letter-spacing: 0.15em;
  color: rgba(248,240,220,0.45);
  text-transform: uppercase;
  flex-shrink: 0;
  min-width: 130px;
  text-align: left;
}
.final-list li .fi-name {
  font-family: 'Cinzel', serif;
  font-size: 1.1rem;
  color: var(--cream);
  text-align: left;
}

@keyframes slideIn {
  to { opacity:1; transform:translateX(0); }
}

#restartBtn {
  margin-top: 2.5rem;
  background: transparent;
  border: 1px solid rgba(247,208,96,0.3);
  color: rgba(248,240,220,0.4);
  font-family: 'Cinzel', serif;
  font-size: 0.78rem;
  letter-spacing: 0.15em;
  text-transform: uppercase;
  padding: 0.65rem 2rem;
  border-radius: 40px;
  cursor: pointer;
  transition: color 0.2s, border-color 0.2s;
}
#restartBtn:hover { color:var(--gold); border-color:var(--gold); }
</style>
</head>
<body>

<!-- ══ SETUP ══ -->
<div id="setup">
  <div class="setup-crown">👑</div>
  <h1>Den Store<br>Skriveprisen</h1>
  <div class="setup-divider"></div>
  <p>Fyll inn navnene på vinnerne før kåringen</p>

  <div class="category-block">
    <div class="cat-label" style="color:#f7d060">
      <div class="cat-dot" style="background:#f7d060"></div>
      Morsomste tekst
    </div>
    <input type="text" id="w1" placeholder="Vinner – navn" />
  </div>

  <div class="category-block">
    <div class="cat-label" style="color:#a78bfa">
      <div class="cat-dot" style="background:#a78bfa"></div>
      Skumleste tekst
    </div>
    <input type="text" id="w2" placeholder="Vinner – navn" />
  </div>

  <div class="category-block">
    <div class="cat-label" style="color:#34d399">
      <div class="cat-dot" style="background:#34d399"></div>
      Beste fortelling
    </div>
    <input type="text" id="w3" placeholder="Vinner – navn" />
  </div>

  <div class="category-block">
    <div class="cat-label" style="color:#60a5fa">
      <div class="cat-dot" style="background:#60a5fa"></div>
      Beste skildring
    </div>
    <input type="text" id="w4" placeholder="Vinner – navn" />
  </div>

  <button id="startBtn">✦ Start kåringen ✦</button>
</div>

<!-- ══ CEREMONY ══ -->
<div id="ceremony">
  <canvas id="fireworkCanvas"></canvas>
  <div class="stars" id="starsContainer"></div>
  <div id="flashOverlay"></div>

  <div id="stage">
    <div id="progressDots"></div>

    <div id="showTitle">Den Store Skriveprisen</div>
    <div id="showLine"></div>

    <div id="categoryAnnounce">
      <div id="catLabel">Neste kategori</div>
      <div id="catName"></div>
    </div>

    <div id="stepHint">Klikk for å starte musikken</div>

    <div id="drumIndicator">
      <div class="drum-dot" id="d1"></div>
      <div class="drum-dot" id="d2"></div>
      <div class="drum-dot" id="d3"></div>
      <span>Trommevirvel</span>
      <div class="drum-dot" id="d4"></div>
      <div class="drum-dot" id="d5"></div>
      <div class="drum-dot" id="d6"></div>
    </div>

    <div id="winnerArea">
      <div id="winnerLabel">Vinner</div>
      <div id="winnerName"></div>
      <div id="trophyRow"></div>
    </div>

    <button id="nextBtn">Neste kategori →</button>
  </div>

  <div class="click-anywhere" id="clickHint">klikk hvor som helst</div>
</div>

<!-- ══ FINAL ══ -->
<div id="finalScreen">
  <div class="setup-crown" style="margin-bottom:0.5rem">🏆</div>
  <h2>Den Store Skriveprisen</h2>
  <div id="finalSubtitle">Årets vinnere</div>
  <ul class="final-list" id="finalList"></ul>
  <button id="restartBtn">Start på nytt</button>
</div>

<script>
// ══════════════════════════════
//  CATEGORIES
// ══════════════════════════════
const CATEGORIES = [
  { id:'w1', label:'Morsomste tekst',  emoji:'😂', color:'#f7d060', trophy:'🤣🏆😂' },
  { id:'w2', label:'Skumleste tekst',  emoji:'👻', color:'#a78bfa', trophy:'💀🏆👻' },
  { id:'w3', label:'Beste fortelling', emoji:'📖', color:'#34d399', trophy:'✨🏆📖' },
  { id:'w4', label:'Beste skildring',  emoji:'🎨', color:'#60a5fa', trophy:'🖊️🏆🎨' },
];

// ══════════════════════════════
//  AUDIO
// ══════════════════════════════
const ctx = new (window.AudioContext || window.webkitAudioContext)();

function playFanfare(colorHex) {
  // Quick triumphant ascending motif
  const melody = [
    {f:392,t:0},   {f:523,t:0.12},{f:659,t:0.24},
    {f:784,t:0.38},{f:659,t:0.52},{f:784,t:0.62},{f:1047,t:0.78}
  ];
  melody.forEach(({f,t}) => {
    const osc = ctx.createOscillator();
    const gain = ctx.createGain();
    osc.connect(gain); gain.connect(ctx.destination);
    osc.type = 'triangle';
    osc.frequency.value = f;
    const when = ctx.currentTime + t;
    gain.gain.setValueAtTime(0, when);
    gain.gain.linearRampToValueAtTime(0.2, when + 0.04);
    gain.gain.exponentialRampToValueAtTime(0.001, when + 0.42);
    osc.start(when); osc.stop(when + 0.45);
  });
}

let drumInterval = null;
function startDrumRoll() {
  let t = ctx.currentTime;
  let speed = 0.28; // starts slow, speeds up
  let beats = 0;
  const tick = () => {
    for (let i = 0; i < 4; i++) {
      const buf = ctx.createBuffer(1, Math.floor(ctx.sampleRate * 0.045), ctx.sampleRate);
      const data = buf.getChannelData(0);
      for (let j = 0; j < data.length; j++)
        data[j] = (Math.random()*2-1) * Math.pow(1 - j/data.length, 2.5);
      const src = ctx.createBufferSource();
      const gain = ctx.createGain();
      src.buffer = buf; src.connect(gain); gain.connect(ctx.destination);
      gain.gain.setValueAtTime(0.4 + beats*0.008, t + i * (speed/4));
      src.start(t + i * (speed/4));
    }
    t += speed;
    beats++;
    if (speed > 0.14) speed -= 0.008; // accelerate
  };
  tick();
  drumInterval = setInterval(tick, speed * 1000);

  // Re-schedule with acceleration
  const accel = setInterval(() => {
    clearInterval(drumInterval);
    if (speed > 0.10) speed = Math.max(0.10, speed - 0.01);
    drumInterval = setInterval(tick, speed * 1000);
  }, 500);
  window._accelInterval = accel;
}

function stopDrumRoll() {
  clearInterval(drumInterval);
  clearInterval(window._accelInterval);
  drumInterval = null;
}

function playGrandReveal() {
  stopDrumRoll();

  // Thunderous hit
  const buf = ctx.createBuffer(1, ctx.sampleRate * 0.4, ctx.sampleRate);
  const d = buf.getChannelData(0);
  for (let j=0; j<d.length; j++)
    d[j] = (Math.random()*2-1) * Math.pow(1 - j/d.length, 1.2);
  const src = ctx.createBufferSource();
  const g = ctx.createGain();
  src.buffer=buf; src.connect(g); g.connect(ctx.destination);
  g.gain.setValueAtTime(1.0, ctx.currentTime);
  src.start();

  // Sub-bass boom
  const osc = ctx.createOscillator();
  const ogain = ctx.createGain();
  osc.connect(ogain); ogain.connect(ctx.destination);
  osc.type = 'sine';
  osc.frequency.setValueAtTime(60, ctx.currentTime);
  osc.frequency.exponentialRampToValueAtTime(30, ctx.currentTime + 0.5);
  ogain.gain.setValueAtTime(0.6, ctx.currentTime);
  ogain.gain.exponentialRampToValueAtTime(0.001, ctx.currentTime + 0.6);
  osc.start(); osc.stop(ctx.currentTime + 0.6);

  setTimeout(() => playFanfare(), 180);

  // Bell chime accent
  setTimeout(() => {
    [1047, 1319, 1568].forEach((freq, i) => {
      const o = ctx.createOscillator();
      const gn = ctx.createGain();
      o.connect(gn); gn.connect(ctx.destination);
      o.type = 'sine';
      o.frequency.value = freq;
      const when = ctx.currentTime + i*0.12;
      gn.gain.setValueAtTime(0.15, when);
      gn.gain.exponentialRampToValueAtTime(0.001, when + 1.2);
      o.start(when); o.stop(when + 1.3);
    });
  }, 700);
}

// ══════════════════════════════
//  FIREWORKS
// ══════════════════════════════
const canvas = document.getElementById('fireworkCanvas');
const fctx = canvas.getContext('2d');
let particles = [];
let fwInterval = null;

function resizeCanvas() { canvas.width=window.innerWidth; canvas.height=window.innerHeight; }
resizeCanvas(); window.addEventListener('resize', resizeCanvas);

function spawnFirework(accentColor) {
  const x = Math.random() * canvas.width;
  const y = Math.random() * canvas.height * 0.55 + 40;
  const palette = accentColor
    ? [accentColor, '#ffffff', '#f7d060', accentColor, '#fff6c0']
    : ['#f7d060','#ff6b6b','#a78bfa','#34d399','#60a5fa','#f472b6','#fbbf24'];
  const color = palette[Math.floor(Math.random()*palette.length)];
  const count = 70 + Math.floor(Math.random()*30);
  for (let i=0; i<count; i++) {
    const angle = (Math.PI*2/count)*i + Math.random()*0.1;
    const speed = Math.random()*6 + 2;
    particles.push({
      x,y,
      vx: Math.cos(angle)*speed,
      vy: Math.sin(angle)*speed - 2,
      alpha: 1,
      color,
      size: Math.random()*3+1,
      decay: Math.random()*0.013+0.01
    });
  }
}

function animateFireworks() {
  fctx.clearRect(0,0,canvas.width,canvas.height);
  particles = particles.filter(p=>p.alpha>0.01);
  particles.forEach(p=>{
    p.x+=p.vx; p.y+=p.vy;
    p.vy+=0.07; p.vx*=0.98;
    p.alpha-=p.decay;
    fctx.globalAlpha=p.alpha;
    fctx.fillStyle=p.color;
    fctx.beginPath();
    fctx.arc(p.x,p.y,p.size,0,Math.PI*2);
    fctx.fill();
  });
  fctx.globalAlpha=1;
  requestAnimationFrame(animateFireworks);
}
animateFireworks();

let currentAccent = null;
function startFireworks(color) {
  currentAccent = color || null;
  spawnFirework(currentAccent); spawnFirework(currentAccent); spawnFirework(null);
  fwInterval = setInterval(()=>{
    spawnFirework(currentAccent);
    spawnFirework(null);
    if (Math.random()>0.5) spawnFirework(currentAccent);
  }, 500);
}

function stopFireworks() { clearInterval(fwInterval); fwInterval=null; }

// Flash effect
function flashScreen() {
  const fl = document.getElementById('flashOverlay');
  fl.style.opacity = '0.7';
  setTimeout(()=> fl.style.opacity='0', 80);
  // Burst ring
  const ring = document.createElement('div');
  ring.className = 'burst-ring';
  ring.style.borderColor = currentCat ? currentCat.color : '#f7d060';
  document.body.appendChild(ring);
  setTimeout(()=> ring.remove(), 900);
}

// ══════════════════════════════
//  STARS
// ══════════════════════════════
(function(){
  const c = document.getElementById('starsContainer');
  for(let i=0;i<140;i++){
    const s=document.createElement('div'); s.className='star';
    const sz=Math.random()*2.5+0.5;
    s.style.cssText=`width:${sz}px;height:${sz}px;left:${Math.random()*100}%;top:${Math.random()*100}%;--d:${(Math.random()*3+2).toFixed(1)}s;--delay:${(Math.random()*5).toFixed(1)}s;--bright:${(Math.random()*0.6+0.2).toFixed(2)};`;
    c.appendChild(s);
  }
})();

// ══════════════════════════════
//  STATE MACHINE
// ══════════════════════════════
let winners = [];
let current = 0;
let step = -1;   // -1=waiting, 0=music played, 1=drum, 2=revealed
let currentCat = null;

const setupEl      = document.getElementById('setup');
const ceremonyEl   = document.getElementById('ceremony');
const finalScreenEl= document.getElementById('finalScreen');
const stepHint     = document.getElementById('stepHint');
const drumIndicator= document.getElementById('drumIndicator');
const winnerArea   = document.getElementById('winnerArea');
const winnerNameEl = document.getElementById('winnerName');
const trophyRow    = document.getElementById('trophyRow');
const nextBtn      = document.getElementById('nextBtn');
const clickHint    = document.getElementById('clickHint');
const catName      = document.getElementById('catName');
const catAnnounce  = document.getElementById('categoryAnnounce');
const progressDots = document.getElementById('progressDots');

// Build progress dots
function buildDots() {
  progressDots.innerHTML = '';
  winners.forEach((_,i)=>{
    const d=document.createElement('div');
    d.className='prog-dot';
    d.style.setProperty('--cat-color', winners[i].color);
    progressDots.appendChild(d);
  });
}

function updateDots() {
  document.querySelectorAll('.prog-dot').forEach((d,i)=>{
    d.classList.remove('done','active');
    if(i<current) d.classList.add('done');
    else if(i===current) d.classList.add('active');
  });
}

document.getElementById('startBtn').addEventListener('click', ()=>{
  winners = [];
  CATEGORIES.forEach(cat=>{
    const val = document.getElementById(cat.id).value.trim();
    if(val) winners.push({...cat, name:val});
  });
  if(!winners.length){ alert('Skriv inn minst ett navn!'); return; }

  setupEl.style.display='none';
  ceremonyEl.style.display='flex';
  step=-1; current=0;
  buildDots();
  showCurrentCategory();
});

function showCurrentCategory() {
  currentCat = winners[current];
  updateDots();

  // Show show title
  document.getElementById('showTitle').classList.add('visible');
  document.getElementById('showLine').classList.add('visible');

  // Announce category
  catName.textContent = currentCat.emoji + ' ' + currentCat.label;
  catName.style.color = currentCat.color;
  catAnnounce.classList.add('visible');

  stepHint.textContent = 'Klikk for å starte musikken';
  drumIndicator.classList.remove('visible');
  winnerArea.classList.remove('visible');
  trophyRow.classList.remove('visible');
  nextBtn.classList.remove('visible');
  nextBtn.style.display='none';
  winnerNameEl.classList.remove('shimmering');
  clickHint.textContent='klikk for å starte';
}

document.getElementById('ceremony').addEventListener('click', handleClick);

function handleClick() {
  if(ctx.state==='suspended') ctx.resume();
  if(step===2) return; // don't re-trigger after reveal

  if(step===-1){
    step=0;
    playFanfare(currentCat.color);
    stepHint.textContent='Klikk for trommevirvel';
    clickHint.textContent='klikk for trommevirvel';
    return;
  }

  if(step===0){
    step=1;
    drumIndicator.classList.add('visible');
    document.querySelectorAll('.drum-dot').forEach(d=>d.classList.add('beating'));
    startDrumRoll();
    stepHint.textContent='Klikk for å avdekke vinneren!';
    clickHint.textContent='klikk for å avdekke!';
    return;
  }

  if(step===1){
    step=2;
    // Grand reveal!
    document.querySelectorAll('.drum-dot').forEach(d=>d.classList.remove('beating'));
    drumIndicator.classList.remove('visible');

    playGrandReveal();
    flashScreen();
    startFireworks(currentCat.color);

    winnerNameEl.textContent = currentCat.name;
    document.getElementById('winnerLabel').textContent = currentCat.label.toUpperCase();
    trophyRow.textContent = currentCat.trophy;
    winnerArea.classList.add('visible');
    setTimeout(()=>{
      trophyRow.classList.add('visible');
      winnerNameEl.classList.add('shimmering');
    }, 500);

    stepHint.textContent='';
    clickHint.textContent='';

    setTimeout(()=>{
      nextBtn.style.display='inline-block';
      nextBtn.textContent = current < winners.length-1
        ? 'Neste kategori →'
        : 'Se alle vinnere 🏆';
      nextBtn.classList.add('visible');
    }, 1500);
  }
}

nextBtn.addEventListener('click', (e)=>{
  e.stopPropagation();
  stopFireworks();
  winnerNameEl.classList.remove('shimmering');
  current++;
  if(current >= winners.length){
    showFinal(); return;
  }
  step=-1;
  winnerArea.classList.remove('visible');
  trophyRow.classList.remove('visible');
  nextBtn.classList.remove('visible');
  nextBtn.style.display='none';
  catAnnounce.classList.remove('visible');
  setTimeout(()=> showCurrentCategory(), 300);
});

function showFinal(){
  ceremonyEl.style.display='none';
  finalScreenEl.style.display='flex';
  startFireworks();

  const list=document.getElementById('finalList');
  list.innerHTML='';
  winners.forEach((w,i)=>{
    const li=document.createElement('li');
    li.style.animationDelay=`${i*0.3}s`;
    li.innerHTML=`
      <span class="fi-emoji">${w.emoji}</span>
      <span class="fi-cat">${w.label}</span>
      <span class="fi-name">${w.name}</span>
    `;
    list.appendChild(li);
  });
}

document.getElementById('restartBtn').addEventListener('click',()=>{
  stopFireworks(); stopDrumRoll();
  finalScreenEl.style.display='none';
  setupEl.style.display='flex';
  CATEGORIES.forEach(cat=> document.getElementById(cat.id).value='');
  document.getElementById('showTitle').classList.remove('visible');
  document.getElementById('showLine').classList.remove('visible');
  catAnnounce.classList.remove('visible');
  winnerArea.classList.remove('visible');
  trophyRow.classList.remove('visible');
  nextBtn.classList.remove('visible');
  drumIndicator.classList.remove('visible');
});
</script>
</body>
</html>
