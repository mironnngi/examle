# examle
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Магазин кроссовок</title>
    <style>
        /* Стили для текста и элементов страницы */
        body {
            font-family: Arial, sans-serif;
            color: #333;
            margin: 0;
            padding: 0;
            background: 
                radial-gradient(circle, #00FF00 5%, transparent 5%) 0 0,
                radial-gradient(circle, #00FF00 5%, transparent 5%) 50px 50px,
                radial-gradient(circle, #000000 5%, transparent 5%) 100px 100px,
                radial-gradient(circle, #000000 5%, transparent 5%) 150px 150px;
            background-color: #fff;
            background-size: 100px 100px;
        }

        h1 {
            text-align: center;
            margin-top: 20px;
        }

        /* Стили для верхнего меню */
        nav {
            background-color: #000;
            padding: 10px 0;
            text-align: center;
        }

        nav ul {
            list-style-type: none;
            padding: 0;
            margin: 0;
        }

        nav ul li {
            display: inline;
            margin: 0 10px;
        }

        nav ul li a {
            color: #fff;
            text-decoration: none;
            font-size: 18px;
            padding: 5px 10px;
            border-radius: 5px;
            background-color: #333;
        }

        nav ul li a:hover {
            background-color: #555;
        }

        /* Стили для карточек продуктов */
        .product {
            display: inline-block;
            margin: 20px;
            padding: 20px;
            border: 1px solid #ccc;
            border-radius: 5px;
            background-color: #fff;
        }

        .product img {
            max-width: 200px;
            height: auto;
            display: block;
            margin: 0 auto 10px;
        }

        .product p {
            font-size: 16px;
            text-align: center;
        }

        /* Стили для раздела "О нас" */
        #about {
            text-align: center;
            padding: 50px 20px;
        }

        #about h2 {
            margin-bottom: 20px;
        }

        #about p {
            font-size: 18px;
            line-height: 1.6;
        }
    </style>
</head>
<body>
    <h1>Магазин кроссовок</h1>

    <nav>
        <ul>
            <li><a href="#home">Главная</a></li>
            <li><a href="#catalog">Каталог</a></li>
            <li><a href="#contact">Контакты</a></li>
            <li><a href="#about">О нас</a></li>
        </ul>
    </nav>

    <section id="home">
        <h2>Добро пожаловать в магазин кроссовок</h2>
        <p>Здесь вы найдете лучшие кроссовки по выгодным ценам.</p>
    </section>

    <section id="catalog">
        <h2>Каталог кроссовок</h2>
        <!-- Карточка с кроссовками -->
        <div class="product">
            <img src="https://via.placeholder.com/200" alt="Кроссовки">
            <p>Кроссовки Nike Air Max</p>
            <p>Цена: $100</p>
        </div>
        
        <!-- Добавьте сколько угодно карточек с кроссовками -->
        <div class="product">
            <img src="https://via.placeholder.com/200" alt="Кроссовки">
            <p>Кроссовки Adidas Ultraboost</p>
            <p>Цена: $120</p>
        </div>

        <div class="product">
            <img src="https://via.placeholder.com/200" alt="Кроссовки">
            <p>Кроссовки Reebok Nano</p>
            <p>Цена: $90</p>
        </div>
    </section>

    <section id="about">
        <h2>О нас</h2>
        <p>Мы - ваш лучший источник кроссовок. У нас есть все, что вам нужно для комфортной и стильной обуви. Покупайте у нас и получайте лучшие цены и качество обслуживания.</p>
    </section>

    <section id="contact">
        <h2>Контакты</h2>
        <p>Insta: ******</p>
    </section>

    <footer>
        <p>&copy; 2024 Магазин кроссовок. Все права защищены.</p>
    </footer>
</body>
</html>
