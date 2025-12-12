<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <title>Tenho uma pergunta...</title>
    <style>
        body {
            background-color: #ffe6f2;
            font-family: Arial, sans-serif;
            text-align: center;
            padding: 20px;
        }
        .card {
            background: white;
            padding: 20px;
            border-radius: 15px;
            box-shadow: 0px 0px 15px rgba(0,0,0,0.2);
            max-width: 350px;
            margin: auto;
        }
        img {
            width: 100%;
            border-radius: 15px;
            margin-bottom: 20px;
        }
        button {
            background-color: #ff4d88;
            color: white;
            border: none;
            padding: 12px 20px;
            font-size: 18px;
            border-radius: 10px;
            cursor: pointer;
            margin-top: 10px;
        }
    </style>
</head>
<body>

    <div class="card">
        <img src="foto.jpg" alt="Nós dois">
        <h2>Eu tenho uma pergunta muito importante...</h2>
        <h1>💗 Quer namorar comigo? 💗</h1>
        <button onclick="alert('Ebaaa! Você disse SIM! ❤️')">SIM</button>
        <button onclick="alert('Ah não 😢 Pense de novo!')">NÃO</button>
    </div>

</body>
</html>
