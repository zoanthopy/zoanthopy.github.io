
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Zoanthopy</title>
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">
<style>
*{box-sizing:border-box;margin:0;padding:0;font-family:'Inter',sans-serif}
body{background:#0b0d12;color:#fff}
header{display:flex;justify-content:space-between;align-items:center;padding:24px 8%;position:sticky;top:0;background:#0b0d12cc;backdrop-filter:blur(10px)}
nav a{margin-left:24px;color:#aaa;text-decoration:none;font-size:14px}
nav a:hover{color:#fff}
.logo{font-weight:700;font-size:20px}
.hero{padding:120px 8%;text-align:center}
.hero h1{font-size:56px;margin-bottom:20px}
.hero p{font-size:20px;color:#aaa;max-width:700px;margin:auto}
.hero button{margin-top:32px;padding:14px 28px;border:none;border-radius:8px;background:#4f7cff;color:white;font-size:16px;cursor:pointer}
.section{padding:100px 8%}
.section h2{font-size:36px;margin-bottom:20px}
.section p{color:#aaa;max-width:800px}
.cards{display:grid;grid-template-columns:repeat(auto-fit,minmax(260px,1fr));gap:30px;margin-top:40px}
.card{background:#12151d;padding:28px;border-radius:14px;transition:0.3s}
.card:hover{transform:translateY(-6px);background:#161a23}
.card h3{margin-bottom:10px}
.footer{padding:40px 8%;border-top:1px solid #1d2330;color:#777;font-size:14px;display:flex;justify-content:space-between;flex-wrap:wrap}
.button-outline{border:1px solid #4f7cff;background:transparent;color:#4f7cff;margin-top:20px;padding:12px 24px;border-radius:8px;cursor:pointer}
</style>
</head>
<body>

<header>
<div class="logo">Zoanthopy</div>
<nav>
<a href="#about">About</a>
<a href="#projects">Projects</a>
<a href="#future">Future Apps</a>
</nav>
</header>

<section class="hero">
<h1>Building Tools for the Next Generation of Collectors</h1>
<p>Zoanthopy is focused on creating powerful, clean, and data-driven applications for collectors, investors, and enthusiasts. Our first flagship product, TCG Radar, helps users track trading card markets in real time.</p>
<button>Explore TCG Radar</button>
</section>

<section id="about" class="section">
<h2>About Zoanthopy</h2>
<p>Zoanthopy is an independent software studio focused on building modern tools that simplify complex markets. Our mission is to create beautiful, fast, and useful applications for collectors and digital communities. We focus heavily on data transparency, market tracking, and clean design that makes information easy to understand.</p>
</section>

<section id="projects" class="section">
<h2>Current Project</h2>
<div class="cards">
<div class="card">
<h3>TCG Radar</h3>
<p>TCG Radar is a next-generation trading card price tracker built for collectors and investors. Track Pokemon cards, booster boxes, and sealed products across major marketplaces with historical price charts, market trends, and deal alerts.</p>
<button class="button-outline">Learn More</button>
</div>
</div>
</section>

<section id="future" class="section">
<h2>Future Projects</h2>
<div class="cards">
<div class="card">
<h3>Market Analytics Apps</h3>
<p>Advanced analytics platforms for collectibles, trading cards, and resale markets.</p>
</div>
<div class="card">
<h3>Collector Portfolio Tools</h3>
<p>Apps that allow collectors to track their entire inventory value and performance over time.</p>
</div>
<div class="card">
<h3>AI Market Insights</h3>
<p>Future applications will use AI to identify market trends, undervalued items, and collector opportunities.</p>
</div>
</div>
</section>

<footer class="footer">
<div>© 2026 Zoanthopy</div>
<div>Building the future of collector technology.</div>
</footer>

</body>
</html>
