# Wedding-invitation<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Undangan Pernikahan Ridwansyah & Ema</title>

<style>
body {
  margin: 0;
  font-family: 'Georgia', serif;
  background: #f5f3ef;
  color: #333;
}
section {
  padding: 60px 20px;
  text-align: center;
}
.cover {
  height: 100vh;
  background: linear-gradient(rgba(0,0,0,.45), rgba(0,0,0,.45)),
              url('background.jpg') center/cover no-repeat;
  color: white;
  display: flex;
  align-items: center;
  justify-content: center;
  flex-direction: column;
}
.cover h1 {
  font-size: 38px;
  margin: 10px 0;
}
.cover p {
  font-size: 18px;
}
.btn {
  margin-top: 30px;
  padding: 12px 30px;
  background: #c9a24d;
  color: white;
  border-radius: 30px;
  text-decoration: none;
  font-size: 16px;
}
.card {
  background: white;
  border-radius: 20px;
  padding: 40px 20px;
  max-width: 600px;
  margin: auto;
  box-shadow: 0 15px 30px rgba(0,0,0,.1);
}
h2 {
  color: #c9a24d;
}
.divider {
  width: 70px;
  height: 3px;
  background: #c9a24d;
  margin: 20px auto;
}
.footer {
  font-size: 14px;
  color: #777;
}
</style>
</head>

<body>

<!-- MUSIK (opsional, boleh dihapus kalau tidak mau) -->
<audio autoplay loop>
  <source src="musik.mp3" type="audio/mpeg">
</audio>

<!-- COVER -->
<section class="cover">
  <p>Undangan Pernikahan</p>
  <h1>Ridwansyah & Ema</h1>
  <p>18 Januari 2026</p>
  <a href="#isi" class="btn">Buka Undangan</a>
</section>

<!-- ISI UNDANGAN -->
<section id="isi">
  <div class="card">
    <p>Assalamu’alaikum Warahmatullahi Wabarakatuh</p>

    <p>
      Dengan memohon rahmat dan ridho Allah SWT, kami bermaksud
      mengundang Bapak/Ibu/Saudara/i untuk menghadiri pernikahan kami:
    </p>

    <h2>Ridwansyah</h2>
    <div class="divider"></div>
    <h2>Ema</h2>

    <h3>Akad Nikah</h3>
    <p>
      Minggu, 18 Januari 2026<br>
      Pukul 08:00 WIB<br>
      Di kediaman mempelai pria
    </p>

    <h3>Resepsi</h3>
    <p>
      Minggu, 18 Januari 2026<br>
      Pukul 13:00 – 20:00 WIB<br>
      Di kediaman mempelai pria
    </p>

    <p>
      Merupakan suatu kehormatan dan kebahagiaan bagi kami
      apabila Bapak/Ibu/Saudara/i berkenan hadir dan memberikan doa restu.
    </p>

    <p>Wassalamu’alaikum Warahmatullahi Wabarakatuh</p>

    <div class="footer">
      <p>Kami yang berbahagia</p>
      <strong>Ridwansyah & Ema</strong>
    </div>
  </div>
</section>

</body>
</html>
