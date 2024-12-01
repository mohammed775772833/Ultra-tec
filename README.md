html
<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ultra Tec - الترا تكنولجي</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #007bff;
            color: white;
            padding: 10px 0;
            text-align: center;
            position: relative;
            overflow: hidden;
        }
        .marquee {
            white-space: nowrap;
            overflow: hidden;
            box-sizing: border-box;
            animation: marquee 10s linear infinite;
        }
        @keyframes marquee {
            0% { transform: translateX(100%); }
            100% { transform: translateX(-100%); }
        }
        .content {
            padding: 20px;
            text-align: center;
        }
        footer {
            background-color: #007bff;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: relative;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>

<header>
    <div class="marquee">الترا تكنولوجي ترحب بكم</div>
</header>

<div class="content">
    <h1>مرحبًا بكم في Ultra Tec</h1>
    <p>نقدم خدمات تصميم الويب، التسويق الإلكتروني، والاستشارات.</p>
    <p>الموقع: اليمن، صنعاء، شارع الستين</p>
    <p>أرقام التواصل: 775772833</p>
</div>

<footer>
    <p>&copy; 2023 Ultra Tec. جميع الحقوق محفوظة.</p>
</footer>

</body>
</html>
