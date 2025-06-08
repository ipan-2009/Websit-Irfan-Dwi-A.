<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Portofolio Irfan</title>
  <link rel="stylesheet" href="Untitled-2.css">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">
</head>
<body>

  <header>
    <h1>Selamat Datang di Portofolio Saya</h1>
    <nav>
      <a href="#beranda">Beranda</a>
      <a href="#tentang">Tentang Saya</a>
      <a href="#proyek">Proyek</a>
      <a href="#kontak">Kontak</a>
    </nav>
  </header>

  <section id="beranda" class="hero">
    <img src="poto.jpg" alt="profile-irfan" class="glow-border">
    <h1 class="fade-in">Halo, saya <span class="highlight">Irfan dwi A.</span></h1>
    <p class="fade-in-delay">Web Developer fokus pada Front-End & UI/UX Design</p>
  </section>

  <section id="tentang" class="slide-left">
    <h2>Tentang Saya</h2>
    <p>Saya adalah pengembang web yang menyukai tampilan antarmuka interaktif dan responsif. Pengalaman saya meliputi HTML, CSS, JavaScript, dan React.</p>
  </section>

  <section id="proyek" class="slide-right">
    <h2>Proyek</h2>
    <ul>
      <li> Website Portfolio Pribadi</li>
      <li> Aplikasi To-Do List dengan React</li>
      <li> Desain UI untuk Aplikasi E-commerce</li>
    </ul>
  </section>

  <section id="kontak" class="fade-in">
    <h2>Kontak</h2>
    <p>Hubungi saya via WhatsApp: 
      <a href="https://wa.me/62882005509840" target="_blank">+62 882-0055-09840</a>
    </p>

    <form id="contactForm">
      <input type="text" name="name" placeholder="Nama Anda" required><br>
      <input type="text" name="phone" placeholder="Nomor HP Anda" required><br>
      <textarea name="message" placeholder="Pesan Anda" required></textarea><br>
      <button type="submit">Kirim</button>
    </form>

   <div class="social-icons blinking-color">
  <a href="https://github.com/ipan-2009" target="_blank"><i class="fab fa-github"></i></a>
  <a href="https://www.instagram.com/panpanzzz2" target="_blank"><i class="fab fa-instagram"></i></a>
  <a href="https://tiktok.com/@iponzzzyy" target="_blank"><i class="fab fa-tiktok"></i></a>
</div>
  </section>

  <footer>
    &copy; 2025 Irfan. Semua hak dilindungi.
  </footer>

  <script src="Untitled-3.js"></script>
</body>
</html>
