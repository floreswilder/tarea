<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tu Concierto</title>
    <link rel="stylesheet" href="css/style.css">
</head>
<body>
    <header>
        <h1>Tu concierto</h1>
        <p>Bienvenido a este blog de conciertos...</p>
    </header>
    <main>
        <img src="contenido1.png" alt="Concierto">
        <p>Información adicional sobre el concierto.</p>
    </main>
    <footer>
        <a href="#">Info</a>
    </footer>
</body>
</html>
/* Agrega esta regla al principio del archivo */
body p {
    color: green;
}

/* En la línea 3, agrega !important a la declaración existente */
h1 {
    color: white !important;
}

/* Agrega esta regla después de la declaración anterior */
p {
    color: blue;
}

/* Agrega esta regla al final del archivo */
body {
    color: red;
}
