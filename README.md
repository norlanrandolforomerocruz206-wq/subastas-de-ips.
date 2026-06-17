# subastas-de-ips.
este es un repositorio creado con fines educativos.
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DarkNet IP Broker - Proyecto Escolar</title>
    <style>
        /* Estilos CSS integrados para facilitar tu proyecto */
        body {
            background-color: #0d0d0d;
            color: #00ff66;
            font-family: 'Courier New', Courier, monospace;
            margin: 0;
            padding: 0;
            display: flex;
            flex-direction: column;
            align-items: center;
        }

        header {
            text-align: center;
            padding: 20px;
            border-bottom: 2px solid #00ff66;
            width: 100%;
            box-shadow: 0px 0px 15px #00ff66;
        }

        .glitch {
            font-size: 2.5rem;
            font-weight: bold;
            text-transform: uppercase;
            letter-spacing: 5px;
            animation: glitch 1s linear infinite;
        }

        .container {
            max-width: 1000px;
            width: 90%;
            margin: 30px auto;
        }

        .warning-box {
            border: 1px solid #ff3333;
            background-color: rgba(255, 51, 51, 0.1);
            color: #ff3333;
            padding: 15px;
            text-align: center;
            margin-bottom: 30px;
            font-weight: bold;
            box-shadow: 0px 0px 10px #ff3333;
        }

        .grid-ips {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 20px;
        }

        .card {
            border: 1px solid #00ff66;
            background: #1a1a1a;
            padding: 20px;
            border-radius: 5px;
            transition: all 0.3s ease;
        }

        .card:hover {
            box-shadow: 0 0 15px #00ff66;
            transform: scale(1.02);
        }

        .card h3 {
            margin-top: 0;
            color: #fff;
        }

        .status {
            display: inline-block;
            padding: 3px 8px;
            border-radius: 3px;
            font-size: 0.8rem;
            font-weight: bold;
        }

        .available { background-color: #00ff66; color: #000; }
        .reserved { background-color: #ffcc00; color: #000; }

        .btn-comprar {
            display: block;
            width: 100%;
            background: transparent;
            border: 1px solid #00ff66;
            color: #00ff66;
            padding: 10px;
            margin-top: 15px;
            cursor: pointer;
            font-family: 'Courier New', monospace;
            font-weight: bold;
            text-transform: uppercase;
        }

        .btn-comprar:hover {
            background: #00ff66;
            color: #000;
        }

        footer {
            margin-top: 5px;
            padding: 20px;
            font-size: 0.8rem;
            color: #666;
            text-align: center;
        }
    </style>
</head>
<body>

    <header>
        <div class="glitch">NET-SHADOW IP BROKER</div>
        <p>Simulador de Redes Avanzadas y Enrutamiento Ficticio</p>
    </header>

    <div class="container">
        
        <div class="warning-box">
            [AVISO ACADÉMICO] Esta página es una simulación interactiva para un proyecto escolar de informática. No se venden servicios reales.
        </div>

        <h2>Lotes de Direcciones IP Disponibles (Simulación)</h2>
        <p>Selecciona un rango de red enmascarado para tus pruebas de penetración autorizadas:</p>
        <br>

        <div class="grid-ips">
            <div class="card">
                <h3>Rango: 185.220.101.XX</h3>
                <p><strong>Ubicación proxy:</strong> Islandia</p>
                <p><strong>Protocolo:</strong> IPv4 SOCKS5</p>
                <p><strong>Anonimato:</strong> Alto (No-Logs)</p>
                <span class="status available">DISPONIBLE</span>
                <button class="btn-comprar" onclick="alert('Simulación de compra: ¡Rango asignado al terminal!')">Adquirir Enrutamiento</button>
            </div>

            <div class="card">
                <h3>Rango: 45.153.160.XX</h3>
                <p><strong>Ubicación proxy:</strong> Suiza</p>
                <p><strong>Protocolo:</strong> IPv4 HTTPS</p>
                <p><strong>Anonimato:</strong> Militar Estricto</p>
                <span class="status available">DISPONIBLE</span>
                <button class="btn-comprar" onclick="alert('Simulación de compra: ¡Rango asignado al terminal!')">Adquirir Enrutamiento</button>
            </div>

            <div class="card">
                <h3>Rango: 109.201.133.XX</h3>
                <p><strong>Ubicación proxy:</strong> Desconocida</p>
                <p><strong>Protocolo:</strong> IPv6 Dynamic</p>
                <p><strong>Anonimato:</strong> Encriptación Cuántica</p>
                <span class="status reserved">RESERVADO</span>
                <button class="btn-comprar" style="border-color: #555; color: #555; cursor: not-allowed;" disabled>No Disponible</button>
            </div>
        </div>

    </div>

    <footer>
        <p>&copy; 2026 Proyecto de Informática - Net-Shadow Simulator. Desarrollado con fines educativos.</p>
    </footer>

</body>
</html>
