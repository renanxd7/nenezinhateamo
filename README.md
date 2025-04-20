<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mensagem para Layane</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f9f9f9;
            color: #333;
            text-align: center;
            padding: 50px;
        }
        h1 {
            color: #e63946;
        }
        p {
            font-size: 1.5rem;
            color: #1d3557;
        }
        .heart {
            color: #e63946;
            font-size: 3rem;
        }
        .buttons {
            margin-top: 20px;
        }
        button {
            padding: 10px 20px;
            font-size: 1.2rem;
            cursor: pointer;
            border: none;
            border-radius: 5px;
            margin: 10px;
            background-color: #1d3557;
            color: white;
        }
        button:hover {
            background-color: #457b9d;
        }
    </style>
</head>
<body>
    <h1>Para Layane</h1>
    <p>Eu te amo, Layane!</p>
    <div class="heart">❤️</div>

    <div class="buttons">
        <p>Vai liberar pra mim?</p>
        <button id="yesButton" onclick="alert('Sim!')">Sim</button>
        <button id="noButton" onclick="hideNoButton()">Não</button>
    </div>

    <script>
        function hideNoButton() {
            document.getElementById("noButton").style.display = "none";
            setTimeout(function() {
                document.getElementById("noButton").style.display = "inline-block";
            }, 1000); // O botão reaparece após 1 segundo
        }
    </script>
</body>
</html>
