
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Resenha do Paulo Arthur</title>
<style>
  body {
    margin: 0;
    font-family: 'Segoe UI', Arial, sans-serif;
    background: radial-gradient(circle at center, rgba(0, 77, 102, 0.9) 0%, rgba(0, 20, 30, 1) 100%);
    color: #e0f7ff;
    text-align: center;
    overflow-x: hidden;
    transition: background 0.8s ease-in-out;
    min-height: 100vh;
  }

  .container { padding: 20px; min-height: 100vh; display: flex; flex-direction: column; justify-content: center; align-items: center; }
  h1 { font-size: 30px; text-shadow: 0 0 15px #00eaff; margin-bottom: 5px; }

  .btn-container { position: relative; display: inline-block; margin-top: 30px; }
  .btn-atom {
    position: relative;
    padding: 18px 45px;
    font-size: 22px;
    font-weight: bold;
    text-transform: uppercase;
    border: none;
    border-radius: 50px;
    background: radial-gradient(circle, #00eaff, #0066ff);
    color: #fff;
    cursor: pointer;
    z-index: 10;
    box-shadow: 0 0 20px #00eaff;
    animation: pulse-glow 1.5s infinite alternate;
    letter-spacing: 2px;
  }

  @keyframes pulse-glow {
    from { transform: scale(1); box-shadow: 0 0 15px #00eaff; }
    to { transform: scale(1.08); box-shadow: 0 0 35px #00eaff, 0 0 50px rgba(0, 234, 255, 0.6); }
  }

  .orbit {
    position: absolute;
    top: 50%; left: 50%;
    width: 160%; height: 55px;
    border: 2.5px solid rgba(0, 234, 255, 0.4);
    border-radius: 50%;
    pointer-events: none;
    animation: rotate-orbit 2s linear infinite;
  }
  .orbit:nth-child(2) { animation-duration: 3.5s; animation-delay: -0.5s; width: 180%; }

  @keyframes rotate-orbit {
    0% { transform: translate(-50%, -50%) rotate(0deg) scale(1); }
    50% { transform: translate(-50%, -50%) rotate(180deg) scale(1.1); }
    100% { transform: translate(-50%, -50%) rotate(360deg) scale(1); }
  }

  #explosion-overlay {
    position: fixed;
    top: 0; left: 0; width: 100%; height: 100%;
    background: #00eaff;
    opacity: 0;
    pointer-events: none;
    z-index: 999;
  }
  .flash-active { animation: flash-anim 0.7s ease-out; }
  @keyframes flash-anim { 0% { opacity: 0; } 30% { opacity: 1; } 100% { opacity: 0; } }

  .hidden { display: none; }
  .card {
    background: rgba(0, 0, 0, 0.4); 
    border-radius: 25px;
    padding: 25px;
    box-shadow: 0 0 40px rgba(0, 234, 255, 0.3);
    border: 1.5px solid rgba(0, 234, 255, 0.7);
    max-width: 310px;
    backdrop-filter: blur(8px);
    animation: popIn 0.6s ease-out;
  }

  #countdown {
    display: flex;
    justify-content: space-around;
    background: rgba(0, 234, 255, 0.1);
    border-radius: 15px;
    padding: 12px;
    margin: 15px 0;
    border: 1px solid rgba(0, 234, 255, 0.2);
  }
  .time-box { font-size: 10px; text-transform: uppercase; color: #00eaff; }
  .time-box span { display: block; font-size: 22px; color: #fff; font-weight: bold; }

  @keyframes popIn { from { opacity: 0; transform: scale(0.7); } to { opacity: 1; transform: scale(1); } }
  .beer { position: fixed; top: -50px; font-size: 25px; animation: fall linear forwards; z-index: 100; }
  @keyframes fall { to { transform: translateY(110vh) rotate(360deg); opacity: 0; } }
  
  #player { position: absolute; width: 1px; height: 1px; opacity: 0; }
</style>
</head>
<body>

<div id="explosion-overlay"></div>

<iframe id="player" allow="autoplay"></iframe>

<div class="container" id="inicio">
  <h1>🚀 Você foi convocado 🚀</h1>
  <p style="opacity: 0.8;">Toque no reator para entrar na resenha</p>
  <div class="btn-container">
    <div class="orbit"></div>
    <div class="orbit"></div>
    <button class="btn-atom" onclick="entrar()">RESENHA</button>
  </div>
</div>

<div class="container hidden" id="convite">
  <div class="card">
    <h1>🔥 Resenha do Paulo Arthur 🔥</h1>
    <p style="margin: 5px 0;">🎂 Aniversário do brabo</p>
    <p style="font-size: 26px; color: #00eaff; font-weight: bold; margin: 5px 0; text-shadow: 0 0 10px #00eaff;">15/03</p>

    <div id="countdown">
      <div class="time-box"><span id="days">00</span>Dias</div>
      <div class="time-box"><span id="hours">00</span>Hrs</div>
      <div class="time-box"><span id="mins">00</span>Min</div>
    </div>

    <p style="font-size: 15px;">📍 <strong>Sítio Agrovale</strong></p>
    <p style="font-size: 15px;">🎤 No som: <strong>PH Maia</strong></p>
    <p style="font-size: 16px; margin-top: 15px; color: #fff; line-height: 1.4; font-weight: 500;">🍻 Até o Zeca já confirmou,<br>agora só falta você!</p>
    
    <button class="btn-atom" onclick="confirmar()" style="margin-top:15px; font-size: 14px; padding: 12px 25px; animation: none;">Confirmar presença ✅</button>
  </div>
</div>

<script>
function entrar() {
  const iframe = document.getElementById('player');
  // Carrega a música SEM MUDO direto no clique (isso resolve o problema do som)
  iframe.src = "https://www.youtube.com/embed/_H_171CJYHM?autoplay=1&start=28&playlist=_H_171CJYHM&loop=1";

  document.getElementById('explosion-overlay').classList.add('flash-active');
  
  setTimeout(() => {
    document.getElementById('inicio').classList.add('hidden');
    document.getElementById('convite').classList.remove('hidden');
    
    const imgZeca = "https://adnews.nyc3.digitaloceanspaces.com/media/7f0dd8bf7d9db02ccee77ccfbd27ed9d.jpg";
    document.body.style.background = `linear-gradient(rgba(0,0,0,0.4), rgba(0,0,0,0.4)), url('${imgZeca}') no-repeat center center fixed`;
    document.body.style.backgroundSize = "cover";
    startTimer();
  }, 300);
}

function startTimer() {
  const eventDate = new Date("March 15, 2026 14:00:00").getTime();
  setInterval(() => {
    const now = new Date().getTime();
    const diff = eventDate - now;
    if (diff > 0) {
      document.getElementById('days').innerText = Math.floor(diff / (1000 * 60 * 60 * 24));
      document.getElementById('hours').innerText = Math.floor((diff % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
      document.getElementById('mins').innerText = Math.floor((diff % (1000 * 60 * 60)) / (1000 * 60));
    }
  }, 1000);
}

function confirmar(){
  soltarCerveja();
  setTimeout(() => {
    // Número atualizado 61 993190917
    window.location.href='https://wa.me/5561993190917?text=Até%20o%20Zeca%20confirmou,%20eu%20não%20fico%20de%20fora!%20Confirmado!%20🍻';
  }, 1500);
}

function soltarCerveja(){
  for(let i=0;i<30;i++){
    const b = document.createElement('div');
    b.classList.add('beer'); b.innerText='🍺';
    b.style.left = Math.random()*100+'vw';
    b.style.animationDuration = (Math.random()*2+2)+'s';
    document.body.appendChild(b);
    setTimeout(() => b.remove(), 4000);
  }
}
</script>
</body>
</html>
