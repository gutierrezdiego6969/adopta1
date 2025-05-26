<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Adopta con Amor</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #fefefe;
      color: #333;
    }
    header {
      background-color: #ff7043;
      color: white;
      padding: 1rem;
      text-align: center;
    }
    nav {
      background-color: #ffe0b2;
      padding: 1rem;
      text-align: center;
    }
    nav a {
      margin: 0 15px;
      text-decoration: none;
      color: #333;
      font-weight: bold;
    }
    section {
      padding: 2rem;
      max-width: 1000px;
      margin: auto;
    }
    .galeria {
      display: flex;
      flex-wrap: wrap;
      gap: 1rem;
      justify-content: center;
    }
    .galeria img {
      width: 250px;
      border-radius: 8px;
    }
    form {
      display: flex;
      flex-direction: column;
      gap: 1rem;
      max-width: 500px;
      margin: auto;
    }
    input, textarea, button {
      padding: 10px;
      font-size: 1rem;
    }
    button {
      background-color: #ff7043;
      color: white;
      border: none;
      cursor: pointer;
    }
    footer {
      text-align: center;
      padding: 1rem;
      background-color: #ffe0b2;
      font-size: 0.9rem;
    }
    @media (max-width: 600px) {
      .galeria {
        flex-direction: column;
        align-items: center;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>Adopta con Amor</h1>
    <p>Concientizando sobre la adopción de perritos de refugios</p>
  </header>

  <nav>
    <a href="#sobre-nosotros">Sobre Nosotros</a>
    <a href="#galeria">Galería</a>
    <a href="#comentarios">Comentarios</a>
  </nav>

  <section id="sobre-nosotros">
    <h2>Nuestra Misión</h2>
    <p>
      Somos una institución dedicada a impartir pláticas en escuelas, empresas y comunidades para crear conciencia sobre la importancia de adoptar perritos que viven en refugios. Creemos que cada vida cuenta, y que un hogar amoroso puede cambiarlo todo.
    </p>
  </section>

  <section id="galeria">
    <h2>Galería de Pláticas</h2>
    <div class="galeria">
      <img src="https://via.placeholder.com/250x180?text=Platica+1" alt="Plática 1">
      <img src="https://via.placeholder.com/250x180?text=Platica+2" alt="Plática 2">
      <img src="https://via.placeholder.com/250x180?text=Platica+3" alt="Plática 3">
    </div>
  </section>

  <section id="comentarios">
    <h2>Deja tu Comentario</h2>
    <form>
      <input type="text" name="nombre" placeholder="Tu nombre" required>
      <textarea name="comentario" rows="4" placeholder="Escribe tu comentario..." required></textarea>
      <button type="submit">Enviar</button>
    </form>
  </section>

  <footer>
    &copy; 2025 Adopta con Amor - Todos los derechos reservados
  </footer>

</body>
</html>
