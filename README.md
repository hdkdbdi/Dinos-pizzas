# Dinos-pizzas
Pizzas
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Dinos Pizzas</title>

  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: #0e0e0e;
      color: #fff;
    }

    header {
      background: linear-gradient(135deg, #1e7f3b, #f5a623);
      text-align: center;
      padding: 20px 10px;
    }

    header img {
      width: 160px;
    }

    nav {
      display: flex;
      justify-content: space-around;
      background-color: #000;
      padding: 12px 0;
      position: sticky;
      top: 0;
      z-index: 10;
    }

    nav a {
      color: #f5a623;
      text-decoration: none;
      font-weight: bold;
      font-size: 14px;
    }

    section {
      padding: 25px 15px;
    }

    h1, h2 {
      text-align: center;
      color: #f5a623;
    }

    .hero p {
      text-align: center;
      font-size: 15px;
      color: #ddd;
    }

    .menu-img {
      width: 100%;
      border-radius: 12px;
      margin-top: 15px;
      box-shadow: 0 0 15px rgba(0,0,0,0.6);
    }

    .btn {
      display: block;
      width: fit-content;
      margin: 20px auto;
      background-color: #25D366;
      color: #000;
      padding: 14px 25px;
      border-radius: 30px;
      text-decoration: none;
      font-weight: bold;
      font-size: 16px;
    }

    footer {
      background-color: #000;
      text-align: center;
      padding: 20px;
      font-size: 13px;
      color: #aaa;
    }
  </style>
</head>

<body>

  <header>
    <img src="logo.png" alt="Dinos Pizzas">
  </header>

  <nav>
    <a href="#inicio">Inicio</a>
    <a href="#menu">Menú</a>
    <a href="#contacto">Contacto</a>
  </nav>

  <section id="inicio" class="hero">
    <h1>Las pizzas más salvajes 🦖🍕</h1>
    <p>Sabor jurásico, ingredientes de calidad y el mejor precio</p>
  </section>

  <section id="menu">
    <h2>🍕 Nuestro Menú</h2>
    <p style="text-align:center;font-size:14px;">
      Desliza y amplía para ver todos los precios y especialidades
    </p>

    <img src="menu.jpg" alt="Menú Dinos Pizzas" class="menu-img">
  </section>

  <section id="contacto">
    <h2>📞 Contacto</h2>

    <p style="text-align:center;">
      🕕 <strong>Horario:</strong><br>
      Todos los días de 6:00 p.m. a 11:00 p.m.
    </p>

    <p style="text-align:center; margin-top:15px;">
      📱 <strong>WhatsApp:</strong><br>
      996 107 0587
    </p>

    <a class="btn" href="https://wa.me/529961070587">
      Escribir por WhatsApp
    </a>

    <p style="text-align:center; margin-top:20px;">
      ☎️ <strong>Llamadas:</strong><br>
      996 730 7086<br>
      996 112 0192<br>
      996 431 0263
    </p>
  </section>

  <footer>
    © 2026 Dinos Pizzas · Todos los derechos reservados
  </footer>

</body>
</html>
