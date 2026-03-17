<!DOCTYPE html>
<html lang="pt-PT">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>PPA Portugal | Motores Premium</title>
<link href="https://fonts.googleapis.com/css2?family=Rajdhani:wght@700;800&family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
<style>
*{margin:0;padding:0;box-sizing:border-box}body{font-family:'Inter',sans-serif;color:#1A1A1A;line-height:1.6}h1,h2,h3{font-family:'Rajdhani',sans-serif;font-weight:700}.lang-toggle{position:fixed;top:20px;right:20px;z-index:1000;background:#fff;border-radius:30px;box-shadow:0 4px 20px rgba(0,0,0,.15);display:flex}.lang-btn{padding:12px 22px;border:none;background:transparent;cursor:pointer;font-weight:700;font-size:.9rem;border-radius:30px;transition:.3s;font-family:'Rajdhani',sans-serif}.lang-btn.active{background:#FF6B00;color:#fff}[lang]:not(.active-lang){display:none!important}.whatsapp-float{position:fixed;bottom:30px;right:30px;background:#25D366;color:#fff;width:70px;height:70px;border-radius:50%;display:flex;align-items:center;justify-content:center;font-size:2.2rem;box-shadow:0 6px 30px rgba(37,211,102,.45);z-index:999;text-decoration:none;animation:pulse 2s infinite}@keyframes pulse{0%,100%{transform:scale(1)}50%{transform:scale(1.05)}}.whatsapp-float:hover{transform:scale(1.15)!important}.hero{background:linear-gradient(135deg,#0D0D0D 0%,#2A2A2A 100%);color:#fff;padding:110px 20px 80px;position:relative;overflow:hidden}.hero::after{content:'';position:absolute;top:-50%;right:-20%;width:80%;height:200%;background:radial-gradient(ellipse at center,rgba(255,107,0,.12) 0%,transparent 60%);pointer-events:none}.hero-content{max-width:1200px;margin:0 auto;position:relative;z-index:1}.hero-badge{display:inline-block;background:rgba(255,107,0,.15);border:2px solid #FF6B00;color:#FF6B00;padding:10px 24px;border-radius:30px;font-weight:800;font-size:.85rem;margin-bottom:25px;letter-spacing:.08em;text-transform:uppercase;font-family:'Rajdhani',sans-serif}.hero h1{font-size:clamp(2.5rem,6vw,4.5rem);line-height:1.1;margin-bottom:25px;font-weight:800}.hero h1 span{color:#FF6B00;display:block}.hero p{font-size:1.25rem;margin-bottom:40px;opacity:.95;max-width:750px;line-height:1.7}.hero p strong{color:#FF6B00}.hero-cta{display:flex;gap:18px;flex-wrap:wrap}.btn{padding:18px 36px;font-size:1.1rem;font-weight:700;border-radius:10px;text-decoration:none;display:inline-flex;align-items:center;gap:12px;transition:.3s;font-family:'Rajdhani',sans-serif;letter-spacing:.02em}.btn-whatsapp{background:#25D366;color:#fff;box-shadow:0 6px 25px rgba(37,211,102,.35)}.btn-whatsapp:hover{background:#20BA5A;transform:translateY(-3px)}.btn-outline{background:transparent;color:#fff;border:2px solid #fff}.btn-outline:hover{background:#fff;color:#1A1A1A}.btn-download{background:#FF6B00;color:#fff}.btn-download:hover{background:#E65F00;transform:translateY(-3px)}.usps{background:#FF6B00;padding:45px 20px;color:#fff}.usps-grid{max-width:1200px;margin:0 auto;display:grid;grid-template-columns:repeat(auto-fit,minmax(240px,1fr));gap:35px;text-align:center}.usp h3{font-size:2rem;margin-bottom:8px;font-weight:800}.usp p{font-size:1rem;opacity:.97;font-weight:500}.products{padding:100px 20px;background:#FAFAFA}.section-header{max-width:1200px;margin:0 auto 60px;text-align:center}.section-header h2{font-size:clamp(2.2rem,5vw,3.2rem);margin-bottom:18px;color:#1A1A1A}.section-header p{font-size:1.15rem;color:#666;max-width:700px;margin:0 auto}.product-grid{max-width:1200px;margin:0 auto;display:grid;grid-template-columns:repeat(auto-fit,minmax(340px,1fr));gap:35px}.product-card{background:#fff;border-radius:16px;overflow:hidden;box-shadow:0 4px 25px rgba(0,0,0,.08);transition:.4s;border:1px solid #E8E8E8}.product-card:hover{transform:translateY(-10px);box-shadow:0 15px 45px rgba(0,0,0,.15)}.product-img-wrapper{background:linear-gradient(135deg,#f8f8f8 0%,#e8e8e8 100%);padding:40px;display:flex;align-items:center;justify-content:center;min-height:280px;position:relative;overflow:hidden}.product-img{max-width:100%;max-height:250px;object-fit:contain;filter:drop-shadow(0 8px 20px rgba(0,0,0,.15))}.product-content{padding:30px}.product-badge{display:inline-block;background:#FF6B00;color:#fff;padding:6px 16px;border-radius:20px;font-size:.75rem;font-weight:700;margin-bottom:15px;text-transform:uppercase;letter-spacing:.05em}.product-content h3{font-size:1.6rem;margin-bottom:15px;color:#1A1A1A}.product-content p{color:#555;margin-bottom:20px;line-height:1.75}.product-features{list-style:none;margin:20px 0}.product-features li{padding:8px 0;color:#444;display:flex;align-items:center;gap:10px;font-size:.95rem}.product-features li::before{content:'✓';color:#FF6B00;font-weight:700;font-size:1.2rem}.benefits{padding:100px 20px;background:#fff}.benefits-grid{max-width:1200px;margin:0 auto;display:grid;grid-template-columns:repeat(auto-fit,minmax(300px,1fr));gap:40px}.benefit{text-align:center;padding:40px 30px;border-radius:16px;background:#FAFAFA;transition:.4s;border:2px solid transparent}.benefit:hover{background:#1A1A1A;color:#fff;transform:translateY(-8px);border-color:#FF6B00}.benefit-icon{font-size:3.5rem;margin-bottom:20px}.benefit h3{font-size:1.5rem;margin-bottom:15px}.benefit p{color:#666;line-height:1.7}.benefit:hover p{color:rgba(255,255,255,.9)}.coverage{background:linear-gradient(135deg,#1A1A1A 0%,#0D0D0D 100%);padding:100px 20px;color:#fff;text-align:center}.coverage h2{font-size:clamp(2rem,5vw,3rem);margin-bottom:50px}.cities-grid{max-width:1000px;margin:0 auto;display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:30px}.city-card{background:rgba(255,255,255,.06);padding:30px;border-radius:12px;border:2px solid rgba(255,107,0,.3);transition:.3s}.city-card:hover{background:rgba(255,107,0,.15);border-color:#FF6B00;transform:translateY(-5px)}.city-card h3{font-size:1.6rem;color:#FF6B00;margin-bottom:8px}.city-card p{opacity:.9;font-weight:500}.cta-section{background:#FF6B00;padding:90px 20px;text-align:center;color:#fff;position:relative;overflow:hidden}.cta-section::before{content:'';position:absolute;width:600px;height:600px;background:radial-gradient(circle,rgba(255,255,255,.12) 0%,transparent 70%);top:-300px;right:-300px;animation:float 8s ease-in-out infinite}@keyframes float{0%,100%{transform:translate(0,0)}50%{transform:translate(-30px,-30px)}}.cta-content{max-width:850px;margin:0 auto;position:relative;z-index:1}.cta-content h2{font-size:clamp(2rem,5vw,2.8rem);margin-bottom:25px;font-weight:800}.cta-content p{font-size:1.25rem;margin-bottom:30px;opacity:.97;line-height:1.7}.cta-phone{font-size:2.2rem;font-weight:800;margin:25px 0 35px;font-family:'Rajdhani',sans-serif;letter-spacing:.02em}footer{background:#0D0D0D;color:#fff;padding:50px 20px;text-align:center}footer p{opacity:.75;margin-bottom:12px;font-size:.95rem}@media (max-width:768px){.hero{padding:90px 20px 60px}.hero-cta{flex-direction:column}.btn{width:100%;justify-content:center}.product-grid{grid-template-columns:1fr}.whatsapp-float{width:60px;height:60px;bottom:20px;right:20px;font-size:1.8rem}}
</style>
</head>
<body>

<div class="lang-toggle">
<button class="lang-btn active" onclick="setLanguage('pt')">🇵🇹 PT</button>
<button class="lang-btn" onclick="setLanguage('es')">🇪🇸 ES</button>
</div>

<a href="https://wa.me/351SEUNUMERO" class="whatsapp-float" target="_blank" title="WhatsApp">💬</a>

<!-- PORTUGUÊS -->
<section class="hero active-lang" lang="pt">
<div class="hero-content">
<div class="hero-badge">🏭 FABRICANTE DIRECTO | MADE IN BRAZIL</div>
<h1>Motores PPA<br><span>Preço de Fábrica</span></h1>
<p><strong>Abertura Ultra-Rápida • Produção em Grande Escala • Stock Permanente em Portugal</strong><br>
Distribua os melhores automatismos do mercado com margens competitivas. Suporte técnico completo em Portugal.</p>
<div class="hero-cta">
<a href="https://wa.me/351SEUNUMERO?text=Olá!%20Gostaria%20de%20informações%20sobre%20os%20motores%20PPA" class="btn btn-whatsapp">💬 Falar no WhatsApp</a>
<a href="#produtos" class="btn btn-outline">Ver Motores</a>
<a href="#" class="btn btn-download" onclick="alert('Adicione aqui o link do catálogo PDF');return false">📥 Descarregar Catálogo</a>
</div>
</div>
</section>

<!-- ESPAÑOL -->
<section class="hero" lang="es">
<div class="hero-content">
<div class="hero-badge">🏭 FABRICANTE DIRECTO | MADE IN BRAZIL</div>
<h1>Motores PPA<br><span>Precio de Fábrica</span></h1>
<p><strong>Apertura Ultra-Rápida • Producción a Gran Escala • Stock Permanente en Portugal</strong><br>
Distribuya los mejores automatismos del mercado con márgenes competitivos. Soporte técnico completo en Portugal.</p>
<div class="hero-cta">
<a href="https://wa.me/351SEUNUMERO?text=¡Hola!%20Me%20gustaría%20información%20sobre%20los%20motores%20PPA" class="btn btn-whatsapp">💬 Hablar por WhatsApp</a>
<a href="#productos" class="btn btn-outline">Ver Motores</a>
<a href="#" class="btn btn-download" onclick="alert('Añada aquí el enlace del catálogo PDF');return false">📥 Descargar Catálogo</a>
</div>
</div>
</section>

<!-- USPs PT -->
<section class="usps active-lang" lang="pt">
<div class="usps-grid">
<div class="usp"><h3>⚡ 3x Mais Rápido</h3><p>Motores de abertura ultra-rápida</p></div>
<div class="usp"><h3>💰 Até -40%</h3><p>Preço directo de fabricante</p></div>
<div class="usp"><h3>📦 Stock PT</h3><p>Entrega rápida em Portugal</p></div>
<div class="usp"><h3>🛠️ Suporte Total</h3><p>Assistência técnica garantida</p></div>
</div>
</section>

<!-- USPs ES -->
<section class="usps" lang="es">
<div class="usps-grid">
<div class="usp"><h3>⚡ 3x Más Rápido</h3><p>Motores de apertura ultra-rápida</p></div>
<div class="usp"><h3>💰 Hasta -40%</h3><p>Precio directo de fabricante</p></div>
<div class="usp"><h3>📦 Stock PT</h3><p>Entrega rápida en Portugal</p></div>
<div class="usp"><h3>🛠️ Soporte Total</h3><p>Asistencia técnica garantizada</p></div>
</div>
</section>

<!-- PRODUTOS PT -->
<section class="products active-lang" lang="pt" id="produtos">
<div class="section-header">
<h2>Linha Completa de Motores</h2>
<p>Tecnologia Jetflex Brushless • Produção em Grande Escala • Melhor Custo-Benefício</p>
</div>
<div class="product-grid">

<div class="product-card">
<div class="product-img-wrapper">
<svg class="product-img" viewBox="0 0 300 200" style="max-height:200px">
<rect fill="#f0f0f0" width="300" height="200"/>
<text x="150" y="100" text-anchor="middle" dominant-baseline="middle" font-family="Arial" font-size="16" fill="#999">Motor DZ Cube</text>
</svg>
</div>
<div class="product-content">
<span class="product-badge">MAIS VENDIDO</span>
<h3>DZ Cube Jetflex</h3>
<p>Motor deslizante brushless de alto desempenho para portões até 850kg. Abertura ultra-rápida com tecnologia de ponta.</p>
<ul class="product-features">
<li>Capacidade até 850kg</li>
<li>Motor brushless silencioso</li>
<li>Abertura em 8 segundos</li>
<li>Sistema anti-esmagamento</li>
</ul>
</div>
</div>

<div class="product-card">
<div class="product-img-wrapper">
<svg class="product-img" viewBox="0 0 300 200" style="max-height:200px">
<rect fill="#f0f0f0" width="300" height="200"/>
<text x="150" y="100" text-anchor="middle" dominant-baseline="middle" font-family="Arial" font-size="16" fill="#999">Motor DZ Stark</text>
</svg>
</div>
<div class="product-content">
<span class="product-badge">ALTA POTÊNCIA</span>
<h3>DZ Stark Jetflex</h3>
<p>Motor industrial para portões pesados até 1500kg. Ideal para condomínios e indústrias com alto fluxo.</p>
<ul class="product-features">
<li>Capacidade até 1500kg</li>
<li>Motor industrial Jetflex</li>
<li>Uso intensivo diário</li>
<li>Garantia estendida</li>
</ul>
</div>
</div>

<div class="product-card">
<div class="product-img-wrapper">
<svg class="product-img" viewBox="0 0 300 200" style="max-height:200px">
<rect fill="#f0f0f0" width="300" height="200"/>
<text x="150" y="100" text-anchor="middle" dominant-baseline="middle" font-family="Arial" font-size="16" fill="#999">Motor DZ IND</text>
</svg>
</div>
<div class="product-content">
<span class="product-badge">INDUSTRIAL</span>
<h3>DZ IND</h3>
<p>Motor deslizante industrial com tecnologia robusta para uso comercial intensivo.</p>
<ul class="product-features">
<li>Uso industrial intensivo</li>
<li>Alta durabilidade</li>
<li>Cremalheira incluída</li>
<li>Sensor de obstáculos</li>
</ul>
</div>
</div>

<div class="product-card">
<div class="product-img-wrapper">
<svg class="product-img" viewBox="0 0 300 200" style="max-height:200px">
<rect fill="#f0f0f0" width="300" height="200"/>
<text x="150" y="100" text-anchor="middle" dominant-baseline="middle" font-family="Arial" font-size="16" fill="#999">Motor Pistão</text>
</svg>
</div>
<div class="product-content">
<span class="product-badge">BATENTE</span>
<h3>Motor Pistão</h3>
<p>Automatismo de batente electromecânico para portões de 2 folhas. Instalação simples e rápida.</p>
<ul class="product-features">
<li>Portões de batente</li>
<li>Abertura até 180°</li>
<li>Central electrónica integrada</li>
<li>Ideal para condomínios</li>
</ul>
</div>
</div>

<div class="product-card">
<div class="product-img-wrapper">
<svg class="product-img" viewBox="0 0 300 200" style="max-height:200px">
<rect fill="#f0f0f0" width="300" height="200"/>
<text x="150" y="100" text-anchor="middle" dominant-baseline="middle" font-family="Arial" font-size="16" fill="#999">Pivô SK</text>
</svg>
</div>
<div class="product-content">
<span class="product-badge">PIVOTANTE</span>
<h3>Pivô SK Jetflex</h3>
<p>Motor para portões pivotantes até 500kg. Tecnologia brushless para abertura suave e silenciosa.</p>
<ul class="product-features">
<li>Portões pivotantes</li>
<li>Até 500kg de capacidade</li>
<li>Motor Jetflex silencioso</li>
<li>Baixo consumo</li>
</ul>
</div>
</div>

<div class="product-card">
<div class="product-img-wrapper">
<svg class="product-img" viewBox="0 0 300 200" style="max-height:200px">
<rect fill="#f0f0f0" width="300" height="200"/>
<text x="150" y="100" text-anchor="middle" dominant-baseline="middle" font-family="Arial" font-size="16" fill="#999">Barreira K10</text>
</svg>
</div>
<div class="product-content">
<span class="product-badge">ULTRA-RÁPIDA</span>
<h3>Barreira K10</h3>
<p>Barreira automática de alta velocidade com iluminação LED. Abertura em 3 segundos para controlo de acessos.</p>
<ul class="product-features">
<li>Abertura em 3 segundos</li>
<li>Iluminação LED integrada</li>
<li>Sistema anti-esmagamento</li>
<li>Motor brushless</li>
</ul>
</div>
</div>

</div>
</section>

<!-- PRODUCTOS ES (versão espanhola similar) -->
<section class="products" lang="es" id="productos">
<div class="section-header">
<h2>Línea Completa de Motores</h2>
<p>Tecnología Jetflex Brushless • Producción a Gran Escala • Mejor Coste-Beneficio</p>
</div>
<div class="product-grid">
<!-- Produtos em espanhol com mesmo layout -->
<div class="product-card">
<div class="product-img-wrapper">
<svg class="product-img" viewBox="0 0 300 200" style="max-height:200px">
<rect fill="#f0f0f0" width="300" height="200"/>
<text x="150" y="100" text-anchor="middle" dominant-baseline="middle" font-family="Arial" font-size="16" fill="#999">Motor DZ Cube</text>
</svg>
</div>
<div class="product-content">
<span class="product-badge">MÁS VENDIDO</span>
<h3>DZ Cube Jetflex</h3>
<p>Motor deslizante brushless de alto rendimiento para puertas hasta 850kg.</p>
<ul class="product-features">
<li>Capacidad hasta 850kg</li>
<li>Motor brushless silencioso</li>
<li>Apertura en 8 segundos</li>
<li>Sistema anti-aplastamiento</li>
</ul>
</div>
</div>
</div>
</section>

<!-- BENEFÍCIOS PT -->
<section class="benefits active-lang" lang="pt">
<div class="section-header">
<h2>Porquê Escolher PPA?</h2>
<p>Vantagens exclusivas para instaladores e revendas profissionais</p>
</div>
<div class="benefits-grid">
<div class="benefit">
<div class="benefit-icon">🏭</div>
<h3>Fabricação em Escala</h3>
<p>Produzimos milhares de motores mensalmente no Brasil. Isto garante preços impossíveis de competir e disponibilidade permanente.</p>
</div>
<div class="benefit">
<div class="benefit-icon">⚡</div>
<h3>Velocidade Incomparável</h3>
<p>Os nossos motores abrem 3x mais rápido que a concorrência europeia. Tecnologia brushless Jetflex de última geração.</p>
</div>
<div class="benefit">
<div class="benefit-icon">📦</div>
<h3>Stock Permanente em PT</h3>
<p>Grande stock em Portugal para entrega imediata. Sem esperas, sem atrasos.</p>
</div>
<div class="benefit">
<div class="benefit-icon">🛠️</div>
<h3>Suporte Técnico Local</h3>
<p>Equipa técnica em Portugal para suporte rápido. Atendemos instaladores via WhatsApp, telefone e email.</p>
</div>
<div class="benefit">
<div class="benefit-icon">💰</div>
<h3>Melhor Preço Garantido</h3>
<p>Como fabricantes, eliminamos intermediários. Compare com Nice, CAME, BFT - o nosso preço é até 40% mais baixo.</p>
</div>
<div class="benefit">
<div class="benefit-icon">⭐</div>
<h3>Pós-Venda Premium</h3>
<p>Garantia de fábrica + reposição rápida de peças. Nunca deixamos sem suporte.</p>
</div>
</div>
</section>

<!-- COBERTURA PT -->
<section class="coverage active-lang" lang="pt">
<h2>Atendemos Instaladores em Portugal & Galicia</h2>
<div class="cities-grid">
<div class="city-card"><h3>Lisboa</h3><p>Portugal</p></div>
<div class="city-card"><h3>Leiria</h3><p>Portugal</p></div>
<div class="city-card"><h3>Mafra</h3><p>Portugal</p></div>
<div class="city-card"><h3>Galicia</h3><p>España</p></div>
</div>
</section>

<!-- CTA PT -->
<section class="cta-section active-lang" lang="pt">
<div class="cta-content">
<h2>Pronto para Trabalhar com a PPA?</h2>
<p>Fale connosco agora e descubra como podemos impulsionar o seu negócio com motores premium e preços de fabricante. Stock permanente em Portugal e suporte técnico garantido.</p>
<div class="cta-phone">📞 +351 XXX XXX XXX</div>
<a href="https://wa.me/351SEUNUMERO?text=Olá!%20Sou%20instalador%20e%20gostaria%20de%20conhecer%20as%20condições%20PPA" class="btn btn-whatsapp" style="font-size:1.25rem;padding:20px 45px">💬 Falar no WhatsApp Agora</a>
</div>
</section>

<footer>
<p>&copy; 2024 PPA Indústria e Comércio | Todos os direitos reservados</p>
<p>Motores Premium • Made in Brazil • Stock em Portugal • Suporte Técnico Local</p>
</footer>

<script>
let currentLang='pt';
function setLanguage(lang){
currentLang=lang;
document.querySelectorAll('.lang-btn').forEach(btn=>btn.classList.remove('active'));
event.target.classList.add('active');
document.querySelectorAll('[lang]').forEach(el=>el.classList.remove('active-lang'));
document.querySelectorAll(`[lang="${lang}"]`).forEach(el=>el.classList.add('active-lang'));
document.documentElement.lang=lang==='pt'?'pt-PT':'es';
}
document.querySelectorAll('a[href^="#"]').forEach(anchor=>{
anchor.addEventListener('click',function(e){
e.preventDefault();
const href=this.getAttribute('href');
if(href==='#produtos'||href==='#productos'){
const target=currentLang==='pt'?document.querySelector('[lang="pt"]#produtos'):document.querySelector('[lang="es"]#productos');
if(target)target.scrollIntoView({behavior:'smooth',block:'start'});
}
});
});
</script>
</body>
</html>
