# Pengenalan-diri

<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Website Pengenalan Diri</title>

    <!-- CSS -->
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            background: #f5f0ff;
            color: #333;
            text-align: center;
        }

        header {
            background: #7057d9;
            color: white;
            padding: 20px;
        }

        nav {
            margin-top: 15px;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 10px;
            font-weight: bold;
        }

        nav a:hover {
            color: #ffd6ec;
        }

        .hero {
            background: #e5dcff;
            padding: 80px 20px;
        }

        .hero h2 {
            font-size: 32px;
            margin-bottom: 15px;
        }

        section {
            padding: 50px 20px;
        }

        h2 {
            color: #7057d9;
            margin-bottom: 20px;
        }

        p {
            line-height: 1.8;
        }

        button {
            background: #7057d9;
            color: white;
            border: none;
            padding: 12px 25px;
            border-radius: 20px;
            cursor: pointer;
            margin-top: 20px;
        }

        button:hover {
            background: #4934a5;
        }

        .card {
            background: white;
            padding: 25px;
            margin: 15px auto;
            max-width: 350px;
            border-radius: 15px;
            box-shadow: 0 4px 10px #00000015;
        }

        footer {
            background: #7057d9;
            color: white;
            padding: 20px;
        }

        @media (max-width: 600px) {
            nav a {
                display: inline-block;
                margin: 7px;
            }

            .hero h2 {
                font-size: 25px;
            }
        }
    </style>
</head>

<body>

    <!-- HEADER -->
    <header>
        <h1>My Personal Website</h1>

        <nav>
            <a href="#home">Home</a>
            <a href="#about">Tentang Saya</a>
            <a href="#hobi">Hobi</a>
            <a href="#kontak">Kontak</a>
        </nav>
    </header>

    <!-- HOME -->
    <section id="home" class="hero">
        <h2>Halo, Saya [Nama Kamu]!</h2>

        <p>
            Selamat datang di website pengenalan diri saya.
            Senang bisa berbagi cerita tentang diri saya.
        </p>

        <button onclick="sapa()">
            Kenalan Yuk!
        </button>
    </section>

    <!-- TENTANG SAYA -->
    <section id="about">
        <h2>Tentang Saya</h2>

        <p>
            Nama saya [Nama Kamu]. Saya adalah seorang pelajar
            yang sedang belajar dan mengembangkan kemampuan diri.
        </p>

        <p>
            Saya memiliki semangat untuk belajar,
            mencoba hal baru, dan meraih cita-cita.
        </p>
    </section>

    <!-- HOBI -->
    <section id="hobi">
        <h2>Hobi Saya</h2>

        <div class="card">
            <h3>🎵 Mendengarkan Musik</h3>
            <p>
                Saya suka mendengarkan musik
                di waktu luang.
            </p>
        </div>

        <div class="card">
            <h3>📚 Membaca</h3>
            <p>
                Saya senang membaca untuk
                menambah pengetahuan.
            </p>
        </div>

        <div class="card">
            <h3>⚽ Berolahraga</h3>
            <p>
                Saya suka menjaga kesehatan
                dengan berolahraga.
            </p>
        </div>
    </section>

    <!-- KONTAK -->
    <section id="kontak">
        <h2>Hubungi Saya</h2>

        <p>
            Terima kasih sudah mengunjungi
            website pengenalan diri saya!
        </p>

        <button onclick="pesan()">
            Klik di sini
        </button>
    </section>

    <!-- FOOTER -->
    <footer>
        <p>&copy; 2026 My Personal Website</p>
        <p>Dibuat dengan HTML, CSS, dan JavaScript.</p>
    </footer>

    <!-- JAVASCRIPT -->
    <script>
        function sapa() {
            alert("Halo! Senang berkenalan dengan kamu 😊");
        }

        function pesan() {
            alert("Terima kasih sudah mengunjungi website saya!");
        }
    </script>

</body>
</html>
