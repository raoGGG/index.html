<!doctype html>
<html lang="ja">
<head>
  <meta charset="utf-8">
  <title>ページ内リンク（アンカー）の例</title>
  <style>
    body { font-family: sans-serif; margin:0; }
    header {
      position: fixed; top:0; left:0; right:0;
      background:#333; color:#fff;
      padding: 10px 20px;
    }
    header a {
      color:#fff; text-decoration:none; margin: 0 15px;
    }
    section {
      height: 100vh; /* 画面いっぱいに表示 */
      padding-top: 60px; /* ヘッダー分の余白 */
    }
    #about   { background:#f0f0f0; }
    #service { background:#d0eaff; }
    #contact { background:#ffe0e0; }
  </style>
</head>
<body>

  <!-- ヘッダー -->
  <header>
    <a href="#about">About</a>
    <a href="#service">Service</a>
    <a href="#contact">Contact</a>
  </header>

  <!-- セクション -->
  <section id="about">
    <h1>About</h1>
    <p>ここは About セクションです。</p>
  </section>

  <section id="service">
    <h1>Service</h1>
    <p>ここは Service セクションです。</p>
  </section>

  <section id="contact">
    <h1>Contact</h1>
    <p>ここは Contact セクションです。</p>
  </section>

</body>
</html>
