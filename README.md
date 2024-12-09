<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portal de Videojuegos Avanzado</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #1a1a1a;
            color: #fff;
        }
        header {
            background-image: linear-gradient(90deg, #1e90ff, #00bfff);
            padding: 30px;
            text-align: center;
            color: #fff;
        }
        header h1 {
            margin: 0;
            font-size: 3em;
            animation: fadeIn 2s;
        }
        header p {
            font-size: 1.2em;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #333;
            padding: 10px 0;
        }
        nav a {
            color: #fff;
            text-decoration: none;
            margin: 0 15px;
            font-size: 1.1em;
            transition: color 0.3s;
        }
        nav a:hover {
            color: #1e90ff;
        }
        .container {
            padding: 20px;
            max-width: 1200px;
            margin: auto;
        }
        .game-list, .news-section, .contact {
            margin-bottom: 50px;
        }
        .game-list h2, .news-section h2, .contact h2 {
            border-bottom: 3px solid #1e90ff;
            display: inline-block;
            padding-bottom: 5px;
        }
        .game-list ul {
            list-style: none;
            padding: 0;
        }
        .game-list li {
            padding: 10px;
            background-color: #282828;
            margin-bottom: 10px;
            border-radius: 5px;
        }
        .game-list li:hover {
            background-color: #1e90ff;
            color: #000;
        }
        .gallery {
            display: flex;
            gap: 15px;
            flex-wrap: wrap;
        }
        .gallery img {
            width: 100%;
            max-width: 300px;
            border-radius: 10px;
            transition: transform 0.3s, box-shadow 0.3s;
        }
        .gallery img:hover {
            transform: scale(1.1);
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.5);
        }
        footer {
            text-align: center;
            padding: 20px;
            background-color: #333;
            color: #fff;
        }
        footer p {
            margin: 0;
        }
        @keyframes fadeIn {
            from {
                opacity: 0;
                transform: translateY(-20px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Portal de Videojuegos</h1>
        <p>¡Explora el mundo de los videojuegos como nunca antes!</p>
    </header>
    <nav>
        <a href="#games">Videojuegos</a>
        <a href="#gallery">Galería</a>
        <a href="#news">Noticias</a>
        <a href="#contact">Contacto</a>
    </nav>
    <div class="container">
        <section id="games" class="game-list">
            <h2>Lista de Videojuegos</h2>
            <ul>
                <li>The Legend of Zelda: Tears of the Kingdom</li>
                <li>Cyberpunk 2077: Phantom Liberty</li>
                <li>Hogwarts Legacy</li>
                <li>Call of Duty: Modern Warfare II</li>
                <li>Resident Evil 4 (Remake)</li>
            </ul>
        </section>
        <section id="gallery">
            <h2>Galería de Videojuegos</h2>
            <div class="gallery">
                <img src="https://via.placeholder.com/300x200?text=Zelda" alt="Zelda">
                <img src="https://via.placeholder.com/300x200?text=Cyberpunk" alt="Cyberpunk">
                <img src="https://via.placeholder.com/300x200?text=Hogwarts" alt="Hogwarts Legacy">
                <img src="https://via.placeholder.com/300x200?text=COD" alt="Call of Duty">
                <img src="https://via.placeholder.com/300x200?text=RE4" alt="Resident Evil 4">
            </div>
        </section>
        <section id="news" class="news-section">
            <h2>Noticias Recientes</h2>
            <p>📰 *Zelda* rompe récords de ventas en 2024.</p>
            <p>📰 *Cyberpunk 2077* presenta una actualización gratuita.</p>
            <p>📰 *Hogwarts Legacy* lidera nominaciones en los Game Awards.</p>
        </section>
        <section id="contact" class="contact">
            <h2>Contacto</h2>
            <p>Para sugerencias o consultas, escríbenos a: <a href="mailto:soporte@videojuegos.com" style="color: #1e90ff;">soporte@videojuegos.com</a></p>
        </section>
    </div>
    <footer>
        <p>&copy; 2024 Portal de Videojuegos. Diseñado con pasión por gamers.</p>
    </footer>
</body>
</html> 
