<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Página Web Simple</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f0f0;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #444;
            padding: 10px 0;
        }
        nav a {
            color: white;
            padding: 10px 20px;
            text-decoration: none;
            text-align: center;
        }
        nav a:hover {
            background-color: #555;
        }
        .content {
            padding: 20px;
        }
        footer {
            text-align: center;
            padding: 10px;
            background-color: #333;
            color: white;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>

<header>
    <h1>Bienvenido a mi página web</h1>
</header>

<nav>
    <a href="#home">Inicio</a>
    <a href="#about">Sobre mí</a>
    <a href="#contact">Contacto</a>
</nav>

<div class="content">
    <h2>Contenido principal</h2>
    <p>Este es un ejemplo simple de una página web. Puedes agregar más contenido aquí.</p>
</div>

<footer>
    <p>&copy; 2025 Mi Página Web</p>
</footer>

</body>
</html>

