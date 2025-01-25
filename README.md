<!DOCTYPE html>
<html lang="it">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Il Tuo Sito</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }

        header {
            background-color: #222;
            padding: 1rem 0;
        }

        nav ul {
            list-style: none;
            display: flex;
            justify-content: center;
            gap: 2rem;
            margin: 0;
            padding: 0;
        }

        nav ul li a {
            color: #fff;
            text-decoration: none;
            font-size: 1.2rem;
        }

        section {
            max-width: 1200px;
            margin: 2rem auto;
            padding: 1rem;
        }

        #home {
            text-align: center;
        }

        #home img {
            margin: 1rem 0;
            border-radius: 10px;
            width: 80%;
            max-width: 800px;
        }

        .social-links {
            margin-top: 1rem;
        }

        .social-links a {
            margin: 0 10px;
            text-decoration: none;
            font-size: 1.2rem;
            color: #222;
            font-weight: bold;
        }

        #merchandising {
            text-align: center;
        }

        .products {
            display: flex;
            justify-content: center;
            gap: 2rem;
            margin-top: 2rem;
            flex-wrap: wrap;
        }

        .product {
            background-color: #fff;
            border-radius: 10px;
            padding: 1rem;
            box-shadow: 0px 4px 10px rgba(0, 0, 0, 0.1);
            width: 200px;
        }

        .product img {
            width: 100%;
            border-radius: 10px;
            margin-bottom: 1rem;
        }

        footer {
            background-color: #222;
            color: #fff;
            text-align: center;
            padding: 1rem 0;
            margin-top: 2rem;
        }

        footer img {
            margin-top: 10px;
            width: 50px;
        }
    </style>
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#merchandising">Merchandising</a></li>
            </ul>
        </nav>
    </header>

    <section id="home">
        <h1>Benvenuto nel mio sito!</h1>
        <p>Qui troverai tutte le mie informazioni e i collegamenti ai miei social.</p>
        <img src="images/SFONDO_DESKTOP_2.jpg" alt="Immagine di Benvenuto">
        <div class="social-links">
            <a href="https://instagram.com/franzzinho.real?igsh=MTNoYng1OGVxaGQ2cQ==" target="_blank">Instagram</a>
            <a href="https://tiktok.com/@franzzinho.real?_t=8oTIcTP2vzN&_r=1" target="_blank">TikTok</a>
            <a href="https://open.spotify.com/playlist/6FufeeFmX0VN1OkYH06zI7?si=8954cbd0a899" target="_blank">Spotify</a>
            <a href="https://streamelements.com/franzzinho_tw/tip" target="_blank">Donazioni</a>
        </div>
    </section>

    <section id="merchandising">
        <h2>Merchandising</h2>
        <p>Acquista le mie magliette e altri prodotti qui!</p>
        <div class="products">
            <div class="product">
                <img src="images/SFONDO_DESKTOP_SFERA.jpg" alt="Prodotto 1">
                <p>Prodotto 1 - €100</p>
                <button>Acquista</button>
            </div>
            <div class="product">
                <img src="images/SFONDO_DESKTOP_3.jpg" alt="Prodotto 2">
                <p>Prodotto 2 - €200</p>
                <button>Acquista</button>
            </div>
        </div>
    </section>

    <footer>
        <p>© 2025 - SCANTOT NANO.</p>
        <img src="images/SFONDO_DESKTOP_SFERA.jpg" alt="Decorazione Footer">
    </footer>
</body>
</html>
