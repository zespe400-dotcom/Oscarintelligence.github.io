# Oscarintelligence.github.io<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Oscar Intelligence Web</title>
    
    <style>
        /* Importar fuente de Google Fonts */
        @import url('https://fonts.googleapis.com/css2?family=Roboto:wght@300;400;700&display=swap');

        body {
            font-family: 'Roboto', sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            margin: 0;
            /* Degradado de fondo suave */
            background: linear-gradient(135deg, #f0f4f8 0%, #c5d9e9 100%);
            color: #333;
        }

        .card {
            background-color: white;
            padding: 40px 60px;
            border-radius: 20px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.1);
            text-align: center;
            max-width: 400px;
            transition: transform 0.3s ease;
        }

        .card:hover {
            transform: translateY(-5px);
        }

        h1 {
            font-size: 2.5em;
            color: #1a4d80;
            margin-bottom: 10px;
            font-weight: 700;
        }

        p {
            font-size: 1.1em;
            color: #666;
            margin-bottom: 30px;
            font-weight: 300;
        }

        .button {
            display: inline-block;
            background-color: #007bff;
            color: white;
            text-decoration: none;
            padding: 12px 25px;
            border-radius: 50px;
            font-weight: 500;
            transition: background-color 0.3s ease, transform 0.1s;
            box-shadow: 0 4px 10px rgba(0, 123, 255, 0.4);
        }

        .button:hover {
            background-color: #0056b3;
            transform: translateY(-2px);
        }
    </style>
</head>
<body>
    <div class="card">
        <h1>Oscar Intelligence</h1>
        <p>Esta página es de Oscar Intelligence.</p>
        
        <a href="https://www.google.com" target="_blank" class="button">
            Explora Google
        </a>
    </div>
</body>
</html>
