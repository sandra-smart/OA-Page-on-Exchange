<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Goodwill Opportunity Accelerator — Exchange</title>
<link href="https://fonts.googleapis.com/css2?family=Fraunces:ital,opsz,wght@0,9..144,300;0,9..144,600;0,9..144,700;1,9..144,300&family=DM+Sans:opsz,wght@9..40,400;9..40,500;9..40,600;9..40,700&display=swap" rel="stylesheet">
<style>
:root {
  --navy:    #1C3F6E;
  --blue:    #2563A8;
  --blue-m:  #3A7DC7;
  --blue-l:  #C8DFF5;
  --blue-xl: #EBF4FC;
  --teal:    #0D7377;
  --green:   #166534;
  --green-l: #DCFCE7;
  --amber:   #92400E;
  --amber-l: #FEF3C7;
  --slate:   #334155;
  --muted:   #64748B;
  --border:  #E2E8F0;
  --bg:      #F6F9FC;
  --white:   #FFFFFF;
  --text:    #1E293B;
  --ess:     #1D4ED8;
  --ess-l:   #DBEAFE;
  --hf:      #7C3AED;
  --hf-l:    #EDE9FE;
  --opt:     #0F766E;
  --opt-l:   #CCFBF1;
  --r:10px;
  --sh: 0 1px 3px rgba(0,0,0,.06), 0 4px 16px rgba(28,63,110,.08);
  --sh2: 0 4px 12px rgba(0,0,0,.08), 0 12px 32px rgba(28,63,110,.12);
}
*,*::before,*::after{box-sizing:border-box;margin:0;padding:0;}
html{scroll-behavior:smooth;}
body{font-family:'DM Sans',system-ui,sans-serif;background:var(--bg);color:var(--text);font-size:15px;line-height:1.6;}
img{max-width:100%;}
a{color:var(--blue);text-decoration:none;}

/* ── PROTOTYPE BANNER ── */
.proto{background:#FEF08A;border-bottom:2px solid #CA8A04;padding:8px 20px;text-align:center;font-size:12.5px;font-weight:600;color:#78350F;position:sticky;top:0;z-index:300;letter-spacing:.02em;}
.proto span{font-weight:400;opacity:.85;margin-left:6px;}

/* ── EXCHANGE HEADER ── */
.ex-header{background:var(--navy);height:50px;display:flex;align-items:center;justify-content:space-between;padding:0 28px;position:sticky;top:34px;z-index:200;box-shadow:0 2px 8px rgba(0,0,0,.25);}
.ex-brand{display:flex;align-items:center;gap:10px;color:#fff;font-size:13.5px;font-weight:700;letter-spacing:.05em;text-transform:uppercase;}
.ex-brand .g{width:26px;height:26px;background:white;border-radius:5px;display:flex;align-items:center;justify-content:center;font-family:'Fraunces',serif;font-size:15px;color:var(--navy);font-weight:600;}
.ex-nav{display:flex;gap:2px;}
.ex-nav a{color:rgba(255,255,255,.65);font-size:13px;padding:6px 11px;border-radius:5px;transition:.2s;}
.ex-nav a:hover,.ex-nav a.on{color:#fff;background:rgba(255,255,255,.12);}
.ex-search{display:flex;align-items:center;gap:8px;background:rgba(255,255,255,.1);border:1px solid rgba(255,255,255,.15);border-radius:20px;padding:5px 14px;}
.ex-search input{background:transparent;border:none;outline:none;color:#fff;font-size:13px;width:160px;}
.ex-search input::placeholder{color:rgba(255,255,255,.45);}

/* ── HERO ── */
.hero{background:linear-gradient(150deg,#1C3F6E 0%,#1a4f8a 50%,#2563A8 100%);padding:52px 48px 44px;position:relative;overflow:hidden;}
.hero::before,.hero::after{content:'';position:absolute;border-radius:50%;background:rgba(255,255,255,.04);}
.hero::before{width:500px;height:500px;right:-100px;top:-150px;}
.hero::after{width:300px;height:300px;left:-80px;bottom:-120px;}
.hero-inner{max-width:900px;position:relative;z-index:1;margin:0 auto;}
.hero-crumb{font-size:12px;color:rgba(255,255,255,.55);margin-bottom:14px;letter-spacing:.04em;}
.hero-crumb span{color:rgba(255,255,255,.9);}
.hero h1{font-family:'Fraunces',serif;font-size:clamp(30px,4.5vw,52px);font-weight:600;line-height:1.08;color:#fff;margin-bottom:12px;letter-spacing:-.02em;}
.hero h1 em{font-style:italic;font-weight:300;color:rgba(255,255,255,.85);}
.hero-sub{font-size:16px;color:rgba(255,255,255,.82);max-width:620px;line-height:1.65;margin-bottom:26px;}
.hero-orientation{background:rgba(255,255,255,.09);border:1px solid rgba(255,255,255,.18);border-left:3px solid rgba(255,255,255,.5);border-radius:0 8px 8px 0;padding:14px 18px;max-width:680px;font-size:14px;color:rgba(255,255,255,.88);line-height:1.6;}
.hero-orientation strong{color:#fff;display:block;margin-bottom:4px;font-size:13px;letter-spacing:.05em;text-transform:uppercase;}
.hero-meta{display:flex;gap:20px;margin-top:24px;flex-wrap:wrap;}
.hero-badge{display:flex;align-items:center;gap:6px;background:rgba(255,255,255,.12);border:1px solid rgba(255,255,255,.18);border-radius:100px;padding:5px 14px;font-size:12px;font-weight:600;color:rgba(255,255,255,.9);}

/* ── PAGE WRAP ── */
.wrap{max-width:1200px;margin:0 auto;padding:0 32px 100px;}

/* ── SECTION HEADS ── */
.sec-head{margin-top:56px;margin-bottom:6px;}
.sec-label{font-size:11.5px;font-weight:700;letter-spacing:.1em;text-transform:uppercase;color:var(--blue);margin-bottom:6px;}
.sec-head h2{font-family:'Fraunces',serif;font-size:28px;font-weight:600;color:var(--navy);letter-spacing:-.01em;}
.sec-desc{color:var(--muted);font-size:14.5px;max-width:740px;line-height:1.65;margin-top:6px;margin-bottom:24px;}

/* ── PHASE TABS ── */
.phase-nav{position:sticky;top:84px;z-index:100;background:var(--bg);padding:12px 0;margin-top:32px;}
.phase-nav-inner{display:flex;gap:4px;background:#fff;border-radius:12px;padding:8px;box-shadow:var(--sh);flex-wrap:wrap;}
.ptab{flex:1;min-width:120px;text-align:center;padding:10px 10px;border-radius:8px;font-size:13px;font-weight:600;color:var(--muted);cursor:pointer;transition:.2s;border:1.5px solid transparent;white-space:nowrap;background:transparent;}
.ptab:hover{background:var(--blue-xl);color:var(--navy);}
.ptab.on{background:var(--navy);color:#fff;}
.ptab .n{display:inline-flex;align-items:center;justify-content:center;width:18px;height:18px;border-radius:50%;background:rgba(255,255,255,.2);font-size:10px;font-weight:700;margin-right:4px;}
.ptab .ico{font-size:14px;margin-right:3px;}

/* ── ADOPTION TOGGLE ── */
.tier-bar{display:flex;align-items:center;gap:12px;background:#fff;border:1px solid var(--border);border-radius:10px;padding:12px 16px;margin-bottom:24px;flex-wrap:wrap;}
.tier-bar .lbl{font-size:13px;font-weight:600;color:var(--slate);margin-right:4px;}
.tier-btn{display:flex;align-items:center;gap:6px;padding:7px 16px;border-radius:7px;font-size:13px;font-weight:600;cursor:pointer;border:1.5px solid transparent;transition:.2s;}
.tier-btn.ess{background:var(--ess-l);color:var(--ess);border-color:var(--ess-l);}
.tier-btn.ess.on{background:var(--ess);color:#fff;border-color:var(--ess);}
.tier-btn.hf{background:var(--hf-l);color:var(--hf);border-color:var(--hf-l);}
.tier-btn.hf.on{background:var(--hf);color:#fff;border-color:var(--hf);}
.tier-info{font-size:12.5px;color:var(--muted);margin-left:auto;}

/* ── CONTENT PANELS ── */
.panel{display:none;}
.panel.on{display:block;}

/* ── CARDS ── */
.cards{display:grid;grid-template-columns:repeat(3,1fr);gap:16px;}
.card{background:#fff;border-radius:var(--r);padding:22px 20px 18px;display:flex;flex-direction:column;gap:7px;box-shadow:var(--sh);border:1px solid var(--border);transition:.22s;position:relative;overflow:hidden;}
.card::after{content:'';position:absolute;top:0;left:0;right:0;height:3px;background:linear-gradient(90deg,var(--blue),var(--blue-m));transform:scaleX(0);transform-origin:left;transition:.22s;}
.card:hover{box-shadow:var(--sh2);transform:translateY(-2px);}
.card:hover::after{transform:scaleX(1);}
.card-top{display:flex;align-items:flex-start;justify-content:space-between;gap:8px;}
.card-num{font-size:11px;font-weight:700;letter-spacing:.08em;text-transform:uppercase;color:var(--muted);}
.card h3{font-size:15px;font-weight:700;color:var(--navy);line-height:1.3;}
.card .desc{font-size:13.5px;color:var(--slate);line-height:1.55;flex:1;}
.card-tiers{display:flex;gap:5px;flex-wrap:wrap;margin-top:2px;}
.tier-pill{font-size:11px;font-weight:700;padding:2px 8px;border-radius:100px;letter-spacing:.04em;}
.tp-ess{background:var(--ess-l);color:var(--ess);}
.tp-hf{background:var(--hf-l);color:var(--hf);}
.tp-opt{background:var(--opt-l);color:var(--opt);}
.card-footer{margin-top:10px;display:flex;flex-direction:column;gap:7px;}
.track{font-size:12px;color:var(--muted);background:var(--bg);border-radius:6px;padding:6px 10px;border:1px solid var(--border);}
.track strong{color:var(--slate);display:block;font-size:11px;text-transform:uppercase;letter-spacing:.05em;margin-bottom:2px;}
.btn{display:inline-flex;align-items:center;gap:6px;padding:8px 16px;border-radius:7px;font-size:13px;font-weight:600;text-decoration:none;transition:.18s;cursor:pointer;border:none;width:fit-content;}
.btn-live{background:var(--blue);color:#fff;}
.btn-live:hover{background:var(--navy);}
.btn-tbd{background:var(--bg);color:var(--muted);border:1.5px solid var(--border);}
.btn-dev{background:#F1F5F9;color:#94A3B8;border:1.5px dashed #CBD5E1;cursor:default;}
.status-dot{width:7px;height:7px;border-radius:50%;background:currentColor;display:inline-block;}

/* ── HIDDEN ON TIER FILTER ── */
.card.ess-hide:not(.hf-visible){opacity:.35;pointer-events:none;}

/* ── INTRO RESOURCES ── */
.intro-strip{background:#fff;border-radius:14px;border:1px solid var(--border);overflow:hidden;margin-top:0;}
.intro-strip-head{background:var(--navy);padding:20px 28px;display:flex;align-items:center;gap:14px;}
.intro-strip-head h2{font-family:'Fraunces',serif;font-size:22px;color:#fff;font-weight:600;}
.intro-strip-head p{font-size:13.5px;color:rgba(255,255,255,.75);margin-top:3px;}
.res-grid{display:grid;grid-template-columns:repeat(2,1fr);gap:1px;background:var(--border);}
.res-item{background:#fff;padding:14px 20px;display:flex;align-items:center;gap:12px;transition:.18s;}
.res-item:hover{background:var(--blue-xl);}
.res-ico{width:34px;height:34px;border-radius:8px;background:var(--blue-xl);display:flex;align-items:center;justify-content:center;font-size:16px;flex-shrink:0;}
.res-info{flex:1;min-width:0;}
.res-name{font-size:14px;font-weight:600;color:var(--navy);}
.res-note{font-size:12px;color:var(--muted);margin-top:1px;}
.res-action{flex-shrink:0;}
.res-action a{font-size:12px;font-weight:600;color:var(--blue);padding:5px 12px;border-radius:6px;border:1px solid var(--blue-l);transition:.18s;}
.res-action a:hover{background:var(--blue);color:#fff;}
.res-action .tbd{color:var(--amber);border-color:#FDE68A;background:var(--amber-l);pointer-events:none;font-size:12px;font-weight:600;padding:5px 10px;border-radius:6px;border:1px solid;}
.res-action .upd{color:var(--opt);border-color:#99F6E4;background:var(--opt-l);font-size:12px;font-weight:600;padding:5px 10px;border-radius:6px;border:1px solid;}

/* ── OBJECTIVES ── */
.obj-grid{display:grid;grid-template-columns:repeat(2,1fr);gap:14px;margin-top:0;}
.obj{background:#fff;border-radius:var(--r);padding:20px;display:flex;gap:14px;border:1px solid var(--border);box-shadow:var(--sh);transition:.2s;}
.obj:hover{box-shadow:var(--sh2);}
.obj-icon{width:40px;height:40px;border-radius:10px;background:var(--blue-xl);display:flex;align-items:center;justify-content:center;font-size:20px;flex-shrink:0;}
.obj-body strong{display:block;font-size:14px;font-weight:700;color:var(--navy);margin-bottom:3px;}
.obj-body p{font-size:13.5px;color:var(--slate);line-height:1.5;}

/* ── FRAMEWORK BLOCK ── */
.fw-block{background:#fff;border:2px dashed var(--blue-l);border-radius:12px;padding:48px 20px;text-align:center;margin-top:4px;}
.fw-block p{font-size:12.5px;font-weight:700;letter-spacing:.06em;text-transform:uppercase;color:var(--blue);margin-top:6px;}

/* ── PHASE INTRO BANNER ── */
.phase-banner{border-radius:12px;padding:20px 24px;margin-bottom:22px;display:flex;align-items:flex-start;gap:16px;}
.pb-org{background:#EFF6FF;border:1px solid #BFDBFE;}
.pb-1{background:#F0FDF4;border:1px solid #BBF7D0;}
.pb-2{background:#FAF5FF;border:1px solid #DDD6FE;}
.pb-3{background:#FFF7ED;border:1px solid #FED7AA;}
.pb-imp{background:#F0FDFA;border:1px solid #99F6E4;}
.pb-icon{font-size:32px;flex-shrink:0;}
.pb-head{font-family:'Fraunces',serif;font-size:20px;font-weight:600;margin-bottom:4px;}
.pb-org .pb-head{color:#1E40AF;}
.pb-1 .pb-head{color:#166534;}
.pb-2 .pb-head{color:#6B21A8;}
.pb-3 .pb-head{color:#C2410C;}
.pb-imp .pb-head{color:#115E59;}
.pb-desc{font-size:13.5px;color:var(--slate);line-height:1.55;}

/* ── GETTING STARTED CALLOUT ── */
.start-box{background:linear-gradient(135deg,#1C3F6E,#2563A8);border-radius:14px;padding:28px 32px;margin-bottom:32px;display:flex;gap:24px;align-items:center;flex-wrap:wrap;}
.start-box .sb-text h3{font-family:'Fraunces',serif;font-size:22px;font-weight:600;color:#fff;margin-bottom:6px;}
.start-box .sb-text p{font-size:14px;color:rgba(255,255,255,.82);line-height:1.6;max-width:580px;}
.start-steps{display:flex;flex-direction:column;gap:8px;margin-top:12px;}
.start-step{display:flex;align-items:flex-start;gap:10px;font-size:13.5px;color:rgba(255,255,255,.88);}
.step-num{width:22px;height:22px;border-radius:50%;background:rgba(255,255,255,.2);display:flex;align-items:center;justify-content:center;font-size:11px;font-weight:700;flex-shrink:0;color:#fff;}
.start-box .sb-cta{display:flex;flex-direction:column;gap:8px;flex-shrink:0;}
.cta-btn{padding:10px 22px;border-radius:8px;font-size:13.5px;font-weight:700;cursor:pointer;border:none;transition:.18s;white-space:nowrap;}
.cta-primary{background:#fff;color:var(--navy);}
.cta-primary:hover{background:#EBF4FC;color:var(--blue);}
.cta-secondary{background:rgba(255,255,255,.12);color:#fff;border:1.5px solid rgba(255,255,255,.3);}

/* ── BACK TO TOP ── */
#btt{position:fixed;bottom:24px;right:24px;width:42px;height:42px;border-radius:50%;background:var(--navy);color:#fff;display:flex;align-items:center;justify-content:center;box-shadow:var(--sh2);cursor:pointer;opacity:0;transition:.3s;z-index:999;font-size:16px;border:none;}
#btt.show{opacity:1;}
#btt:hover{background:var(--blue);transform:translateY(-2px);}

/* ── FOOTER ── */
footer{background:var(--navy);color:rgba(255,255,255,.5);text-align:center;padding:22px;font-size:13px;}

/* ── RESP ── */
@media(max-width:960px){.cards{grid-template-columns:repeat(2,1fr);}.obj-grid{grid-template-columns:1fr;}.res-grid{grid-template-columns:1fr;}}
@media(max-width:640px){.cards{grid-template-columns:1fr;}.hero{padding:36px 20px 28px;}.wrap{padding:0 16px 60px;}.ex-nav,.ex-search{display:none;}.ptab{min-width:80px;font-size:11px;}.phase-nav{top:50px;}}
</style>
</head>
<body>

<div class="proto">⚠ PROTOTYPE — Not the live page. <span>Gray buttons = link not yet added · Dashed border = resource in development · Yellow = update needed before publishing</span></div>

<header class="ex-header">
  <div class="ex-brand"><div class="g">g</div>Goodwill Exchange</div>
  <nav class="ex-nav">
    <a href="#">Home</a>
    <a href="#">Resources</a>
    <a href="#">Networking and Professional Development</a>
    <a href="#">Goodwill Priorities</a>
    <a href="#">Gateway Data</a>
 <a href="#">Brandfolder</a>
 <a href="#">Goodwill Academy eLearning</a>
  </nav>
  <div class="ex-search"><svg width="13" height="13" fill="none" stroke="rgba(255,255,255,.5)" stroke-width="2" viewBox="0 0 24 24"><circle cx="11" cy="11" r="8"/><path d="m21 21-4.35-4.35"/></svg><input placeholder="Search Exchange…"></div>
</header>

<!-- HERO -->
<div class="hero">
  <div class="hero-inner">
    <div class="hero-crumb">Goodwill® Exchange → Resources → Mission Resources→ <span>Opportunity Accelerator</span></div>
    <h1>Goodwill Opportunity<br><em>Accelerator</em>®</h1>
    <p class="hero-sub">Is a step-by-step approach to pairing support services people need with career training to help them build a career that lasts. </p>
    <div class="hero-orientation">
      <strong>📍 How to use this page</strong>
      This is your complete resource hub for adopting and implementing the OA. <b>New to OA?</b> Start with the Intro Resources. <b>Already implementing?</b> Jump to your current phase using the tabs below to find the tools and guidance you need.
    </div>
    <div class="hero-meta">
      <a href="https://sandra-smart.github.io/OA-Service-Delivery-Areas/" class="hero-badge" target="_blank">📋 21 Service Areas</a>
      <a class="hero-badge">🏅 Two Adoption Levels (Link TBD)</a>
    </div>
  </div>
</div>

<div class="wrap">

  <!-- GETTING STARTED BOX -->
  <div class="start-box" style="margin-top:36px;">
    <div class="sb-text">
      <h3>Where are you in your OA journey?</h3>
      <p>The OA has two adoption levels. Use the filter on each section to see what applies to you.</p>
      <div class="start-steps">
        <div class="start-step"><div class="step-num">1</div><span><strong style="color:#fff">OA Gold</strong> — Core adoption. You deliver fundamental OA services with flexibility in tools and delivery methods. Great starting point.</span></div>
        <div class="start-step"><div class="step-num">2</div><span><strong style="color:#fff">OA Platinum</strong> — Full adoption using specific evidence-based tools (Northstar, ART, Skills to Succeed) for maximum participant outcomes.</span></div>
      </div>
    </div>
    <div class="sb-cta">
      <button class="cta-btn cta-secondary" onclick="switchTab('org')">Jump to Org Prep →</button>
<button class="cta-btn cta-secondary" onclick="switchTab('p1')">Jump to Assess and Plan →</button>
<button class="cta-btn cta-secondary" onclick="switchTab('p2')">Jump to Equip and Connect →</button>
<button class="cta-btn cta-secondary" onclick="switchTab('p3')">Jump to Launch and Evaluate →</button>
    </div>
  </div>

<!-- GETTING STARTED BOX -->
  <div class="start-box" style="margin-top:36px;">
    <div class="sb-text">
      <h3>New to OA?</h3>
                </div>
    <div class="sb-cta">
      <button class="cta-btn cta-primary" onclick="document.getElementById('intro').scrollIntoView({behavior:'smooth'})">Start with Intro Resources</button>
    </div>
  </div>


  <!-- OBJECTIVES -->
  <div class="sec-head">
    <div class="sec-label">About the OA</div>
    <h2>Objectives</h2>
  </div>
  <p class="sec-desc">The Opportunity Accelerator is designed to accomplish four objectives.</p>
  <div class="obj-grid">
    <div class="obj"><div class="obj-icon">🎯</div><div class="obj-body"><strong>Equip Job Seekers</strong><p>Provide access to resources needed to obtain employment, advance careers, and experience economic mobility.</p></div></div>
    <div class="obj"><div class="obj-icon">🤝</div><div class="obj-body"><strong>Engage Teams & Partners</strong><p>Connect Goodwill team members and partners with best-in-class resources to enhance workforce development services.</p></div></div>
    <div class="obj"><div class="obj-icon">🌐</div><div class="obj-body"><strong>Connect Communities</strong><p>Collaborate with national partners to connect Goodwill members and their communities to resources and support.</p></div></div>
    <div class="obj"><div class="obj-icon">📣</div><div class="obj-body"><strong>Advocate & Promote</strong><p>Engage in advocacy and public relations to educate communities and promote the success of the OA model.</p></div></div>
  </div>

  <!-- FRAMEWORK -->
  <div class="sec-head"><div class="sec-label">Visual Reference</div><h2>OA Framework</h2></div>
  <p class="sec-desc">The OA organizes service delivery across Organizational Prep, three delivery phases, and ongoing impact evaluation.</p>
  <div class="fw-block">
    <div style="font-size:40px">🖼</div>
    <p>[INSERT OA FRAMEWORK IMAGE HERE]</p>
      </div>

  <!-- INTRO RESOURCES -->
  <div id="intro" style="margin-top:52px;">
    <div class="sec-head" style="margin-top:0;">
      <div class="sec-label">Start Here</div>
      <h2>Introductory OA Resources</h2>
    </div>
    <p class="sec-desc">New to the Opportunity Accelerator? These resources build your foundation before diving into phase-by-phase tools.</p>
    <div class="intro-strip">
      <div class="intro-strip-head">
        <div>
          <h2>📚 Core Resources</h2>
          <p>Foundational materials — start with the Introduction course if you're brand new.</p>
        </div>
      </div>
      <div class="res-grid">
        <div class="res-item"><div class="res-ico">🎓</div><div class="res-info"><div class="res-name">Introduction to the Opportunity Accelerator</div><div class="res-note">Free course on Rockstar Learning — start here</div></div><div class="res-action"><a href="https://goodwill.rockstarlearning.com/course/introduction-to-the-opportunity-accelerator-course" target="_blank">Open →</a></div></div>
        <div class="res-item"><div class="res-ico">🗺</div><div class="res-info"><div class="res-name">Journey Maps & Personas for Goodwill Employees</div><div class="res-note">Understand the participant experience across the OA journey</div></div><div class="res-action"><span class="tbd">Link TBD</span></div></div>
        <div class="res-item"><div class="res-ico">✅</div><div class="res-info"><div class="res-name">OA Readiness Assessment</div><div class="res-note">Assess your organization's readiness before beginning adoption</div></div><div class="res-action"><span class="upd">Update Needed</span></div></div>
        <div class="res-item"><div class="res-ico">📐</div><div class="res-info"><div class="res-name">OA Logic Model</div><div class="res-note">The theory of change underlying the OA framework</div></div><div class="res-action"><a href="https://exchange.goodwill.org/documents/d/goodwill/oa-logic-model?download=true" target="_blank">Download →</a></div></div>
        <div class="res-item"><div class="res-ico">📊</div><div class="res-info"><div class="res-name">OA Fidelity Index</div><div class="res-note">Measure how closely your implementation aligns with the model</div></div><div class="res-action"><span class="upd">Update Needed</span></div></div>
        <div class="res-item"><div class="res-ico">📖</div><div class="res-info"><div class="res-name">Mission Advancement Playbook</div><div class="res-note">Comprehensive guide for mission strategy and advancement</div></div><div class="res-action"><a href="https://exchange.goodwill.org/mission-playbook" target="_blank">Open →</a></div></div>
        <div class="res-item"><div class="res-ico">📚</div><div class="res-info"><div class="res-name">Goodwill OA Guides</div><div class="res-note">Collection of guides for implementing OA practices</div></div><div class="res-action"><a href="https://exchange.goodwill.org/opportunity-accelerator-guides" target="_blank">Open →</a></div></div>
        <div class="res-item"><div class="res-ico">🔗</div><div class="res-info"><div class="res-name">OA Key Service Delivery Areas</div><div class="res-note">Interactive overview of all 21 OA service areas</div></div><div class="res-action"><a href="https://sandra-smart.github.io/OA-Service-Delivery-Areas/" target="_blank">Open →</a></div></div>
      </div>
    </div>
  </div>

  <!-- PHASE NAV -->
  <div class="phase-nav">
    <div class="phase-nav-inner">
      <div class="ptab on" onclick="switchTab('org')"><span class="ico">🏗</span>Org Prep</div>
      <div class="ptab" onclick="switchTab('p1')"><span class="n">1</span>Assess & Plan</div>
      <div class="ptab" onclick="switchTab('p2')"><span class="n">2</span>Equip & Connect</div>
      <div class="ptab" onclick="switchTab('p3')"><span class="n">3</span>Launch & Evaluate</div>
    
    </div>
  </div>

  <!-- TIER BAR (shown once, controls all panels) -->
  <div class="tier-bar" style="margin-top:16px;" id="tierbar">
    <span class="lbl">Show resources for:</span>
    <div class="tier-btn ess on" onclick="setTier('ess')">🔵 OA Essentials</div>
    <div class="tier-btn hf" onclick="setTier('hf')">🟣 OA High Fidelity</div>
    <div class="tier-btn" style="background:var(--bg);color:var(--muted);border-color:var(--border);" onclick="setTier('all')">All</div>
    <span class="tier-info" id="tier-hint">Showing core adoption requirements</span>
  </div>

  <!-- ===== PANEL: ORG PREP ===== -->
  <div class="panel on" id="panel-org">
    <div class="phase-banner pb-org">
      <div class="pb-icon">🏗</div>
      <div><div class="pb-head">Organizational Preparation</div><p class="pb-desc">Build your foundation before delivering OA services. Trained staff, aligned systems, and strong community and employer partnerships are what make everything else work. Use these tools to get your organization ready.</p></div>
    </div>
    <div class="cards">
      <div class="card" data-ess="required" data-hf="required">
        <div class="card-top"><div class="card-num">Org Prep · 1</div></div>
        <h3>Functionally Aligned Staffing Model</h3>
        <p class="desc">Organize your team into distinct functional roles: Career Navigators, Trainers, Business Engagement Staff, Mission Leaders, and Data Specialists — each owning a specific area of OA service delivery. This structure improves participant outcomes and scales your capacity.</p>
        <div class="card-tiers">
          <span class="tier-pill tp-ess">Essentials: Core functions covered</span>
          <span class="tier-pill tp-hf">High Fidelity: All 5 roles required</span>
        </div>
        <div class="card-footer">
          <a href="#" class="btn btn-tbd"><span class="status-dot"></span>Link TBD — Staffing Case Study</a>
        </div>
      </div>
      <div class="card" data-ess="required" data-hf="required">
        <div class="card-top"><div class="card-num">Org Prep · 2</div></div>
        <h3>Goodwill Career Coach & Navigator Certificate</h3>
        <p class="desc">Free professional certificate on Coursera created from Goodwill's 120 years of workforce expertise. Covers intensive, collaborative coaching methods to help clients identify and address employment barriers. Required for all navigators at High Fidelity.</p>
        <div class="card-tiers">
          <span class="tier-pill tp-ess">Essentials: 50% certified in Year 1</span>
          <span class="tier-pill tp-hf">High Fidelity: 100% certified in Year 1</span>
        </div>
        <div class="card-footer">
     
          <a href="#" class="btn btn-tbd"><span class="status-dot"></span>Link TBD — Smartsheet Request Form</a>
        </div>
      </div>
      <div class="card" data-ess="required" data-hf="required">
        <div class="card-top"><div class="card-num">Org Prep · 3</div></div>
        <h3>OA Fellows Program</h3>
        <p class="desc">Leadership development that creates internal OA ambassadors. Fellows are trained to understand the framework, equip peers across your organization, and drive adoption from the inside. Organizations with Fellows consistently move through adoption faster.</p>
        <div class="card-tiers">
          <span class="tier-pill tp-ess">Essentials: At least 1 Fellow</span>
          <span class="tier-pill tp-hf">High Fidelity: At least 2 Fellows</span>
        </div>
        <div class="card-footer">
         
          <a href="#" class="btn btn-tbd"><span class="status-dot"></span>Link TBD — Fellows Application</a>
        </div>
      </div>
      <div class="card" data-ess="required" data-hf="required">
        <div class="card-top"><div class="card-num">Org Prep · 4</div></div>
        <h3>Referral & Wraparound Network Integration</h3>
        <p class="desc">Build community partnerships and use technology to connect participants to support services. At High Fidelity, this means Automated Referral Technology (ART) platforms like Unite Us, WellSky, or FindHelp — enabling electronic warm hand-offs and closed-loop tracking.</p>
        <div class="card-tiers">
          <span class="tier-pill tp-ess">Essentials: Referral process + partnerships</span>
          <span class="tier-pill tp-hf">High Fidelity: ART platform required</span>
        </div>
        <div class="card-footer">

          <a href="#" class="btn btn-tbd"><span class="status-dot"></span>Link TBD — ART Tools on Exchange</a>
        </div>
      </div>
      <div class="card" data-ess="required" data-hf="required">
        <div class="card-top"><div class="card-num">Org Prep · 5</div></div>
        <h3>Employer Partnership Planning & Outreach</h3>
        <p class="desc">Engage employers strategically to create job placement opportunities and co-created training programs. At High Fidelity, use labor market data (Chmura, DOL) to target occupations paying living wages and build true co-creation partnerships with dedicated Business Engagement Staff.</p>
        <div class="card-tiers">
          <span class="tier-pill tp-ess">Essentials: Local employer referral partnerships</span>
          <span class="tier-pill tp-hf">High Fidelity: LMI-informed, co-created training</span>
        </div>
        <div class="card-footer">
       
          <a href="#" class="btn btn-tbd"><span class="status-dot"></span>Link TBD — CaseWorthy on Exchange</a>
        </div>
      </div>
      <div class="card" data-ess="required" data-hf="required">
        <div class="card-top"><div class="card-num">Org Prep · 6</div></div>
        <h3>Evaluating Impact & Metrics</h3>
        <p class="desc">Collect and analyze data to measure KPIs and participant feedback throughout the journey. Monthly data submission to GII is required at both levels. At High Fidelity, use CaseWorthy or equivalent with an extended data set and 365-day post-placement follow-up.</p>
        <div class="card-tiers">
          <span class="tier-pill tp-ess">Essentials: Short KPI list, 180-day follow-up</span>
          <span class="tier-pill tp-hf">High Fidelity: Full KPI list, 365-day follow-up</span>
        </div>
        <div class="card-footer">

          <a href="#" class="btn btn-tbd"><span class="status-dot"></span>Link TBD — CaseWorthy on Exchange</a>
        </div>
      </div>
    </div>
  </div>

  <!-- ===== PANEL: PHASE 1 ===== -->
  <div class="panel" id="panel-p1">
    <div class="phase-banner pb-1">
      <div class="pb-icon">🎯</div>
      <div><div class="pb-head">Phase 1 — Assess & Plan</div><p class="pb-desc">Recruit job seekers, conduct intake, run assessments, and build personalized career and financial plans. The goal here is understanding each participant deeply enough to create a plan that actually works for them.</p></div>
    </div>
    <div class="cards">
      <div class="card" data-ess="na" data-hf="required">
        <div class="card-top"><div class="card-num">Phase 1 · 7</div></div>
        <h3>Outreach & Recruitment</h3>
        <p class="desc">Proactively reach the people who need OA services most — especially those facing the greatest employment barriers who may not know where to turn. At High Fidelity, ART platforms and referral partners create systematic pathways from community touchpoints directly into OA services.</p>
        <div class="card-tiers">
          <span class="tier-pill tp-ess">Essentials: Not required</span>
          <span class="tier-pill tp-hf">High Fidelity: ART + referral partners</span>
        </div>
        <div class="card-footer">
         
          <a href="#" class="btn btn-tbd"><span class="status-dot"></span>Link TBD — ART Tools on Exchange</a>
        </div>
      </div>
      <div class="card" data-ess="required" data-hf="required">
        <div class="card-top"><div class="card-num">Phase 1 · 8</div></div>
        <h3>Registration & Intake</h3>
        <p class="desc">The critical first interaction that sets the tone for the entire participant journey. Collect demographic, work history, and eligibility information in a way that builds trust. Intake data directly informs the ICFP and every service decision that follows.</p>
        <div class="card-tiers">
          <span class="tier-pill tp-ess">Essentials: Short KPI list</span>
          <span class="tier-pill tp-hf">High Fidelity: Long KPI list</span>
        </div>
        <div class="card-footer">
         
          <a href="#" class="btn btn-tbd"><span class="status-dot"></span>Link TBD — Updated Pre-Enrollment Form</a>
        </div>
      </div>
      <div class="card" data-ess="required" data-hf="required">
        <div class="card-top"><div class="card-num">Phase 1 · 9a</div></div>
        <h3>Needs Assessment</h3>
        <p class="desc">Holistic evaluation of barriers across financial capability, healthcare, food security, housing, transportation, legal issues, and family care. Required at both levels for 100% of participants — this is the foundation for coordinating wraparound services.</p>
        <div class="card-tiers">
          <span class="tier-pill tp-ess">Essentials: 100% of participants</span>
          <span class="tier-pill tp-hf">High Fidelity: 100% of participants</span>
          <span class="tier-pill tp-opt">Tool choice flexible</span>
        </div>
        <div class="card-footer">
        
          <a href="#" class="btn btn-tbd"><span class="status-dot"></span>Link TBD — Recommended Assessment Tool</a>
        </div>
      </div>
      <div class="card" data-ess="required" data-hf="required">
        <div class="card-top"><div class="card-num">Phase 1 · 9b</div></div>
        <h3>Basic Education Assessment</h3>
        <p class="desc">Measure reading, writing, math, and language proficiency using validated tools (TABE, CASAS, TOEFL, or similar). Required for participants without a diploma who are enrolling in occupational training — prevents placement in programs where literacy requirements exceed current skill levels.</p>
        <div class="card-tiers">
          <span class="tier-pill tp-ess">Essentials: For non-diploma enrollees</span>
          <span class="tier-pill tp-hf">High Fidelity: For non-diploma enrollees</span>
        </div>
        <div class="card-footer">
         
          <a href="#" class="btn btn-tbd"><span class="status-dot"></span>Link TBD — Recommended Tool</a>
        </div>
      </div>
      <div class="card" data-ess="required" data-hf="required">
        <div class="card-top"><div class="card-num">Phase 1 · 9c</div></div>
        <h3>Career Readiness & Interest Assessment</h3>
        <p class="desc">Evaluate work-related interests, soft skills, and career readiness using validated tools like JOFI or the O*NET Interest Profiler. Helps Career Navigators match participants to career pathways that align with both their interests and the local labor market.</p>
        <div class="card-tiers">
          <span class="tier-pill tp-ess">Essentials: Valid assessment required</span>
          <span class="tier-pill tp-hf">High Fidelity: Valid assessment required</span>
          <span class="tier-pill tp-opt">JOFI or O*NET recommended</span>
        </div>
        <div class="card-footer">
        
          <a href="#" class="btn btn-live" target="_blank">O*NET Interest Profiler →</a>
        </div>
      </div>
      <div class="card" data-ess="required" data-hf="required">
        <div class="card-top"><div class="card-num">Phase 1 · 9d</div></div>
        <h3>Digital Skills Assessment</h3>
        <p class="desc">Measure digital literacy baseline using Northstar (required at High Fidelity) or another valid tool. Results guide decisions about which level of digital skills training to provide — from basic computer use through industry-specific certifications.</p>
        <div class="card-tiers">
          <span class="tier-pill tp-ess">Essentials: Any valid assessment</span>
          <span class="tier-pill tp-hf">High Fidelity: Northstar required</span>
        </div>
        <div class="card-footer">
        
          <a href="https://www.digitalliteracyassessment.org/" class="btn btn-live" target="_blank">Northstar Assessment →</a>
        </div>
      </div>
      <div class="card" data-ess="required" data-hf="required">
        <div class="card-top"><div class="card-num">Phase 1 · 10</div></div>
        <h3>Orientation</h3>
        <p class="desc">The official start of the participant's OA journey. Every participant must complete orientation before enrollment at both levels. Participants learn what services are available, what's expected of them, and how to navigate their pathway. Informed commitment — not passive sign-up.</p>
        <div class="card-tiers">
          <span class="tier-pill tp-ess">Essentials: 100% of participants</span>
          <span class="tier-pill tp-hf">High Fidelity: 100% of participants</span>
          <span class="tier-pill tp-opt">Group or individual, virtual or in-person</span>
        </div>
        <div class="card-footer">
         
          <a class="btn btn-dev">🔧 Resource in development</a>
        </div>
      </div>
      <div class="card" data-ess="required" data-hf="required">
        <div class="card-top"><div class="card-num">Phase 1 · 11</div></div>
        <h3>Individual Career & Financial Plan (ICFP)</h3>
        <p class="desc">The personalized roadmap where everything comes together. Every participant completes an ICFP with SMART goals covering their career pathway, financial stability, and self-sufficiency. This living document guides every service decision and is updated as participants progress.</p>
        <div class="card-tiers">
          <span class="tier-pill tp-ess">Essentials: 100% of participants</span>
          <span class="tier-pill tp-hf">High Fidelity: 100% of participants</span>
          <span class="tier-pill tp-opt">GII template or equivalent</span>
        </div>
        <div class="card-footer">

          <a href="#" class="btn btn-tbd"><span class="status-dot"></span>Link TBD — Updated ICFP Form</a>
        </div>
      </div>
    </div>
  </div>

  <!-- ===== PANEL: PHASE 2 ===== -->
  <div class="panel" id="panel-p2">
    <div class="phase-banner pb-2">
      <div class="pb-icon">🛠</div>
      <div><div class="pb-head">Phase 2 — Equip & Connect</div><p class="pb-desc">Implement skills training, provide holistic wraparound support, and prepare participants for employment. This phase is about building the competencies — and removing the barriers — that make sustainable employment possible.</p></div>
    </div>
    <div class="cards">
      <div class="card" data-ess="required" data-hf="required">
        <div class="card-top"><div class="card-num">Phase 2 · 12</div></div>
        <h3>Wraparound Supports</h3>
        <p class="desc">Address the non-employment barriers that derail progress: housing, transportation, childcare, healthcare, food security, legal issues, and more. Participants cannot focus on career development when they're in crisis. At High Fidelity, ART platforms enable electronic referrals and closed-loop tracking with partner organizations.</p>
        <div class="card-tiers">
          <span class="tier-pill tp-ess">Essentials: Resources aligned with individual needs</span>
          <span class="tier-pill tp-hf">High Fidelity: ART-coordinated referrals</span>
        </div>
        <div class="card-footer">
        
          <a href="#" class="btn btn-tbd"><span class="status-dot"></span>Link TBD — ART Tools on Exchange</a>
        </div>
      </div>
      <div class="card" data-ess="required" data-hf="required">
        <div class="card-top"><div class="card-num">Phase 2 · 13</div></div>
        <h3>Financial Education</h3>
        <p class="desc">Earning income doesn't automatically create economic stability. Financial education covers budgeting, banking, credit building, debt management, savings, tax prep, benefits enrollment, and navigating benefit cliffs. Required at both levels for 100% of participants — offered and integrated with career planning in the ICFP.</p>
        <div class="card-tiers">
          <span class="tier-pill tp-ess">Essentials: Must offer to 100%</span>
          <span class="tier-pill tp-hf">High Fidelity: Must offer to 100%</span>
        </div>
        <div class="card-footer">

          <a class="btn btn-dev">🔧 Resource in development</a>
        </div>
      </div>
      <div class="card" data-ess="required" data-hf="required">
        <div class="card-top"><div class="card-num">Phase 2 · 14</div></div>
        <h3>Foundational Skills Training</h3>
        <p class="desc">Build the workplace competencies employers identify as critical: communication, teamwork, time management, professionalism, and problem-solving. Technical skills get people hired — foundational skills determine whether they keep jobs and advance. At High Fidelity, at least one Skills to Succeed Academy course is required.</p>
        <div class="card-tiers">
          <span class="tier-pill tp-ess">Essentials: Must offer foundational training</span>
          <span class="tier-pill tp-hf">High Fidelity: Skills to Succeed Academy required</span>
        </div>
        <div class="card-footer">
          
          <a href="#" class="btn btn-tbd"><span class="status-dot"></span>Link TBD — Skills to Succeed Academy</a>
        </div>
      </div>
      <div class="card" data-ess="required" data-hf="required">
        <div class="card-top"><div class="card-num">Phase 2 · 15</div></div>
        <h3>Digital Skills Training</h3>
        <p class="desc">Digital literacy is foundational to virtually every career pathway today. Training follows the Goodwill Digital Career Accelerator (GDCA) framework across five progressive levels — from basic computer use (Level 2) through mid-career credentials (Level 5). Northstar Online Learning is recommended for High Fidelity.</p>
        <div class="card-tiers">
          <span class="tier-pill tp-ess">Essentials: GDCA framework, needs-based</span>
          <span class="tier-pill tp-hf">High Fidelity: GDCA + Northstar Online Learning</span>
        </div>
        <div class="card-footer">
       
          <a href="#" class="btn btn-tbd"><span class="status-dot"></span>Link TBD — Northstar Online Learning (NSOL)</a>
        </div>
      </div>
      <div class="card" data-ess="required" data-hf="required">
        <div class="card-top"><div class="card-num">Phase 2 · 16</div></div>
        <h3>Occupation-Specific Skills Training</h3>
        <p class="desc">Technical training leading to industry-recognized credentials in fields with real local demand. At High Fidelity, training must be co-created with employer input and target occupations paying living wages (per the MIT Living Wage Calculator). Partners include GCTA, Cisco, IBM, Cengage, Coursera, and more.</p>
        <div class="card-tiers">
          <span class="tier-pill tp-ess">Essentials: Aligned with local labor market</span>
          <span class="tier-pill tp-hf">High Fidelity: Living wage focus + employer co-creation</span>
        </div>
        <div class="card-footer">
        
          <a href="#" class="btn btn-tbd"><span class="status-dot"></span>Link TBD — GCTA, Cisco, IBM, Coursera & more</a>
        </div>
      </div>
      <div class="card" data-ess="na" data-hf="required">
        <div class="card-top"><div class="card-num">Phase 2 · 17</div></div>
        <h3>Career Exploration Opportunities</h3>
        <p class="desc">Hands-on experiences — job shadowing, OJT, internships, apprenticeships, VR simulations, and more — that help participants make informed career decisions before committing to training. Participants who explore before training have higher completion rates and better retention because they know what they're signing up for.</p>
        <div class="card-tiers">
          <span class="tier-pill tp-ess">Essentials: Not required</span>
          <span class="tier-pill tp-hf">High Fidelity: Must offer career exploration</span>
          <span class="tier-pill tp-opt">WIOA, TANF, apprenticeships, subsidized employment</span>
        </div>
        <div class="card-footer">
        
          <a class="btn btn-dev">🔧 Resource in development</a>
        </div>
      </div>
      <div class="card" data-ess="required" data-hf="required">
        <div class="card-top"><div class="card-num">Phase 2 · 18</div></div>
        <h3>Job Search & Prep Assistance</h3>
        <p class="desc">All prior services converge here: résumé development, cover letters, interview preparation, online application navigation, professional presentation, disclosure coaching, and LinkedIn profiles. Required for 100% of participants at both levels. Career Navigators provide ongoing support through what can be a lengthy, emotionally challenging process.</p>
        <div class="card-tiers">
          <span class="tier-pill tp-ess">Essentials: Résumé + interview prep required</span>
          <span class="tier-pill tp-hf">High Fidelity: Résumé + interview prep required</span>
        </div>
        <div class="card-footer">
          
          <a class="btn btn-dev">🔧 Resource in development</a>
        </div>
      </div>
    </div>
  </div>

  <!-- ===== PANEL: PHASE 3 ===== -->
  <div class="panel" id="panel-p3">
    <div class="phase-banner pb-3">
      <div class="pb-icon">🚀</div>
      <div><div class="pb-head">Phase 3 — Launch & Evaluate</div><p class="pb-desc">Secure employment, support retention, and maintain long-term connection with alumni. Getting the job is the beginning, not the end — this phase is where sustainable economic mobility is built.</p></div>
    </div>
    <div class="cards">
      <div class="card" data-ess="required" data-hf="required">
        <div class="card-top"><div class="card-num">Phase 3 · 19</div></div>
        <h3>Job Placement Assistance</h3>
        <p class="desc">Engage employer partners to identify openings and place participants in jobs — not just any jobs, but positions aligned with their training, career goals, and wage targets. At High Fidelity, placements must meet living wage thresholds per the MIT Living Wage Calculator for the participant's geographic area.</p>
        <div class="card-tiers">
          <span class="tier-pill tp-ess">Essentials: Must offer placement assistance</span>
          <span class="tier-pill tp-hf">High Fidelity: Living wage placements required</span>
        </div>
        <div class="card-footer">
          
          <a class="btn btn-dev">🔧 Resource in development</a>
        </div>
      </div>
      <div class="card" data-ess="required" data-hf="required">
        <div class="card-top"><div class="card-num">Phase 3 · 20</div></div>
        <h3>Retention Services & Follow-Up</h3>
        <p class="desc">The first 90–180 days of employment are the highest-risk period. Structured follow-up at set intervals enables Career Navigators to address emerging problems before they cause job loss. Services include crisis intervention, workplace coaching, benefits navigation, and financial stability support. High Fidelity extends follow-up through one full year.</p>
        <div class="card-tiers">
          <span class="tier-pill tp-ess">Essentials: Follow-up at 30/60/90/180 days</span>
          <span class="tier-pill tp-hf">High Fidelity: Follow-up through 365 days</span>
          <span class="tier-pill tp-opt">The Work Number for verification</span>
        </div>
        <div class="card-footer">
         
          <a class="btn btn-dev">🔧 Resource in development</a>
        </div>
      </div>
      <div class="card" data-ess="na" data-hf="required">
        <div class="card-top"><div class="card-num">Phase 3 · 21</div></div>
        <h3>Alumni Engagement</h3>
        <p class="desc">Transform program graduates into community partners. Alumni serve as mentors for current participants, employer ambassadors, storytellers for funders, and advocates in their communities. Required at High Fidelity (at least one engagement method). Alumni who give back expand your organizational capacity — and demonstrate OA's long-term transformative impact.</p>
        <div class="card-tiers">
          <span class="tier-pill tp-ess">Essentials: Not required</span>
          <span class="tier-pill tp-hf">High Fidelity: At least 1 engagement method</span>
          <span class="tier-pill tp-opt">Format and frequency flexible</span>
        </div>
        <div class="card-footer">
          
          <a class="btn btn-dev">🔧 Resource in development</a>
        </div>
      </div>
    </div>
  </div>

  <!-- ===== PANEL: IMPACT ===== -->
  <div class="panel" id="panel-imp">
    <div class="phase-banner pb-imp">
      <div class="pb-icon">📊</div>
      <div><div class="pb-head">Evaluating Impact</div><p class="pb-desc">Data collection and impact measurement runs throughout every phase — not just at the end. These resources support your organization in tracking participant outcomes, measuring program performance, and contributing to network-wide learning.</p></div>
    </div>
    <div class="cards">
      <div class="card" data-ess="required" data-hf="required">
        <div class="card-top"><div class="card-num">Impact</div></div>
        <h3>OA Fidelity Index</h3>
        <p class="desc">Measure how closely your OA implementation aligns with the model framework. Use this tool to identify gaps, celebrate progress, and plan next steps on your adoption journey — whether you're moving toward Essentials or High Fidelity.</p>
        <div class="card-footer">
          <a href="#" class="btn btn-tbd"><span class="status-dot"></span>Link TBD — Updated Fidelity Index</a>
        </div>
      </div>
      <div class="card" data-ess="required" data-hf="required">
        <div class="card-top"><div class="card-num">Impact</div></div>
        <h3>OA Adoption Criteria Document</h3>
        <p class="desc">Your complete roadmap for adoption. Contains all 21 criteria with Essentials and High Fidelity requirements, and guidance on moving from implementation to formal adoption. Return to this document repeatedly as you progress.</p>
        <div class="card-footer">
          <a href="#" class="btn btn-tbd"><span class="status-dot"></span>Link TBD — Adoption Criteria PDF</a>
        </div>
      </div>
      <div class="card" data-ess="required" data-hf="required">
        <div class="card-top"><div class="card-num">Impact</div></div>
        <h3>CaseWorthy Case Management</h3>
        <p class="desc">Required case management platform at OA High Fidelity. Captures the full list of OA KPIs, tracks participants across all service phases, and supports monthly data submission to GII. Contact GII for implementation support and configuration guidance.</p>
        <div class="card-footer">
          <a href="#" class="btn btn-tbd"><span class="status-dot"></span>Link TBD — CaseWorthy on Exchange</a>
        </div>
      </div>
      <div class="card" data-ess="required" data-hf="required">
        <div class="card-top"><div class="card-num">Impact</div></div>
        <h3>Standardized Participant Feedback</h3>
        <p class="desc">Collect participant feedback at four key moments: intake, goal completion, placement, and post-placement intervals. Participant voice ensures you're measuring what actually matters to the people you serve — not just what's easy to track.</p>
        <div class="card-footer">
          <a class="btn btn-dev">🔧 Resource in development</a>
        </div>
      </div>
    </div>
  </div>

</div><!-- end .wrap -->

<button id="btt" onclick="window.scrollTo({top:0,behavior:'smooth'})">↑</button>

<footer>Goodwill Industries International · Goodwill Exchange · Opportunity Accelerator · Prototype v2 — Not the live page</footer>

<script>
// Tab switching
function switchTab(id) {
  document.querySelectorAll('.ptab').forEach((t,i) => {
    const ids = ['org','p1','p2','p3','imp'];
    t.classList.toggle('on', ids[i] === id);
  });
  document.querySelectorAll('.panel').forEach(p => p.classList.toggle('on', p.id === 'panel-' + id));
  document.getElementById('tierbar').scrollIntoView({behavior:'smooth', block:'nearest'});
}

// Tier filter
let currentTier = 'ess';
function setTier(tier) {
  currentTier = tier;
  document.querySelectorAll('.tier-btn').forEach(b => b.classList.remove('on'));
  event.target.classList.add('on');
  const hints = {ess:'Showing core adoption requirements', hf:'Showing full High Fidelity requirements', all:'Showing all criteria'};
  document.getElementById('tier-hint').textContent = hints[tier];

  document.querySelectorAll('.card').forEach(card => {
    if (tier === 'all') { card.style.opacity = ''; card.style.pointerEvents = ''; return; }
    const val = card.dataset[tier];
    const fade = (val === 'na');
    card.style.opacity = fade ? '0.38' : '';
    card.style.pointerEvents = fade ? 'none' : '';
  });
}

// Back to top
window.addEventListener('scroll', () => {
  document.getElementById('btt').classList.toggle('show', window.scrollY > 300);
});
</script>
</body>
</html>
