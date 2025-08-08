# https-muhalizainalabidin-boop.github.io
<!doctype html>

<html lang="id">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width,initial-scale=1">
  <title>Menjelajahi Pulau Sulawesi</title>
  <meta name="description" content="Portal pariwisata Pulau Sulawesi — destinasi, budaya, kuliner, dan galeri foto.">
  <style>
    :root{
      --accent: #00a896; --accent-2: #00796b; --bg:#fbfbfb; --card:#ffffff; --muted:#6b6b6b;
      --maxw:1200px;
    }
    *{box-sizing:border-box}
    body{margin:0;font-family:Inter, system-ui, -apple-system, 'Segoe UI', Roboto, 'Helvetica Neue', Arial;background:var(--bg);color:#0b0b0b;line-height:1.5}/* NAV */
.nav{position:fixed;left:0;right:0;top:0;display:flex;align-items:center;justify-content:space-between;padding:0.6rem 1.2rem;background:linear-gradient(180deg, rgba(255,255,255,0.85), rgba(255,255,255,0.6));backdrop-filter:blur(6px);z-index:30;border-bottom:1px solid rgba(0,0,0,0.05)}
.brand{display:flex;gap:.6rem;align-items:center}
.brand .logo{height:42px;width:42px;border-radius:8px;background:linear-gradient(135deg,var(--accent),var(--accent-2));display:flex;align-items:center;justify-content:center;color:white;font-weight:700}
.menu{display:flex;gap:1rem;align-items:center}
.menu a{color:#05273a;text-decoration:none;font-weight:600;padding:.35rem .6rem;border-radius:8px}
.menu a:hover{background:rgba(0,0,0,0.04)}
.cta{background:var(--accent);color:white;padding:.5rem .75rem;border-radius:8px;text-decoration:none}

/* HERO / SLIDER */
.hero{height:78vh;min-height:520px;display:grid;grid-template-columns:1fr 420px;gap:2rem;align-items:center;max-width:var(--maxw);margin:88px auto 2rem;padding:0 1rem}
.hero-left{padding:1rem}
.eyebrow{display:inline-block;background:linear-gradient(90deg,var(--accent),var(--accent-2));color:white;padding:.25rem .6rem;border-radius:999px;font-weight:700;margin-bottom:1rem}
h1{font-size:clamp(2rem,4vw,3rem);margin:.2rem 0}
p.lead{color:var(--muted);font-size:1.05rem}
.actions{margin-top:1.25rem;display:flex;gap:.8rem;flex-wrap:wrap}

/* card with slider */
.card{background:var(--card);border-radius:14px;box-shadow:0 10px 30px rgba(2,10,10,0.06);overflow:hidden}
.slider{position:relative;height:420px}
.slide{position:absolute;inset:0;opacity:0;transform:scale(1.02);transition:all .6s ease;display:flex;align-items:center;justify-content:center}
.slide.active{opacity:1;transform:scale(1)}
.slide img{width:100%;height:420px;object-fit:cover}
.slider .controls{position:absolute;left:10px;right:10px;bottom:10px;display:flex;justify-content:space-between;pointer-events:none}
.btn{pointer-events:auto;background:rgba(255,255,255,0.85);border-radius:10px;padding:.4rem .6rem;font-weight:700;border:0}

/* SECTIONS */
section{max-width:var(--maxw);margin:2rem auto;padding:0 1rem}
.grid{display:grid;gap:1rem}
.cols-3{grid-template-columns:repeat(3,1fr)}
.cols-2{grid-template-columns:repeat(2,1fr)}

.card--panel{background:var(--card);padding:1rem;border-radius:12px;box-shadow:0 6px 18px rgba(2,10,10,0.04)}
.small{font-size:.95rem;color:var(--muted)}

/* GALLERY */
.gallery{display:grid;grid-template-columns:repeat(auto-fill,minmax(220px,1fr));gap:12px}
.gallery img{width:100%;height:160px;object-fit:cover;border-radius:10px;cursor:pointer;display:block}

/* LIGHTBOX */
.lightbox{position:fixed;inset:0;background:rgba(2,6,10,0.75);display:none;align-items:center;justify-content:center;z-index:60}
.lightbox.open{display:flex}
.lightbox img{max-width:95%;max-height:85%;border-radius:10px;box-shadow:0 12px 40px rgba(0,0,0,0.6)}

/* FOOTER */
footer{background:linear-gradient(90deg,var(--accent-2),#004d40);color:white;padding:2rem 1rem;margin-top:3rem}
footer .wrap{max-width:var(--maxw);margin:auto;display:flex;justify-content:space-between;gap:1rem;align-items:center}

/* RESPONSIVE */
@media (max-width:980px){.hero{grid-template-columns:1fr;min-height:680px;padding-bottom:1rem}.slider{height:320px}.slide img{height:320px}.hero{margin-top:84px}}
@media (max-width:620px){.menu{display:none}.brand{gap:.4rem}}

/* simple animations */
.reveal{opacity:0;transform:translateY(18px);transition:all .7s cubic-bezier(.2,.9,.3,1)}
.reveal.in{opacity:1;transform:none}

  </style>
</head>
<body>
  <header class="nav" role="navigation">
    <div class="brand">
      <div class="logo">S</div>
      <div>
        <div style="font-weight:800">Pulau Sulawesi</div>
        <div style="font-size:.8rem;color:var(--muted)">Menjelajahi budaya & alam</div>
      </div>
    </div>
    <nav class="menu" aria-label="Main">
      <a href="#tentang">Tentang</a>
      <a href="#destinasi">Destinasi</a>
      <a href="#kuliner">Kuliner</a>
      <a href="#galeri">Galeri</a>
      <a class="cta" href="#kontak">Hubungi</a>
    </nav>
  </header>  <main>
    <section class="hero">
      <div class="hero-left">
        <span class="eyebrow">Selamat Datang</span>
        <h1 class="reveal">Menjelajahi Pulau Sulawesi — Alam, Budaya, & Rasa</h1>
        <p class="lead reveal">Sulawesi menawarkan lanskap menakjubkan — dari terumbu karang Bunaken sampai upacara adat Tana Toraja. Temukan destinasi terbaik, kuliner khas, serta galeri foto yang memukau.</p>
        <div class="actions reveal">
          <a class="cta" href="#destinasi">Jelajahi Destinasi</a>
          <a style="text-decoration:none;padding:.5rem .75rem;border-radius:8px;border:1px solid rgba(0,0,0,0.06);" href="#galeri">Lihat Galeri</a>
        </div><div style="margin-top:1.25rem;display:flex;gap:.6rem;flex-wrap:wrap" class="reveal">
      <div class="card--panel" style="min-width:160px"> <strong>Waktu terbaik:</strong><div class="small">April — Oktober</div></div>
      <div class="card--panel" style="min-width:160px"> <strong>Bahasa:</strong><div class="small">Indonesia, lokal</div></div>
    </div>
  </div>

  <aside class="card">
    <div class="slider" id="slider">
      <div class="slide active"><img loading="lazy" src="https://upload.wikimedia.org/wikipedia/commons/4/41/Bunaken_Dive.jpg" alt="Bunaken"></div>
      <div class="slide"><img loading="lazy" src="https://upload.wikimedia.org/wikipedia/commons/8/87/Toraja_House_Sulawesi.jpg" alt="Tana Toraja"></div>
      <div class="slide"><img loading="lazy" src="https://upload.wikimedia.org/wikipedia/commons/f/fd/Wakatobi_National_Park.jpg" alt="Wakatobi"></div>
      <div class="slide"><img loading="lazy" src="https://upload.wikimedia.org/wikipedia/commons/3/38/Lore_Lindu.jpg" alt="Lore Lindu"></div>
      <div class="controls">
        <button class="btn" id="prev">◀</button>
        <button class="btn" id="next">▶</button>
      </div>
    </div>
  </aside>
</section>

<section id="tentang" class="reveal">
  <h2>Tentang Sulawesi</h2>
  <div class="grid cols-2" style="margin-top:1rem">
    <div class="card--panel">
      <p>Sulawesi adalah pulau besar di Indonesia dengan garis pantai panjang dan bentuk yang khas. Pulau ini terkenal akan keragaman suku, adat, dan keindahan bawah lautnya. Terdiri dari beberapa provinsi: Sulawesi Utara, Tengah, Selatan, Tenggara, Gorontalo, dan Barat Daya (bagian administrasi).</p>
      <p class="small">Luas, budaya, dan ekosistemnya membuat Sulawesi menjadi tujuan wisata yang kaya pengalaman.</p>
    </div>
    <div class="card--panel">
      <h3>Fakta singkat</h3>
      <ul class="small">
        <li>Bentuk pulau yang unik dengan empat semenanjung utama.</li>
        <li>Rumah bagi taman laut terkenal seperti Bunaken dan Wakatobi.</li>
        <li>Kebudayaan khas: Tana Toraja (upacara adat), Gorontalo, Bugis, Makassar, dan seterusnya.</li>
      </ul>
    </div>
  </div>
</section>

<section id="destinasi" class="reveal">
  <h2>Destinasi Populer</h2>
  <div class="grid cols-3" style="margin-top:1rem">
    <div class="card--panel">
      <h4>Bunaken (Manado)</h4>
      <p class="small">Spot diving kelas dunia dengan terumbu karang yang lebat dan kehidupan laut yang beragam.</p>
    </div>
    <div class="card--panel">
      <h4>Wakatobi</h4>
      <p class="small">Taman laut yang eksotis—surga bagi penyelam dan fotografer bawah air.</p>
    </div>
    <div class="card--panel">
      <h4>Tana Toraja</h4>
      <p class="small">Kunjungi pemakaman batu, rumah adat tongkonan, dan saksikan upacara adat yang sarat makna.</p>
    </div>
    <div class="card--panel">
      <h4>Lore Lindu</h4>
      <p class="small">Hutan dataran tinggi dengan situs megalitik dan satwa endemik.</p>
    </div>
    <div class="card--panel">
      <h4>Togean Islands</h4>
      <p class="small">Surganya pulau-pulau terpencil, snorkeling, dan suasana tenang.</p>
    </div>
    <div class="card--panel">
      <h4>Bantimurung</h4>
      <p class="small">Air terjun menawan dan taman kupu-kupu di Sulawesi Selatan.</p>
    </div>
  </div>
</section>

<section id="kuliner" class="reveal">
  <h2>Kuliner Khas</h2>
  <div style="display:flex;gap:1rem;flex-wrap:wrap;margin-top:1rem">
    <div class="card--panel" style="min-width:220px"> <strong>Coto Makassar</strong><div class="small">Soto daging asli Makassar, kaya rempah.</div></div>
    <div class="card--panel" style="min-width:220px"> <strong>Pallubasa</strong><div class="small">Sup daging khas Makassar dengan cita rasa kuat.</div></div>
    <div class="card--panel" style="min-width:220px"> <strong>Tinutuan</strong><div class="small">Bubur Manado sehat penuh sayuran.</div></div>
    <div class="card--panel" style="min-width:220px"> <strong>Kapurung</strong><div class="small">Masakan khas Palu dari sagu dan ikan.</div></div>
  </div>
</section>

<section id="galeri" class="reveal">
  <h2>Galeri Foto</h2>
  <div class="gallery" style="margin-top:1rem">
    <img loading="lazy" src="https://upload.wikimedia.org/wikipedia/commons/8/87/Toraja_House_Sulawesi.jpg" alt="Rumah Adat Toraja">
    <img loading="lazy" src="https://upload.wikimedia.org/wikipedia/commons/4/41/Bunaken_Dive.jpg" alt="Bunaken">
    <img loading="lazy" src="https://upload.wikimedia.org/wikipedia/commons/f/fd/Wakatobi_National_Park.jpg" alt="Wakatobi">
    <img loading="lazy" src="https://upload.wikimedia.org/wikipedia/commons/3/38/Lore_Lindu.jpg" alt="Lore Lindu">
    <img loading="lazy" src="https://upload.wikimedia.org/wikipedia/commons/1/16/Bantimurung.JPG" alt="Bantimurung">
    <img loading="lazy" src="https://upload.wikimedia.org/wikipedia/commons/3/3b/Coto_Makassar.jpg" alt="Coto Makassar">
    <img loading="lazy" src="https://upload.wikimedia.org/wikipedia/commons/d/d4/Tinutuan_Manado.jpg" alt="Tinutuan">
    <img loading="lazy" src="https://upload.wikimedia.org/wikipedia/commons/6/66/Togean_Islands.jpg" alt="Togean Islands">
  </div>
</section>

<section id="kontak" class="reveal">
  <h2>Info Kontak & Tips</h2>
  <div class="grid cols-2" style="margin-top:1rem">
    <div class="card--panel">
      <h4>Tips Perjalanan</h4>
      <ul class="small">
        <li>Siapkan adaptasi cuaca — beberapa daerah tinggi bisa dingin di malam hari.</li>
        <li>Hormati adat lokal, terutama di Tana Toraja saat menghadiri upacara.</li>
        <li>Gunakan pemandu lokal saat menjelajah area konservasi dan Pulau terpencil.</li>
      </ul>
    </div>
    <div class="card--panel">
      <h4>Hubungi</h4>
      <p class="small">Untuk info tur dan paket lokal, hubungi: <br><strong>email: info@sulawesi.travel</strong> (contoh)</p>
    </div>
  </div>
</section>

  </main>  <div id="lightbox" class="lightbox" role="dialog" aria-hidden="true">
    <button id="lbClose" class="btn" style="position:absolute;top:18px;right:18px;">✕</button>
    <img src="" alt="preview">
  </div>  <footer>
    <div class="wrap">
      <div>
        <strong>Pulau Sulawesi</strong>
        <div class="small">© 2025 — Sumber gambar: Wikimedia Commons (placeholder)</div>
      </div>
      <div class="small">Didukung oleh komunitas pariwisata lokal</div>
    </div>
  </footer>  <script>
    // Simple slider
    (function(){
      const slides = document.querySelectorAll('.slide');
      let idx = 0; let t;
      const next = () => { slides[idx].classList.remove('active'); idx = (idx+1)%slides.length; slides[idx].classList.add('active'); }
      const prev = () => { slides[idx].classList.remove('active'); idx = (idx-1+slides.length)%slides.length; slides[idx].classList.add('active'); }
      document.getElementById('next').addEventListener('click', ()=>{ next(); reset(); });
      document.getElementById('prev').addEventListener('click', ()=>{ prev(); reset(); });
      function play(){ t=setInterval(next,4000) }
      function reset(){ clearInterval(t); play(); }
      play();
    })();

    // Lightbox gallery
    (function(){
      const lb = document.getElementById('lightbox');
      const lbImg = lb.querySelector('img');
      const close = document.getElementById('lbClose');
      document.querySelectorAll('.gallery img').forEach(img=>{
        img.addEventListener('click', ()=>{
          lbImg.src = img.src; lbImg.alt = img.alt; lb.classList.add('open'); lb.setAttribute('aria-hidden','false');
        })
      });
      close.addEventListener('click', ()=>{ lb.classList.remove('open'); lb.setAttribute('aria-hidden','true'); });
      lb.addEventListener('click', (e)=>{ if(e.target===lb) { lb.classList.remove('open'); lb.setAttribute('aria-hidden','true'); } });
    })();

    // reveal on scroll
    (function(){
      const obs = new IntersectionObserver((entries)=>{
        entries.forEach(ent=>{ if(ent.isIntersecting) ent.target.classList.add('in'); });
      },{threshold:.12});
      document.querySelectorAll('.reveal').forEach(el=>obs.observe(el));
    })();

    // smooth scroll for nav
    document.querySelectorAll('a[href^="#"]').forEach(a=>{
      a.addEventListener('click', (e)=>{
        const href = a.getAttribute('href'); if(href === '#') return; const target = document.querySelector(href);
        if(target){ e.preventDefault(); target.scrollIntoView({behavior:'smooth',block:'start'}); }
      })
    });
  </script></body>
</html>
