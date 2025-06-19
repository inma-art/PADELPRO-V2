<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Tienda de Pádel</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      background-color: #e6f5ea;
      color: #2e4d2e;
      margin: 0;
      padding: 0;
    }

    header {
      background-color: #a0dab0;
      text-align: center;
      padding: 1rem 0;
      box-shadow: 0 2px 4px rgba(0,0,0,0.1);
    }

    header h1 {
      margin: 0;
      font-size: 2rem;
    }

    nav ul {
      list-style: none;
      padding: 0;
      display: flex;
      justify-content: center;
      gap: 2rem;
      margin-top: 0.5rem;
    }

    nav a {
      text-decoration: none;
      color: #2e4d2e;
      font-weight: bold;
    }

    main {
      padding: 2rem;
    }

    section {
      margin-bottom: 3rem;
    }

    .producto {
      background-color: #ffffff;
      border: 1px solid #c0eac4;
      border-radius: 10px;
      padding: 1rem;
      text-align: center;
      max-width: 300px;
      margin: 1rem auto;
      box-shadow: 0 4px 8px rgba(0,0,0,0.05);
    }

    .producto img {
      max-width: 100%;
      border-radius: 8px;
    }

    .producto a {
      display: inline-block;
      margin-top: 0.5rem;
      padding: 0.5rem 1rem;
      background-color: #76c893;
      color: #fff;
      border-radius: 5px;
      text-decoration: none;
    }

    .producto a:hover {
      background-color: #5eb47f;
    }

    footer {
      background-color: #a0dab0;
      text-align: center;
      padding: 1rem;
      font-size: 0.9rem;
    }
  </style>
</head>
<body>
  <header>
    <h1>Tienda de Pádel</h1>
    <nav>
      <ul>
        <li><a href="#palas">Palas</a></li>
        <li><a href="#zapatillas">Zapatillas</a></li>
        <li><a href="#accesorios">Accesorios</a></li>
      </ul>
    </nav>
  </header>

  <main>
    <section id="palas">
      <h2>Palas de Pádel</h2>
      <div class="producto">
        <img src="https://via.placeholder.com/200" alt="Pala de Pádel" />
        <h3>Pala Avanzada</h3>
        <p>Control y potencia profesional.</p>
        <a href="https://www.amazon.es/dp/ejemplo1?tag=tu-tag" target="_blank">Ver en Amazon</a>
      </div>
    </section>

    <section id="zapatillas">
      <h2>Zapatillas</h2>
      <div class="producto">
        <img src="https://via.placeholder.com/200" alt="Zapatillas" />
        <h3>Zapatillas Ultra Agarre</h3>
        <p>Perfectas para pista rápida.</p>
        <a href="https://www.amazon.es/dp/ejemplo2?tag=tu-tag" target="_blank">Ver en Amazon</a>
      </div>
    </section>

    <section id="accesorios">
      <h2>Accesorios</h2>
      <div class="producto">
        <img src="https://via.placeholder.com/200" alt="Accesorios" />
        <h3>Muñequeras</h3>
        <p>Comodidad y estilo en cada partido.</p>
        <a href="https://www.amazon.es/dp/ejemplo3?tag=tu-tag" target="_blank">Ver en Amazon</a>
      </div>
    </section>
  </main>

  <footer>
    <p>&copy; 2025 Tienda de Pádel - Enlaces afiliados de Amazon.</p>
  </footer>
</body>
</html>
