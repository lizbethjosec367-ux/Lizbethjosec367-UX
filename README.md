<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Lizbeth Elena Josec Ruelas | CV</title>
  <meta name="description" content="CV de Lizbeth Elena Josec Ruelas, técnica en Arquitectura de Plataformas y Servicios de Tecnologías de la Información (APSTI).">
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;500;600;700;800&display=swap" rel="stylesheet">
  <style>
    :root {
      --oscuro: #12343b;
      --oscuro-2: #0e2a30;
      --acento: #1aa6a6;
      --claro: #7fd6d6;
      --texto: #3a4a50;
    }
    * { box-sizing: border-box; margin: 0; padding: 0; }
    body {
      font-family: 'Montserrat', system-ui, sans-serif;
      background: #e9eef0;
      color: var(--texto);
      padding: 32px 16px;
    }
    .cv {
      max-width: 900px;
      margin: 0 auto;
      display: flex;
      background: #fff;
      box-shadow: 0 8px 30px rgba(18, 52, 59, 0.18);
      min-height: 1100px;
    }

    /* Columna lateral */
    .lateral {
      width: 300px;
      flex: none;
      background: var(--oscuro);
      color: #fff;
    }
    .foto-caja {
      background: var(--oscuro-2);
      padding: 40px 0 30px;
      display: flex;
      justify-content: center;
    }
    .foto-caja img {
      width: 170px;
      height: 170px;
      border-radius: 50%;
      object-fit: cover;
      object-position: center top;
      border: 5px solid var(--acento);
    }
    .lateral-cuerpo { padding: 30px 0 40px; }
    .lateral h2 {
      background: var(--acento);
      color: #fff;
      font-size: 13px;
      font-weight: 700;
      letter-spacing: 2px;
      padding: 8px 26px;
      margin-bottom: 14px;
    }
    .bloque { margin-bottom: 28px; }
    .bloque-contenido { padding: 0 26px; font-size: 12px; line-height: 1.5; }
    .dato { margin-bottom: 12px; }
    .dato b { display: block; color: var(--claro); font-weight: 700; }
    .dato a { color: #fff; text-decoration: none; word-break: break-all; }
    .dato a:hover { text-decoration: underline; }
    .lista-simple div { margin-bottom: 9px; }

    /* Columna principal */
    .principal { flex: 1; min-width: 0; }
    .encabezado {
      padding: 48px 40px 28px;
      border-bottom: 4px solid var(--acento);
    }
    .encabezado h1 {
      font-size: 34px;
      line-height: 1.12;
      font-weight: 800;
      color: var(--oscuro);
      letter-spacing: 0.5px;
    }
    .encabezado p {
      margin-top: 12px;
      font-size: 12.5px;
      font-weight: 600;
      color: var(--acento);
      letter-spacing: 1px;
      line-height: 1.5;
      text-transform: uppercase;
    }
    .contenido { padding: 28px 40px 40px; }
    .seccion { margin-bottom: 28px; }
    .seccion h2 {
      font-size: 14px;
      font-weight: 700;
      letter-spacing: 2px;
      color: var(--oscuro);
      border-left: 5px solid var(--acento);
      padding-left: 12px;
      margin-bottom: 12px;
      text-transform: uppercase;
    }
    .seccion p { font-size: 12.5px; line-height: 1.7; }
    .item { margin-bottom: 14px; }
    .item h3 { font-size: 13px; font-weight: 700; color: var(--oscuro); line-height: 1.4; }
    .item .lugar { font-size: 12px; font-weight: 600; color: var(--acento); }
    .item p { margin-top: 2px; }
    .cursos { list-style: none; }
    .cursos li {
      position: relative;
      padding-left: 22px;
      margin-bottom: 12px;
      font-size: 12.5px;
      line-height: 1.45;
    }
    .cursos li::before {
      content: "";
      position: absolute;
      left: 0; top: 5px;
      width: 9px; height: 9px;
      border-radius: 50%;
      background: var(--acento);
    }
    .cursos b { color: var(--oscuro); display: block; }

    .acciones { max-width: 900px; margin: 0 auto 16px; text-align: right; }
    .acciones button {
      font-family: inherit;
      font-size: 13px;
      font-weight: 600;
      color: #fff;
      background: var(--acento);
      border: 0;
      border-radius: 6px;
      padding: 10px 18px;
      cursor: pointer;
    }
    .acciones button:hover { background: #148a8a; }

    /* Celular */
    @media (max-width: 720px) {
      body { padding: 0; }
      .acciones { padding: 12px; }
      .cv { flex-direction: column; min-height: 0; box-shadow: none; }
      .lateral { width: 100%; }
      .encabezado { padding: 32px 22px 22px; }
      .encabezado h1 { font-size: 26px; }
      .contenido { padding: 24px 22px 32px; }
    }

    /* Imprimir o guardar como PDF */
    @media print {
      @page { size: A4; margin: 0; }
      body { background: #fff; padding: 0; }
      .acciones { display: none; }
      .cv { box-shadow: none; max-width: none; min-height: 297mm; }
      * { -webkit-print-color-adjust: exact; print-color-adjust: exact; }
    }
  </style>
</head>
<body>

  <div class="acciones">
    <button onclick="window.print()">Descargar en PDF</button>
  </div>

  <main class="cv">

    <aside class="lateral">
      <div class="foto-caja">
        <img src="foto.jpg" alt="Foto de Lizbeth Elena Josec Ruelas">
      </div>

      <div class="lateral-cuerpo">

        <section class="bloque">
          <h2>CONTACTO</h2>
          <div class="bloque-contenido">
            <div class="dato"><b>Celular</b><a href="tel:+51991639790">991 639 790</a></div>
            <div class="dato"><b>Correo</b><a href="mailto:lizbethjosec367@gmail.com">lizbethjosec367@gmail.com</a></div>
            <div class="dato"><b>Ubicación</b>Santa Lucía, Lampa, Puno — Perú</div>
            <div class="dato"><b>GitHub</b><a href="https://github.com/Lizbethjosec367-UX">github.com/Lizbethjosec367-UX</a></div>
          </div>
        </section>

        <section class="bloque">
          <h2>APTITUDES</h2>
          <div class="bloque-contenido lista-simple">
            <div>Trabajo en equipo</div>
            <div>Responsabilidad y puntualidad</div>
            <div>Comunicación efectiva</div>
            <div>Resolución de problemas</div>
            <div>Adaptabilidad</div>
            <div>Aprendizaje rápido</div>
          </div>
        </section>

        <section class="bloque">
          <h2>HERRAMIENTAS</h2>
          <div class="bloque-contenido lista-simple">
            <div>Word, Excel y PowerPoint</div>
            <div>Git y GitHub</div>
