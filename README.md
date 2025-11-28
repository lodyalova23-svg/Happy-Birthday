<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kado Ultah Dzaki</title>

    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background: linear-gradient(135deg, #ff9a9e, #fad0c4);
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
        }

        .container {
            text-align: center;
            background: white;
            padding: 25px;
            border-radius: 20px;
            width: 90%;
            max-width: 400px;
            box-shadow: 0 0 15px rgba(0,0,0,0.2);
        }

        button {
            padding: 12px 20px;
            font-size: 18px;
            border: none;
            background: #ff6f91;
            color: white;
            border-radius: 10px;
            cursor: pointer;
        }

        button:hover {
            background: #ff3f7e;
        }

        .hidden {
            display: none;
        }

        #emojiRain span {
            position: absolute;
            animation: fall 2s linear infinite;
            font-size: 24px;
        }

        @keyframes fall {
            0% { transform: translateY(-50px); opacity: 1; }
            100
