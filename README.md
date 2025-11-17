<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Happy Princess Day</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            background: linear-gradient(135deg, #ff9ad5, #ffd6f6);
            font-family: "Poppins", sans-serif;
            text-align: center;
            color: white;
        }

        .container {
            margin-top: 80px;
            animation: fadeIn 2s ease-in-out;
        }

        h1 {
            font-size: 60px;
            text-shadow: 0 0 15px white, 0 0 30px #ff69b4;
        }

        .crown {
            width: 150px;
            margin-top: 20px;
            animation: float 3s infinite ease-in-out;
        }

        .msg {
            font-size: 25px;
            width: 80%;
            margin: auto;
            margin-top: 20px;
            line-height: 1.6;
        }

        button {
            margin-top: 40px;
            padding: 15px 30px;
            font-size: 20px;
            border: none;
            border-radius: 10px;
            background-color: #ff4fa8;
            color: white;
            cursor: pointer;
            box-shadow: 0px 0px 15px #ffb3e6;
            transition: 0.3s;
        }

        button:hover {
            transform: scale(1.1);
            box-shadow: 0px 0px 25px #ffffff;
        }

        @keyframes float {
            0% { transform: translateY(0); }
            50% { transform: translateY(-15px); }
            100% { transform: translateY(0); }
        }

        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }

    </style>
</head>
<body>

    <div class="container">
        <img src="https://cdn-icons-png.flaticon.com/512/1998/1998181.png" class="crown">
        <h1>💖 Happy Princess Day 💖</h1>
        <p class="msg">
            May your day shine brighter than your crown,  
            sparkle more than stardust,  
            and be filled with kindness, beauty, and magic.  
            You truly are a princess! 👑✨
        </p>

        <button onclick="alert('Wishing you a magical Princess Day! 👑✨')">
            Tap for a Surprise ✨
        </button>
    </div>

</body>
</html>
