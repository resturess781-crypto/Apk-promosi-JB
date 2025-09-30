<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Ress Store - Jual Beli Akun Game</title>
  <style>
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background: linear-gradient(135deg, #1a2a6c, #b21f1f, #1a2a6c);
      color: white;
      margin: 0;
      padding: 0;
      display: flex;
      justify-content: center;
      align-items: center;
      min-height: 100vh;
      text-align: center;
    }
    .container {
      background: rgba(0, 0, 0, 0.7);
      padding: 40px;
      border-radius: 15px;
      max-width: 500px;
      box-shadow: 0 10px 30px rgba(0, 0, 0, 0.5);
    }
    h1 {
      font-size: 2.5em;
      margin-bottom: 20px;
      color: #ffcc00;
    }
    p {
      font-size: 1.1em;
      margin: 15px 0;
    }
    .contact {
      margin-top: 30px;
    }
    .number {
      font-size: 1.4em;
      font-weight: bold;
      color: #4dff4d;
      margin: 15px 0;
      word-break: break-all;
    }
    .btn {
      display: inline-block;
      margin: 10px;
      padding: 12px 24px;
      background: #00c853;
      color: white;
      text-decoration: none;
      border-radius: 50px;
      font-weight: bold;
      transition: 0.3s;
    }
    .btn:hover {
      background: #009624;
      transform: scale(1.05);
    }
    .copy-btn {
      background: #2196f3;
    }
    .copy-btn:hover {
      background: #0b7dda;
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>🔥 Ress Store 🔥</h1>
    <p>Jual Beli Akun Game Terpercaya!</p>
    <p>Akun Mobile Legends, Free Fire, PUBG, Valorant, dan lainnya!</p>
    <p>Harga Murah • Akun Aman • Proses Cepat</p>

    <div class="contact">
      <p>Hubungi Kami Sekarang:</p>
      <div class="number" id="phone">0895325957123</div>
      <a href="https://wa.me/62895325957123" target="_blank" class="btn">💬 Chat via WhatsApp</a>
      <button class="btn copy-btn" onclick="copyNumber()">📋 Salin Nomor</button>
    </div>
  </div>

  <script>
    function copyNumber() {
      const text = "0895325957123";
      navigator.clipboard.writeText(text).then(() => {
        alert("Nomor berhasil disalin: " + text);
      }).catch(err => {
        alert("Gagal menyalin nomor. Silakan salin manual.");
      });
    }
  </script>
</body>
</html>
