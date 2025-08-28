<!DOCTYPE html><html lang="en">
<head><script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-8648198938608752"
     crossorigin="anonymous"></script>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>EMI Calculator – Fast & Simple</title>
  <meta name="description" content="Free EMI calculator for loans: home, car, personal. Calculate monthly EMI, total interest, and total payment instantly." />
  <link rel="icon" href="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 100 100'%3E%3Ccircle cx='50' cy='50' r='48' fill='%23007bff'/%3E%3Ctext x='50' y='60' font-size='46' text-anchor='middle' fill='white' font-family='Arial, Helvetica, sans-serif'%3E₹%3C/text%3E%3C/svg%3E" />
  <style>
    :root {
      --bg: #0b1020;      /* deep navy */
      --card: #111735;    /* card base */
      --muted: #7e88c3;   /* muted text */
      --text: #ecf1ff;    /* main text */
      --accent: #4f7cff;  /* brand blue */
      --accent-2: #25d366;/* green */
      --warn: #ffcc00;    /* yellow */
      --shadow: 0 10px 30px rgba(0,0,0,.35);
      --radius: 18px;
    }
    * { box-sizing: border-box }
    body {
      margin: 0; font-family: ui-sans-serif, system-ui, -apple-system, Segoe UI, Roboto, Helvetica, Arial, "Apple Color Emoji", "Segoe UI Emoji";
      background: radial-gradient(1200px 800px at 70% -10%, #1a245a 0%, var(--bg) 40%);
      color: var(--text);
    }
    header {
      position: sticky; top: 0; z-index: 5;
      backdrop-filter: blur(8px);
      background: linear-gradient(180deg, rgba(11,16,32,.9), rgba(11,16,32,.6));
      border-bottom: 1px solid rgba(255,255,255,.06);
    }
    .wrap { max-width: 1100px; margin: 0 auto; padding: 16px; }
    .brand { display:flex; align-items:center; gap:12px; font-weight:700; letter-spacing:.2px }
    .brand .logo { width:34px; height:34px; display:grid; place-items:center; border-radius:10px; background:linear-gradient(135deg, var(--accent), #8aa6ff); box-shadow: var(--shadow) }
    .brand span { font-size: 18px }
    .grid { display: grid; gap: 18px; grid-template-columns: 1fr; }
    @media(min-width: 880px){ .grid { grid-template-columns: 1.1fr .9fr } }
    .card {
      background: linear-gradient(180deg, rgba(255,255,255,.02), rgba(255,255,255,.01));
      border: 1px solid rgba(255,255,255,.08);
      border-radius: var(--radius);
      box-shadow: var(--shadow);
      padding: 18px;
    }
    h1 { font-size: clamp(26px, 3.2vw, 38px); margin: 8px 0 6px }
    p.lead { color: var(--muted); margin: 0 0 14px; line-height: 1.5 }label { font-size: 14px; color: var(--muted); display:block; margin-bottom:6px }
input, select {
  width: 100%;
  background: #0e1430;
  color: var(--text);
  border: 1px solid rgba(255,255,255,.1);
  border-radius: 12px;
  padding: 14px 14px;
  outline: none;
  transition: border .2s ease;
}
input:focus { border-color: var(--accent) }
.row { display:grid; grid-template-columns: 1fr; gap:12px }
@media(min-width:640px){ .row{ grid-template-columns: 1fr 1fr } }

.btn {
  display:inline-flex; align-items:center; justify-content:center; gap:10px;
  padding: 12px 16px; border-radius: 12px; border:1px solid rgba(255,255,255,.14);
  background: linear-gradient(180deg, rgba(255,255,255,.06), rgba(255,255,255,.02));
  color: var(--text); text-decoration:none; font-weight:600; cursor:pointer;
}
.btn:hover { border-color: var(--accent) }
.btn.primary { background: linear-gradient(180deg, var(--accent), #2d57ff); border-color: transparent }

.kpi { display:grid; grid-template-columns: 1fr; gap:12px }
@media(min-width:560px){ .kpi{ grid-template-columns: repeat(3,1fr) } }
.tile { background:#0e1430; border:1px solid rgba(255,255,255,.08); border-radius:14px; padding:16px }
.tile small { color: var(--muted); display:block; margin-bottom:6px }
.tile strong { font-size: 20px }

.ad-slot { border:2px dashed rgba(255,255,255,.18); border-radius:14px; padding:16px; text-align:center; color:var(--muted) }

footer { color: var(--muted); font-size: 14px; padding: 30px 0 60px; text-align:center }
footer a { color: var(--text) }

.table { width:100%; border-collapse: collapse; font-size: 14px }
.table th, .table td { border-bottom:1px solid rgba(255,255,255,.08); padding:10px; text-align:right }
.table th:first-child, .table td:first-child { text-align:left }
.muted { color: var(--muted) }
.pill { display:inline-block; padding:4px 10px; border-radius:999px; background:#0e1430; border:1px solid rgba(255,255,255,.1); font-size:12px; color:var(--muted) }

  </style>
</head>
<body>
  <header>
    <div class="wrap" style="display:flex; align-items:center; justify-content:space-between; gap:12px">
      <div class="brand">
        <div class="logo">₹</div>
        <span>EMI Calculator</span>
      </div>
      <nav style="display:flex; gap:10px; align-items:center">
        <a class="pill" href="#faq">FAQ</a>
        <a class="pill" href="#contact">Contact</a>
      </nav>
    </div>
  </header>  <main class="wrap" style="padding-top:24px">
    <div class="grid">
      <!-- Calculator card -->
      <section class="card">
        <h1>Free EMI Calculator</h1>
        <p class="lead">Calculate monthly EMI, total interest, and total payment for any loan (home, car, personal). Fast, private, and works offline once loaded.</p><div class="row" style="margin-top:14px">
      <div>
        <label>Loan Amount (₹)</label>
        <input id="amount" type="number" min="0" step="1000" placeholder="e.g., 500000" />
      </div>
      <div>
        <label>Annual Interest Rate (%)</label>
        <input id="rate" type="number" min="0" step="0.01" placeholder="e.g., 10.5" />
      </div>
    </div>
    <div class="row" style="margin-top:12px">
      <div>
        <label>Tenure</label>
        <input id="tenure" type="number" min="1" step="1" placeholder="e.g., 60" />
      </div>
      <div>
        <label>Tenure Unit</label>
        <select id="tenureUnit">
          <option value="months">Months</option>
          <option value="years">Years</option>
        </select>
      </div>
    </div>

    <div style="display:flex; gap:10px; margin-top:16px; flex-wrap:wrap">
      <button class="btn primary" id="calcBtn">Calculate EMI</button>
      <button class="btn" id="shareBtn">Share Result</button>
      <button class="btn" id="copyBtn">Copy</button>
    </div>

    <div class="kpi" style="margin-top:18px">
      <div class="tile">
        <small>Monthly EMI</small>
        <strong id="emi">—</strong>
      </div>
      <div class="tile">
        <small>Total Interest</small>
        <strong id="interest">—</strong>
      </div>
      <div class="tile">
        <small>Total Payment</small>
        <strong id="total">—</strong>
      </div>
    </div>

    <!-- AdSense placeholder: replace with your ad code -->
    <div class="ad-slot" style="margin-top:18px">
      Ad space — paste Google AdSense code here after approval.
    </div>

  </section>

  <!-- Amortization + SEO content card -->
  <aside class="card">
    <h2 style="margin-top:4px">Amortization (first 12 months)</h2>
    <p class="muted" style="margin-top:0">See how each payment splits into principal and interest.</p>
    <div style="overflow:auto; max-height: 340px; border-radius:12px">
      <table class="table" id="table">
        <thead>
          <tr>
            <th>Month</th>
            <th>EMI (₹)</th>
            <th>Interest (₹)</th>
            <th>Principal (₹)</th>
            <th>Balance (₹)</th>
          </tr>
        </thead>
        <tbody></tbody>
      </table>
    </div>

    <!-- Affiliate tip area -->
    <div class="ad-slot" style="margin-top:16px">
      Tip: Add affiliate links for loans/credit cards here.
    </div>
  </aside>
</div>

<!-- FAQ for SEO -->
<section id="faq" class="card" style="margin-top:18px">
  <h2>EMI Calculator – FAQ</h2>
  <details>
    <summary>What is EMI?</summary>
    <p class="muted">EMI (Equated Monthly Installment) is the fixed amount you pay every month towards your loan.</p>
  </details>
  <details>
    <summary>How is EMI calculated?</summary>
    <p class="muted">EMI = P × r × (1 + r)<sup>n</sup> ÷ ((1 + r)<sup>n</sup> − 1) where P = principal, r = monthly interest rate, n = number of months.</p>
  </details>
  <details>
    <summary>Is my data stored?</summary>
    <p class="muted">No. All calculations run in your browser on your device.</p>
  </details>
</section>

<section id="contact" class="card" style="margin-top:18px">
  <h2>Contact</h2>
  <p class="muted">For feedback or partnerships: <a href="mailto:you@example.com">you@example.com</a></p>
</section>

<footer>
  <div>© <span id="year"></span> EMI Calculator. All rights reserved.</div>
  <div style="margin-top:6px"><a href="#">Privacy</a> · <a href="#">Terms</a></div>
</footer>

  </main>  <!-- JSON-LD FAQ Schema for SEO -->  <script type="application/ld+json">
  {
    "@context": "https://schema.org",
    "@type": "FAQPage",
    "mainEntity": [
      {
        "@type": "Question",
        "name": "What is EMI?",
        "acceptedAnswer": {"@type": "Answer", "text": "EMI (Equated Monthly Installment) is the fixed amount you pay every month towards your loan."}
      },
      {
        "@type": "Question",
        "name": "How is EMI calculated?",
        "acceptedAnswer": {"@type": "Answer", "text": "EMI = P × r × (1 + r)^n ÷ ((1 + r)^n − 1) where P = principal, r = monthly interest rate, n = number of months."}
      },
      {
        "@type": "Question",
        "name": "Is my data stored?",
        "acceptedAnswer": {"@type": "Answer", "text": "No. All calculations run locally in the user's browser and nothing is uploaded."}
      }
    ]
  }
  </script>  <script>
    const fmt = (n) => isFinite(n) ? n.toLocaleString('en-IN', { maximumFractionDigits: 2 }) : '—';

    function calculate() {
      const P = parseFloat(document.getElementById('amount').value);
      const annualRate = parseFloat(document.getElementById('rate').value);
      let n = parseInt(document.getElementById('tenure').value, 10);
      const unit = document.getElementById('tenureUnit').value;

      if (unit === 'years') n = n * 12;
      const r = annualRate / 12 / 100;

      if (!P || !annualRate || !n) {
        document.getElementById('emi').textContent = '—';
        document.getElementById('interest').textContent = '—';
        document.getElementById('total').textContent = '—';
        document.querySelector('#table tbody').innerHTML = '';
        return;
      }

      const pow = Math.pow(1 + r, n);
      const EMI = (P * r * pow) / (pow - 1);
      const total = EMI * n;
      const interest = total - P;

      document.getElementById('emi').textContent = `₹ ${fmt(EMI)}`;
      document.getElementById('interest').textContent = `₹ ${fmt(interest)}`;
      document.getElementById('total').textContent = `₹ ${fmt(total)}`;

      // Build amortization for first 12 months
      const tbody = document.querySelector('#table tbody');
      tbody.innerHTML = '';
      let balance = P;
      for (let i = 1; i <= Math.min(12, n); i++) {
        const interestComp = balance * r;
        const principalComp = EMI - interestComp;
        balance = Math.max(0, balance - principalComp);
        const tr = document.createElement('tr');
        tr.innerHTML = `
          <td>${i}</td>
          <td>₹ ${fmt(EMI)}</td>
          <td>₹ ${fmt(interestComp)}</td>
          <td>₹ ${fmt(principalComp)}</td>
          <td>₹ ${fmt(balance)}</td>
        `;
        tbody.appendChild(tr);
      }

      // Update URL parameters for shareability
      const params = new URLSearchParams({ amount: P, rate: annualRate, tenure: n });
      history.replaceState(null, '', `${location.pathname}?${params.toString()}`);
    }

    function prefillFromURL() {
      const q = new URLSearchParams(location.search);
      const A = q.get('amount'), R = q.get('rate'), N = q.get('tenure');
      if (A) document.getElementById('amount').value = A;
      if (R) document.getElementById('rate').value = R;
      if (N) {
        document.getElementById('tenure').value = N;
        document.getElementById('tenureUnit').value = 'months';
      }
      if (A && R && N) calculate();
    }

    document.getElementById('calcBtn').addEventListener('click', calculate);
    document.getElementById('copyBtn').addEventListener('click', async () => {
      const e = document.getElementById('emi').textContent;
      const i = document.getElementById('interest').textContent;
      const t = document.getElementById('total').textContent;
      const text = `EMI Result\n${e}\nTotal Interest: ${i}\nTotal Payment: ${t}`;
      try { await navigator.clipboard.writeText(text); alert('Copied to clipboard!'); } catch { alert('Copy failed.'); }
    });
    document.getElementById('shareBtn').addEventListener('click', async () => {
      const url = location.href;
      const title = 'EMI Calculator Result';
      const text = 'Check out this EMI calculation.';
      if (navigator.share) {
        try { await navigator.share({ title, text, url }); } catch {}
      } else {
        try { await navigator.clipboard.writeText(url); alert('Link copied!'); } catch { alert(url); }
      }
    });

    document.getElementById('year').textContent = new Date().getFullYear();
    prefillFromURL();
  </script></body>
</html>
