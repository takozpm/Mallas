<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Compra mallas para cercos en Chonchi. Ofrecemos diferentes medidas y opciones.">
    <title>Mallas Para Cercos Chonchi-Chiloe</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background: url('fondocercos.jpg') no-repeat center center fixed;
            background-size: cover;
            animation: movimientoFondo 10s infinite alternate ease-in-out;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }

        @keyframes movimientoFondo {
            0% {
                background-position: center top;
            }
            100% {
                background-position: center bottom;
            }
        }

        header {
            background-color: rgba(111, 79, 40, 0.8); /* Color café con opacidad */
            color: white;
            text-align: center;
            padding: 20px 0;
            margin-bottom: 20px;
            width: 100%;
            border-radius: 8px;
        }

        header h1 {
            margin: 0;
        }

        main {
            display: flex;
            flex-direction: column;
            align-items: center;
            padding: 30px;
            background-color: rgba(51, 51, 51, 0.8); /* Fondo gris oscuro con opacidad */
            color: white;
            border-radius: 16px; /* Bordes redondeados */
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.5);
            max-width: 800px;
            margin: 0 auto;
        }

        .descripcion {
            text-align: left;
            font-size: 18px;
            color: #fff;
            width: 100%;
            margin-bottom: 20px;
        }

        .descripcion p {
            margin-bottom: 10px;
        }

        .descripcion ul {
            list-style-type: disc; /* Esto agrega el punto negro */
            padding-left: 20px; /* Agrega espacio a la izquierda */
        }

        .descripcion li {
            margin-bottom: 10px;
        }

        .formulario {
            background-color: #444; /* Color gris ligeramente más claro */
            padding: 20px;
            border-radius: 16px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.5);
            width: 100%;
            max-width: 500px;
        }

        .formulario label {
            display: block;
            margin-bottom: 8px;
        }

        .formulario select, .formulario input[type="number"] {
            width: 100%;
            box-sizing: border-box; /* Asegura que todos los elementos tengan el mismo tamaño */
            padding: 8px;
            margin-bottom: 10px;
            border-radius: 4px;
            border: 1px solid #ccc;
        }

        .formulario button {
            background-color: #28a745;
            color: white;
            border: none;
            padding: 10px 20px;
            border-radius: 4px;
            cursor: pointer;
            width: 100%;
        }

        .formulario button:hover {
            background-color: #218838;
        }
    </style>
</head>
<body>

<header>
    <h1>Mallas Para Cercos Chonchi-Chiloe</h1>
</header>

<main>
    <img src="cercos de metro.jpg" width="600px" height="350px" alt="Malla para cerco" class="producto">

    <div class="descripcion">
        <p style="font-size: 24px; font-weight: bold;">𝗖𝗢𝗠𝗣𝗥𝗔 𝗬 𝗩𝗘𝗡𝗧𝗔𝗦 𝗠𝗔𝗬𝗢𝗥𝗜𝗦𝗧𝗔𝗦</p>
        <ul>
            <li>Mallas para Cercos de perlon y plastica</li>
            <li>Equipamiento industrial</li>
            <li>Artículos EPP</li>
            <li>Varios</li>
            <li>Centro Empresarial</li>
            <li>Centro de negocios Mayoristas</li>
            <li>Finanzas</li>
        </ul>
        <p>Ofrecemos cercos de mallas resistentes y duraderas en Chonchi. Puedes elegir entre diferentes tamaños:</p>
        <ul>
            <li>1,00 x 25</li>
            <li>1,20 x 25</li>
            <li>1,50 x 25</li>
            <li>2,00 x 25</li>
        </ul>
    </div>

    <div class="formulario">
        <h2>Realiza tu Pedido</h2>
        <form action="procesar_pedido.php" method="POST">
            <label for="medidas">Selecciona las Medidas</label>
            <select id="medidas" name="medidas" required>
                <option value="1.00x25">1,00 x 25</option>
                <option value="1.20x25">1,20 x 25</option>
                <option value="1.50x25">1,50 x 25</option>
                <option value="2.00x25">2,00 x 25</option>
            </select>

            <label for="cantidad">Cantidad de Mallas</label>
            <input type="number" id="cantidad" name="cantidad" placeholder="Ej. 10" required>

            <button type="submit">Hacer Pedido</button>
        </form>
    </div>
</main>

</body>
</html>
