# Practica4guadalupe.Github.io
Guadalupe Guzmán Guadalupe
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>ventas de motos</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f2f2f2;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #333;
            color: white;
            padding: 20px 0;
            text-align: center;
        }

        .container {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            padding: 20px;
        }

        .moto-card {
            background-color: white;
            border: 1px solid #ccc;
            border-radius: 8px;
            width: 300px;
            margin: 15px;
            padding: 15px;
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
            text-align: center;
        }

        .moto-card img {
            width: 100%;
            height: auto;
            border-radius: 5px;
        }

        .moto-card h2 {
            font-size: 1.2em;
            margin: 10px 0;
        }

        .moto-card p {
            color: #555;
        }

        .precio {
            font-size: 1.2em;
            color: #e91e63;
            font-weight: bold;
        }

        .boton-contacto {
            background-color: #e91e63;
            color: white;
            padding: 10px 20px;
            margin-top: 10px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }

        footer {
            background-color: #333;
            color: white;
            padding: 15px;
            text-align: center;
        }
    </style>
</head>
<body>

<header>
    <h1>MOTOS GUZMAN</h1>
    <p>¡Encuentra la moto de tus sueños!</p>
</header>

<div class="container">
    <div class="moto-card">
        <img src="https://via.placeholder.com/300x200" alt="Moto 1">
        <h2>Yamaha R3</h2>
        <p>Motor bicilíndrico, 321cc, diseño deportivo.</p>
        <p class="precio">$155,999.00</p>
        <button class="boton-contacto">Contactar</button>
    </div>

    <div class="moto-card">
        <img src="https://via.placeholder.com/300x200" alt="Moto 2">
        <h2>Honda CB500F</h2>
        <p>Motor de 471cc, ideal para ciudad y carretera.</p>
        <p class="precio"> $949,990.00 MXN </p>
        <button class="boton-contacto">Contactar</button>
    </div>

    <div class="moto-card">
        <img src="https://via.placeholder.com/300x200" alt="Moto 3">
        <h2>Kawasaki Ninja 400</h2>
        <p>Estilo agresivo, 399cc, excelente rendimiento.</p>
        <p class="precio">$165,990.00 MXN </p>
        <button class="boton-contacto">Contactar</button>
    </div>
</div>

<footer>
    <p>© 2025 tiendas de motos . Todos los derechos reservados.</p>
</footer>

</body>
</html>
