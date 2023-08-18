# web-design-toolkit
Diseño web

<!--Codigo para un sitio web de diseño básico -->

<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>Sitio Web de Creación y Diseño Web</title>
</head>
<body>
    <header>
        <h1>Mi Sitio de Creación y Diseño Web</h1>
        <nav>
            <ul>
                <li><a href="#">Inicio</a></li>
                <li><a href="#">Portafolio</a></li>
                <li><a href="#">Servicios</a></li>
                <li><a href="#">Contacto</a></li>
            </ul>
        </nav>
    </header>

    <section class="hero">
        <h2>Bienvenido a nuestro mundo creativo</h2>
        <p>Donde tus ideas toman forma en línea</p>
        <a href="#" class="cta-button">Ver Portafolio</a>
    </section>

    <section class="portfolio">
        <h2>Nuestro Portafolio</h2>
        <!-- Aquí podrías agregar tus proyectos -->
    </section>

    <section class="services">
        <h2>Nuestros Servicios</h2>
        <!-- Aquí podrías listar tus servicios -->
    </section>

    <footer>
        <p>&copy; 2023 Sitio de Creación y Diseño Web</p>
    </footer>
</body>
</html>

 


/* Estilos generales */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

/* Encabezado */
header {
    background-color: #333;
    color: white;
    padding: 10px 0;
    text-align: center;
}

header h1 {
    margin: 0;
}

nav ul {
    list-style: none;
    padding: 0;
}

nav li {
    display: inline;
    margin-right: 20px;
}

nav a {
    color: white;
    text-decoration: none;
}

/* Sección de héroe */
.hero {
    background-image: url('hero-background.jpg');
    background-size: cover;
    color: white;
    text-align: center;
    padding: 100px 0;
}

.cta-button {
    display: inline-block;
    background-color: #333;
    color: white;
    padding: 10px 20px;
    border-radius: 5px;
    text-decoration: none;
    margin-top: 20px;
}

/* Otras secciones y pie de página */
/* Puedes agregar más estilos para las otras secciones y el pie de página aquí */



