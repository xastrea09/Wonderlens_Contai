# Wonderlens_Contai
See the city through your lens
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>WonderLens_Contai – know your city through the lens</title>
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <style>
    :root{
      --accent:#ff006e;
      --bg:#0d0d0d;
      --txt:#f1f1f1;
      --card:#111;
    }
    *{box-sizing:border-box;margin:0;padding:0;font-family:-apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,Helvetica,Arial,sans-serif;}
    body{background:var(--bg);color:var(--txt);line-height:1.6;}
    a{color:var(--accent);text-decoration:none;}
    header{text-align:center;padding:4rem 1rem 2rem;}
    header img{width:120px;height:120px;border-radius:50%;object-fit:cover;border:3px solid var(--accent);}
    header h1{margin:.5rem 0 .25rem;font-size:2.2rem;}
    header p{font-size:1rem;opacity:.8;}
    section{padding:2rem 1rem;max-width:1000px;margin:auto;}
    .grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(250px,1fr));gap:1rem;}
    .card{background:var(--card);border-radius:8px;overflow:hidden;}
    .card img{width:100%;display:block;}
    .btn{display:inline-block;background:var(--accent);color:#fff;padding:.75rem 1.5rem;border-radius:4px;margin:.5rem .25rem;}
    footer{text-align:center;padding:2rem 1rem;font-size:.8rem;opacity:.6;}
  </style>
</head>
<body>

<!-- HEADER -->
<header>
  <!-- IG profile pic – auto-updates when you change it on Instagram -->
  <img src="https://instagram.com/wonderlens_contai/photo" alt="WonderLens_Contai logo">
  <h1>WonderLens_Contai</h1>
  <p>know your city through the lens</p>
  <a class="btn" href="#gallery">Gallery</a>
  <a class="btn" href="#contact">Book us</a>
</header>

<!-- ABOUT -->
<section id="about">
  <h2>About</h2>
  <p>We are a collective of young visual storytellers based in Contai, Purba Medinipur. From golden-hour streets to midnight skies, we freeze every emotion the city breathes.</p>
</section>

<!-- GALLERY -->
<section id="gallery">
  <h2>Gallery</h2>
  <div class="grid">
    <div class="card"><img src="img/1.jpg" alt=""></div>
    <div class="card"><img src="img/2.jpg" alt=""></div>
    <div class="card"><img src="img/3.jpg" alt=""></div>
    <div class="card"><img src="img/4.jpg" alt=""></div>
  </div>
</section>

<!-- SERVICES -->
<section id="services">
  <h2>Services</h2>
  <table style="width:100%;border-collapse:collapse;margin-top:1rem;">
    <thead>
      <tr style="border-bottom:1px solid var(--accent);text-align:left;">
        <th style="padding:.5rem;">Package</th>
        <th style="padding:.5rem;">What’s included</th>
        <th style="padding:.5rem;">Price</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td style="padding:.5rem;">Basic</td>
        <td style="padding:.5rem;">1-hr shoot, 25 edits</td>
        <td style="padding:.5rem;">₹2 999</td>
      </tr>
      <tr>
        <td style="padding:.5rem;">Standard</td>
        <td style="padding:.5rem;">2-hr shoot, 50 edits, 1-min reel</td>
        <td style="padding:.5rem;">₹4 999</td>
      </tr>
      <tr>
        <td style="padding:.5rem;">Premium</td>
        <td style="padding:.5rem;">Half-day, 100+ edits, 3 reels, drone</td>
        <td style="padding:.5rem;">₹9 999</td>
      </tr>
    </tbody>
  </table>
</section>

<!-- CONTACT -->
<section id="contact">
  <h2>Contact</h2>
  <p>
    📞 <a href="tel:+917001602125">+91 70016 02125</a><br>
    📞 <a href="tel:+919046742008">+91 90467 42008</a><br>
    📧 <a href="mailto:wonderlens.contai@gmail.com">wonderlens.contai@gmail.com</a><br>
    📍 Contai, Purba Medinipur, WB – 721401
  </p>
  <p>
    Follow the journey:<br>
    <a href="https://instagram.com/wonderlens_contai" target="_blank">Instagram</a> •
    <a href="https://youtube.com/@wonderlenscontai" target="_blank">YouTube</a> •
    <a href="https://wa.me/917001602125" target="_blank">WhatsApp</a>
  </p>
</section>

<!-- FOOTER -->
<footer>© 2025 WonderLens_Contai. All rights reserved.</footer>

</body>
</html>
