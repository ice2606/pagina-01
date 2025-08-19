# calzado-Narv-ez-castro
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Página Principal</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
            line-height: 1.6;
        }
        header {
            background: #50a1ff;
            color: #fff;
            padding: 1rem 0;
            text-align: center;
        }
        header h1 {
            margin: 0;
        }
        nav {
            background: #333;
            color: #fff;
            text-align: center;
            padding: 0.5rem 0;
        }
        nav a {
            color: #fff;
            text-decoration: none;
            padding: 0 15px;
        }
        nav a:hover {
            text-decoration: underline;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
            padding: 20px 0;
        }
        .main-content {
            background: #fff;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        footer {
            text-align: center;
            padding: 1rem 0;
            background: #333;
            color: #fff;
            margin-top: 20px;
        }
    </style>
</head>
<body>

    <header>
        <h1>Bienvenido a mi Página Principal</h1>
    </header>

    <nav>
        <a href="#inicio">Inicio</a>
        <a href="#acerca">Acerca de</a>
        <a href="#servicios">Servicios</a>
        <a href="#contacto">Contacto</a>
    </nav>

    <div class="container">
        <section id="inicio" class="main-content">
            <h2>Inicio</h2>
            <p>Este es el contenido de la sección de inicio. Puedes añadir texto, imágenes y cualquier otro elemento HTML aquí.</p>
            <p>¡Explora las diferentes secciones del sitio!</p>
        </section>

        <section id="acerca" class="main-content">
            <h2>Acerca de nosotros</h2>
            <p>Aquí puedes contar la historia de tu empresa, tu proyecto o sobre ti. Describe la misión, la visión y lo que te hace único.</p>
        </section>

        <section id="servicios" class="main-content">
            <h2>Nuestros Servicios</h2>
            <ul>
                <li>Servicio 1: Una breve descripción de lo que ofreces.</li>
                <li>Servicio 2: Otra descripción.</li>
                <li>Servicio 3: Y una más.</li>
            </ul>
        </section>
        
        <section id="contacto" class="main-content">
            <h2>Contacto</h2>
            <p>Puedes incluir tu información de contacto, como un formulario, correo electrónico o número de teléfono.</p>
            <p>Correo electrónico: <a href="mailto:tu.correo@ejemplo.com">tu.correo@ejemplo.com</a></p>
        </section>
    </div>

    <footer>
        <p>&copy; 2025 Mi Sitio Web. Todos los derechos reservados.</p>
    </footer>

</body>
</html>
