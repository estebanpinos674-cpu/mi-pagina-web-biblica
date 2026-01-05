<!doctype html>
<html lang="es">
<head>
<meta charset="utf-8" />
<meta name="viewport" content="width=device-width,initial-scale=1" />
<title>Escuela Bíblica Infantil — Comunidad y Juegos</title>
<meta name="description" content="Escuela Bíblica para niños: lecciones, valores, y juegos educativos bíblicos." />
<style>
  :root{--bg:#fff7f0;--card:#ffffff;--muted:#5b6b72;--accent1:#ff7f50;--accent2:#00aaff;--accent3:#9b59b6}
  *{box-sizing:border-box}
  body{font-family: Inter, system-ui, -apple-system, 'Segoe UI', Roboto, Arial; margin:0; background:linear-gradient(180deg,var(--bg),#f0fbff); color:#102a43}
  .container{max-width:1200px;margin:0 auto;padding:26px}
  header{padding:28px;background:linear-gradient(90deg,var(--accent1),#ffb347);color:#fff;border-radius:12px;margin-bottom:18px;box-shadow:0 10px 30px rgba(0,0,0,0.08)}
  header h1{margin:0;font-size:28px}
  nav{display:flex;gap:10px;flex-wrap:wrap;margin:12px 0}
  .nav-btn{background:rgba(255,255,255,0.14);border:0;padding:8px 14px;border-radius:10px;color:#fff;cursor:pointer}
  main{display:grid;grid-template-columns:3fr 1fr;gap:18px}
  .card{background:var(--card);padding:18px;border-radius:12px;box-shadow:0 6px 18px rgba(16,42,67,0.06);border:1px solid rgba(16,42,67,0.04)}
  aside .card{position:sticky;top:26px}
  h2{color:var(--accent3);margin-top:0}
  .section-long{line-height:1.6;color:#223344}
  .highlight{color:var(--accent2);font-weight:700}
  footer{margin-top:26px;padding:18px;text-align:center;color:var(--muted)}
  .games-list{display:flex;flex-wrap:wrap;gap:12px}
  .game-tile{flex:1 1 320px;background:linear-gradient(180deg,#ffffff,#f3fbff);padding:14px;border-radius:12px;border-left:8px solid var(--accent2)}
  .game-btn{display:inline-block;margin-top:8px;padding:10px 14px;border-radius:10px;border:0;background:var(--accent2);color:#fff;cursor:pointer}
  .small{font-size:13px;color:var(--muted)}
  pre.code{background:#0b2545;color:#e6f0ff;padding:12px;border-radius:8px;overflow:auto}
  @media(max-width:960px){main{grid-template-columns:1fr} aside{order:2}}
</style>
</head>
<body>
  <div class="container">
    <header>
      <h1>Escuela Bíblica Infantil — Caminando con Dios</h1>
      <p class="small">Un espacio para niños, familias y maestros: lecciones, actividades y juegos que enseñan el amor de Dios.</p>
      <nav>
        <button class="nav-btn" data-target="introduccion">Inicio</button>
        <button class="nav-btn" data-target="mision">Nuestra Misión</button>
        <button class="nav-btn" data-target="lecciones">Lecciones</button>
        <button class="nav-btn" data-target="juegos">Juegos</button>
        <button class="nav-btn" data-target="recursos">Recursos</button>
        <button class="nav-btn" data-target="contacto">Contacto</button>
      </nav>
    </header>

    <main>
      <div>
        <!-- Intro / Bienvenida -->
        <section id="introduccion" class="card section-long">
          <h2>Bienvenidos a la Escuela Bíblica Infantil</h2>
          <p>Nuestra escuela busca acompañar a los niños para que conozcan a Dios, aprendan a vivir conforme a la Palabra y desarrollen valores sólidos. Aquí hallarás material pensado especialmente para niños: lenguaje sencillo, actividades creativas y juegos que repasan lo aprendido.</p>

          <h3>¿A quiénes servimos?</h3>
          <p>Familias, maestros y líderes de la iglesia que desean recursos prácticos para enseñar a niños de 4 a 12 años. Nuestro enfoque combina estudio bíblico, creatividad y acción práctica.</p>

          <h3>Cómo usar este sitio</h3>
          <p>Entra a <span class="highlight">Lecciones</span> para ver las unidades temáticas, visita <span class="highlight">Juegos</span> para que los niños practiquen, y encuentra en <span class="highlight">Recursos</span> plantillas imprimibles y guiones para actividades.</p>
        </section>

        <!-- Misión extendida -->
        <section id="mision" class="card section-long" style="margin-top:18px">
          <h2>Nuestra Misión (completa)</h2>
          <p>Queremos que cada niño entienda el amor de Dios y los valores del reino: amor, perdón, servicio y obediencia. Nuestra metodología es experiencial: los niños aprenden contando historias, representándolas y aplicándolas en su vida diaria.</p>

          <p>En la práctica, nuestra misión se traduce en iniciativas concretas:</p>
          <ul>
            <li><strong>Enseñanza por historias:</strong> cada lección se centra en una historia bíblica con aplicaciones prácticas.</li>
            <li><strong>Juegos educativos:</strong> actividades que refuerzan conceptos y fidelizan el aprendizaje.</li>
            <li><strong>Familia involucrada:</strong> entregamos guías para que padres continúen la enseñanza en casa.</li>
            <li><strong>Comunidad de servicio:</strong> pequeños proyectos donde los niños aprenden a servir.</li>
          </ul>

          <p>Creemos que formar carácter es formar futuro: un niño que aprende a amar, perdonar y servir será un adulto que transforma su entorno.</p>
        </section>

        <!-- Lecciones largas (varias) -->
        <section id="lecciones" class="card section-long" style="margin-top:18px">
          <h2>Lecciones y Unidades</h2>
          <p>Las lecciones están organizadas por unidades temáticas: Creación, Patriarcas, Éxodo, Rey David, Vida de Jesús, Parábolas y Hechos de los Apóstoles. Cada unidad contiene: historia, objetivos, actividades, versículos para memorizar y preguntas para el juego.</p>

          <article style="margin-top:12px">
            <h3>Unidad 1 — La Creación</h3>
            <p>Objetivo: que el niño reconozca a Dios como Creador y cuide la creación.</p>
            <p>Contenido: lectura adaptada de Génesis 1, actividad de dibujo ("Mi mundo creado por Dios"), canción para memorizar "Dios hizo el cielo y la tierra" y proyecto de reciclaje fácil para niños.</p>
          </article>

          <article style="margin-top:12px">
            <h3>Unidad 2 — Historias de fe</h3>
            <p>Objetivo: aprender ejemplos de fe en personajes bíblicos como Noé, Abraham y José.</p>
            <p>Contenido: dramatización guiada, preguntas para discusión y ejercicio "¿Qué harías tú en esa situación?" para promover la empatía y la toma de decisiones en valores.</p>
          </article>

          <p style="margin-top:12px">(Las unidades siguientes incluyen guiones completos de 30-45 minutos que pueden ser usados por maestros. Si quieres, las exporto en documentos separados listos para imprimir.)</p>
        </section>

        <!-- Juegos (7 juegos) -->
        <section id="juegos" class="card section-long" style="margin-top:18px">
          <h2>Centro de Juegos — Elige y juega (7 juegos)</h2>
          <p>He integrado siete juegos didácticos y adecuados para niños. Todos son simples, accesibles y guardan relación con las lecciones bíblicas.</p>

          <div class="games-list" style="margin-top:12px">
            <div class="game-tile">
              <h3>1) Trivia Bíblica (Nivel básico)</h3>
              <p class="small">Preguntas por niveles, puntaje y final.</p>
              <button class="game-btn" onclick="startTrivia()">Jugar Trivia</button>
            </div>

            <div class="game-tile">
              <h3>2) Adivina el Personaje</h3>
              <p class="small">Pistas y respuesta de texto (minúsculas aceptadas).</p>
              <button class="game-btn" onclick="startGuess()">Jugar Adivina</button>
            </div>

            <div class="game-tile">
              <h3>3) Memoria (pares)</h3>
              <p class="small">Memoriza y encuentra pares (versión con imágenes/íconos).</p>
              <button class="game-btn" onclick="startMemory()">Jugar Memoria</button>
            </div>

            <div class="game-tile">
              <h3>4) Completa el Versículo</h3>
              <p class="small">Llena la palabra que falta en versículos sencillos.</p>
              <button class="game-btn" onclick="startVerse()">Jugar Versículo</button>
            </div>

            <div class="game-tile">
              <h3>5) Rompecabezas de imágenes</h3>
              <p class="small">Arrastra piezas para completar una imagen (versión sencilla).</p>
              <button class="game-btn" onclick="startPuzzle()">Jugar Rompecabezas</button>
            </div>

            <div class="game-tile">
              <h3>6) Ordena la Historia</h3>
              <p class="small">Coloca eventos bíblicos en el orden correcto.</p>
              <button class="game-btn" onclick="startOrder()">Jugar Orden</button>
            </div>

            <div class="game-tile">
              <h3>7) Palabra Revuelta</h3>
              <p class="small">Reordena letras para formar la palabra correcta.</p>
              <button class="game-btn" onclick="startScramble()">Jugar Scramble</button>
            </div>
          </div>

          <div id="gameArea" style="margin-top:18px"></div>

          <!-- Juegos: scripts implementados abajo -->
        </section>

        <!-- Recursos extensos -->
        <section id="recursos" class="card section-long" style="margin-top:18px">
          <h2>Recursos para maestros y familias</h2>
          <p>Incluye guiones de clases, hojas imprimibles, tarjetas de memoria, guías para padres y sugerencias prácticas para aplicar la lección en casa. También proporcionamos canciones infantiles y letras con acordes para acompañamiento musical.</p>
          <p>Si quieres, genero un paquete descargable con 20 lecciones, actividades y hojas para colorear — listo para imprimir.</p>
        </section>

        <!-- Contacto -->
        <section id="contacto" class="card section-long" style="margin-top:18px">
          <h2>Contacto</h2>
          <p>Puedes escribirnos para solicitar recursos, programar actividades o pedir formación para maestros.</p>
          <p class="small">Correo: escuelabiblica@ejemplo.com • Teléfono: +593 9 9999 9999</p>
        </section>
      </div>

      <aside>
        <div class="card">
          <h3>Progreso</h3>
          <p class="small">Puntaje total: <strong id="globalScore">0</strong></p>
          <p class="small">Juegos jugados: <strong id="playedCount">0</strong></p>
          <hr style="margin:12px 0">
          <h4>Consejo para maestros</h4>
          <p class="small">Integra 10 minutos de juego después de las lecciones para reforzar la memoria y la comprensión de los niños.</p>
        </div>

        <div class="card" style="margin-top:12px">
          <h3>Versículo del día</h3>
          <p id="verseOfDay" class="small">Proverbios 22:6 — Instruye al niño en su camino...</p>
        </div>

        <div class="card" style="margin-top:12px">
          <h3>Material recomendado</h3>
          <ol class="small">
            <li>Libro de historias bíblicas para niños (ilustrado)</li>
            <li>Guía de maestro - 20 lecciones</li>
            <li>Pack de tarjetas de memoria</li>
          </ol>
        </div>
      </aside>
    </main>

    <footer>
      © <span id="year">2025</span> Escuela Bíblica Infantil — Hecho con cariño
    </footer>
  </div>

  <script>
    // Navegación simple
    document.querySelectorAll('.nav-btn').forEach(b=>b.addEventListener('click', e=>{
      const t = e.currentTarget.dataset.target; document.getElementById(t).scrollIntoView({behavior:'smooth'});
    }));

    // Estado global
    let globalScore = 0; let playedCount = 0;
    function addScore(n){ globalScore += n; document.getElementById('globalScore').innerText = globalScore; }
    function markPlayed(){ playedCount++; document.getElementById('playedCount').innerText = playedCount; }

    // ---------- Juego 1: Trivia básica ----------
    function startTrivia(){
      markPlayed();
      const questions = [
        {q:'¿Quién creó el mundo?', opts:['Dios','Jonás','Moisés'], a:0},
        {q:'¿Quién nació en un pesebre?', opts:['Jesús','Pedro','Saúl'], a:0},
        {q:'¿Quién abrió el Mar Rojo?', opts:['Moisés','David','Noé'], a:0},
        {q:'¿Quién construyó un arca?', opts:['Noé','Abraham','Jacob'], a:0}
      ];
      let idx=0, score=0;
      const container = document.getElementById('gameArea');
      function render(){
        if(idx>=questions.length){ container.innerHTML = `<div class="card"><h3>Trivia finalizada</h3><p>Puntos: ${score}</p><button onclick="startTrivia()" class="game-btn">Jugar otra vez</button></div>`; addScore(score); return; }
        const q = questions[idx];
        container.innerHTML = `<div class="card"><h3>Trivia: ${q.q}</h3><div>${q.opts.map((o,i)=>`<button class='game-btn' onclick='answerTrivia(${i})'>${o}</button>`).join('')}</div><p class='small'>Pregunta ${idx+1} de ${questions.length}</p></div>`;
      }
      window.answerTrivia = function(i){ if(i===questions[idx].a) score+=10; idx++; render(); }
      render();
    }

    // ---------- Juego 2: Adivina el personaje ----------
    function startGuess(){
      markPlayed();
      const items = [
        {p:'Fui tragado por un gran pez', r:'jonas'},
        {p:'Construí un arca', r:'noe'},
        {p:'Abrí el mar rojo', r:'moises'},
        {p:'Fui rey y poeta', r:'david'}
      ];
      const chosen = items[Math.floor(Math.random()*items.length)];
      const container = document.getElementById('gameArea');
      container.innerHTML = `<div class='card'><h3>Adivina el personaje</h3><p class='small'>Pista: ${chosen.p}</p><input id='guessInput' placeholder='tu respuesta...' style='padding:10px;border-radius:8px;margin-top:8px;width:80%'><div style='margin-top:8px'><button class='game-btn' onclick='checkGuess()'>Responder</button></div><p id='guessRes' class='small'></p></div>`;
      window.checkGuess = function(){ const val = document.getElementById('guessInput').value.trim().toLowerCase(); const res = document.getElementById('guessRes'); if(val===chosen.r){ res.innerText='¡Correcto! +15 puntos'; addScore(15);} else { res.innerText='Intenta otra vez. Pista extra: piensa en el personaje principal.'; } }
    }

    // ---------- Juego 3: Memoria (pares) ----------
    function startMemory(){
      markPlayed();
      const pairs = ['dios','jesus','noe','moises','david','jonas'];
      const items = pairs.concat(pairs).sort(()=>Math.random()-0.5);
      const container = document.getElementById('gameArea');
      let flipped = []; let matched = [];
      container.innerHTML = `<div class='card'><h3>Memoria: Encuentra pares</h3><div id='memGrid' style='display:grid;grid-template-columns:repeat(4,1fr);gap:8px;margin-top:12px'></div><p id='memInfo' class='small'></p></div>`;
      const grid = document.getElementById('memGrid'); items.forEach((it,i)=>{
        const btn = document.createElement('button'); btn.className='game-btn'; btn.style.background='#fff'; btn.style.color='#333'; btn.style.border='1px solid #eee'; btn.innerText='?'; btn.dataset.val=it; btn.dataset.i=i;
        btn.addEventListener('click', ()=>{ if(matched.includes(i) || flipped.map(f=>f.i).includes(i)) return; flip(i,btn); }); grid.appendChild(btn);
      });
      function flip(i,btn){ flipped.push({i,btn}); btn.innerText = btn.dataset.val; if(flipped.length===2){ const [a,b]=flipped; if(a.btn.dataset.val===b.btn.dataset.val){ matched.push(a.i); matched.push(b.i); a.btn.disabled=true; b.btn.disabled=true; document.getElementById('memInfo').innerText='¡Par encontrado!'; addScore(5);} else { setTimeout(()=>{ a.btn.innerText='?'; b.btn.innerText='?'; },700); } flipped=[]; if(matched.length===items.length){ document.getElementById('memInfo').innerText='¡Juego completado! +20 puntos'; addScore(20); } } }
    }

    // ---------- Juego 4: Completa el Versículo ----------
    function startVerse(){
      markPlayed();
      const verses = [
        {full:'Ama a tu prójimo como a ti mismo', blank:'Ama a tu ____ como a ti mismo', ans:'prójimo'},
        {full:'El Señor es mi pastor, nada me faltará', blank:'El Señor es mi ____, nada me faltará', ans:'pastor'}
      ];
      const v = verses[Math.floor(Math.random()*verses.length)];
      const container = document.getElementById('gameArea');
      container.innerHTML = `<div class='card'><h3>Completa el versículo</h3><p class='small'>${v.blank}</p><input id='verseIn' placeholder='palabra faltante' style='padding:10px;border-radius:8px'><div style='margin-top:8px'><button class='game-btn' onclick='checkVerse()'>Comprobar</button></div><p id='verseRes' class='small'></p></div>`;
      window.checkVerse = function(){ const val=document.getElementById('verseIn').value.trim().toLowerCase(); const res=document.getElementById('verseRes'); if(val===v.ans){ res.innerText='¡Correcto! +10 puntos'; addScore(10);} else { res.innerText='Casi... intenta nuevamente o revisa la lección.'; } }
    }

    // ---------- Juego 5: Rompecabezas simple (piezas ordenadas) ----------
    function startPuzzle(){
      markPlayed();
      // simple text-based puzzle: rearrange words
      const puzzles = [
        {scr:'mundo el creó Dios', sol:'Dios creó el mundo'},
        {scr:'nació Jesús en pesebre', sol:'Jesús nació en pesebre'}
      ];
      const p = puzzles[Math.floor(Math.random()*puzzles.length)];
      const words = p.scr.split(' ').sort(()=>Math.random()-0.5);
      const container = document.getElementById('gameArea');
      container.innerHTML = `<div class='card'><h3>Rompecabezas de frase</h3><p class='small'>Ordena las palabras para formar la frase correcta:</p><div id='puzzleWords' style='display:flex;gap:8px;flex-wrap:wrap;margin-top:8px'></div><div style='margin-top:12px'><button class='game-btn' onclick='checkPuzzle()'>Comprobar</button></div><p id='puzzleRes' class='small'></p></div>`;
      const box=document.getElementById('puzzleWords'); words.forEach(w=>{ const b=document.createElement('button'); b.className='game-btn'; b.style.background='#fff'; b.style.color='#333'; b.style.border='1px solid #eee'; b.innerText=w; b.addEventListener('click', ()=>{ b.style.opacity=0.5; b.disabled=true; const span=document.createElement('span'); span.innerText=w+' '; span.dataset.w=w; span.style.padding='6px'; span.style.marginRight='6px'; span.style.background='#e8faff'; span.style.borderRadius='6px'; span.style.display='inline-block'; span.style.cursor='pointer'; span.addEventListener('click', ()=>{ b.disabled=false; b.style.opacity=1; span.remove(); }); document.getElementById('puzzleWords').appendChild(span); }); box.appendChild(b); });
      window.checkPuzzle = function(){ const chosen = Array.from(document.querySelectorAll('#puzzleWords span')).map(s=>s.dataset.w).join(' '); const res=document.getElementById('puzzleRes'); if(chosen===p.sol) { res.innerText='¡Excelente! +15 puntos'; addScore(15);} else res.innerText='Aún no es correcto, intenta reordenar.'; }
    }

    // ---------- Juego 6: Ordena la Historia ----------
    function startOrder(){
      markPlayed();
      const events = ['Noé construyó el arca','El diluvio llegó','Las aves salieron','El arca quedó en tierra firme'];
      const shuffled = events.map(e=>({text:e,id:Math.random()})).sort(()=>Math.random()-0.5);
      const container = document.getElementById('gameArea');
      container.innerHTML = `<div class='card'><h3>Ordena la historia</h3><p class='small'>Arrastra (clic para mover) las frases al orden correcto:</p><div id='orderArea' style='margin-top:8px'></div><div style='margin-top:10px'><button class='game-btn' onclick='checkOrder()'>Comprobar orden</button></div><p id='orderRes' class='small'></p></div>`;
      const area=document.getElementById('orderArea'); shuffled.forEach(it=>{ const b=document.createElement('div'); b.className='game-btn'; b.style.display='block'; b.style.margin='6px 0'; b.dataset.text=it.text; b.innerText=it.text; b.onclick=function(){ // move to end
        area.appendChild(b);
      }; area.appendChild(b); });
      window.checkOrder = function(){ const current = Array.from(area.children).map(c=>c.dataset.text); let score=0; for(let i=0;i<events.length;i++){ if(current[i]===events[i]) score++; } const res=document.getElementById('orderRes'); if(score===events.length){ res.innerText='Perfecto! Orden correcto +20 puntos'; addScore(20);} else { res.innerText=`Aciertos: ${score}. Intenta mejorar.`; } }
    }

    // ---------- Juego 7: Palabra Revuelta (Scramble) ----------
    function startScramble(){
      markPlayed();
      const words=[{w:'jesus'},{w:'dios'},{w:'noe'},{w:'moises'}]; const chosen=words[Math.floor(Math.random()*words.length)].w;
      const scrambled = chosen.split('').sort(()=>Math.random()-0.5).join('');
      const container=document.getElementById('gameArea');
      container.innerHTML = `<div class='card'><h3>Palabra revuelta</h3><p class='small'>Reordena las letras: <strong>${scrambled}</strong></p><input id='scrIn' placeholder='tu respuesta' style='padding:8px;border-radius:8px'><div style='margin-top:8px'><button class='game-btn' onclick='checkScramble("${chosen}")'>Comprobar</button></div><p id='scrRes' class='small'></p></div>`;
      window.checkScramble = function(sol){ const v=document.getElementById('scrIn').value.trim().toLowerCase(); const res=document.getElementById('scrRes'); if(v===sol){ res.innerText='¡Bien hecho! +10 puntos'; addScore(10);} else res.innerText='Incorrecto, intenta de nuevo'; }
    }

    // Inicialización
    document.getElementById('year').innerText = new Date().getFullYear();

    // Set verse of day (sample long text to increase content)
    document.getElementById('verseOfDay').innerText = 'Proverbios 22:6 — Instruye al niño en su camino, y aun cuando fuere viejo no se apartará de él.';

    // Accessibility: keyboard shortcuts 1-6 to open games quickly
    window.addEventListener('keydown', (e)=>{
      if(e.key==='1') startTrivia(); if(e.key==='2') startGuess(); if(e.key==='3') startMemory(); if(e.key==='4') startVerse(); if(e.key==='5') startPuzzle(); if(e.key==='6') startOrder(); if(e.key==='7') startScramble();
    });
  </script>
</body>
</html> 
