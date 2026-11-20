<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Ringkasan sejarah Perundingan Linggarjati: latar belakang, tokoh, isi perjanjian, dan dampaknya.">
  <title>Perundingan Linggarjati — Sejarah Indonesia</title>
  <style>
    :root {
      --ink: #1f302b;
      --muted: #62726c;
      --green: #245c49;
      --green-dark: #173d32;
      --cream: #f7f5ed;
      --paper: #fffefa;
      --gold: #d3a64f;
      --line: #e5e3d9;
      --red: #a64d43;
      --shadow: 0 16px 40px rgba(27, 47, 39, 0.08);
    }

    * {
      box-sizing: border-box;
    }

    html {
      scroll-behavior: smooth;
    }

    body {
      margin: 0;
      color: var(--ink);
      background: var(--cream);
      font-family: system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
      line-height: 1.7;
    }

    a {
      color: inherit;
    }

    .topbar {
      position: sticky;
      top: 0;
      z-index: 10;
      background: rgba(247, 245, 237, 0.94);
      border-bottom: 1px solid var(--line);
      backdrop-filter: blur(12px);
    }

    .nav {
      width: min(1120px, calc(100% - 40px));
      min-height: 68px;
      margin: 0 auto;
      display: flex;
      align-items: center;
      justify-content: space-between;
      gap: 24px;
    }

    .brand {
      color: var(--green-dark);
      font-weight: 800;
      letter-spacing: -0.03em;
      text-decoration: none;
    }

    .nav-links {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
      font-size: 0.88rem;
    }

    .nav-links a {
      color: var(--muted);
      text-decoration: none;
    }

    .nav-links a:hover {
      color: var(--green);
    }

    .hero {
      position: relative;
      overflow: hidden;
      padding: 88px 20px 82px;
      color: white;
      background:
        radial-gradient(ellipse at 85% 20%, rgba(211, 166, 79, 0.28), transparent 35%),
        linear-gradient(125deg, var(--green-dark), var(--green));
    }

    .hero::after {
      position: absolute;
      right: -80px;
      bottom: -180px;
      width: 460px;
      height: 460px;
      border: 1px solid rgba(255, 255, 255, 0.13);
      border-radius: 50%;
      content: "";
      box-shadow: 0 0 0 45px rgba(255,255,255,0.035),
                  0 0 0 95px rgba(255,255,255,0.025);
    }

    .hero-inner {
      position: relative;
      z-index: 1;
      width: min(960px, 100%);
      margin: 0 auto;
    }

    .eyebrow {
      display: inline-block;
      margin-bottom: 14px;
      color: #f0d99f;
      font-size: 0.78rem;
      font-weight: 800;
      letter-spacing: 0.16em;
      text-transform: uppercase;
    }

    h1, h2, h3, p {
      margin-top: 0;
    }

    h1 {
      max-width: 760px;
      margin-bottom: 18px;
      font-family: Georgia, "Times New Roman", serif;
      font-size: clamp(2.6rem, 7vw, 5.2rem);
      font-weight: 500;
      letter-spacing: -0.045em;
      line-height: 1.04;
    }

    .hero p {
      max-width: 650px;
      margin-bottom: 30px;
      color: rgba(255, 255, 255, 0.82);
      font-size: 1.1rem;
    }

    .hero-meta {
      display: flex;
      flex-wrap: wrap;
      gap: 12px;
    }

    .pill {
      padding: 7px 13px;
      border: 1px solid rgba(255, 255, 255, 0.26);
      border-radius: 999px;
      color: rgba(255, 255, 255, 0.92);
      font-size: 0.88rem;
    }

    main {
      width: min(960px, calc(100% - 40px));
      margin: 0 auto;
      padding: 58px 0 80px;
    }

    section {
      scroll-margin-top: 90px;
      margin-bottom: 58px;
    }

    .section-heading {
      display: flex;
      align-items: baseline;
      gap: 14px;
      margin-bottom: 20px;
    }

    .section-number {
      color: var(--gold);
      font-family: Georgia, "Times New Roman", serif;
      font-size: 1.35rem;
      font-weight: 700;
    }

    h2 {
      margin-bottom: 0;
      color: var(--green-dark);
      font-family: Georgia, "Times New Roman", serif;
      font-size: clamp(1.7rem, 4vw, 2.4rem);
      font-weight: 500;
      letter-spacing: -0.025em;
      line-height: 1.2;
    }

    .intro-card,
    .info-card,
    .agreement-card,
    .impact-card {
      background: var(--paper);
      border: 1px solid var(--line);
      border-radius: 18px;
      box-shadow: var(--shadow);
    }

    .intro-card {
      padding: 28px 30px;
      border-left: 4px solid var(--gold);
    }

    .intro-card p:last-child {
      margin-bottom: 0;
    }

    .details-grid {
      display: grid;
      grid-template-columns: repeat(2, 1fr);
      gap: 14px;
    }

    .info-card {
      padding: 20px;
      box-shadow: none;
    }

    .info-card span {
      display: block;
      margin-bottom: 4px;
      color: var(--muted);
      font-size: 0.83rem;
    }

    .info-card strong {
      color: var(--green-dark);
      font-size: 1.02rem;
    }

    .agreement-card {
      padding: 26px 30px;
    }

    .agreement-card ol {
      margin: 0;
      padding-left: 1.35rem;
    }

    .agreement-card li {
      padding: 7px 0 7px 7px;
    }

    .agreement-card li::marker {
      color: var(--gold);
      font-weight: 800;
    }

    .impact-grid {
      display: grid;
      grid-template-columns: repeat(2, 1fr);
      gap: 18px;
    }

    .impact-card {
      padding: 24px;
      box-shadow: none;
    }

    .impact-card h3 {
      display: flex;
      align-items: center;
      gap: 10px;
      margin-bottom: 14px;
      color: var(--green-dark);
      font-size: 1.08rem;
    }

    .impact-card.negative h3 {
      color: var(--red);
    }

    .impact-card ul {
      margin: 0;
      padding-left: 1.2rem;
      color: var(--muted);
    }

    .impact-card li {
      padding: 4px 0;
    }

    .timeline {
      position: relative;
      margin: 8px 0 0 8px;
      padding-left: 28px;
      border-left: 2px solid var(--line);
    }

    .timeline-item {
      position: relative;
      padding: 0 0 26px;
    }

    .timeline-item:last-child {
      padding-bottom: 0;
    }

    .timeline-item::before {
      position: absolute;
      top: 8px;
      left: -36px;
      width: 14px;
      height: 14px;
      background: var(--gold);
      border: 3px solid var(--cream);
      border-radius: 50%;
      content: "";
    }

    .timeline-item time {
      display: block;
      margin-bottom: 3px;
      color: var(--green);
      font-size: 0.86rem;
      font-weight: 800;
    }

    .timeline-item p {
      margin-bottom: 0;
      color: var(--muted);
    }

    .closing-note {
      padding: 24px 28px;
      color: white;
      background: var(--green-dark);
      border-radius: 18px;
    }

    .closing-note p {
      margin-bottom: 0;
      color: rgba(255, 255, 255, 0.84);
    }

    footer {
      padding: 24px 20px;
      color: var(--muted);
      border-top: 1px solid var(--line);
      text-align: center;
      font-size: 0.88rem;
    }

    @media (max-width: 640px) {
      .nav {
        align-items: flex-start;
        flex-direction: column;
        justify-content: center;
        gap: 6px;
        padding: 12px 0;
      }

      .nav-links {
        gap: 12px;
        font-size: 0.8rem;
      }

      .hero {
        padding: 68px 20px;
      }

      main {
        padding-top: 42px;
      }

      .details-grid,
      .impact-grid {
        grid-template-columns: 1fr;
      }

      .intro-card,
      .agreement-card {
        padding: 22px;
      }
    }
  </style>
</head>
<body>
  <header class="topbar">
    <nav class="nav" aria-label="Navigasi utama">
      <a class="brand" href="#beranda">CATATAN SEJARAH</a>
      <div class="nav-links">
        <a href="#latar-belakang">Latar Belakang</a>
        <a href="#pelaksanaan">Pelaksanaan</a>
        <a href="#isi-perjanjian">Isi Perjanjian</a>
        <a href="#dampak">Dampak</a>
        <a href="#akhir">Akhir Linggarjati</a>
      </div>
    </nav>
  </header>

  <header class="hero" id="beranda">
    <div class="hero-inner">
      <span class="eyebrow">Sejarah Indonesia · 1946–1947</span>
      <h1>Perundingan Linggarjati</h1>
      <p>
        Upaya diplomasi Indonesia dan Belanda untuk menyelesaikan konflik
        setelah Proklamasi Kemerdekaan.
      </p>
      <div class="hero-meta">
        <span class="pill">Linggarjati, Jawa Barat</span>
        <span class="pill">10–15 November 1946</span>
        <span class="pill">Ditandatangani 25 Maret 1947</span>
      </div>
    </div>
  </header>

  <main>
    <section id="latar-belakang">
      <div class="section-heading">
        <span class="section-number">01</span>
        <h2>Latar Belakang</h2>
      </div>
      <div class="intro-card">
        <p>
          Perundingan Linggarjati merupakan salah satu perundingan penting
          pertama antara Indonesia dan Belanda setelah Proklamasi Kemerdekaan.
        </p>
        <p>
          Konflik meningkat karena Belanda belum bersedia mengakui kemerdekaan
          Indonesia, sementara Indonesia ingin mempertahankan kemerdekaan dan
          memperoleh pengakuan resmi. Untuk membantu menyelesaikan konflik,
          Inggris mempertemukan kedua pihak melalui perundingan di Linggarjati,
          Kabupaten Kuningan, Jawa Barat.
        </p>
      </div>
    </section>

    <section id="pelaksanaan">
      <div class="section-heading">
        <span class="section-number">02</span>
        <h2>Pelaksanaan dan Tokoh</h2>
      </div>
      <div class="details-grid">
        <article class="info-card">
          <span>Waktu perundingan</span>
          <strong>10–15 November 1946</strong>
        </article>
        <article class="info-card">
          <span>Penandatanganan</span>
          <strong>25 Maret 1947</strong>
        </article>
        <article class="info-card">
          <span>Tempat</span>
          <strong>Linggarjati, Jawa Barat</strong>
        </article>
        <article class="info-card">
          <span>Delegasi Indonesia</span>
          <strong>Dipimpin Sutan Sjahrir</strong>
        </article>
        <article class="info-card">
          <span>Delegasi Belanda</span>
          <strong>Dipimpin Wim Schermerhorn</strong>
        </article>
        <article class="info-card">
          <span>Penengah</span>
          <strong>Lord Killearn dari Inggris</strong>
        </article>
      </div>
    </section>

    <section id="isi-perjanjian">
      <div class="section-heading">
        <span class="section-number">03</span>
        <h2>Isi Perjanjian Linggarjati</h2>
      </div>
      <div class="agreement-card">
        <p>Hasil perundingan terdiri atas 17 pasal. Beberapa kesepakatan utamanya:</p>
        <ol>
          <li>
            Belanda mengakui secara de facto Republik Indonesia dengan wilayah
            kekuasaan meliputi Jawa, Madura, dan Sumatra.
          </li>
          <li>Indonesia dan Belanda sepakat membentuk Negara Indonesia Serikat (RIS).</li>
          <li>RIS akan terdiri atas Republik Indonesia, Kalimantan, dan Negara Indonesia Timur.</li>
          <li>RIS dan Kerajaan Belanda akan membentuk Uni Indonesia-Belanda.</li>
          <li>Pembentukan RIS direncanakan selesai sebelum 1 Januari 1949.</li>
        </ol>
      </div>
    </section>

    <section id="dampak">
      <div class="section-heading">
        <span class="section-number">04</span>
        <h2>Dampak Perjanjian</h2>
      </div>
      <div class="impact-grid">
        <article class="impact-card">
          <h3><span aria-hidden="true">＋</span> Dampak Positif</h3>
          <ul>
            <li>Indonesia memperoleh pengakuan de facto dari Belanda.</li>
            <li>Kedudukan Indonesia semakin dikenal dalam hubungan internasional.</li>
            <li>Konflik antara Indonesia dan Belanda sempat mengalami penurunan.</li>
          </ul>
        </article>
        <article class="impact-card negative">
          <h3><span aria-hidden="true">−</span> Dampak Negatif</h3>
          <ul>
            <li>Wilayah Republik Indonesia hanya diakui meliputi Jawa, Madura, dan Sumatra.</li>
            <li>Hasil perjanjian dianggap sebagian masyarakat terlalu menguntungkan Belanda.</li>
            <li>Muncul perbedaan pendapat di kalangan masyarakat dan tokoh politik Indonesia.</li>
          </ul>
        </article>
      </div>
    </section>

    <section id="akhir">
      <div class="section-heading">
        <span class="section-number">05</span>
        <h2>Pelanggaran dan Akhir Linggarjati</h2>
      </div>
      <div class="timeline">
        <article class="timeline-item">
          <time>Setelah perjanjian</time>
          <p>
            Hubungan Indonesia dan Belanda kembali memburuk. Kedua pihak saling
            menuduh melanggar kesepakatan.
          </p>
        </article>
        <article class="timeline-item">
          <time>21 Juli 1947</time>
          <p>
            Belanda melancarkan Agresi Militer Belanda I dengan menyerang
            wilayah Republik Indonesia di Jawa dan Sumatra.
          </p>
        </article>
      </div>
    </section>

    <aside class="closing-note">
      <strong>Catatan</strong>
      <p>
        Peristiwa ini menunjukkan bahwa perjuangan mempertahankan kemerdekaan
        belum selesai dan Indonesia perlu mencari dukungan internasional yang
        lebih kuat.
      </p>
    </aside>
  </main>

  <footer>
    <p>Materi sejarah: Perundingan Linggarjati</p>
  </footer>
</body>
</html>
