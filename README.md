<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>For You</title>
    <style>
        :root {
            --peach: #FFDAB9;
            --light-peach: #FFF0E6;
            --soft-pink: #FFB7B2;
        }
        body {
            background-color: var(--light-peach);
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            text-align: center;
            color: #5d4037;
            padding: 50px 20px;
        }
        .flower { font-size: 80px; margin: 20px; animation: bloom 3s infinite alternate; }
        @keyframes bloom { from { transform: scale(1); } to { transform: scale(1.1); } }
        
        .container {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
            margin-top: 40px;
        }
        .box {
            background-color: var(--peach);
            padding: 20px;
            border-radius: 15px;
            width: 200px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
            transition: transform 0.3s;
        }
        .box:hover { transform: translateY(-10px); }
        h1 { font-weight: 300; }
    </style>
</head>
<body>

    <div class="flower">🌸</div>
    <h1>I am truly sorry.</h1>
    <p>Please forgive me, I value us more than anything.</p>

    <div class="container">
        <div class="box"><h3>I'm Sorry</h3><p>I know I messed up and I take full responsibility.</p></div>
        <div class="box"><h3>I Miss You</h3><p>Every moment without you feels empty.</p></div>
        <div class="box"><h3>I Love You</h3><p>You mean the world to me, now and always.</p></div>
        <div class="box"><h3>My Promise</h3><p>I will try harder to be the partner you deserve.</p></div>
    </div>

</body>
</html>
