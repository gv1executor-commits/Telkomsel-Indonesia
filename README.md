<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <title>Pendaftaran Belajar Pancasila</title>
</head>
<body>
  <h2>Pendaftaran Belajar Pancasila</h2>

  <form action="https://formspree.io/f/yourformid" method="POST">
    <!-- Input Nama -->
    <label for="nama">Nama Lengkap:</label><br>
    <input type="text" id="nama" name="nama" required><br><br>

    <!-- Soal Pilihan Ganda -->
    <p>1. Sila pertama dalam Pancasila adalah?</p>
    <input type="radio" id="a1" name="soal1" value="A" required>
    <label for="a1">A. Kemanusiaan yang adil dan beradab</label><br>
    <input type="radio" id="b1" name="soal1" value="B">
    <label for="b1">B. Ketuhanan Yang Maha Esa</label><br>
    <input type="radio" id="c1" name="soal1" value="C">
    <label for="c1">C. Persatuan Indonesia</label><br>
    <input type="radio" id="d1" name="soal1" value="D">
    <label for="d1">D. Keadilan sosial bagi seluruh rakyat Indonesia</label><br><br>

    <p>2. Sila ketiga Pancasila berbunyi?</p>
    <input type="radio" id="a2" name="soal2" value="A" required>
    <label for="a2">A. Persatuan Indonesia</label><br>
    <input type="radio" id="b2" name="soal2" value="B">
    <label for="b2">B. Kerakyatan yang dipimpin oleh hikmat kebijaksanaan</label><br>
    <input type="radio" id="c2" name="soal2" value="C">
    <label for="c2">C. Ketuhanan Yang Maha Esa</label><br>
    <input type="radio" id="d2" name="soal2" value="D">
    <label for="d2">D. Kemanusiaan yang adil dan beradab</label><br><br>

    <!-- Tombol Submit -->
    <button type="submit">Daftar & Kirim Jawaban</button>
  </form>
</body>
</html>
