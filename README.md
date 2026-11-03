<!doctype html>
<html lang="es">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Cristofer | Marketing digital para negocios de Aiquile</title>
<meta name="description" content="Redes sociales, videos cortos y menús digitales con QR para negocios locales de Aiquile.">
<style>
  /* ====== 1) CAMBIA TUS COLORES AQUÍ (los de tu marca en Canva) ====== */
  :root{
    --color-principal:#1f6feb;
    --color-oscuro:#0f1b2d;
    --color-claro:#f5f7fb;
    --color-texto:#1c2430;
    --color-whatsapp:#25d366;
  }
  *{box-sizing:border-box;margin:0;padding:0}
  html{scroll-behavior:smooth}
  body{font-family:system-ui,-apple-system,"Segoe UI",Roboto,Arial,sans-serif;color:var(--color-texto);background:#fff;line-height:1.55;font-size:17px}
  img{max-width:100%;display:block}
  a{color:inherit}
  .wrap{max-width:960px;margin:0 auto;padding:0 20px}
  section{padding:56px 0}
  h1{font-size:clamp(1.9rem,6vw,2.8rem);line-height:1.15}
  h2{font-size:clamp(1.5rem,4.5vw,2rem);margin-bottom:8px}
  .sub{color:#5b6573;margin-bottom:28px}
  .btn{display:inline-block;background:var(--color-whatsapp);color:#fff;font-weight:700;text-decoration:none;padding:14px 24px;border-radius:999px;font-size:1.05rem}
  .btn.sec{background:transparent;border:2px solid #fff;margin-left:8px}

  /* Hero */
  header.hero{background:var(--color-oscuro);color:#fff;padding:64px 0 56px}
  .marca{display:inline-block;font-weight:700;letter-spacing:.5px;color:var(--color-principal);background:#fff;padding:4px 12px;border-radius:999px;font-size:.85rem;margin-bottom:18px}
  .hero p{margin:16px 0 28px;color:#d6deea;max-width:560px}

  /* Servicios */
  .grid{display:grid;gap:18px;grid-template-columns:repeat(auto-fit,minmax(240px,1fr))}
  .card{background:var(--color-claro);border-radius:16px;padding:24px}
  .card .ico{font-size:2rem;margin-bottom:10px}
  .card h3{margin-bottom:6px;font-size:1.15rem}

  /* Ejemplos */
  .ejemplos{background:var(--color-claro)}
  .ej{background:#fff;border-radius:16px;overflow:hidden;box-shadow:0 2px 10px rgba(0,0,0,.06)}
  .ej .foto{aspect-ratio:4/5;background:linear-gradient(135deg,var(--color-principal),var(--color-oscuro));display:flex;align-items:center;justify-content:center;color:#fff;font-weight:700;text-align:center;padding:16px}
  .ej .foto img{width:100%;height:100%;object-fit:cover}
  .ej .txt{padding:16px}
  .ej .txt small{color:#5b6573}

  /* Precios */
  .precio{display:flex;flex-direction:column;gap:6px}
  .precio .monto{font-size:1.8rem;font-weight:800;color:var(--color-principal)}
  .precio ul{padding-left:18px;font-size:.95rem}
  .destacado{border:2px solid var(--color-principal);background:#fff}
  .nota{margin-top:18px;font-size:.92rem;color:#5b6573}

  /* Pasos */
  .pasos{counter-reset:p;display:grid;gap:16px}
  .paso{display:flex;gap:16px;align-items:flex-start}
  .paso::before{counter-increment:p;content:counter(p);flex:0 0 40px;height:40px;border-radius:50%;background:var(--color-principal);color:#fff;font-weight:800;display:flex;align-items:center;justify-content:center}

  /* Contacto */
  .contacto{background:var(--color-oscuro);color:#fff;text-align:center}
  .contacto p{margin:12px auto 24px;color:#d6deea;max-width:520px}
  footer{padding:20px;text-align:center;font-size:.85rem;color:#5b6573}

  /* Botón flotante */
  .flotante{position:fixed;right:16px;bottom:16px;width:60px;height:60px;border-radius:50%;background:var(--color-whatsapp);display:flex;align-items:center;justify-content:center;box-shadow:0 4px 14px rgba(0,0,0,.3);text-decoration:none;font-size:1.9rem;z-index:10}
</style>
</head>
<body>

<header class="hero">
  <div class="wrap">
    <span class="marca" id="marca">TU MARCA</span>
    <h1>Tu negocio se ve mejor en redes y recibe más consultas por WhatsApp</h1>
    <p>Soy <strong id="nombre">Cristofer</strong>, de Aiquile. Manejo publicaciones, videos cortos y menús digitales para negocios de aquí. Te preparo 3 publicaciones de prueba sin costo.</p>
    <a class="btn wa" href="#">Pedir mis 3 publicaciones gratis</a>
  </div>
</header>

<section>
  <div class="wrap">
    <h2>Qué hago por tu negocio</h2>
    <p class="sub">Tres servicios concretos, sin complicaciones.</p>
    <div class="grid">
      <div class="card"><div class="ico">📸</div><h3>Publicaciones para redes</h3><p>Diseños con tus productos, textos claros y una llamada a escribirte por WhatsApp. Programadas con anticipación.</p></div>
      <div class="card"><div class="ico">🎬</div><h3>Videos cortos (reels)</h3><p>Videos de 10 a 15 segundos para Facebook, Instagram y TikTok que muestran lo mejor de tu negocio.</p></div>
      <div class="card"><div class="ico">📲</div><h3>Menú o catálogo digital con QR</h3><p>Una página con tus productos y precios, y un QR para la mesa o el mostrador. Tus clientes piden por WhatsApp.</p></div>
    </div>
  </div>
</section>

<section class="ejemplos">
  <div class="wrap">
    <h2>Ejemplos de mi trabajo</h2>
    <p class="sub">Trabajos de muestra para distintos rubros.</p>
    <div class="grid">
      <!-- ====== 2) PON TUS IMÁGENES en una carpeta "img": ejemplo1.jpg, ejemplo2.jpg, ejemplo3.jpg (menos de 500 KB cada una) ====== -->
      <div class="ej">
        <div class="foto"><img src="img/ejemplo1.jpg" alt="Publicaciones para un negocio de comida" loading="lazy" onerror="this.remove()"><span style="position:absolute"></span></div>
        <div class="txt"><strong>Negocio de comida</strong><br><small>6 publicaciones y 1 reel</small></div>
      </div>
      <div class="ej">
        <div class="foto"><img src="img/ejemplo2.jpg" alt="Publicaciones para un negocio de ropa o peluquería" loading="lazy" onerror="this.remove()"></div>
        <div class="txt"><strong>Ropa / peluquería</strong><br><small>6 publicaciones y calendario de 30 días</small></div>
      </div>
      <div class="ej">
        <div class="foto"><img src="img/ejemplo3.jpg" alt="Menú digital con código QR" loading="lazy" onerror="this.remove()"></div>
        <div class="txt"><strong>Menú digital con QR</strong><br><small><a href="https://TU-USUARIO.github.io/menu-demo/" target="_blank" rel="noopener">Ver el menú de ejemplo</a></small></div>
      </div>
    </div>
  </div>
</section>

<section>
  <div class="wrap">
    <h2>Precios</h2>
    <p class="sub">Pago por adelantado, sin permanencia obligatoria.</p>
    <div class="grid">
      <div class="card precio destacado">
        <h3>Mes de prueba</h3>
        <div class="monto">Bs 145</div>
        <ul><li>8 publicaciones</li><li>1 reel</li><li>WhatsApp Business configurado</li></ul>
        <small>Solo el primer mes</small>
      </div>
      <div class="card precio">
        <h3>Básico</h3>
        <div class="monto">desde Bs 290</div>
        <ul><li>8 publicaciones al mes</li><li>2 historias</li><li>Respuestas rápidas</li></ul>
      </div>
      <div class="card precio">
        <h3>Medio</h3>
        <div class="monto">desde Bs 490</div>
        <ul><li>12 publicaciones</li><li>2 reels</li><li>Calendario de contenido</li><li>Catálogo de WhatsApp</li></ul>
      </div>
      <div class="card precio">
        <h3>Completo</h3>
        <div class="monto">desde Bs 790</div>
        <ul><li>16 publicaciones</li><li>4 reels</li><li>Menú o catálogo digital</li><li>Reporte mensual</li></ul>
      </div>
    </div>
    <p class="nota"><strong>Menú digital con QR:</strong> desde Bs 150, pago único. Los precios son referenciales y se ajustan a tu negocio.</p>
  </div>
</section>

<section class="ejemplos">
  <div class="wrap">
    <h2>Cómo trabajamos</h2>
    <div class="pasos" style="margin-top:24px">
      <div class="paso"><div><strong>Me escribes por WhatsApp.</strong><br>Me cuentas de tu negocio y qué quieres mostrar.</div></div>
      <div class="paso"><div><strong>Te envío 3 publicaciones de prueba, gratis.</strong><br>Las ves y me dices qué cambiarías.</div></div>
      <div class="paso"><div><strong>Si te gustan, empezamos el mes de prueba.</strong><br>Tú recibes todo ordenado y yo te envío un reporte semanal simple.</div></div>
    </div>
  </div>
</section>

<section class="contacto">
  <div class="wrap">
    <h2>¿Empezamos?</h2>
    <p>Escríbeme y mañana mismo preparo tus 3 publicaciones de prueba, sin costo y sin compromiso.</p>
    <a class="btn wa" href="#">Escribir por WhatsApp</a>
  </div>
</section>

<footer>© <span id="anio"></span> <span id="marca2">TU MARCA</span> · Aiquile, Cochabamba, Bolivia</footer>

<a class="flotante wa" href="#" aria-label="Escribir por WhatsApp">💬</a>

<script>
  /* ====== 3) CAMBIA ESTOS DATOS ====== */
  var CONFIG = {
    nombre: "Cristofer",
    marca:  "TU MARCA",            // ejemplo: "Cristofer Digital"
    whatsapp: "59171765682",       // 591 + tu número, sin espacios ni signos
    mensaje: "Hola, vi tu portafolio y me interesa recibir las 3 publicaciones de prueba para mi negocio."
  };

  document.getElementById("nombre").textContent = CONFIG.nombre;
  document.getElementById("marca").textContent  = CONFIG.marca;
  document.getElementById("marca2").textContent = CONFIG.marca;
  document.getElementById("anio").textContent   = new Date().getFullYear();
  var link = "https://wa.me/" + CONFIG.whatsapp + "?text=" + encodeURIComponent(CONFIG.mensaje);
  document.querySelectorAll(".wa").forEach(function(a){ a.href = link; a.target = "_blank"; a.rel = "noopener"; });
</script>
</body>
</html>
