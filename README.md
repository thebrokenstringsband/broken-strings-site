[index(2).html](https://github.com/user-attachments/files/23509668/index.2.html)

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Broken Strings Band</title>
  <style>
    :root {
      --bg: #0f0f12;
      --card: #18181c;
      --text: #f3f4f6;
      --muted: #a1a1aa;
      --accent: #eab308;
      --accent-2: #f97316;
      --btn: #27272a;
      --btn-text: #f8fafc;
    }
    * { box-sizing: border-box; }
    html, body { margin: 0; padding: 0; background: var(--bg); color: var(--text); font-family: system-ui, -apple-system, Segoe UI, Roboto, Helvetica, Arial, "Apple Color Emoji", "Segoe UI Emoji"; }
    a { color: var(--accent-2); text-decoration: none; }
    a:hover { text-decoration: underline; }
    .wrap { max-width: 980px; margin: 0 auto; padding: 24px; }
    header {
      position: relative;
      padding: 64px 0 32px;
      text-align: center;
      background: radial-gradient(1200px 400px at 50% -10%, rgba(250,204,21,.25), transparent 60%);
    }
    .title {
      font-size: clamp(36px, 6vw, 64px);
      font-weight: 800;
      letter-spacing: .5px;
      line-height: 1.0;
      margin: 0 0 8px 0;
      display: inline-block;
      padding-bottom: 6px;
      border-image: linear-gradient(90deg, var(--accent), var(--accent-2)) 1;
      border-width: 0 0 4px 0;
      border-style: solid;
    }
    .tagline { color: var(--muted); font-size: clamp(16px, 2.7vw, 20px); margin: 8px 0 0 0; }
    .cta-row { margin-top: 22px; display: flex; gap: 12px; justify-content: center; flex-wrap: wrap; }
    .btn {
      background: var(--btn); color: var(--btn-text); border: 1px solid #3f3f46;
      padding: 12px 16px; border-radius: 12px; font-weight: 600;
      display: inline-flex; gap: 10px; align-items: center;
    }
    .btn:hover { transform: translateY(-1px); }
    .grid { display: grid; gap: 16px; grid-template-columns: repeat(12, 1fr); }
    .card {
      background: linear-gradient(180deg, rgba(255,255,255,.04), rgba(255,255,255,0));
      border: 1px solid #27272a; border-radius: 14px; padding: 18px;
    }
    .section-title { margin: 0 0 10px 0; font-size: 20px; letter-spacing: .3px; }
    .pill { display:inline-block; padding:6px 10px; border-radius: 999px; border:1px solid #303038; color:var(--muted); font-size: 12px; }
    .two { grid-column: span 12; }
    @media (min-width: 720px) {
      .two { grid-column: span 6; }
    }
    ul.clean { list-style: none; margin: 0; padding: 0; }
    ul.clean li { padding: 8px 0; border-bottom: 1px dashed #2a2a31; }
    ul.clean li:last-child { border: none; }
    .show { display:flex; justify-content: space-between; gap:10px; align-items:center; }
    .muted { color: var(--muted); }
    .qr {
      width: 100%;
      aspect-ratio: 1/1;
      background: repeating-linear-gradient(45deg, #111 0 16px, #0d0d10 16px 32px);
      border: 1px dashed #3f3f46;
      border-radius: 12px;
      display:flex; align-items:center; justify-content:center;
      color:#8b8b94; text-align:center; padding:16px;
    }
    footer { text-align:center; color: var(--muted); padding: 32px 0 80px; }
    .small { font-size: 12px; }
    .row { display:flex; gap:8px; flex-wrap: wrap; }
    .kbd { font-family: ui-monospace, SFMono-Regular, Menlo, Consolas, "Liberation Mono", monospace; background:#1f1f24; border:1px solid #2b2b31; padding:2px 6px; border-radius:6px; font-size:12px; color:#cbd5e1; }
    .tip-grid { display:grid; gap:10px; grid-template-columns: repeat(3, 1fr); }
    .tip { border:1px solid #303038; border-radius:12px; padding:12px; text-align:center; }
    .tip a { font-weight:700; }
  </style>
</head>
<body>
  <header>
    <div class="wrap">
      <h1 class="title">Broken Strings Band</h1>
      <p class="tagline">70’s • 80’s • 90’s • Current &mdash; Rock, Country &amp; Pop. Requests encouraged.</p>
      <div class="cta-row">
        <a class="btn" href="#tip">Tip / Support</a>
        <a class="btn" href="#request">Request a Song</a>
        <a class="btn" href="#shows">Upcoming Shows</a>
      </div>
    </div>
  </header>

  <main class="wrap">
    <section class="grid">
      <div class="card two">
        <h2 class="section-title">About</h2>
        <p>We’re a crowd-friendly cover band built for good vibes: guitar-driven sing-alongs, country classics, and pop bangers. We love taking requests and keeping the dance floor full.</p>
        <div class="row"><span class="pill">St. Louis</span><span class="pill">Fenton</span><span class="pill">Chesterfield</span></div>
      </div>

      <div id="tip" class="card two">
        <h2 class="section-title">Tip / Support</h2>
        <div class="tip-grid">
          <div class="tip">
            <div class="muted small">Venmo</div>
            <a href="https://venmo.com/u/Rob-Racer-1" target="_blank">@Rob-Racer-1</a>
          </div>
          <div class="tip">
            <div class="muted small">PayPal</div>
            <a href="https://paypal.me/RobRacer223" target="_blank">paypal.me/RobRacer223</a>
          </div>
          <div class="tip">
            <div class="muted small">Cash App</div>
            <span class="muted">Add your cashtag</span>
          </div>
        </div>
        <p class="small muted" style="margin-top:10px;">Prefer cash? We love that too &mdash; just wave us down 🤘</p>
      </div>

      <div class="card two">
        <h2 class="section-title">Follow</h2>
        <ul class="clean">
          <li><a href="https://instagram.com/the_broken_strings_band" target="_blank">Instagram</a> <span class="muted small">@the_broken_strings_band</span></li>
        </ul>
      </div>

      <div id="shows" class="card two">
        <h2 class="section-title">Upcoming Shows</h2>
        <ul class="clean">
          <li class="show">
            <span><strong>Next Up</strong> &middot; <a href="https://facebook.com/borgettisbarandgrill" target="_blank">Borgettis Bar and Grill</a></span>
            <span class="muted">Fenton, MO</span>
          </li>
        </ul>
        <p class="small muted">Want to book us? Email <a href="mailto:thebrokenstringsband1@gmail.com?subject=Booking%20Inquiry%20(Broken%20Strings%20Band)">thebrokenstringsband1@gmail.com</a></p>
      </div>

      <div id="request" class="card two">
        <h2 class="section-title">Request a Song</h2>
        <p class="muted small">This sends us an email with your request during the show.</p>
        <form action="mailto:thebrokenstringsband1@gmail.com" method="post" enctype="text/plain">
          <label for="rname">Your Name</label><br/>
          <input id="rname" name="name" placeholder="Jane Doe" style="width:100%;padding:10px;border-radius:10px;border:1px solid #303038;background:#121216;color:#e5e7eb;margin:6px 0 10px;"><br/>
          <label for="rsong">Song / Artist</label><br/>
          <input id="rsong" name="song" placeholder="Tennessee Whiskey – Chris Stapleton" style="width:100%;padding:10px;border-radius:10px;border:1px solid #303038;background:#121216;color:#e5e7eb;margin:6px 0 10px;"><br/>
          <button class="btn" type="submit">Send Request</button>
        </form>
        <p class="small muted" style="margin-top:8px;">Tip: swap the <span class="kbd">mailto:</span> action with a free form service (e.g., Formspree/Tally) for a slicker experience.</p>
      </div>

      <div class="card two">
        <h2 class="section-title">Press / Tech</h2>
        <ul class="clean">
          <li>Style: Guitar-forward covers; tight harmonies; dance-floor friendly.</li>
          <li>Typical set length: 45–60 min x 3.</li>
          <li>PA provided upon request.</li>
        </ul>
      </div>

      <div class="card two">
        <h2 class="section-title">QR Code</h2>
        <div class="qr">
          <div>
            <div style="font-weight:700; margin-bottom:6px;">Your QR goes here</div>
            <div class="small">Once you host this page, generate a QR to that URL and paste the image here.</div>
          </div>
        </div>
        <p class="small muted" style="margin-top:8px;">Tip: When your site URL is live, create a QR (PNG/SVG) and drop it into this section.</p>
      </div>

    </section>
  </main>

  <footer>
    <div class="wrap small">© <span id="year"></span> Broken Strings Band • All rights reserved</div>
  </footer>

  <script>
    document.getElementById('year').textContent = new Date().getFullYear();
  </script>
</body>
</html>
