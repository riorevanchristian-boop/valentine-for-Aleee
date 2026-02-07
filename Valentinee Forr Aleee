<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kejutan Valentine</title>
    <style>
        body {
            font-family: 'Dancing Script', cursive; /* Font romantis */
            background: linear-gradient(135deg, #ffe6f2, #ffb3ba); /* Gradien latar belakang */
            color: #d63384;
            text-align: center;
            padding: 20px;
            margin: 0;
            overflow-x: hidden;
        }
        .slide {
            display: none;
            animation: fadeIn 1s ease-in-out;
        }
        .active {
            display: block;
        }
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }
        button {
            background-color: #ff69b4;
            color: white;
            border: none;
            padding: 15px 30px;
            font-size: 18px;
            margin: 10px;
            cursor: pointer;
            border-radius: 25px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.2);
            transition: all 0.3s;
        }
        button:hover {
            background-color: #ff1493;
            transform: scale(1.05);
        }
        #noBtn {
            cursor: not-allowed;
            opacity: 0.5;
        }
        p {
            font-size: 20px;
            line-height: 1.6;
            max-width: 600px;
            margin: 20px auto;
        }
        .flowers {
            font-size: 30px;
            margin: 20px 0;
        }
        .love-text {
            font-size: 24px;
            font-weight: bold;
            color: #ff1493;
            margin: 20px 0;
        }
        .credit {
            position: fixed;
            bottom: 10px;
            right: 10px;
            font-size: 12px;
            color: #999;
            font-family: Arial, sans-serif;
        }
    </style>
    <link href="https://fonts.googleapis.com/css2?family=Dancing+Script&display=swap" rel="stylesheet"> <!-- Font eksternal -->
</head>
<body>
    <div id="slide1" class="slide active">
        <h1>💖 Kejutan Valentine! 💖</h1>
        <p>Mau lanjut?</p>
        <button id="yesBtn">Yes</button>
        <button id="noBtn" disabled>No</button>
    </div>
    
    <div id="slide2" class="slide">
        <h1>Happy Valentine! 🌹</h1>
        <p>Dalam setiap detak jantungku, aku menemukan cinta yang tak pernah pudar untukmu. Sejak hari pertama kita bertemu, dunia terasa lebih indah, penuh warna dan harapan. Aku bersyukur memiliki seseorang seperti kamu yang membuat hari-hariku penuh kebahagiaan. Mari kita lanjutkan perjalanan ini bersama, karena aku yakin bahwa cinta kita akan semakin kuat seiring waktu. Tanggal awal jadian kita, 12 Desember 2025, akan selalu menjadi kenangan manis yang aku simpan di hati. Aku mencintaimu lebih dari kata-kata bisa ungkapkan.</p>
        
        <!-- Ganti gambar dengan emoji bunga untuk "cukup banyak" -->
        <div class="flowers">🌸🌸🌸🌸🌸🌸🌸🌸🌸🌸🌸🌸🌸🌸🌸🌸🌸🌸🌸🌸</div>
        
        <div class="love-text">Love Love 💕💕</div>
    </div>

    <div class="credit">Website by yoyoo</div>

    <script>
        document.getElementById('yesBtn').addEventListener('click', function() {
            document.getElementById('slide1').classList.remove('active');
            document.getElementById('slide2').classList.add('active');
        });
    </script>
</body>
</html>
