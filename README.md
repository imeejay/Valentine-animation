<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Happy Valentine's Tavia</title>
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            background-color: #ffebee;
            font-family: 'Arial', sans-serif;
        }
        .container {
            text-align: center;
        }
        h1 {
            font-size: 3rem;
            color: #d32f2f;
            animation: fadeIn 2s ease-in-out;
        }
        .heart {
            font-size: 5rem;
            color: #d32f2f;
            animation: explode 1s ease-in-out infinite;
        }
        @keyframes fadeIn {
            0% { opacity: 0; }
            100% { opacity: 1; }
        }
        @keyframes explode {
            0% { transform: scale(1); }
            50% { transform: scale(1.5); }
            100% { transform: scale(1); }
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Happy Valentine's Tavia</h1>
        <div class="heart">❤️</div>
    </div>
</body>
</html>
