<!DOCTYPE html>
<html lang="zh-TW">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>數位心路 2026 論壇</title>
<style>
  *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }
  :root {
    --bg: #f4f7fb;
    --surface: #ffffff;
    --card: #eef2f8;
    --accent1: #1a56db;
    --accent2: #0891b2;
    --accent3: #7c3aed;
    --text: #0f172a;
    --sub: #1e3a5f;
    --muted: #475569;
    --border: #c7d8f0;
    --hero-bg: #0f2a5e;
    --hero-text: #ffffff;
    --hero-sub: #93c5fd;
  }
  html { scroll-behavior: smooth; }
  body { font-family: "Microsoft JhengHei", "蘋方-繁", "PingFang TC", "Heiti TC", sans-serif; background: var(--bg); color: var(--text); line-height: 1.7; overflow-x: hidden; }

  /* ── NAV ── */
  nav {
    position: fixed; top: 0; left: 0; right: 0; z-index: 100;
    padding: 10px 40px;
    display: flex; align-items: center; justify-content: space-between;
    background: rgba(255,255,255,0.95); backdrop-filter: blur(14px);
    border-bottom: 2px solid var(--border);
    box-shadow: 0 2px 16px rgba(15,42,94,0.08);
  }
  .nav-logo img { height: 48px; width: auto; background: #fff; border-radius: 8px; padding: 2px 6px; }
  .nav-logo-fallback { font-size: 0.85rem; font-weight: 900; color: var(--accent1); }
  .nav-right { display: flex; align-items: center; gap: 10px; }
  .nav-share-btn {
    display: flex; align-items: center; gap: 6px;
    border: 2px solid; border-radius: 50px;
    padding: 7px 16px; font-size: 0.82rem; font-weight: 700;
    cursor: pointer; text-decoration: none; transition: all .2s;
    background: transparent;
  }
  .nav-share-btn.line { border-color: #06c755; color: #06c755; }
  .nav-share-btn.line:hover { background: #06c755; color: #fff; }
  .nav-share-btn.fb { border-color: #1877f2; color: #1877f2; }
  .nav-share-btn.fb:hover { background: #1877f2; color: #fff; }
  .nav-cta {
    background: var(--accent1); color: #fff; border: none; border-radius: 50px;
    padding: 10px 24px; font-size: 0.9rem; font-weight: 700;
    cursor: pointer; text-decoration: none; transition: background .2s, transform .2s;
  }
  .nav-cta:hover { background: #1344b8; transform: translateY(-1px); }

  /* ── HERO ── */
  #hero {
    min-height: 100vh; display: flex; align-items: center; justify-content: center;
    text-align: center; padding: 120px 24px 80px; position: relative; overflow: hidden;
    background: var(--hero-bg);
  }
  .hero-bg {
    position: absolute; inset: 0;
    background:
      radial-gradient(ellipse 70% 50% at 50% -10%, rgba(96,165,250,0.35) 0%, transparent 65%),
      radial-gradient(ellipse 40% 35% at 85% 85%, rgba(124,58,237,0.25) 0%, transparent 60%),
      radial-gradient(ellipse 40% 35% at 15% 70%, rgba(6,182,212,0.2) 0%, transparent 60%);
  }
  .grid-overlay {
    position: absolute; inset: 0;
    background-image: linear-gradient(rgba(255,255,255,0.04) 1px, transparent 1px), linear-gradient(90deg, rgba(255,255,255,0.04) 1px, transparent 1px);
    background-size: 44px 44px;
  }
  .hero-inner { position: relative; max-width: 860px; }
  .hero-logo { display: flex; justify-content: center; margin-bottom: 36px; }
  .hero-logo img { height: 100px; width: auto; background: #fff; border-radius: 12px; padding: 8px 16px; filter: drop-shadow(0 4px 24px rgba(96,165,250,0.4)); }
  .badge {
    display: inline-block;
    background: rgba(255,255,255,0.12); border: 1px solid rgba(255,255,255,0.3);
    color: #bfdbfe; border-radius: 50px; padding: 7px 22px;
    font-size: 0.8rem; font-weight: 700; letter-spacing: 0.08em; margin-bottom: 28px;
  }
  .hero-title {
    font-size: clamp(2.2rem, 6vw, 4rem); font-weight: 900; line-height: 1.15;
    color: #ffffff; letter-spacing: 0.04em; margin-bottom: 14px;
    text-shadow: 0 2px 24px rgba(0,0,0,0.3);
  }
  .hero-sub {
    font-size: clamp(1rem, 2.2vw, 1.3rem); font-weight: 600;
    color: var(--hero-sub); margin-bottom: 40px; letter-spacing: 0.04em; line-height: 1.5;
  }
  .hero-meta { display: flex; flex-wrap: wrap; gap: 16px; justify-content: center; margin-bottom: 48px; }
  .hero-meta-item {
    display: flex; align-items: center; gap: 10px;
    background: rgba(255,255,255,0.12); border: 1px solid rgba(255,255,255,0.25);
    border-radius: 14px; padding: 12px 22px; font-size: 0.95rem; color: #e0f2fe;
    font-weight: 500;
  }
  .hero-meta-item strong { color: #ffffff; font-weight: 800; }
  .hero-actions { display: flex; flex-wrap: wrap; gap: 14px; justify-content: center; align-items: center; }
  .btn-primary {
    display: inline-block; background: #ffffff; color: var(--accent1);
    text-decoration: none; padding: 16px 48px; border-radius: 50px;
    font-size: 1.1rem; font-weight: 900;
    box-shadow: 0 4px 32px rgba(0,0,0,0.25); transition: transform .2s, box-shadow .2s;
    letter-spacing: 0.04em;
  }
  .btn-primary:hover { transform: translateY(-3px); box-shadow: 0 8px 48px rgba(0,0,0,0.35); }
  .btn-share-line, .btn-share-fb {
    display: inline-flex; align-items: center; gap: 8px;
    text-decoration: none; padding: 14px 24px; border-radius: 50px;
    font-size: 0.95rem; font-weight: 700; transition: transform .2s, opacity .2s;
    border: 2px solid;
  }
  .btn-share-line { background: transparent; border-color: #06c755; color: #4ade80; }
  .btn-share-line:hover { background: #06c755; color: #fff; }
  .btn-share-fb { background: transparent; border-color: #60a5fa; color: #93c5fd; }
  .btn-share-fb:hover { background: #1877f2; border-color: #1877f2; color: #fff; }

  /* ── SECTIONS ── */
  section { padding: 96px 24px; }
  .container { max-width: 900px; margin: 0 auto; }
  .section-label { font-size: 0.75rem; font-weight: 800; letter-spacing: 0.2em; color: var(--accent1); text-transform: uppercase; margin-bottom: 10px; }
  .section-title { font-size: clamp(1.6rem, 3vw, 2.4rem); font-weight: 900; margin-bottom: 36px; line-height: 1.3; color: var(--text); }
  .divider { width: 60px; height: 5px; background: linear-gradient(90deg, var(--accent1), var(--accent2)); border-radius: 3px; margin-bottom: 40px; }

  /* ── ABOUT ── */
  #about { background: var(--surface); }
  .about-text p { color: var(--muted); margin-bottom: 18px; font-size: 1.02rem; line-height: 2; text-align: justify; }
  .about-text p:last-child { margin-bottom: 0; }

  /* ── HIGHLIGHTS ── */
  #highlights { background: var(--bg); }
  .highlights-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 20px; }
  .highlight-card {
    background: var(--surface); border: 2px solid var(--border);
    border-radius: 18px; padding: 30px 24px;
    transition: transform .2s, border-color .2s, box-shadow .2s;
    box-shadow: 0 2px 12px rgba(15,42,94,0.06);
  }
  .highlight-card:hover { transform: translateY(-5px); border-color: var(--accent1); box-shadow: 0 8px 32px rgba(26,86,219,0.12); }
  .highlight-icon { font-size: 2.2rem; margin-bottom: 14px; }
  .highlight-card h3 { font-size: 1.05rem; font-weight: 800; margin-bottom: 8px; color: var(--text); }
  .highlight-card p { font-size: 0.88rem; color: var(--muted); line-height: 1.7; }

  /* ── AGENDA ── */
  #agenda { background: var(--surface); }
  .agenda-list { display: flex; flex-direction: column; border-radius: 16px; overflow: hidden; border: 2px solid var(--border); box-shadow: 0 4px 24px rgba(15,42,94,0.08); }
  .agenda-item { display: grid; grid-template-columns: 170px 1fr; border-bottom: 1px solid var(--border); }
  .agenda-item:last-child { border-bottom: none; }
  .agenda-time {
    padding: 20px 16px 20px 20px; font-size: 0.83rem; font-weight: 800;
    color: var(--accent1); letter-spacing: 0.03em;
    border-right: 2px solid var(--border);
    display: flex; align-items: center;
    background: #f0f5ff;
  }
  .agenda-content { padding: 20px 24px; background: var(--surface); }
  .agenda-title { font-weight: 700; font-size: 0.97rem; margin-bottom: 5px; line-height: 1.45; color: var(--text); }
  .agenda-speaker { font-size: 0.97rem; color: var(--sub); font-weight: 600; display: flex; align-items: center; gap: 6px; }
  .agenda-speaker::before { content: '▸'; color: var(--accent1); }
  .agenda-break .agenda-time { background: #e0f2fe; color: var(--accent2); }
  .agenda-break .agenda-content { background: #f0faff; }
  .agenda-break .agenda-title { color: var(--accent2); font-weight: 800; }
  .agenda-note { text-align: center; margin-top: 20px; font-size: 0.82rem; color: var(--muted); font-style: italic; }

  /* ── REGISTER ── */
  #register { background: var(--hero-bg); text-align: center; }
  .register-box {
    background: rgba(255,255,255,0.08); border: 2px solid rgba(255,255,255,0.2);
    border-radius: 28px; padding: 64px 48px; max-width: 680px; margin: 0 auto;
    backdrop-filter: blur(10px);
  }
  .register-box h2 { font-size: clamp(1.5rem, 3vw, 2.1rem); font-weight: 900; margin-bottom: 16px; color: #fff; }
  .register-box p { color: #93c5fd; margin-bottom: 36px; font-size: 1rem; }
  .register-share { margin-top: 28px; display: flex; flex-wrap: wrap; gap: 12px; justify-content: center; }
  .register-share-label { width: 100%; font-size: 0.83rem; color: #bfdbfe; margin-bottom: 4px; }

  /* ── FLOATING SHARE ── */
  .float-share { position: fixed; right: 20px; top: 50%; transform: translateY(-50%); display: flex; flex-direction: column; gap: 10px; z-index: 90; }
  .float-btn {
    width: 46px; height: 46px; border-radius: 50%;
    display: flex; align-items: center; justify-content: center;
    text-decoration: none; box-shadow: 0 4px 16px rgba(0,0,0,0.2);
    transition: transform .2s, box-shadow .2s;
    border: 2px solid transparent;
  }
  .float-btn:hover { transform: scale(1.12); box-shadow: 0 8px 24px rgba(0,0,0,0.25); }
  .float-btn.line { background: #06c755; }
  .float-btn.fb { background: #1877f2; }

  /* ── FOOTER ── */
  footer {
    background: #0a1f4a; border-top: 2px solid rgba(255,255,255,0.1);
    padding: 44px 24px; text-align: center;
  }
  footer .org { font-weight: 800; font-size: 1rem; margin-bottom: 8px; color: #fff; }
  footer .guide { font-size: 0.84rem; color: #93c5fd; margin-bottom: 4px; }
  footer .copy { font-size: 0.78rem; color: rgba(147,197,253,0.45); margin-top: 14px; }

  @media (max-width: 600px) {
    nav { padding: 10px 16px; }
    .nav-share-btn { display: none; }
    .agenda-item { grid-template-columns: 110px 1fr; }
    .agenda-time { font-size: 0.73rem; padding: 14px 10px; }
    .register-box { padding: 40px 20px; }
    .float-share { right: 10px; }
  }
</style>
</head>
<body>

<!-- FLOATING SHARE -->
<div class="float-share">
  <a class="float-btn line" href="#" onclick="shareToLine(event)" title="分享到 LINE">
    <svg width="22" height="22" viewBox="0 0 24 24" fill="white"><path d="M19.365 9.863c.349 0 .63.285.63.631 0 .345-.281.63-.63.63H17.61v1.125h1.755c.349 0 .63.283.63.63 0 .344-.281.629-.63.629h-2.386c-.345 0-.627-.285-.627-.629V8.108c0-.345.282-.63.63-.63h2.386c.346 0 .627.285.627.63 0 .349-.281.63-.63.63H17.61v1.125h1.755zm-3.855 3.016c0 .27-.174.51-.432.596-.064.021-.133.031-.199.031-.211 0-.391-.09-.51-.25l-2.443-3.317v2.94c0 .344-.279.629-.631.629-.346 0-.626-.285-.626-.629V8.108c0-.27.173-.51.43-.595.06-.023.136-.033.194-.033.195 0 .375.104.495.254l2.462 3.33V8.108c0-.345.282-.63.63-.63.345 0 .63.285.63.63v4.771zm-5.741 0c0 .344-.282.629-.631.629-.345 0-.627-.285-.627-.629V8.108c0-.345.282-.63.63-.63.346 0 .628.285.628.63v4.771zm-2.466.629H4.917c-.345 0-.63-.285-.63-.629V8.108c0-.345.285-.63.63-.63.348 0 .63.285.63.63v4.141h1.756c.348 0 .629.283.629.63 0 .344-.281.629-.629.629M24 10.314C24 4.943 18.615.572 12 .572S0 4.943 0 10.314c0 4.811 4.27 8.842 10.035 9.608.391.082.923.258 1.058.59.12.301.079.766.038 1.08l-.164 1.02c-.045.301-.24 1.186 1.049.645 1.291-.539 6.916-4.078 9.436-6.975C23.176 14.393 24 12.458 24 10.314"/></svg>
  </a>
  <a class="float-btn fb" href="#" onclick="shareToFacebook(event)" title="分享到 Facebook">
    <svg width="20" height="20" viewBox="0 0 24 24" fill="white"><path d="M24 12.073c0-6.627-5.373-12-12-12s-12 5.373-12 12c0 5.99 4.388 10.954 10.125 11.854v-8.385H7.078v-3.47h3.047V9.43c0-3.007 1.792-4.669 4.533-4.669 1.312 0 2.686.235 2.686.235v2.953H15.83c-1.491 0-1.956.925-1.956 1.874v2.25h3.328l-.532 3.47h-2.796v8.385C19.612 23.027 24 18.062 24 12.073z"/></svg>
  </a>
</div>

<!-- NAV -->
<nav>
  <div class="nav-logo">
    <img src="https://cdn.phototourl.com/free/2026-04-27-4a300249-7fa3-489b-bbd1-95a15976dece.png" alt="健康樂活智慧醫療照護聯盟"
      onerror="this.style.display='none'; document.querySelector('.nav-logo-fallback').style.display='block'">
    <span class="nav-logo-fallback" style="display:none">健康樂活 智慧醫療照護聯盟</span>
  </div>
  <div class="nav-right">
    <a class="nav-share-btn line" href="#" onclick="shareToLine(event)">
      <svg width="15" height="15" viewBox="0 0 24 24" fill="currentColor"><path d="M19.365 9.863c.349 0 .63.285.63.631 0 .345-.281.63-.63.63H17.61v1.125h1.755c.349 0 .63.283.63.63 0 .344-.281.629-.63.629h-2.386c-.345 0-.627-.285-.627-.629V8.108c0-.345.282-.63.63-.63h2.386c.346 0 .627.285.627.63 0 .349-.281.63-.63.63H17.61v1.125h1.755zm-3.855 3.016c0 .27-.174.51-.432.596-.064.021-.133.031-.199.031-.211 0-.391-.09-.51-.25l-2.443-3.317v2.94c0 .344-.279.629-.631.629-.346 0-.626-.285-.626-.629V8.108c0-.27.173-.51.43-.595.06-.023.136-.033.194-.033.195 0 .375.104.495.254l2.462 3.33V8.108c0-.345.282-.63.63-.63.345 0 .63.285.63.63v4.771zm-5.741 0c0 .344-.282.629-.631.629-.345 0-.627-.285-.627-.629V8.108c0-.345.282-.63.63-.63.346 0 .628.285.628.63v4.771zm-2.466.629H4.917c-.345 0-.63-.285-.63-.629V8.108c0-.345.285-.63.63-.63.348 0 .63.285.63.63v4.141h1.756c.348 0 .629.283.629.63 0 .344-.281.629-.629.629M24 10.314C24 4.943 18.615.572 12 .572S0 4.943 0 10.314c0 4.811 4.27 8.842 10.035 9.608.391.082.923.258 1.058.59.12.301.079.766.038 1.08l-.164 1.02c-.045.301-.24 1.186 1.049.645 1.291-.539 6.916-4.078 9.436-6.975C23.176 14.393 24 12.458 24 10.314"/></svg>
      分享 LINE
    </a>
    <a class="nav-share-btn fb" href="#" onclick="shareToFacebook(event)">
      <svg width="14" height="14" viewBox="0 0 24 24" fill="currentColor"><path d="M24 12.073c0-6.627-5.373-12-12-12s-12 5.373-12 12c0 5.99 4.388 10.954 10.125 11.854v-8.385H7.078v-3.47h3.047V9.43c0-3.007 1.792-4.669 4.533-4.669 1.312 0 2.686.235 2.686.235v2.953H15.83c-1.491 0-1.956.925-1.956 1.874v2.25h3.328l-.532 3.47h-2.796v8.385C19.612 23.027 24 18.062 24 12.073z"/></svg>
      分享 Facebook
    </a>
    <a class="nav-cta" href="https://forms.gle/UFmSpQdQ26bsPQi79" target="_blank">立即報名</a>
  </div>
</nav>

<!-- HERO -->
<section id="hero">
  <div class="hero-bg"></div>
  <div class="grid-overlay"></div>
  <div class="hero-inner">
    <div class="hero-logo">
      <img src="https://cdn.phototourl.com/free/2026-04-27-4a300249-7fa3-489b-bbd1-95a15976dece.png" alt="健康樂活智慧醫療照護聯盟" onerror="this.style.display='none'">
    </div>
    <div class="badge">健康樂活與智慧醫療照護聯盟 ✦ 2026 第二季論壇</div>
    <div class="hero-title">數位心路</div>
    <div class="hero-sub">跨域整合科技與動態需求的<br>心理健康照護新典範</div>
    <div class="hero-meta">
      <div class="hero-meta-item">📅&ensp;<strong>2026年6月26日　13:00 – 17:00</strong></div>
      <div class="hero-meta-item">📍&ensp;<strong>台北世貿一館 A5 會議室</strong></div>
    </div>
    <div class="hero-actions">
      <a class="btn-primary" href="https://forms.gle/UFmSpQdQ26bsPQi79" target="_blank">立即線上報名 →</a>
      <a class="btn-share-line" href="#" onclick="shareToLine(event)">
        <svg width="17" height="17" viewBox="0 0 24 24" fill="currentColor"><path d="M19.365 9.863c.349 0 .63.285.63.631 0 .345-.281.63-.63.63H17.61v1.125h1.755c.349 0 .63.283.63.63 0 .344-.281.629-.63.629h-2.386c-.345 0-.627-.285-.627-.629V8.108c0-.345.282-.63.63-.63h2.386c.346 0 .627.285.627.63 0 .349-.281.63-.63.63H17.61v1.125h1.755zm-3.855 3.016c0 .27-.174.51-.432.596-.064.021-.133.031-.199.031-.211 0-.391-.09-.51-.25l-2.443-3.317v2.94c0 .344-.279.629-.631.629-.346 0-.626-.285-.626-.629V8.108c0-.27.173-.51.43-.595.06-.023.136-.033.194-.033.195 0 .375.104.495.254l2.462 3.33V8.108c0-.345.282-.63.63-.63.345 0 .63.285.63.63v4.771zm-5.741 0c0 .344-.282.629-.631.629-.345 0-.627-.285-.627-.629V8.108c0-.345.282-.63.63-.63.346 0 .628.285.628.63v4.771zm-2.466.629H4.917c-.345 0-.63-.285-.63-.629V8.108c0-.345.285-.63.63-.63.348 0 .63.285.63.63v4.141h1.756c.348 0 .629.283.629.63 0 .344-.281.629-.629.629M24 10.314C24 4.943 18.615.572 12 .572S0 4.943 0 10.314c0 4.811 4.27 8.842 10.035 9.608.391.082.923.258 1.058.59.12.301.079.766.038 1.08l-.164 1.02c-.045.301-.24 1.186 1.049.645 1.291-.539 6.916-4.078 9.436-6.975C23.176 14.393 24 12.458 24 10.314"/></svg>
        分享到 LINE
      </a>
      <a class="btn-share-fb" href="#" onclick="shareToFacebook(event)">
        <svg width="16" height="16" viewBox="0 0 24 24" fill="currentColor"><path d="M24 12.073c0-6.627-5.373-12-12-12s-12 5.373-12 12c0 5.99 4.388 10.954 10.125 11.854v-8.385H7.078v-3.47h3.047V9.43c0-3.007 1.792-4.669 4.533-4.669 1.312 0 2.686.235 2.686.235v2.953H15.83c-1.491 0-1.956.925-1.956 1.874v2.25h3.328l-.532 3.47h-2.796v8.385C19.612 23.027 24 18.062 24 12.073z"/></svg>
        分享到 Facebook
      </a>
    </div>
  </div>
</section>

<!-- ABOUT -->
<section id="about">
  <div class="container">
    <div class="section-label">關於本論壇</div>
    <h2 class="section-title">從科技到人心，開創照護新局</h2>
    <div class="divider"></div>
    <div class="about-text">
      <p>在宅醫療著重藥物安全、心智健康與活動力三大核心面向。「健康樂活與智慧醫療照護聯盟」2026年第二季論壇以「跨域整合科技與動態需求的心理健康照護新典範」為主題，匯聚國內各領域專家，共同分享數位療法於心理健康照護的實務應用，並深入探討相關技術發展及倫理議題。</p>
      <p>現代社會節奏日益加快，資訊過載與高強度的生活壓力已成常態；生活型態趨於室內化，加上人與人之間面對面、有溫度的互動逐漸減少，使得心理與精神健康問題愈發受到重視。廣泛性焦慮症（GAD）、憂鬱症（MDD）與注意力不足過動症（ADHD）等，皆是當前社會不可忽視的課題。面對這些挑戰，除藥物治療外，數位療法（Digital Therapeutics, DTx）提供了另一條可行路徑，藉由提升醫療的可近性與即時性，結合高頻率、遊戲化的訓練設計，以及精準的數據追蹤與回饋機制，有效提高患者的治療遵從性（Adherence）。</p>
      <p>本論壇將邀請國內醫學中心專科醫師、學者專家及研發機構技術人員，分享人工智慧（AI）、行動應用程式、穿戴裝置與數位醫材等科技工具的應用實例，跨越醫療院所、學校與居家等多元場域，展示如何重塑符合個人化動態需求的心理健康照護模式。</p>
      <p>與此同時，論壇也將審慎檢視數據隱私、倫理規範、臨床驗證與監管機制等關鍵議題，正面回應數位療法發展過程中的挑戰，共同描繪心理與精神健康照護的未來樣貌，進而建構更具永續性的整體生態體系。透過跨領域專家對話與案例分享，本論壇期望凝聚各方共識，攜手探索心理健康照護的創新可能，打造更具韌性與可持續發展潛力的在宅醫療健康生態系。</p>
    </div>
  </div>
</section>

<!-- HIGHLIGHTS -->
<section id="highlights">
  <div class="container">
    <div class="section-label">論壇亮點</div>
    <h2 class="section-title">四大核心主軸</h2>
    <div class="divider"></div>
    <div class="highlights-grid">
      <div class="highlight-card">
        <div class="highlight-icon">🧠</div>
        <h3>心理健康新視野</h3>
        <p>深入探討 GAD、MDD、ADHD 等課題的非藥物介入策略與數位療法路徑。</p>
      </div>
      <div class="highlight-card">
        <div class="highlight-icon">🤖</div>
        <h3>AI 與科技應用</h3>
        <p>展示人工智慧、穿戴裝置、行動應用程式在心理照護領域的實務案例。</p>
      </div>
      <div class="highlight-card">
        <div class="highlight-icon">🏫</div>
        <h3>跨域多元場域</h3>
        <p>涵蓋醫療院所、校園與居家環境，打造全面性的心理健康支持網絡。</p>
      </div>
      <div class="highlight-card">
        <div class="highlight-icon">⚖️</div>
        <h3>倫理與監管</h3>
        <p>正視數據隱私、臨床驗證與法規監管等關鍵挑戰，共建可信賴的數位醫療生態。</p>
      </div>
    </div>
  </div>
</section>

<!-- AGENDA -->
<section id="agenda">
  <div class="container">
    <div class="section-label">活動議程</div>
    <h2 class="section-title">2026年6月26日</h2>
    <div class="divider"></div>
    <div class="agenda-list">
      <div class="agenda-item agenda-break">
        <div class="agenda-time">13:00 – 13:30</div>
        <div class="agenda-content"><div class="agenda-title">報到入場</div></div>
      </div>
      <div class="agenda-item">
        <div class="agenda-time">13:30 – 13:40</div>
        <div class="agenda-content"><div class="agenda-title">主持人開場、致詞、合影</div></div>
      </div>
      <div class="agenda-item">
        <div class="agenda-time">13:40 – 14:10</div>
        <div class="agenda-content">
          <div class="agenda-title">廣泛性焦慮症的非藥物介入案例分享</div>
          <div class="agenda-speaker">李信謙副院長　臺北醫學大學附設醫院</div>
        </div>
      </div>
      <div class="agenda-item">
        <div class="agenda-time">14:10 – 14:30</div>
        <div class="agenda-content">
          <div class="agenda-title">穿戴裝置運用於廣泛性焦慮症之發展</div>
          <div class="agenda-speaker">胡長霖博士　工研院生醫所</div>
        </div>
      </div>
      <div class="agenda-item">
        <div class="agenda-time">14:30 – 15:00</div>
        <div class="agenda-content">
          <div class="agenda-title">重度憂鬱症的非藥物介入案例分享</div>
          <div class="agenda-speaker">陳坤波執行長　迦樂醫院</div>
        </div>
      </div>
      <div class="agenda-item agenda-break">
        <div class="agenda-time">15:00 – 15:20</div>
        <div class="agenda-content"><div class="agenda-title">☕ Tea Break</div></div>
      </div>
      <div class="agenda-item">
        <div class="agenda-time">15:20 – 15:50</div>
        <div class="agenda-content">
          <div class="agenda-title">ADHD 學童在學校環境的科技支持案例分享</div>
          <div class="agenda-speaker">簡吟文助理教授　清大特殊教育學系</div>
        </div>
      </div>
      <div class="agenda-item">
        <div class="agenda-time">15:50 – 16:10</div>
        <div class="agenda-content">
          <div class="agenda-title">科技運用於 ADHD 學童之非藥物介入發展應用</div>
          <div class="agenda-speaker">陳建任博士　工研院服科中心</div>
        </div>
      </div>
      <div class="agenda-item">
        <div class="agenda-time">16:10 – 16:40</div>
        <div class="agenda-content">
          <div class="agenda-title">科技可以幫忙兒童身心治療甚麼？（暫訂）</div>
          <div class="agenda-speaker">林籠昌主任　高醫附設中和紀念醫院小兒神經科</div>
        </div>
      </div>
      <div class="agenda-item">
        <div class="agenda-time">16:40 – 17:00</div>
        <div class="agenda-content">
          <div class="agenda-title">Panel Discussion &amp; Conclusion</div>
          <div class="agenda-speaker">主持人　胡紀平副秘書長</div>
        </div>
      </div>
    </div>
    <p class="agenda-note">＊ 主辦單位保留議程更動之權利</p>
  </div>
</section>

<!-- REGISTER -->
<section id="register">
  <div class="container">
    <div class="register-box">
      <h2>立即報名參加</h2>
      <p>名額有限，歡迎各界先進踴躍報名，共同探索心理健康照護的創新未來！</p>
      <a class="btn-primary" href="https://forms.gle/UFmSpQdQ26bsPQi79" target="_blank">前往報名表單 →</a>
      <div class="register-share">
        <div class="register-share-label">📢 歡迎分享給朋友</div>
        <a class="btn-share-line" href="#" onclick="shareToLine(event)">
          <svg width="17" height="17" viewBox="0 0 24 24" fill="currentColor"><path d="M19.365 9.863c.349 0 .63.285.63.631 0 .345-.281.63-.63.63H17.61v1.125h1.755c.349 0 .63.283.63.63 0 .344-.281.629-.63.629h-2.386c-.345 0-.627-.285-.627-.629V8.108c0-.345.282-.63.63-.63h2.386c.346 0 .627.285.627.63 0 .349-.281.63-.63.63H17.61v1.125h1.755zm-3.855 3.016c0 .27-.174.51-.432.596-.064.021-.133.031-.199.031-.211 0-.391-.09-.51-.25l-2.443-3.317v2.94c0 .344-.279.629-.631.629-.346 0-.626-.285-.626-.629V8.108c0-.27.173-.51.43-.595.06-.023.136-.033.194-.033.195 0 .375.104.495.254l2.462 3.33V8.108c0-.345.282-.63.63-.63.345 0 .63.285.63.63v4.771zm-5.741 0c0 .344-.282.629-.631.629-.345 0-.627-.285-.627-.629V8.108c0-.345.282-.63.63-.63.346 0 .628.285.628.63v4.771zm-2.466.629H4.917c-.345 0-.63-.285-.63-.629V8.108c0-.345.285-.63.63-.63.348 0 .63.285.63.63v4.141h1.756c.348 0 .629.283.629.63 0 .344-.281.629-.629.629M24 10.314C24 4.943 18.615.572 12 .572S0 4.943 0 10.314c0 4.811 4.27 8.842 10.035 9.608.391.082.923.258 1.058.59.12.301.079.766.038 1.08l-.164 1.02c-.045.301-.24 1.186 1.049.645 1.291-.539 6.916-4.078 9.436-6.975C23.176 14.393 24 12.458 24 10.314"/></svg>
          分享到 LINE
        </a>
        <a class="btn-share-fb" href="#" onclick="shareToFacebook(event)">
          <svg width="16" height="16" viewBox="0 0 24 24" fill="currentColor"><path d="M24 12.073c0-6.627-5.373-12-12-12s-12 5.373-12 12c0 5.99 4.388 10.954 10.125 11.854v-8.385H7.078v-3.47h3.047V9.43c0-3.007 1.792-4.669 4.533-4.669 1.312 0 2.686.235 2.686.235v2.953H15.83c-1.491 0-1.956.925-1.956 1.874v2.25h3.328l-.532 3.47h-2.796v8.385C19.612 23.027 24 18.062 24 12.073z"/></svg>
          分享到 Facebook
        </a>
      </div>
    </div>
  </div>
</section>

<!-- FOOTER -->
<footer>
  <div class="org">健康樂活與智慧醫療照護聯盟</div>
  <div class="guide">指導單位：經濟部技術司</div>
  <div class="guide">活動地點：台北世貿一館 A5 會議室｜110 臺北市信義區信義路五段 5 號</div>
  <div class="copy">© 2026 健康樂活與智慧醫療照護聯盟　All Rights Reserved</div>
</footer>

<script>
  function shareToLine(e) {
    e.preventDefault();
    var msg = '【論壇活動】數位心路：跨域整合科技與動態需求的心理健康照護新典範\n📅 2026年6月26日 13:00–17:00\n📍 台北世貿一館A5會議室\n\n' + window.location.href;
    window.open('https://social-plugins.line.me/lineit/share?url=' + encodeURIComponent(window.location.href) + '&text=' + encodeURIComponent(msg), '_blank', 'width=600,height=600');
  }
  function shareToFacebook(e) {
    e.preventDefault();
    window.open('https://www.facebook.com/sharer/sharer.php?u=' + encodeURIComponent(window.location.href), '_blank', 'width=600,height=600');
  }
</script>
</body>
</html>
