# <!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>ProbityComputer Solutions</title>
  <meta name="description" content="ProbityComputer Solutions — IT services, repairs, networks, web design & support." />
  <meta name="theme-color" content="#0b7285" />

  <!-- Fav icon (inline SVG fallback) -->
  <link rel="icon" href="data:image/svg+xml,<svg xmlns=%22http://www.w3.org/2000/svg%22 viewBox=%220 0 100 100%22><rect width=%22100%22 height=%22100%22 rx=%2218%22 fill=%22%230b7285%22/><text x=%2250%22 y=%2258%22 font-size=%2248%22 text-anchor=%22middle%22 fill=%22white%22 font-family=%22Arial%22>P</text></svg>">

  <style>
    :root{
      --bg:#f7fbfc;
      --card:#ffffff;
      --accent:#0b7285;
      --muted:#667085;
      --radius:14px;
      --glass: rgba(255,255,255,0.6);
      --maxw:1100px;
      --shadow: 0 8px 30px rgba(11,114,133,0.08);
      --glass-2: rgba(11,114,133,0.06);
      font-family: Inter, ui-sans-serif, system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial;
    }
    *{box-sizing:border-box}
    html,body{height:100%}
    body{
      margin:0;
      background:
        linear-gradient(180deg, rgba(11,114,133,0.06), rgba(11,114,133,0.02)),
        var(--bg);
      color:#0b2430;
      -webkit-font-smoothing:antialiased;
      -moz-osx-font-smoothing:grayscale;
      line-height:1.45;
      padding:48px 20px;
      display:flex;
      justify-content:center;
      align-items:flex-start;
      gap:24px;
      font-size:16px;
    }

    .site{
      width:100%;
      max-width:var(--maxw);
    }

    header{
      display:flex;
      justify-content:space-between;
      align-items:center;
      gap:16px;
      margin-bottom:28px;
    }
    .brand{
      display:flex;
      gap:12px;
      align-items:center;
    }
    .logo{
      width:60px;
      height:60px;
      border-radius:12px;
      background:linear-gradient(135deg,var(--accent),#055c66);
      box-shadow:var(--shadow);
      display:flex;
      align-items:center;
      justify-content:center;
      color:white;
      font-weight:700;
      font-size:22px;
    }
    nav a{
      margin-left:18px;
      text-decoration:none;
      color:var(--muted);
      font-weight:600;
    }
    .hero{
      background:linear-gradient(180deg, rgba(255,255,255,0.8), rgba(255,255,255,0.6));
      border-radius:var(--radius);
      padding:28px;
      box-shadow:var(--shadow);
      display:grid;
      grid-template-columns:1fr 360px;
      gap:20px;
      align-items:center;
    }
    .hero h1{
      margin:0 0 12px 0;
      font-size:28px;
      color:#052a33;
    }
    .hero p{margin:0 0 18px 0; color:var(--muted)}
    .cta{
      display:flex;
      gap:12px;
      align-items:center;
      flex-wrap:wrap;
    }
    .btn{
      background:var(--accent);
      color:white;
      padding:10px 16px;
      border-radius:10px;
      border:0;
      font-weight:700;
      cursor:pointer;
      text-decoration:none;
      display:inline-flex;
      gap:10px;
      align-items:center;
    }
    .btn.secondary{
      background:transparent;
      color:var(--accent);
      border:1px solid rgba(11,114,133,0.12);
      font-weight:700;
    }

    .card{
      background:var(--card);
      border-radius:12px;
      padding:18px;
      box-shadow: 0 6px 22px rgba(2,6,23,0.06);
    }

    /* Services */
    .services{
      margin-top:26px;
      display:grid;
      grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
      gap:14px;
    }
    .service{
      padding:16px;
      border-radius:12px;
      background:linear-gradient(180deg,var(--glass),transparent);
      border:1px solid var(--glass-2);
    }
    .service h3{margin:8px 0 6px 0}
    .service p{margin:0;color:var(--muted);font-size:14px}

    /* Contact column */
    .contact-col{padding:18px}
    .contact-col h3{margin-top:0}
    label{display:block;margin:8px 0 6px 0;font-size:13px;color:var(--muted)}
    input[type="text"], input[type="email"], textarea{
      width:100%;
      padding:10px 12px;
      border-radius:10px;
      border:1px solid rgba(9,30,40,0.06);
      font-size:14px;
      outline:none;
    }
    textarea{min-height:120px;resize:vertical;padding-top:12px}
    .muted-small{font-size:13px;color:var(--muted);margin-top:8px}

    footer{
      margin-top:22px;
      display:flex;
      justify-content:space-between;
      align-items:center;
      color:var(--muted);
      font-size:14px;
    }

    /* Floating actions */
    .fab-wrap{
      position:fixed;
      right:18px;
      bottom:18px;
      display:flex;
      flex-direction:column;
      gap:12px;
      z-index:999;
    }
    .fab{
      width:56px;height:56px;border-radius:14px;
      display:flex;align-items:center;justify-content:center;
      color:white;font-weight:700;text-decoration:none;
      box-shadow:var(--shadow);
    }
    .fab.whatsapp{background:#25d366;}
    .fab.call{background:#0b7285;}
    .fab:hover{transform:translateY(-3px);transition:all .15s ease}

    /* Responsive */
    @media (max-width:900px){
      .hero{grid-template-columns:1fr}
      body{padding:18px}
    }
  </style>
</head>
<body>
  <div class="site">
    <header>
      <div class="brand">
        <div class="logo">P</div>
        <div>
          <div style="font-weight:800;font-size:18px">ProbityComputer Solutions</div>
          <div style="font-size:13px;color:var(--muted)">IT support • Web • Networks • Repairs</div>
        </div>
      </div>

      <nav aria-label="Main navigation">
        <a href="#services">Services</a>
        <a href="#about">About</a>
        <a href="#contact">Contact</a>
      </nav>
    </header>

    <main>
      <section class="hero" aria-labelledby="hero-heading">
        <div>
          <h1 id="hero-heading">Reliable IT support for small businesses & home users</h1>
          <p>We build websites, setup networks, repair PCs and give fast local support. Trusted, affordable, and friendly service — ready to help in your area.</p>

          <div class="cta">
            <a class="btn" href="#contact" title="Contact us">Get a free quote</a>
            <a class="btn secondary" href="#services" title="See services">See Services</a>
            <a class="btn" style="background:transparent;color:#0b7285;border:0;padding:10px 0" href="mailto:probitycomputersolutions@gmail.com">probitycomputersolutions@gmail.com</a>
          </div>

          <div class="services" id="services" style="margin-top:18px;">
            <div class="service card">
              <strong>Web design & hosting</strong>
              <p>Responsive websites, maintenance, and Netlify-ready builds so your site stays fast and secure.</p>
            </div>
            <div class="service card">
              <strong>PC & laptop repairs</strong>
              <p>Hardware troubleshooting, upgrades, virus removal, and data recovery.</p>
            </div>
            <div class="service card">
              <strong>Networking & Wi-Fi</strong>
              <p>Home and small office Wi-Fi setup, router configuration, and troubleshooting.</p>
            </div>
            <div class="service card">
              <strong>Managed IT & support</strong>
              <p>Ongoing care plans, remote support, and on-site visits by appointment.</p>
            </div>
          </div>

        </div>

        <!-- Contact column -->
        <aside class="card contact-col" id="contact" aria-labelledby="contact-heading">
          <h3 id="contact-heading">Contact us</h3>
          <p class="muted-small">Fill this form or use the WhatsApp / Call buttons at the bottom-right.</p>

          <!-- Netlify form -->
          <form name="contact" method="POST" data-netlify="true" netlify-honeypot="bot-field">
            <input type="hidden" name="form-name" value="contact">
            <p style="display:none"><label>Don’t fill: <input name="bot-field"></label></p>

            <label for="name">Full name</label>
            <input id="name" name="name" type="text" placeholder="Jane Doe" required>

            <label for="email">Email</label>
            <input id="email" name="email" type="email" placeholder="you@example.com" required>

            <label for="phone">Phone (optional)</label>
            <input id="phone" name="phone" type="text" placeholder="+254725722964">

            <label for="message">Message</label>
            <textarea id="message" name="message" placeholder="Tell us about your request..." required></textarea>

            <div style="margin-top:12px;display:flex;gap:10px;align-items:center">
              <button class="btn" type="submit">Send message</button>
              <a class="btn secondary" href="tel:+254725722964" style="padding:10px 12px">Call us</a>
            </div>
          </form>

          <div style="margin-top:14px" class="muted-small">
            <div><strong>Phone:</strong> <a href="tel:+254725722964">+254 725 722 964</a></div>
            <div><strong>Email:</strong> <a href="mailto:probitycomputersolutions@gmail.com">probitycomputersolutions@gmail.com</a></div>
            <div style="margin-top:8px">
              <strong>Address:</strong> <a href="https://www.google.com/maps/search/?api=1&query=Nairobi,+Kenya" target="_blank" rel="noopener noreferrer">Nairobi, Kenya</a>
            </div>
          </div>
        </aside>
      </section>

      <footer>
        <div>© <span id="year"></span> ProbityComputer Solutions — All rights reserved.</div>
        <div style="display:flex;gap:12px;align-items:center">
          <a href="#" aria-label="Facebook" title="Facebook" style="text-decoration:none;color:var(--muted)">Facebook</a>
          <a href="#" aria-label="Twitter" title="Twitter" style="text-decoration:none;color:var(--muted)">Twitter</a>
          <a href="#" aria-label="Instagram" title="Instagram" style="text-decoration:none;color:var(--muted)">Instagram</a>
        </div>
      </footer>
    </main>
  </div>

  <!-- Floating WhatsApp & Call buttons -->
  <div class="fab-wrap" aria-hidden="false">
    <!-- WhatsApp -->
    <a class="fab whatsapp" href="https://wa.me/254725722964?text=Hello%20ProbityComputer%20Solutions%2C%20I%20need%20help%20with..." target="_blank" rel="noopener noreferrer" aria-label="Chat on WhatsApp" title="Chat on WhatsApp">
      <svg width="22" height="22" viewBox="0 0 24 24" fill="none" aria-hidden="true" xmlns="http://www.w3.org/2000/svg">
        <path d="M20.52 3.48A11.92 11.92 0 0 0 12 0C5.372 0 .04 5.333.04 12 0 13.986.405 15.904 1.18 17.6L0 24l6.6-1.766A11.94 11.94 0 0 0 12 24c6.63 0 12-5.373 12-12 0-3.206-1.25-6.2-3.48-8.52z" fill="#fff" opacity="0.06"/>
        <path d="M17.472 14.382c-.297-.149-1.76-.868-2.03-.966-.273-.099-.472-.148-.672.149-.198.297-.768.966-.94 1.164-.173.198-.347.223-.644.074-.297-.149-1.255-.462-2.39-1.479-.885-.788-1.48-1.76-1.653-2.058-.173-.297-.018-.458.13-.606.134-.134.297-.347.446-.52.149-.173.198-.297.298-.496.099-.198.05-.372-.025-.52-.074-.148-.672-1.62-.92-2.22-.242-.581-.487-.5-.672-.51l-.57-.01c-.198 0-.52.074-.793.372s-1.04 1.016-1.04 2.48 1.065 2.87 1.213 3.07c.149.198 2.095 3.2 5.075 4.487 2.98 1.287 2.98.858 3.52.804.539-.049 1.76-.718 2.01-1.413.248-.694.248-1.29.173-1.413-.074-.122-.272-.198-.57-.347z" fill="white"/>
      </svg>
    </a>

    <!-- Call -->
    <a class="fab call" href="tel:+254725722964" aria-label="Call us" title="Call us">
      <svg width="20" height="20" viewBox="0 0 24 24" fill="none" aria-hidden="true" xmlns="http://www.w3.org/2000/svg">
        <path d="M6.62 10.79a15.054 15.054 0 0 0 6.59 6.59l2.2-2.2a1 1 0 0 1 1.02-.24c1.12.37 2.33.57 3.57.57a1 1 0 0 1 1 1V20a1 1 0 0 1-1 1C9.16 21 3 14.84 3 6a1 1 0 0 1 1-1h3.5a1 1 0 0 1 1 1c0 1.24.2 2.45.57 3.57.11.26.03.56-.24 1.02l-2.21 2.2z" fill="white"/>
      </svg>
    </a>
  </div>

  <script>
    // Small JS: current year and smooth scroll
    document.getElementById('year').textContent = new Date().getFullYear();

    // Smooth scrolling for internal links
    (function(){
      const links = document.querySelectorAll('a[href^="#"]');
      for(const a of links){
        a.addEventListener('click', function(e){
          const target = document.querySelector(this.getAttribute('href'));
          if(target){
            e.preventDefault();
            target.scrollIntoView({behavior:'smooth', block:'start'});
          }
        });
      }
    })();
  </script>
</body>
</html>
-solutions-
