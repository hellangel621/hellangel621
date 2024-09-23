<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Örnek Web Sitesi</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Hoşgeldiniz!</h1>
        <nav>
            <ul>
                <li><a href="#hakkimizda">Hakkımızda</a></li>
                <li><a href="#hizmetler">Hizmetler</a></li>
                <li><a href="#iletisim">İletişim</a></li>
            </ul>
        </nav>
    </header>

    <section id="hakkimizda">
        <h2>Hakkımızda</h2>
        <p>Bu, örnek bir web sitesidir. Burada çeşitli bilgileri bulabilirsiniz.</p>
    </section>

    <section id="hizmetler">
        <h2>Hizmetlerimiz</h2>
        <ul>
            <li>Web Tasarım</li>
            <li>SEO Danışmanlığı</li>
            <li>İçerik Yönetimi</li>
        </ul>
    </section>

    <section id="iletisim">
        <h2>İletişim</h2>
        <form>
            <label for="isim">İsim:</label>
            <input type="text" id="isim" name="isim" required>
            <label for="email">E-posta:</label>
            <input type="email" id="email" name="email" required>
            <input type="submit" value="Gönder">
        </form>
    </section>

    <footer>
        <p>Tüm hakları saklıdır &copy; 2024</p>
    </footer>
</body>
</html>

body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
}

header {
    background: #333;
    color: #fff;
    padding: 1rem;
    text-align: center;
}

nav ul {
    list-style: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 1rem;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
}

section {
    padding: 2rem;
    margin: 1rem;
    background: #fff;
    border-radius: 5px;
}

footer {
    text-align: center;
    padding: 1rem;
    background: #333;
    color: #fff;
