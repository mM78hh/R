<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>RoboStudio</title>
    <link rel="icon" type="image/png" href="pixil-frame-0 - 2024-09-08T184915.479.png" />

    <style>
        body, html {
            margin: 0;
            padding: 0;
            font-family: Arial, sans-serif;
            background: url('background-image.jpg') no-repeat center center fixed;
            background-size: cover;
            color: #fff;
        }

        header {
            background-color: rgba(0, 0, 0, 0.7);
            padding: 20px;
            position: fixed;
            width: 100%;
            top: 0;
            left: 0;
            text-align: center;
            z-index: 1000;
            display: flex;
            align-items: center;
            justify-content: center;
            box-sizing: border-box;
        }

        header h1 {
            margin: 0;
            font-size: 40px;
            text-transform: uppercase;
            flex: 1;
            position: relative;
        }

        .header-img {
            width: 50px; /* Устанавливаем ширину изображения */
            height: auto;
            margin-right: 10px; /* Расстояние между изображением и текстом */
            position: absolute;
            right: 20px;
            top: 20px;
        }

        .game-info {
            padding: 100px 20px 500px; /* Увеличен нижний отступ для дополнительного пространства */
            text-align: center;
            margin-right: 20px; /* Оставляем место для сайдбара */
        }

        .game-info h2 {
            font-size: 50px;
            margin-bottom: 10px;
            color: #000;
        }

        .game-info p {
            font-size: 20px;
            width: 60%;
            margin: 0 auto;
            color: #000;
            display: none; /* Скрываем текст */
        }

        .download-btn {
            display: inline-block;
            margin-top: 10px; /* Уменьшен отступ от заголовка */
            padding: 15px 30px;
            background-color: #3498db; /* Синий цвет */
            color: #fff;
            text-transform: uppercase;
            text-decoration: none;
            border-radius: 30px;
            font-size: 16px;
            cursor: pointer;
        }

        .download-btn:hover {
            background-color: #2980b9; /* Темнее синий при наведении */
        }

        .game-info h2:hover + p {
            display: block; /* Показываем текст при наведении на заголовок */
        }

        footer {
            background-color: rgba(0, 0, 0, 0.9);
            padding: 20px;
            position: relative;
            bottom: 0;
            width: 100%;
            color: #fff;
            text-align: center;
        }

        footer p {
            margin: 0;
            font-size: 14px;
        }
    </style>
</head>
<body>

<header>
    <img src="pixil-frame-0 - 2024-09-08T184915.479.png" alt="Top Image" class="header-img">
    <h1>RoboStudio</h1>
</header>

<div class="game-info">
    <h2>Dragon Blue Fly</h2>
    <p>In the game Blue Dragon Flies there you play for different dragons and must pass levels</p>
    <a href="BDF=ZIP.zip" class="download-btn" download>Download Blue Dragon Fly</a>
</div>

<footer>
    <p>RoboStudio</p>
</footer>

</body>
</html>
