<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Portafolio Profesional - Jheferson Rodriguez G</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;600&display=swap" rel="stylesheet">
  <style>
    * {margin:0; padding:0; box-sizing:border-box; font-family:'Poppins', sans-serif;}
    body {background:#0e0e0e; color:#fff; line-height:1.6;}
    header {background:#111; padding:20px; text-align:center;}
    header h1 {font-size:2.2rem; color:#f1c40f;}
    nav a {margin:0 15px; color:#bbb; text-decoration:none; font-weight:500;}
    nav a:hover {color:#f1c40f;}
    section {padding:60px 20px; max-width:1100px; margin:auto;}
    .intro {text-align:center;}
    .intro h2 {font-size:2rem; margin-bottom:15px;}
    .grid {display:grid; grid-template-columns:repeat(auto-fit, minmax(280px,1fr)); gap:20px; margin-top:30px;}
    .card {background:#1a1a1a; padding:20px; border-radius:12px; box-shadow:0 4px 8px rgba(0,0,0,0.3);}
    .card img, 
    .card iframe, 
    .card video {width:100%; border-radius:10px;}
    .card h3 {margin-top:15px; color:#f1c40f;}
    footer {background:#111; text-align:center; padding:20px; margin-top:40px; font-size:0.9rem; color:#888;}
    .btn {display:inline-block; margin-top:20px; padding:12px 20px; background:#f1c40f; color:#000; border-radius:8px; font-weight:600; text-decoration:none;}
    .btn:hover {background:#d4ac0d;}
  </style>
</head>
<body>

  <header>
    <h1>Jheferson Rodriguez G</h1>
    <p>Editor Profesional | Video | Marketing Digital</p>
    <nav>
      <a href="#sobre-mi">Sobre mí</a>
      <a href="#proyectos">Proyectos</a>
      <a href="#videos">Videos</a>
      <a href="#contacto">Contacto</a>
    </nav>
  </header>

  <section id="sobre-mi" class="intro">
    <h2>Sobre mí</h2>
    <p>
      Soy un editor profesional con experiencia en <strong>DaVinci Resolve (Fusion)</strong> y en la gestión de <strong>Marketing Digital</strong>. 
      Me especializo en crear contenido audiovisual de alto impacto, narrativas visuales atractivas y estrategias creativas adaptadas a diferentes plataformas.
    </p>
    <a class="btn" href="#contacto">Contáctame</a>
  </section>

  <section id="proyectos">
    <h2 style="text-align:center;">Proyectos Destacados</h2>
    <div class="grid">
      <div class="card">
        <img src="https://via.placeholder.com/400x250" alt="Proyecto 1">
        <h3>Proyecto Audiovisual 1</h3>
        <p>Edición y montaje profesional con enfoque narrativo.</p>
      </div>
      <div class="card">
        <img src="https://via.placeholder.com/400x250" alt="Proyecto 2">
        <h3>Proyecto Audiovisual 2</h3>
        <p>Creación de contenido visual dinámico y atractivo.</p>
      </div>
      <div class="card">
        <img src="https://via.placeholder.com/400x250" alt="Proyecto 3">
        <h3>Proyecto Audiovisual 3</h3>
        <p>Producción y edición optimizada para redes sociales.</p>
      </div>
    </div>
  </section>

  <section id="videos">
    <h2 style="text-align:center;">Muestras en Video</h2>
    <div class="grid">
      <div class="card">
        <iframe width="100%" height="250" 
                src="https://www.youtube.com/embed/Fxp_Y4SchAI" 
                title="Video de muestra 1" 
                frameborder="0" 
                allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
                allowfullscreen>
        </iframe>
        <h3>Edición Creativa 1</h3>
        <p>Muestra de edición avanzada con DaVinci Resolve.</p>
      </div>
      <div class="card">
        <iframe width="100%" height="250" 
                src="https://www.youtube.com/embed/8FGg-CpNTHk" 
                title="Video de muestra 2" 
                frameborder="0" 
                allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
                allowfullscreen>
        </iframe>
        <h3>Motion Graphics</h3>
        <p>Animaciones y composición visual profesional.</p>
      </div>
      <div class="card">
        <iframe width="100%" height="250" 
                src="https://www.youtube.com/embed/OnJfv1aKxF4" 
                title="Video de muestra 3" 
                frameborder="0" 
                allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
                allowfullscreen>
        </iframe>
        <h3>Spot Publicitario</h3>
        <p>Edición y montaje para campañas visuales.</p>
      </div>
    </div>
  </section>

  <section id="contacto" class="intro">
    <h2>Contacto</h2>
    <p>Si deseas trabajar conmigo o conocer más de mi portafolio, escríbeme:</p>
    <p>Email: <strong>rodriguezjheferson1@gmail.com</strong></p>
    <p>Teléfono/WhatsApp: <strong>+1 849 450 4306</strong></p>
    <a class="btn" href="mailto:rodriguezjheferson1@gmail.com">Enviar correo</a>
  </section>

  <footer>
    <p>© 2025 Jheferson Rodriguez G - Todos los derechos reservados.</p>
  </footer>

</body>

</html>
