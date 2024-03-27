# Status_Facebook
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Beranda Facebook</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f0f2f5;
      margin: 0;
      padding: 0;
    }

    header {
      background-color: #4267B2;
      color: #fff;
      padding: 10px;
      text-align: center;
    }

    main {
      max-width: 600px;
      margin: 20px auto;
      background-color: #fff;
      padding: 20px;
      border-radius: 8px;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    }

    #post-form {
      margin-bottom: 20px;
    }

    .post {
      border-bottom: 1px solid #ddd;
      padding: 10px 0;
    }

    .post img {
      max-width: 100%;
      border-radius: 8px;
      margin-top: 10px;
    }
  </style>
</head>
<body>

  <header>
    <h1>Facebook</h1>
  </header>

  <main>
    <div id="post-form">
      <!-- Form untuk membuat postingan -->
      <textarea placeholder="Apa yang Anda pikirkan?"></textarea>
      <input type="text" placeholder="URL Gambar">
      <button>Post</button>
    </div>

    <!-- Contoh postingan dengan gambar -->
    <div class="post">
      <p>Nama Pengguna</p>
      <p>Ini adalah postingan contoh.</p>
      <img src="https://example.com/gambar.jpg" alt="Contoh Gambar">
    </div>

    <!-- Postingan lainnya... -->
  </main>

</body>
</html>
