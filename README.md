<!DOCTYPE html>
<html lang="pl">
<head>
    <meta charset="UTF-8">
    <title>FryzjerHurt - Hurtownia Fryzjerska</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            background: #f5f5f5;
            color: #333;
        }

        /* nawigacja */
        nav {
            background: #222;
            padding: 15px 20px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        nav h1 {
            color: gold;
            font-size: 20px;
        }

        nav a {
            color: #ccc;
            text-decoration: none;
            margin-left: 15px;
        }

        nav a:hover {
            color: gold;
        }

        /* baner */
        .baner {
            background: #1a1a2e;
            color: white;
            text-align: center;
            padding: 60px 20px;
        }

        .baner h2 {
            font-size: 32px;
            margin-bottom: 10px;
        }

        .baner p {
            color: #bbb;
            margin-bottom: 20px;
        }

        .baner a {
            background: gold;
            color: #222;
            padding: 10px 25px;
            text-decoration: none;
            font-weight: bold;
            border-radius: 5px;
            margin: 5px;
            display: inline-block;
        }

        /* kategorie */
        .kategorie {
            padding: 40px 20px;
            text-align: center;
        }

        .kategorie h2 {
            margin-bottom: 20px;
        }

        .siatka {
            display: grid;
            grid-template-columns: repeat(4, 1fr);
            gap: 15px;
            max-width: 900px;
            margin: 0 auto;
        }

        .karta {
            background: white;
            border: 1px solid #ddd;
            border-radius: 8px;
            padding: 20px;
            text-align: center;
        }

        .karta p {
            font-size: 12px;
            color: #888;
        }

        /* produkty */
        .produkty {
            background: #eee;
            padding: 40px 20px;
            text-align: center;
        }

        .produkty h2 {
            margin-bottom: 20px;
        }

        .lista-produktow {
            display: grid;
            grid-template-columns: repeat(4, 1fr);
            gap: 15px;
            max-width: 900px;
            margin: 0 auto;
        }

        .produkt {
            background: white;
            border: 1px solid #ddd;
            border-radius: 8px;
            padding: 15px;
            text-align: center;
        }

        .produkt span {
            font-size: 40px;
        }

        .produkt h4 {
            margin: 8px 0 4px;
            font-size: 14px;
        }

        .produkt .cena {
            color: #c9933a;
            font-weight: bold;
        }

        .produkt button {
            margin-top: 10px;
            background: #222;
            color: gold;
            border: none;
            padding: 7px 12px;
            border-radius: 5px;
            cursor: pointer;
            width: 100%;
        }

        /* cta */
        .cta {
            background: #1a1a2e;
            color: white;
            text-align: center;
            padding: 50px 20px;
        }

        .cta a {
            background: gold;
            color: #222;
            padding: 12px 28px;
            text-decoration: none;
            font-weight: bold;
            border-radius: 5px;
            margin-top: 15px;
            display: inline-block;
        }

        /* stopka */
        footer {
            background: #111;
            color: #777;
            text-align: center;
            padding: 15px;
            font-size: 13px;
        }
    </style>
</head>
<body>

<!-- nawigacja -->
<nav>
    <h1>✂ FryzjerHurt</h1>
    <div>
        <a href="#">Produkty</a>
        <a href="#">Marki</a>
        <a href="#">Cennik</a>
        <a href="#">Kontakt</a>
    </div>
</nav>

<!-- baner glowny -->
<div class="baner">
    <h2>Hurtownia artykułów fryzjerskich</h2>
    <p>Najniższe ceny hurtowe. Zaufało nam ponad 5000 salonów w Polsce.</p>
    <a href="#">Przeglądaj katalog</a>
    <a href="#" style="background:transparent; border:2px solid gold; color:gold;">Zapytaj o wycenę</a>
</div>

<!-- kategorie -->
<div class="kategorie">
    <h2>Kategorie produktów</h2>
    <div class="siatka">
        <div class="karta">✂️<br><b>Nożyczki</b><p>Sprzęt profesjonalny</p></div>
        <div class="karta">🎨<br><b>Farby</b><p>Farby, rozjaśniacze</p></div>
        <div class="karta">💆<br><b>Pielęgnacja</b><p>Maski, szampony</p></div>
        <div class="karta">💨<br><b>Sprzęt</b><p>Suszarki, prostownice</p></div>
        <div class="karta">🧴<br><b>Materiały</b><p>Folie, rękawiczki</p></div>
        <div class="karta">🪑<br><b>Meble</b><p>Fotele, lustra</p></div>
        <div class="karta">🌿<br><b>Eco</b><p>Produkty vegan</p></div>
        <div class="karta">📦<br><b>Zestawy</b><p>Dla nowych salonów</p></div>
    </div>
</div>

<!-- produkty -->
<div class="produkty">
    <h2>Polecane produkty</h2>
    <div class="lista-produktow">
        <div class="produkt">
            <span>✂️</span>
            <h4>Nożyczki Pro 6"</h4>
            <div class="cena">85,00 zł/szt.</div>
            <small style="color:#aaa">min. 6 szt.</small>
            <button>Dodaj do zapytania</button>
        </div>
        <div class="produkt">
            <span>🎨</span>
            <h4>Schwarzkopf Igora</h4>
            <div class="cena">32,00 zł/szt.</div>
            <small style="color:#aaa">min. 12 szt.</small>
            <button>Dodaj do zapytania</button>
        </div>
        <div class="produkt">
            <span>💨</span>
            <h4>Suszarka Ionic Pro</h4>
            <div class="cena">249,00 zł/szt.</div>
            <small style="color:#aaa">min. 3 szt.</small>
            <button>Dodaj do zapytania</button>
        </div>
        <div class="produkt">
            <span>🧴</span>
            <h4>Folie do balejażu 500</h4>
            <div class="cena">54,00 zł/opak.</div>
            <small style="color:#aaa">min. 10 opak.</small>
            <button>Dodaj do zapytania</button>
        </div>
    </div>
</div>

<!-- cta -->
<div class="cta">
    <h2>Gotowy na zaopatrzenie salonu?</h2>
    <p style="color:#bbb">Załóż konto i kup taniej już dziś.</p>
    <a href="#">Załóż konto handlowe</a>
</div>

<!-- stopka -->
<footer>
    <p>© 2026 FryzjerHurt · Warszawa · kontakt@fryzjerhurt.pl · +48 22 000 00 00</p>
</footer
