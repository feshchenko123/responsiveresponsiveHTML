responsiveHTML
Responsive HTML (адаптивный HTML) — это подход к веб-разработке, при котором сайт автоматически подстраивается под разные размеры экранов и устройства (ПК, планшеты, смартфоны).




<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Responsive Design</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            text-align: center;
        }
        
        .container {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
        }
        
        .box {
            width: 300px;
            margin: 10px;
            padding: 20px;
            background-color: lightblue;
        }

        /* Медиа-запрос для мобильных устройств */
        @media (max-width: 600px) {
            .box {
                width: 100%; /* Блоки занимают всю ширину экрана */
            }
        }
    </style>
</head>
<body>

    <h1>Пример адаптивного HTML</h1>
    <div class="container">
        <div class="box">Блок 1</div>
        <div class="box">Блок 2</div>
        <div class="box">Блок 3</div>
    </div>

</body>
</html>
