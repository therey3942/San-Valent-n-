<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Para mi amor</title>
    <style>
        body {
            background: url('https://source.unsplash.com/1600x900/?love,romance') no-repeat center center fixed;
            background-size: cover;
            font-family: Arial, sans-serif;
            text-align: center;
            color: white;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            flex-direction: column;
        }
        .container {
            background: rgba(0, 0, 0, 0.6);
            padding: 20px;
            border-radius: 15px;
            width: 90%;
            max-width: 500px;
        }
        h1 {
            font-size: 2.5em;
        }
        p {
            font-size: 1.2em;
        }
        .btn {
            background-color: #ff4d6d;
            color: white;
            padding: 15px 25px;
            font-size: 1.2em;
            border: none;
            cursor: pointer;
            border-radius: 10px;
            margin-top: 20px;
            transition: 0.3s;
        }
        .btn:hover {
            background-color: #ff1e50;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Feliz San Valentín, mi amor</h1>
        <p>Desde el primer momento en que te vi, supe que eras especial.  
        No hay día en que no agradezca por tenerte en mi vida.  
        Hoy quiero invitarte a pasar un día inolvidable juntos.  
        ¿Me acompañas?</p>
        <button class="btn" onclick="aceptarInvitacion()">¡Sí, quiero!</button>
    </div>

    <script>
        function aceptarInvitacion() {
            alert('¡Te amo, mi vida! Prepárate para una sorpresa especial ❤️');
        }
    </script>
</body>
</html>
# San-Valent-n-
