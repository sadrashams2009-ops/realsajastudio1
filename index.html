<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width,initial-scale=1,viewport-fit=cover">
<meta name="theme-color" content="#0a0a0a">
<title>GTA Archive — History to Now</title>
<meta name="description" content="An unofficial, fan-made cinematic archive of the Grand Theft Auto series, from 1997 to now.">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Anton&family=Archivo:wght@800&family=Bowlby+One&family=Kaushan+Script&family=Yellowtail&family=Barlow+Condensed:wght@600;800&family=Chakra+Petch:wght@600;700&family=Inter:wght@300;400;500;600&family=Space+Mono:wght@700&family=Syncopate:wght@700&family=Unbounded:wght@400;700&display=swap" rel="stylesheet">

<style>
:root{
  --base:10,10,10; --accent:214,40,40; --accent2:235,235,235; --glow:214,40,40; --glass:255,255,255; --ink:240,240,236;
  --ease:cubic-bezier(.22,1,.36,1);
  --bw:64px; --gap:8px;
  --ui:'Inter',system-ui,-apple-system,'Segoe UI',Roboto,sans-serif;
}
*{box-sizing:border-box;margin:0;padding:0}
html,body{height:100%;overflow:hidden;overscroll-behavior:none;background:rgb(var(--base));color:rgb(var(--ink));font-family:var(--ui);-webkit-font-smoothing:antialiased;color-scheme:dark}
body{height:100dvh}
button{font:inherit;color:inherit;background:none;border:0;cursor:pointer}
a{color:inherit;text-decoration:none}
:focus-visible{outline:2px solid rgb(var(--accent));outline-offset:3px}
.sr{position:absolute;width:1px;height:1px;overflow:hidden;clip:rect(0 0 0 0);white-space:nowrap}

/* ---------- Liquid glass ---------- */
.glass{
  position:relative;
  background:
    linear-gradient(135deg,rgba(255,255,255,.17) 0%,rgba(255,255,255,.04) 42%,rgba(255,255,255,.02) 62%,rgba(255,255,255,.1) 100%),
    rgba(var(--glass),.07);
  -webkit-backdrop-filter:blur(26px) saturate(1.9) brightness(1.06);
  backdrop-filter:blur(26px) saturate(1.9) brightness(1.06);
  box-shadow:
    inset 0 1px 0 rgba(255,255,255,.55),
    inset 0 -1px 0 rgba(255,255,255,.1),
    inset 1px 0 0 rgba(255,255,255,.18),
    inset 0 0 26px 2px rgba(255,255,255,.07),
    0 1px 2px rgba(0,0,0,.25),
    0 26px 60px -20px rgba(0,0,0,.6),
    0 0 70px -18px rgba(var(--glow),.55);
  transition:box-shadow .9s var(--ease);
}
.glass::before{ /* specular that follows the pointer */
  content:"";position:absolute;inset:0;border-radius:inherit;pointer-events:none;
  background:radial-gradient(240px circle at var(--sx,30%) var(--sy,0%),rgba(255,255,255,.32),transparent 62%);
  mix-blend-mode:soft-light;
}
.glass::after{ /* rim light */
  content:"";position:absolute;inset:0;border-radius:inherit;padding:1px;pointer-events:none;
  background:linear-gradient(140deg,rgba(255,255,255,.75),rgba(255,255,255,0) 30%,rgba(255,255,255,0) 68%,rgba(255,255,255,.4));
  -webkit-mask:linear-gradient(#000 0 0) content-box,linear-gradient(#000 0 0);
  -webkit-mask-composite:xor;mask-composite:exclude;
}
@supports not ((backdrop-filter:blur(1px)) or (-webkit-backdrop-filter:blur(1px))){
  .glass{background:rgba(20,20,24,.72)}
}

/* ---------- Stage ---------- */
.stage,.layer{position:fixed;inset:0;pointer-events:none}
.stage{overflow:hidden;background:rgb(var(--base))}
.scene{position:absolute;inset:-4%;will-change:transform,opacity,filter;visibility:hidden}
.plate{position:absolute;inset:0;overflow:hidden}
.fallback{
  position:absolute;inset:0;
  background:
    radial-gradient(62% 52% at 72% 28%,rgba(var(--fa),.5),transparent 70%),
    radial-gradient(70% 60% at 18% 82%,rgba(var(--fb),.4),transparent 70%),
    linear-gradient(180deg,rgba(var(--fb),.22),rgb(var(--fbase)));
}
.shot{
  position:absolute;inset:0;width:100%;height:100%;object-fit:cover;
  opacity:0;transform:scale(1.07);
  filter:var(--grade) blur(8px);
  transition:opacity 1.5s var(--ease),filter 1.5s var(--ease);
  user-select:none;-webkit-user-drag:none;
}
.shot.on{opacity:1;filter:var(--grade) blur(0px)}
.shot.on,.shot.out{animation:drift 20s var(--ease) both;will-change:transform,opacity,filter}
@keyframes drift{from{transform:scale(1.07) translate3d(0,0,0)}to{transform:scale(1) translate3d(var(--dx,-1%),var(--dy,-.6%),0)}}

.wash{background:rgb(var(--accent2));mix-blend-mode:soft-light;opacity:0}
.haze{
  inset:auto -10% -8% -10%;height:62%;
  background:linear-gradient(to top,rgba(var(--glass),.42),rgba(var(--glow),.16) 45%,transparent);
  filter:blur(34px);opacity:0;animation:haze 24s ease-in-out infinite alternate;
}
@keyframes haze{from{transform:translate3d(-3%,0,0)}to{transform:translate3d(3%,-2%,0)}}
#fx{position:absolute;inset:0;width:100%;height:100%}
.light{background:radial-gradient(560px circle at var(--lx,60%) var(--ly,30%),rgba(var(--glow),.3),transparent 66%);mix-blend-mode:screen}
.tint{
  background:
    linear-gradient(to top,rgba(var(--base),.9) 0,rgba(var(--base),.5) 22%,rgba(var(--base),0) 52%),
    linear-gradient(to bottom,rgba(var(--base),.55),rgba(var(--base),0) 20%),
    linear-gradient(to right,rgba(var(--base),.5),rgba(var(--base),0) 46%);
}
.vignette{background:radial-gradient(120% 95% at 50% 46%,transparent 42%,rgba(0,0,0,.72) 100%);opacity:.7}
.grain{
  inset:-50%;width:200%;height:200%;mix-blend-mode:overlay;opacity:.1;animation:grain .9s steps(6) infinite;
  background-image:url("data:image/svg+xml;utf8,<svg xmlns='http://www.w3.org/2000/svg' width='220' height='220'><filter id='n'><feTurbulence type='fractalNoise' baseFrequency='.85' numOctaves='2' stitchTiles='stitch'/><feColorMatrix values='0 0 0 0 1  0 0 0 0 1  0 0 0 0 1  0 0 0 .6 0'/></filter><rect width='100%' height='100%' filter='url(%23n)'/></svg>");
}
@keyframes grain{0%{transform:translate(0,0)}20%{transform:translate(-3%,2%)}40%{transform:translate(2%,-3%)}60%{transform:translate(-2%,-1%)}80%{transform:translate(3%,3%)}100%{transform:translate(0,0)}}
.palms{position:fixed;inset:auto 0 0 0;height:72vh;pointer-events:none;opacity:0;filter:blur(1.6px)}
.palms svg{position:absolute;bottom:-4vh;fill:#05020a;color:#05020a;height:100%;width:auto;transform-origin:50% 100%;animation:sway 9s ease-in-out infinite alternate}
.palms .pl{left:-6vw;opacity:.7}
.palms .pr{right:-8vw;height:78%;transform:scaleX(-1);animation-delay:-4s;opacity:.55}
@keyframes sway{from{rotate:-.9deg}to{rotate:1deg}}


/* ---------- Logo lockups (original wordmark treatments, inspired by the series' logo system) ---------- */
.lg{display:inline-flex;flex-direction:column;letter-spacing:-.01em;text-transform:none;font-weight:400;line-height:1}
.lg b,.lg em{font-weight:400;font-style:normal}
.stack{display:flex;flex-direction:column;font-family:'Bowlby One','Arial Black',Impact,sans-serif}
.stack b{display:block;font-size:.62em;line-height:.88;white-space:nowrap;color:#fff;text-shadow:.035em .05em 0 rgba(0,0,0,.65),0 0 .6em rgba(0,0,0,.4)}
.stack em{font-size:1.45em;line-height:.5;margin-left:.08em}
.n3{color:#fff}
.n4{color:#fff;text-shadow:.05em .06em 0 rgba(0,0,0,.75)}
.n5{color:#7fd67a;text-shadow:.04em .05em 0 rgba(0,0,0,.7),0 0 .4em rgba(127,214,122,.45)}
.script{display:block;font-size:.72em;line-height:1;margin:-.34em 0 0 .9em;white-space:nowrap;transform:rotate(-4deg);transform-origin:0 50%}
.script.vc{font-family:'Yellowtail','Brush Script MT',cursive;color:#ff59ac;text-shadow:.04em .05em 0 #20e6ff,0 0 .4em rgba(255,89,172,.65)}
.script.sa{font-family:'Kaushan Script','Brush Script MT',cursive;color:#f4f2e6;text-shadow:.04em .05em 0 #000,0 0 .5em rgba(0,0,0,.6)}
.lg1{font-family:'Bowlby One','Arial Black',Impact,sans-serif;transform:skewX(-9deg);transform-origin:0 100%}
.lg1 b{display:block;font-size:.66em;line-height:.92;white-space:nowrap;color:#e0261c;-webkit-text-stroke:.035em #f2e8cf;paint-order:stroke fill;text-shadow:.04em .05em 0 #000}
.lg1 .au i{font-style:normal;font-size:.5em;color:#f2e8cf;-webkit-text-stroke:0;margin:0 .35em;vertical-align:.25em;letter-spacing:.1em}
.lg2{flex-direction:row;align-items:center;gap:.18em}
.lg2 .emb{height:.72em;width:auto;flex:none;filter:drop-shadow(0 .03em .06em rgba(0,0,0,.6))}
.lg2 .w{display:flex;align-items:baseline;font-family:'Bowlby One','Arial Black',Impact,sans-serif;color:#fff;text-shadow:.035em .05em 0 rgba(0,0,0,.7),0 0 .5em rgba(0,0,0,.4)}
.lg2 .two{color:#baff3c;text-shadow:.035em .05em 0 rgba(0,0,0,.7),0 0 .35em rgba(186,255,60,.6)}
.lg6{display:grid;justify-items:center}
.lg6>*{grid-area:1/1}
.lg6 .mark{font-family:'Bowlby One','Arial Black',Impact,sans-serif;font-size:2.3em;line-height:.9;color:transparent;background:linear-gradient(150deg,#ff2d92 0%,#ff7a3d 55%,#8a3dff 100%);-webkit-background-clip:text;background-clip:text;filter:drop-shadow(0 .05em .15em rgba(0,0,0,.45))}
.lg6 .stack{align-self:end;margin-bottom:.12em;text-align:center}

/* ---------- HUD ---------- */
.brand{position:fixed;z-index:30;top:calc(env(safe-area-inset-top) + 20px);left:clamp(16px,3vw,32px);display:flex;align-items:baseline;gap:10px;padding:11px 20px;border-radius:999px;font-size:13px;letter-spacing:.02em}
.brand b{font-weight:600;letter-spacing:.08em}
.brand span{opacity:.72}

.hint{position:fixed;z-index:31;width:max-content;max-width:calc(100vw - 24px);top:calc(env(safe-area-inset-top) + 20px);left:50%;translate:-50% 0;display:flex;align-items:center;gap:14px;padding:8px 8px 8px 20px;border-radius:999px;font-size:13px;opacity:0;visibility:hidden;transition:opacity .6s var(--ease),visibility .6s}
.hint.show{opacity:1;visibility:visible}
.hint button{padding:9px 16px;border-radius:999px;background:rgba(var(--accent),.32);box-shadow:inset 0 1px 0 rgba(255,255,255,.4);font-weight:500;white-space:nowrap}
.hint button:hover{background:rgba(var(--accent),.5)}

.hud{position:fixed;z-index:20;left:0;right:0;bottom:152px;display:flex;justify-content:space-between;align-items:flex-end;gap:32px;padding:0 clamp(22px,5vw,88px);pointer-events:none}
.titles{display:grid;flex:1 1 0;min-width:0}
.title{grid-area:1/1;align-self:end;justify-self:start;width:max-content;font-size:calc(clamp(2.6rem,8.4vw,8.6rem) * var(--k,1) * var(--fit,1));line-height:.94;text-transform:uppercase;white-space:nowrap;text-shadow:0 6px 40px rgba(0,0,0,.55);visibility:hidden;will-change:transform,opacity,filter;transform-origin:0 100%}
.title span{display:block}
.panel{pointer-events:auto;width:min(392px,34vw);margin-right:58px;padding:26px 28px 26px;border-radius:34px;display:grid;will-change:transform;transform-style:preserve-3d}
.slide{grid-area:1/1;display:flex;flex-direction:column;gap:14px;visibility:hidden;will-change:transform,opacity,filter}
.p-name{font-size:13px;letter-spacing:.03em;opacity:.8}
.p-head{display:flex;align-items:baseline;justify-content:space-between;gap:14px;flex-wrap:wrap}
.p-year{font-size:3.4rem;line-height:1;color:rgb(var(--accent));text-shadow:0 0 30px rgba(var(--accent),.45)}
.p-city{font-size:11.5px;letter-spacing:.16em;text-transform:uppercase;opacity:.92;text-align:right}
.p-meta{display:grid;grid-template-columns:auto 1fr;gap:6px 16px;font-size:12.5px;padding-top:14px;border-top:1px solid rgba(255,255,255,.16)}
.p-meta dt{opacity:.6}
.p-meta dd{opacity:.95}
.p-desc{font-size:14px;line-height:1.6;opacity:.9;max-width:46ch}
.p-links{display:flex;gap:10px;flex-wrap:wrap;padding-top:2px}
.btn{position:relative;display:inline-flex;align-items:center;padding:11px 20px;border-radius:999px;font-size:11.5px;letter-spacing:.16em;text-transform:uppercase;font-weight:600;background:rgba(var(--accent),.3);box-shadow:inset 0 1px 0 rgba(255,255,255,.55),inset 0 -1px 0 rgba(255,255,255,.1),0 10px 30px -10px rgba(var(--accent),.8);transition:transform .5s var(--ease),background .5s var(--ease),box-shadow .5s var(--ease)}
.btn:hover{transform:translateY(-2px) scale(1.03);background:rgba(var(--accent),.5);box-shadow:inset 0 1px 0 rgba(255,255,255,.7),0 16px 40px -10px rgba(var(--accent),1)}
.btn.ghost{background:rgba(255,255,255,.08);box-shadow:inset 0 1px 0 rgba(255,255,255,.4),0 8px 24px -12px rgba(0,0,0,.6)}

/* Rail */
.rail{position:fixed;z-index:30;right:22px;top:50%;translate:0 -50%;height:min(48vh,440px);padding:18px 10px;border-radius:999px;--r:0}
.rail-track{position:relative;height:100%;width:16px}
.rail-line{position:absolute;left:50%;top:0;bottom:0;width:2px;translate:-50% 0;border-radius:2px;background:rgba(255,255,255,.2);overflow:hidden}
.rail-fill{position:absolute;inset:0;transform-origin:50% 0;transform:scaleY(var(--r));background:rgb(var(--accent));box-shadow:0 0 12px rgb(var(--accent))}
.tick{position:absolute;left:50%;top:calc(var(--f) * 100%);width:24px;height:24px;translate:-50% -50%;display:grid;place-items:center;border-radius:50%}
.tick i{width:5px;height:5px;border-radius:50%;background:rgba(255,255,255,.7);transition:transform .5s var(--ease),background .5s}
.tick:hover i{transform:scale(1.8)}
.tick .lbl{position:absolute;right:calc(100% + 14px);top:50%;translate:8px -50%;padding:5px 11px;border-radius:999px;font-size:11.5px;letter-spacing:.06em;white-space:nowrap;background:rgba(10,10,14,.5);-webkit-backdrop-filter:blur(14px);backdrop-filter:blur(14px);box-shadow:inset 0 1px 0 rgba(255,255,255,.3);opacity:0;pointer-events:none;transition:opacity .4s var(--ease),translate .5s var(--ease)}
.tick:hover .lbl,.tick.on .lbl{opacity:1;translate:0 -50%}
.rail-thumb{position:absolute;left:50%;top:calc(var(--r) * 100%);width:13px;height:13px;translate:-50% -50%;border-radius:50%;background:rgb(var(--accent));box-shadow:0 0 0 3px rgba(255,255,255,.22),0 0 18px rgb(var(--accent));pointer-events:none}

/* Dock */
.dock-wrap{position:fixed;z-index:40;left:0;right:0;bottom:calc(env(safe-area-inset-bottom) + 36px);display:flex;justify-content:center;pointer-events:none;padding:0 12px}
.dock{pointer-events:auto;max-width:100%;border-radius:32px;padding:10px 12px}
.dock-scroll{display:flex;align-items:flex-end;gap:var(--gap);overflow-x:auto;overflow-y:hidden;scrollbar-width:none;touch-action:pan-x;padding:2px}
.dock-scroll::-webkit-scrollbar{display:none}
.d-item{--s:1;flex:none;position:relative;width:calc(var(--bw) * var(--s));height:calc(var(--bw) * (1 + (var(--s) - 1) * .55));border-radius:calc(20px + (var(--s) - 1) * 6px);display:flex;flex-direction:column;align-items:center;justify-content:center;gap:2px;
  background:linear-gradient(160deg,rgba(255,255,255,.2),rgba(255,255,255,.05));
  box-shadow:inset 0 1px 0 rgba(255,255,255,.55),inset 0 -1px 0 rgba(255,255,255,.08),0 8px 22px -10px rgba(0,0,0,.7);
  transition:background .7s var(--ease),box-shadow .7s var(--ease)}
.d-abbr{font-size:calc(1.02rem * (1 + (var(--s) - 1) * .5));font-weight:700;letter-spacing:.03em;line-height:1}
.d-year{font-size:calc(.62rem * (1 + (var(--s) - 1) * .4));opacity:.7;letter-spacing:.06em}
.d-item.active{background:linear-gradient(160deg,rgba(var(--accent),.7),rgba(var(--accent),.3));box-shadow:inset 0 1px 0 rgba(255,255,255,.75),inset 0 -1px 0 rgba(255,255,255,.15),0 0 32px rgba(var(--accent),.7),0 10px 26px -10px rgba(0,0,0,.7)}
.d-item.active .d-year{opacity:.95}
.tip{position:fixed;z-index:50;left:0;top:0;padding:7px 14px;border-radius:999px;font-size:12.5px;letter-spacing:.02em;white-space:nowrap;pointer-events:none;opacity:0;transition:opacity .3s var(--ease)}
.tip.show{opacity:1}

.legal{position:fixed;z-index:35;left:0;right:0;bottom:calc(env(safe-area-inset-bottom) + 10px);text-align:center;font-size:10.5px;letter-spacing:.02em;opacity:.55;padding:0 16px;pointer-events:none}

.drop{position:fixed;z-index:60;inset:20px;border-radius:40px;display:grid;place-items:center;font-size:1.1rem;font-weight:500;opacity:0;visibility:hidden;transition:opacity .4s var(--ease),visibility .4s;pointer-events:none;outline:2px dashed rgba(255,255,255,.5);outline-offset:-14px}
.drop.show{opacity:1;visibility:visible}

/* ---------- Mobile ---------- */
@media (max-width:820px){
  :root{--bw:52px;--gap:7px}
  .hud{flex-direction:column;align-items:stretch;gap:14px;bottom:126px;padding:0 16px}
  .titles{flex:none}
  .panel{width:auto;margin-right:0;padding:16px 18px;border-radius:26px}
  .slide{gap:9px}
  .p-name,.p-meta .plat{display:none}
  .p-year{font-size:2.2rem}
  .p-desc{font-size:13px;line-height:1.5;display:-webkit-box;-webkit-line-clamp:3;-webkit-box-orient:vertical;overflow:hidden}
  .p-meta{padding-top:9px;font-size:12px}
  .brand{padding:9px 16px;font-size:12px}
  .brand span{display:none}
  .rail{right:auto;left:50%;top:calc(env(safe-area-inset-top) + 66px);translate:-50% 0;height:auto;width:min(78vw,330px);padding:9px 16px}
  .rail-track{height:16px;width:100%}
  .rail-line{left:0;right:0;top:50%;bottom:auto;width:auto;height:2px;translate:0 -50%}
  .rail-fill{transform-origin:0 50%;transform:scaleX(var(--r))}
  .tick{left:calc(var(--f) * 100%);top:50%}
  .tick .lbl{display:none}
  .rail-thumb{left:calc(var(--r) * 100%);top:50%}
  .hint{top:calc(env(safe-area-inset-top) + 110px);max-width:calc(100vw - 24px);font-size:12px;padding-left:16px;gap:10px}
  .hint .t-long{display:none}
  .dock{border-radius:28px;padding:8px 10px}
  .legal{font-size:9.5px}
}
@media (max-width:820px) and (max-height:640px){.p-desc{-webkit-line-clamp:2}.hud{bottom:118px}}
@media (min-width:821px) and (max-height:700px){.hud{bottom:138px}.p-desc{font-size:13px}.p-year{font-size:2.6rem}}

@media (prefers-reduced-motion:reduce){
  .shot.on,.shot.out,.haze,.grain,.palms svg{animation:none}
  .shot{transition-duration:.5s}
}
</style>
</head>
<body>

<div class="stage" id="stage" aria-hidden="true"></div>
<div class="layer wash" id="wash" aria-hidden="true"></div>
<div class="layer haze" id="haze" aria-hidden="true"></div>
<div class="layer" aria-hidden="true"><canvas id="fx"></canvas></div>

<div class="palms" id="palms" aria-hidden="true">
  <svg class="pl" viewBox="0 0 300 500" preserveAspectRatio="xMidYMax meet"><use href="#palm"/></svg>
  <svg class="pr" viewBox="0 0 300 500" preserveAspectRatio="xMidYMax meet"><use href="#palm"/></svg>
</div>
<svg width="0" height="0" style="position:absolute" aria-hidden="true">
  <symbol id="palm" viewBox="0 0 300 500">
    <path d="M150 500C156 420 138 300 152 190" fill="none" stroke="currentColor" stroke-width="11" stroke-linecap="round"/>
    <path d="M152 190Q100 110 18 128Q96 138 152 190Z"/>
    <path d="M152 190Q90 172 14 238Q96 202 152 190Z"/>
    <path d="M152 190Q128 92 94 28Q158 100 152 190Z"/>
    <path d="M152 190Q172 82 216 20Q168 102 152 190Z"/>
    <path d="M152 190Q206 112 288 126Q210 138 152 190Z"/>
    <path d="M152 190Q214 172 292 242Q208 204 152 190Z"/>
    <path d="M152 190Q146 130 154 58Q166 130 152 190Z"/>
    <path d="M152 190Q60 200 40 300Q100 230 152 190Z"/>
    <path d="M152 190Q244 200 264 300Q204 230 152 190Z"/>
  </symbol>
</svg>

<div class="layer light" id="light" aria-hidden="true"></div>
<div class="layer tint" aria-hidden="true"></div>
<div class="layer vignette" id="vig" aria-hidden="true"></div>
<div class="layer grain" id="grain" aria-hidden="true"></div>

<header class="brand glass"><b>GTA Archive</b><span>History to now</span></header>

<div class="hint glass" id="hint" role="status">
  <span>No screenshot loaded for this scene<span class="t-long">. Drop image files anywhere.</span></span>
  <button type="button" id="pickBtn" title="Or add hosted URLs to the MEDIA object in the page source">Choose files</button>
</div>

<nav class="rail glass" id="rail" aria-label="Timeline"><div class="rail-track" id="railTrack"><div class="rail-line"><div class="rail-fill"></div></div><div class="rail-thumb"></div></div></nav>

<main class="hud" id="hud">
  <div class="titles" id="titles"></div>
  <aside class="panel glass" id="panel" aria-label="Game information"></aside>
</main>

<div class="dock-wrap"><nav class="dock glass" id="dock" aria-label="Grand Theft Auto games"><div class="dock-scroll" id="dockScroll"></div></nav></div>
<div class="tip glass" id="tip" aria-hidden="true"></div>

<footer class="legal">Unofficial fan-made archive. Grand Theft Auto and related properties belong to Rockstar Games.</footer>
<div class="drop glass" id="drop">Drop images to add them to this scene</div>
<div class="sr" id="live" aria-live="polite"></div>
<input type="file" id="pick" accept="image/*" multiple hidden>

<script>
(() => {
'use strict';

/* =====================================================================
   MEDIA — the real screenshots.
   Add 2–5 image URLs (or relative paths such as "img/gta3-1.jpg") per game.
   Each entry can be a string, or { src, pos:'50% 40%' } to set the focal point.
   Official GTA VI screenshots:  https://www.rockstargames.com/VI/media/screenshots
   Official Vice City page:      https://www.rockstargames.com/games/vicecity
   You can also drop image files onto the page while it is open (session only).
   ===================================================================== */
const MEDIA = {
  gta1: [],
  gta2: [],
  gta3: [],
  vc:   [],
  sa:   [],
  gta4: [],
  gta5: [],
  gta6: []   // also used by the NOW scene
};

/* ---------------------------------------------------------------------
   Scenes
   --------------------------------------------------------------------- */
const RM = 'https://www.rockstargames.com/VI/media';
const SCENES = [
  { key:'gta1', media:'gta1', dock:{abbr:'GTA',year:'1997',label:'Grand Theft Auto'},
    title:['GRAND THEFT','AUTO'], k:1.05, font:"'Space Mono',ui-monospace,monospace", wt:700, ls:'.02em', skew:0,
    name:'Grand Theft Auto', year:'1997', city:'Liberty City / San Andreas / Vice City', era:'Top-down origins',
    platforms:'PC, PlayStation, Game Boy Color',
    desc:'A top-down crime sandbox from DMA Design. Steal cars, take contracts and shake off the police across three cities, one chase at a time.',
    pal:{base:[9,9,9],accent:[214,40,40],accent2:[225,225,225],glow:[214,40,40],glass:[255,255,255],ink:[240,240,236]},
    grade:'grayscale(1) contrast(1.18) brightness(.82)',
    n:{haze:0,wash:0,vig:.85,grain:.24,palms:0}, fx:{mode:'dust',amt:.55}, links:[] },

  { key:'gta2', media:'gta2', dock:{abbr:'II',year:'1999',label:'Grand Theft Auto 2'},
    title:['GRAND THEFT','AUTO 2'], k:1.2, font:"'Chakra Petch',system-ui,sans-serif", wt:700, ls:'.05em', skew:0,
    name:'Grand Theft Auto 2', year:'1999', city:'Anywhere City', era:'Gang-war era',
    platforms:'PC, PlayStation, Dreamcast, Game Boy Color',
    desc:'Set in a near-future city split between rival gangs. Earn their respect, or lose it, and the whole map answers.',
    pal:{base:[14,6,26],accent:[186,255,60],accent2:[140,60,220],glow:[150,70,230],glass:[190,130,255],ink:[236,255,214]},
    grade:'contrast(1.1) saturate(1.05)',
    n:{haze:.2,wash:.3,vig:.72,grain:.12,palms:0}, fx:{mode:'ember',amt:.6}, links:[] },

  { key:'gta3', media:'gta3', dock:{abbr:'III',year:'2001',label:'Grand Theft Auto III'},
    title:['GRAND THEFT','AUTO III'], k:1.3, font:"'Barlow Condensed',system-ui,sans-serif", wt:800, ls:'.02em', skew:0,
    name:'Grand Theft Auto III', year:'2001', city:'Liberty City', era:'Open-world 3D',
    platforms:'PlayStation 2, Windows, Xbox',
    desc:'The series steps into full 3D. A betrayed thief with no voice fights his way up through a gray, fog-prone Liberty City.',
    pal:{base:[10,15,22],accent:[255,138,52],accent2:[92,124,160],glow:[110,140,178],glass:[170,190,212],ink:[232,238,244]},
    grade:'saturate(.8) contrast(1.06) brightness(.9)',
    n:{haze:.36,wash:.12,vig:.72,grain:.1,palms:0}, fx:{mode:'rain',amt:.45}, links:[] },

  { key:'vc', media:'vc', dock:{abbr:'VC',year:'2002',label:'Vice City'},
    title:['VICE CITY'], k:1.3, font:"'Syncopate',system-ui,sans-serif", wt:700, ls:'.1em', skew:0,
    name:'Grand Theft Auto: Vice City', year:'2002', city:'Vice City', era:'The 1980s',
    platforms:'PlayStation 2, Xbox, Windows',
    desc:'It is 1986. Tommy Vercetti climbs Vice City’s criminal ladder through neon, radio and pastel suits.',
    pal:{base:[38,8,52],accent:[255,62,165],accent2:[40,230,255],glow:[255,86,172],glass:[120,240,255],ink:[255,240,250]},
    grade:'saturate(1.25) contrast(1.05)',
    n:{haze:.32,wash:.22,vig:.55,grain:.07,palms:.55}, fx:{mode:'bokeh',amt:.6},
    links:[{href:'https://www.rockstargames.com/games/vicecity',label:'Official page',ghost:true}] },

  { key:'sa', media:'sa', dock:{abbr:'SA',year:'2004',label:'San Andreas'},
    title:['SAN ANDREAS'], k:1.3, font:"'Anton',Impact,sans-serif", wt:400, ls:'.04em', skew:0,
    name:'Grand Theft Auto: San Andreas', year:'2004', city:'Los Santos / San Fierro / Las Venturas', era:'The 1990s',
    platforms:'PlayStation 2, Xbox, Windows',
    desc:'Carl Johnson comes home to Los Santos in 1992. The state of San Andreas opens into three cities, wilderness and everything between.',
    pal:{base:[12,20,10],accent:[255,196,40],accent2:[70,160,60],glow:[255,150,50],glass:[210,230,150],ink:[250,246,222]},
    grade:'saturate(1.1) contrast(1.04)',
    n:{haze:.22,wash:.12,vig:.62,grain:.1,palms:0}, fx:{mode:'motes',amt:.5}, links:[] },

  { key:'gta4', media:'gta4', dock:{abbr:'IV',year:'2008',label:'Grand Theft Auto IV'},
    title:['GRAND THEFT','AUTO IV'], k:1.3, font:"'Inter',system-ui,sans-serif", wt:300, ls:'.16em', skew:0,
    name:'Grand Theft Auto IV', year:'2008', city:'Liberty City', era:'The HD generation',
    platforms:'PlayStation 3, Xbox 360, Windows',
    desc:'Niko Bellic reaches a heavier, more grounded Liberty City. Rain, weight and consequence define the RAGE-engine era.',
    pal:{base:[9,15,21],accent:[78,170,190],accent2:[120,150,175],glow:[90,150,182],glass:[170,200,215],ink:[226,234,240]},
    grade:'saturate(.72) contrast(1.06) brightness(.92)',
    n:{haze:.38,wash:.1,vig:.88,grain:.1,palms:0}, fx:{mode:'rain',amt:1}, links:[] },

  { key:'gta5', media:'gta5', dock:{abbr:'V',year:'2013',label:'Grand Theft Auto V'},
    title:['GRAND THEFT','AUTO V'], k:1.3, font:"'Archivo',system-ui,sans-serif", wt:800, ls:'.01em', skew:0,
    name:'Grand Theft Auto V', year:'2013', city:'Los Santos', era:'Three protagonists',
    platforms:'PS3/4/5, Xbox 360/One/Series X|S, PC',
    desc:'Michael, Franklin and Trevor share Los Santos and Blaine County: freeways, mountains and coastline, still played through GTA Online.',
    pal:{base:[8,18,14],accent:[96,200,110],accent2:[255,214,140],glow:[255,190,110],glass:[255,255,255],ink:[252,250,240]},
    grade:'saturate(1.1) contrast(1.03)',
    n:{haze:.12,wash:.06,vig:.5,grain:.06,palms:0}, fx:{mode:'motes',amt:.4}, links:[] },

  { key:'gta6', media:'gta6', dock:{abbr:'VI',year:'2026',label:'Grand Theft Auto VI'},
    title:['GRAND THEFT','AUTO VI'], k:1.5, font:"'Unbounded',system-ui,sans-serif", wt:700, ls:'.01em', skew:0,
    name:'Grand Theft Auto VI', year:'2026', city:'Vice City · Leonida', era:'The next generation',
    platforms:'PlayStation 5, Xbox Series X|S',
    desc:'Jason and Lucia run from an easy score gone wrong across Vice City and the state of Leonida. Rockstar’s next chapter is due 19 November 2026.',
    pal:{base:[30,6,54],accent:[255,58,140],accent2:[60,180,255],glow:[255,120,70],glass:[255,150,220],ink:[255,244,250]},
    grade:'saturate(1.12) contrast(1.04)',
    n:{haze:.3,wash:.24,vig:.5,grain:.06,palms:.62}, fx:{mode:'bokeh',amt:.95},
    links:[{href:RM,label:'Explore media'}] },

  { key:'now', media:'gta6', dockKey:'gta6', dock:null,
    title:['NOW'], k:1.5, font:"'Unbounded',system-ui,sans-serif", wt:400, ls:'.04em', skew:0,
    name:'The archive, up to date', year:'2026', city:'Los Santos · Vice City', era:'Twenty-nine years in',
    platforms:'PlayStation, Xbox and PC',
    desc:'From a top-down car thief to a state-sized open world. Los Santos is still live, and Vice City is about to reopen.',
    pal:{base:[18,8,38],accent:[255,128,96],accent2:[150,120,255],glow:[255,130,130],glass:[235,215,255],ink:[255,247,250]},
    grade:'saturate(1.08) contrast(1.04)',
    n:{haze:.3,wash:.3,vig:.6,grain:.08,palms:.4}, fx:{mode:'bokeh',amt:.7},
    links:[{href:RM,label:'Explore media'}] }
];
const N = SCENES.length;
const RAIL_LABELS = ['1997','1999','2001','2002','2004','2008','2013','2026','Now'];


/* Logo lockups (built from type + SVG, one per scene) */
const stackOf = last => `<span class="stack"><b>grand</b><b>theft</b><b>${last}</b></span>`;
const LOGOS = {
  gta1: `<span class="lg lg1"><b>GRAND THEFT</b><b class="au"><i>★★★</i>AUTO<i>★★★</i></b></span>`,
  gta2: `<span class="lg lg2"><svg class="emb" viewBox="0 0 132 84" aria-hidden="true"><circle cx="42" cy="42" r="36" fill="#1b0f34" stroke="#baff3c" stroke-width="4"/><text x="42" y="50" text-anchor="middle" font-family="Bowlby One,Arial Black,sans-serif" font-size="24" fill="#fff">GTA</text><path d="M82 36h24V26l22 16-22 16V48H82z" fill="#8c3cdc"/></svg><span class="w"><em>GTA</em><em class="two">2</em></span></span>`,
  gta3: `<span class="lg">${stackOf('auto <em class="n3">III</em>')}</span>`,
  vc:   `<span class="lg">${stackOf('auto')}<span class="script vc">Vice City</span></span>`,
  sa:   `<span class="lg">${stackOf('auto')}<span class="script sa">San Andreas</span></span>`,
  gta4: `<span class="lg">${stackOf('auto <em class="n4">IV</em>')}</span>`,
  gta5: `<span class="lg">${stackOf('auto <em class="n5">V</em>')}</span>`,
  gta6: `<span class="lg lg6"><span class="mark">VI</span>${stackOf('auto')}</span>`
};

/* ---------------------------------------------------------------------
   Helpers
   --------------------------------------------------------------------- */
const $ = (s, r=document) => r.querySelector(s);
const clamp = (v,a,b) => Math.min(b, Math.max(a, v));
const lerp = (a,b,t) => a + (b - a) * t;
const smooth = t => t * t * (3 - 2 * t);
const rgb = a => `${a[0]|0},${a[1]|0},${a[2]|0}`;
const reduce = matchMedia('(prefers-reduced-motion: reduce)').matches;
const coarse = matchMedia('(pointer: coarse)').matches;
const root = document.documentElement;

/* ---------------------------------------------------------------------
   Build DOM
   --------------------------------------------------------------------- */
const stage = $('#stage'), titlesEl = $('#titles'), panelEl = $('#panel');
const layers = [], titleEls = [], slideEls = [];

SCENES.forEach((s, i) => {
  const el = document.createElement('div');
  el.className = 'scene';
  el.style.zIndex = i;
  el.style.setProperty('--grade', s.grade);
  el.innerHTML = `<div class="plate"><div class="fallback" style="--fa:${rgb(s.pal.accent)};--fb:${rgb(s.pal.accent2)};--fbase:${rgb(s.pal.base)}"></div></div>`;
  stage.appendChild(el);
  layers.push({ el, plate: el.firstChild, vis:false, timer:0 });

  const h = document.createElement('h2');
  h.className = 'title';
  h.style.setProperty('--k', s.k);
  h.style.fontFamily = s.font; h.style.fontWeight = s.wt; h.style.letterSpacing = s.ls;
  h.innerHTML = LOGOS[s.key] || s.title.map(l => `<span>${l}</span>`).join('');
  h.setAttribute('aria-hidden', 'true');
  titlesEl.appendChild(h); titleEls.push(h);

  const sl = document.createElement('div');
  sl.className = 'slide';
  sl.setAttribute('aria-hidden', 'true');
  sl.innerHTML = `
    <div class="p-name">${s.name}</div>
    <div class="p-head"><span class="p-year" style="font-family:${s.font.replace(/"/g,"'")};font-weight:${s.wt === 300 ? 300 : Math.min(s.wt,700)}">${s.year}</span><span class="p-city">${s.city}</span></div>
    <dl class="p-meta"><dt>Era</dt><dd>${s.era}</dd><dt class="plat">Platforms</dt><dd class="plat">${s.platforms}</dd></dl>
    <p class="p-desc">${s.desc}</p>
    ${s.links.length ? `<div class="p-links">${s.links.map(l => `<a class="btn${l.ghost ? ' ghost' : ''}" href="${l.href}" target="_blank" rel="noopener noreferrer">${l.label}</a>`).join('')}</div>` : ''}`;
  panelEl.appendChild(sl); slideEls.push({ el: sl, vis:false });
});

/* Fit every title to the space beside the panel (fonts differ a lot in width) */
function fitTitles() {
  const avail = titlesEl.clientWidth;
  titleEls.forEach(h => h.style.setProperty('--fit', 1));
  titleEls.forEach(h => { const w = h.offsetWidth; h.style.setProperty('--fit', w > avail ? (avail / w * .97).toFixed(4) : 1); });
}

/* Dock */
const dockScroll = $('#dockScroll'), dockEl = $('#dock');
const dockItems = [];
SCENES.forEach((s, i) => {
  if (!s.dock) return;
  const b = document.createElement('button');
  b.className = 'd-item'; b.type = 'button'; b.dataset.i = i; b.dataset.key = s.key;
  b.setAttribute('aria-label', `${s.dock.label}, ${s.dock.year}`);
  b.innerHTML = `<span class="d-abbr" style="font-family:${s.font.replace(/"/g,"'")}">${s.dock.abbr}</span><span class="d-year">${s.dock.year}</span>`;
  dockScroll.appendChild(b);
  dockItems.push({ el:b, i, s:1, key:s.key, label:s.dock.label });
});

/* Rail */
const rail = $('#rail'), railTrack = $('#railTrack');
const ticks = SCENES.map((s, i) => {
  const t = document.createElement('button');
  t.className = 'tick'; t.type = 'button'; t.style.setProperty('--f', i / (N - 1));
  t.setAttribute('aria-label', RAIL_LABELS[i]);
  t.innerHTML = `<i></i><span class="lbl">${RAIL_LABELS[i]}</span>`;
  t.addEventListener('click', () => goTo(i));
  railTrack.appendChild(t);
  return t;
});

/* ---------------------------------------------------------------------
   Images
   --------------------------------------------------------------------- */
const norm = m => typeof m === 'string' ? { src:m } : m;
function buildPlate(si) {
  const L = layers[si], sc = SCENES[si];
  L.plate.querySelectorAll('img').forEach(n => n.remove());
  (MEDIA[sc.media] || []).map(norm).forEach((m, n) => {
    const img = new Image();
    img.className = 'shot';
    img.alt = `${sc.name} — screenshot ${n + 1}`;
    img.decoding = 'async';
    img.referrerPolicy = 'no-referrer';
    img.draggable = false;
    img.style.objectPosition = m.pos || '50% 50%';
    img.style.setProperty('--dx', (n % 2 ? 1 : -1) * 1.2 + '%');
    img.style.setProperty('--dy', (n % 3 ? -.7 : .7) + '%');
    img.onload = () => {
      img.dataset.ok = '1';
      if (!L.plate.querySelector('.on')) showShot(si, img);
      updateHint();
    };
    img.onerror = () => {
      console.warn('[GTA Archive] Could not load image:', m.src);
      img.remove(); updateHint();
    };
    img.src = m.src;
    L.plate.appendChild(img);
  });
}
function showShot(si, img) {
  const plate = layers[si].plate, prev = plate.querySelector('.on');
  if (prev === img) return;
  if (prev) { prev.classList.remove('on'); prev.classList.add('out'); setTimeout(() => prev.classList.remove('out'), 1700); }
  img.classList.remove('out'); img.classList.add('on');
}
function cycleShot(si) {
  const plate = layers[si].plate;
  const oks = [...plate.querySelectorAll('img[data-ok="1"]')];
  if (oks.length < 2) return;
  const on = plate.querySelector('.on');
  showShot(si, oks[(oks.indexOf(on) + 1) % oks.length]);
}
SCENES.forEach((_, i) => buildPlate(i));
setInterval(() => { if (!document.hidden) { cycleShot(cur); if (SCENES[cur].media === 'gta6') SCENES.forEach((s, i) => { if (i !== cur && s.media === 'gta6') cycleShot(i); }); } }, 7000);

/* Empty-state hint + drag & drop */
const hint = $('#hint'), pick = $('#pick'), dropEl = $('#drop');
function updateHint() { hint.classList.toggle('show', !layers[cur].plate.querySelector('img[data-ok="1"]')); }
function addFiles(files) {
  const key = SCENES[cur].media;
  [...files].filter(f => f.type.startsWith('image/')).forEach(f => MEDIA[key].push(URL.createObjectURL(f)));
  SCENES.forEach((s, i) => { if (s.media === key) buildPlate(i); });
}
$('#pickBtn').addEventListener('click', () => pick.click());
pick.addEventListener('change', () => { addFiles(pick.files); pick.value = ''; });
let dragDepth = 0;
addEventListener('dragenter', e => { if ([...(e.dataTransfer?.types || [])].includes('Files')) { dragDepth++; dropEl.classList.add('show'); } });
addEventListener('dragleave', () => { dragDepth = Math.max(0, dragDepth - 1); if (!dragDepth) dropEl.classList.remove('show'); });
addEventListener('dragover', e => e.preventDefault());
addEventListener('drop', e => { e.preventDefault(); dragDepth = 0; dropEl.classList.remove('show'); if (e.dataTransfer?.files?.length) addFiles(e.dataTransfer.files); });

/* ---------------------------------------------------------------------
   State + navigation
   --------------------------------------------------------------------- */
let pos = 0, target = 0, cur = 0, dirty = true;
const live = $('#live');
function goTo(i) { g = null; clearTimeout(gTimer); target = clamp(Math.round(i), 0, N - 1); }
function step(d) { goTo(Math.round(target) + d); }

/* wheel: continuous drag that commits to a single scene */
let g = null, gTimer = 0, lockUntil = 0;
function commit() {
  clearTimeout(gTimer);
  if (!g) return;
  const dir = Math.abs(g.acc) > .14 ? Math.sign(g.acc) : 0;
  target = clamp(g.start + dir, 0, N - 1);
  if (dir) lockUntil = performance.now() + 750;
  g = null;
}
addEventListener('wheel', e => {
  e.preventDefault();
  if (performance.now() < lockUntil) return;
  let d = e.deltaMode === 1 ? e.deltaY * 32 : e.deltaY;
  if (Math.abs(e.deltaX) > Math.abs(d)) d = e.deltaX;
  if (!g) g = { start: Math.round(target), acc: 0 };
  g.acc = clamp(g.acc + d * .0034, -1, 1);
  target = clamp(g.start + g.acc, 0, N - 1);
  if (Math.abs(g.acc) >= .6) { commit(); return; }
  clearTimeout(gTimer); gTimer = setTimeout(commit, 130);
}, { passive: false });

/* touch swipe */
let ts = null;
addEventListener('touchstart', e => {
  if (e.target.closest('.dock,.rail,.hint') || e.touches.length > 1) { ts = null; return; }
  const t = e.touches[0];
  ts = { x:t.clientX, y:t.clientY, t:performance.now(), start:Math.round(target), acc:0, axis:null };
}, { passive: true });
addEventListener('touchmove', e => {
  if (!ts) return;
  const t = e.touches[0], dx = ts.x - t.clientX, dy = ts.y - t.clientY;
  if (!ts.axis) { if (Math.hypot(dx, dy) < 8) return; ts.axis = Math.abs(dx) > Math.abs(dy) ? 'x' : 'y'; }
  const d = ts.axis === 'x' ? dx : dy, size = (ts.axis === 'x' ? innerWidth : innerHeight) * .42;
  ts.acc = clamp(d / size, -1, 1);
  target = clamp(ts.start + ts.acc, 0, N - 1);
  e.preventDefault();
}, { passive: false });
const touchEnd = () => {
  if (!ts) return;
  const quick = performance.now() - ts.t < 280;
  const dir = (Math.abs(ts.acc) > .22 || (Math.abs(ts.acc) > .05 && quick)) ? Math.sign(ts.acc) : 0;
  target = clamp(ts.start + dir, 0, N - 1); ts = null;
};
addEventListener('touchend', touchEnd); addEventListener('touchcancel', touchEnd);

/* keyboard */
addEventListener('keydown', e => {
  if (e.altKey || e.ctrlKey || e.metaKey) return;
  const k = e.key;
  if (k === 'ArrowRight' || k === 'ArrowDown' || k === 'PageDown') { e.preventDefault(); step(1); }
  else if (k === 'ArrowLeft' || k === 'ArrowUp' || k === 'PageUp') { e.preventDefault(); step(-1); }
  else if (k === 'Home') { e.preventDefault(); goTo(0); }
  else if (k === 'End') { e.preventDefault(); goTo(N - 1); }
});
dockEl.addEventListener('click', e => { const b = e.target.closest('.d-item'); if (b) goTo(+b.dataset.i); });

/* pointer parallax + glass specular */
let tmx = 0, tmy = 0, mx = 0, my = 0, px = innerWidth * .6, py = innerHeight * .3, pMoved = true;
addEventListener('pointermove', e => {
  if (e.pointerType === 'touch') return;
  tmx = (e.clientX / innerWidth - .5) * 2; tmy = (e.clientY / innerHeight - .5) * 2;
  px = e.clientX; py = e.clientY; pMoved = true;
});
const glassEls = [...document.querySelectorAll('.glass')];
function updateSpecular() {
  glassEls.forEach(el => {
    const r = el.getBoundingClientRect();
    el.style.setProperty('--sx', ((px - r.left) / Math.max(1, r.width) * 100).toFixed(1) + '%');
    el.style.setProperty('--sy', ((py - r.top) / Math.max(1, r.height) * 100).toFixed(1) + '%');
  });
}

/* ---------------------------------------------------------------------
   Render (palette + layers)
   --------------------------------------------------------------------- */
const wash = $('#wash'), haze = $('#haze'), vig = $('#vig'), grainEl = $('#grain'), palms = $('#palms'), light = $('#light');
const cache = {};
const setVar = (k, v) => { if (cache[k] !== v) { cache[k] = v; root.style.setProperty(k, v); } };
const PK = ['base','accent','accent2','glow','glass','ink'];
const curPal = {}; PK.forEach(k => curPal[k] = SCENES[0].pal[k].slice());
const curN = { ...SCENES[0].n };

function render() {
  const i0 = clamp(Math.floor(pos), 0, N - 1), i1 = clamp(i0 + 1, 0, N - 1);
  const f = smooth(clamp(pos - i0, 0, 1));
  const A = SCENES[i0], B = SCENES[i1];
  PK.forEach(k => {
    const c = curPal[k];
    for (let j = 0; j < 3; j++) c[j] = lerp(A.pal[k][j], B.pal[k][j], f);
    setVar('--' + k, rgb(c));
  });
  for (const k in curN) curN[k] = lerp(A.n[k], B.n[k], f);
  wash.style.opacity = curN.wash.toFixed(3);
  haze.style.opacity = curN.haze.toFixed(3);
  vig.style.opacity = curN.vig.toFixed(3);
  grainEl.style.opacity = curN.grain.toFixed(3);
  palms.style.opacity = curN.palms.toFixed(3);
  rail.style.setProperty('--r', (pos / (N - 1)).toFixed(4));

  for (let s = 0; s < N; s++) {
    const d = s - pos, ad = Math.abs(d), L = layers[s];
    if (ad >= 1) { if (L.vis) { L.el.style.visibility = 'hidden'; L.vis = false; } }
    else {
      if (!L.vis) { L.el.style.visibility = 'visible'; L.vis = true; }
      const o = d > 0 ? smooth(1 - ad) : 1;                 // next scene fades in over the current one
      const sc = d > 0 ? 1 + .12 * ad : 1 + .05 * ad;       // 1.12 -> 1
      const bl = d > 0 ? 8 * ad : 5 * ad;                   // 8px -> 0
      L.el.style.opacity = o.toFixed(3);
      L.el.style.transform = `translate3d(${(-mx * 22).toFixed(1)}px,${(-my * 14 - d * 20).toFixed(1)}px,0) scale(${sc.toFixed(4)})`;
      L.el.style.filter = bl > .25 ? `blur(${bl.toFixed(2)}px)` : 'none';
    }

    const T = titleEls[s], to = clamp(1 - ad * 1.9, 0, 1);
    if (to < .01) { if (T.style.visibility !== 'hidden') T.style.visibility = 'hidden'; }
    else {
      T.style.visibility = 'visible'; T.style.opacity = to.toFixed(3);
      T.style.transform = `translate3d(${(mx * -12).toFixed(1)}px,${(d * 56 + my * -6).toFixed(1)}px,0) skewX(${SCENES[s].skew}deg)`;
      T.style.filter = ad > .02 ? `blur(${(ad * 12).toFixed(1)}px)` : 'none';
    }
    const S = slideEls[s], so = clamp(1 - ad * 2.2, 0, 1);
    if (so < .01) { if (S.vis) { S.el.style.visibility = 'hidden'; S.vis = false; } }
    else {
      if (!S.vis) { S.el.style.visibility = 'visible'; S.vis = true; }
      S.el.style.opacity = so.toFixed(3);
      S.el.style.transform = `translate3d(0,${(d * 28).toFixed(1)}px,0)`;
      S.el.style.filter = ad > .02 ? `blur(${(ad * 8).toFixed(1)}px)` : 'none';
    }
  }
}

/* Parallax on the floating glass panel */
function tiltPanel() {
  panelEl.style.transform = `perspective(900px) rotateX(${(my * -2.2).toFixed(2)}deg) rotateY(${(mx * 2.6).toFixed(2)}deg) translate3d(${(mx * -6).toFixed(1)}px,${(my * -4).toFixed(1)}px,0)`;
}

/* Active-scene bookkeeping */
function setActive(i) {
  cur = i;
  const sc = SCENES[i];
  titleEls.forEach((t, k) => t.setAttribute('aria-hidden', k === i ? 'false' : 'true'));
  slideEls.forEach((s, k) => s.el.setAttribute('aria-hidden', k === i ? 'false' : 'true'));
  const dk = sc.dockKey || sc.key;
  dockItems.forEach(d => d.el.classList.toggle('active', d.key === dk));
  ticks.forEach((t, k) => t.classList.toggle('on', k === i));
  live.textContent = `${sc.name}, ${sc.year}`;
  updateHint();
  const act = dockItems.find(d => d.key === dk);
  if (act && dockScroll.scrollWidth > dockScroll.clientWidth + 1) {
    dockScroll.scrollTo({ left: act.el.offsetLeft - (dockScroll.clientWidth - act.el.offsetWidth) / 2, behavior: 'smooth' });
  }
}

/* ---------------------------------------------------------------------
   Dock magnetism
   --------------------------------------------------------------------- */
const tip = $('#tip');
let dpx = null, dockPresence = 0;
dockEl.addEventListener('pointermove', e => { if (e.pointerType === 'mouse') dpx = e.clientX; });
dockEl.addEventListener('pointerleave', () => { dpx = null; tip.classList.remove('show'); });
function stepDock(dt) {
  const cs = getComputedStyle(dockEl);
  const BW = parseFloat(cs.getPropertyValue('--bw')) || 64, GAP = parseFloat(cs.getPropertyValue('--gap')) || 8;
  const n = dockItems.length, scrollable = dockScroll.scrollWidth > dockScroll.clientWidth + 1;
  const r = dockEl.getBoundingClientRect(), cx = r.left + r.width / 2, w0 = n * BW + (n - 1) * GAP;
  const k = 1 - Math.exp(-dt * 14);
  let nearest = -1, nd = 1e9;
  dockItems.forEach((d, j) => {
    let want = d.key === (SCENES[cur].dockKey || SCENES[cur].key) ? 1.14 : 1;
    if (dpx !== null && !scrollable) {
      const c0 = cx - w0 / 2 + j * (BW + GAP) + BW / 2, dx = dpx - c0;
      want += .62 * Math.exp(-(dx * dx) / (2 * (BW * .95) ** 2));
      if (Math.abs(dx) < nd) { nd = Math.abs(dx); nearest = j; }
    }
    d.s += (want - d.s) * k;
    d.el.style.setProperty('--s', d.s.toFixed(3));
  });
  if (nearest >= 0) {
    const it = dockItems[nearest].el.getBoundingClientRect(), tr = dockEl.getBoundingClientRect();
    tip.textContent = dockItems[nearest].label;
    const tw = tip.offsetWidth;
    tip.style.transform = `translate3d(${(it.left + it.width / 2 - tw / 2).toFixed(1)}px,${(tr.top - 44).toFixed(1)}px,0)`;
    tip.classList.add('show');
  } else tip.classList.remove('show');
}

/* ---------------------------------------------------------------------
   Atmosphere particles (rain, dust, embers, motes, bokeh)
   --------------------------------------------------------------------- */
const cv = $('#fx'), ctx = cv.getContext('2d');
let W = 0, H = 0;
function sizeFx() {
  const dpr = Math.min(devicePixelRatio || 1, 1.5);
  W = innerWidth; H = innerHeight;
  cv.width = W * dpr; cv.height = H * dpr;
  ctx.setTransform(dpr, 0, 0, dpr, 0, 0);
}
sizeFx();
const NP = reduce ? 36 : (innerWidth < 820 ? 64 : 130);
const P = Array.from({ length: NP }, (_, i) => ({ i, mode: '', f: 0, kind: '', x: 0, y: 0, vx: 0, vy: 0, r: 1, a: 1, c: 0, len: 0, ph: 0 }));
function spawn(p, mode, first) {
  const R = Math.random;
  p.mode = mode; p.c = (R() * 3) | 0; p.ph = R() * 6.28; p.x = R() * W; p.y = first ? R() * H : H + 30;
  switch (mode) {
    case 'rain':
      if (R() < .24) { p.kind = 'bokeh'; p.r = 18 + R() * 40; p.vx = (R() - .5) * 8; p.vy = (R() - .5) * 6; p.a = .05 + R() * .06; p.y = R() * H; p.c = 1; }
      else { p.kind = 'streak'; p.len = 14 + R() * 28; p.vy = 900 + R() * 700; p.vx = p.vy * .2; p.a = .14 + R() * .2; p.c = 2; p.y = first ? R() * H : -40; }
      break;
    case 'bokeh': p.kind = 'bokeh'; p.r = 16 + R() * 54; p.vy = -(6 + R() * 16); p.vx = (R() - .5) * 10; p.a = .06 + R() * .11; break;
    case 'ember': p.kind = 'spark'; p.r = .8 + R() * 1.8; p.vy = -(30 + R() * 70); p.vx = (R() - .5) * 26; p.a = .5 + R() * .5; break;
    case 'motes': p.kind = 'mote'; p.r = .8 + R() * 2.2; p.vy = -(4 + R() * 10); p.vx = 6 + R() * 14; p.a = .25 + R() * .4; break;
    default: p.kind = 'speck'; p.r = .5 + R() * 1.2; p.vy = (R() - .5) * 10; p.vx = (R() - .5) * 8; p.a = .2 + R() * .5; p.y = R() * H;
  }
}
const rgba = (a, o) => `rgba(${a[0] | 0},${a[1] | 0},${a[2] | 0},${o.toFixed(3)})`;
function stepFx(dt, t) {
  ctx.clearRect(0, 0, W, H);
  const fx = SCENES[cur].fx, allowed = Math.floor(NP * fx.amt);
  const cols = [curPal.accent, curPal.accent2, curPal.ink];
  for (const p of P) {
    const want = (p.mode === fx.mode && p.i < allowed) ? 1 : 0;
    p.f += clamp(want - p.f, -dt * .9, dt * .9);
    if (p.f <= .001 && want === 0) {
      if (p.i < allowed && p.mode !== fx.mode) { spawn(p, fx.mode, true); p.f = 0; } else continue;
    }
    p.x += p.vx * dt; p.y += p.vy * dt;
    if (p.kind === 'streak') { if (p.y > H + 40 || p.x > W + 60) { const f = p.f; spawn(p, p.mode, false); p.y = -40; p.f = f; } }
    else {
      if (p.y < -90 || p.y > H + 90 || p.x > W + 90 || p.x < -90) { const f = p.f, y0 = p.y; spawn(p, p.mode, false); p.f = f; if (p.kind === 'speck') p.y = y0 < 0 ? H : 0; else p.y = p.vy < 0 ? H + 60 : -60; if (p.x > W) p.x = -60; }
      if (p.kind === 'spark' || p.kind === 'mote') p.x += Math.sin(t * .001 + p.ph) * .4;
    }
    const col = cols[p.c], al = p.a * p.f;
    switch (p.kind) {
      case 'streak':
        ctx.globalCompositeOperation = 'source-over';
        ctx.strokeStyle = rgba(col, al); ctx.lineWidth = 1;
        ctx.beginPath(); ctx.moveTo(p.x, p.y); ctx.lineTo(p.x - p.vx / p.vy * p.len, p.y - p.len); ctx.stroke(); break;
      case 'bokeh':
        ctx.globalCompositeOperation = 'lighter';
        ctx.fillStyle = rgba(col, al); ctx.beginPath(); ctx.arc(p.x, p.y, p.r, 0, 6.283); ctx.fill();
        ctx.strokeStyle = rgba(col, al * 1.7); ctx.lineWidth = 1; ctx.stroke(); break;
      case 'speck': {
        ctx.globalCompositeOperation = 'source-over';
        const fl = .5 + .5 * Math.sin(t * .01 + p.ph * 9);
        ctx.fillStyle = rgba(curPal.ink, al * fl); ctx.beginPath(); ctx.arc(p.x, p.y, p.r, 0, 6.283); ctx.fill(); break; }
      default:
        ctx.globalCompositeOperation = 'lighter';
        ctx.fillStyle = rgba(col, al * .18); ctx.beginPath(); ctx.arc(p.x, p.y, p.r * 4, 0, 6.283); ctx.fill();
        ctx.fillStyle = rgba(col, al); ctx.beginPath(); ctx.arc(p.x, p.y, p.r, 0, 6.283); ctx.fill();
    }
  }
  ctx.globalCompositeOperation = 'source-over';
}

/* ---------------------------------------------------------------------
   Main loop
   --------------------------------------------------------------------- */
let last = performance.now();
function frame(t) {
  const dt = Math.min(.05, (t - last) / 1000 || .016); last = t;

  const diff = target - pos;
  if (Math.abs(diff) > .0004) { pos += diff * (1 - Math.exp(-dt * (5.2 + Math.min(Math.abs(diff), 4) * .9))); dirty = true; }
  else if (pos !== target) { pos = target; dirty = true; }

  if (coarse) { tmx = Math.sin(t * .00025) * .45; tmy = Math.cos(t * .0002) * .3; }
  mx += (tmx - mx) * (1 - Math.exp(-dt * 5)); my += (tmy - my) * (1 - Math.exp(-dt * 5));
  const parallaxMoving = Math.abs(tmx - mx) > .0008 || Math.abs(tmy - my) > .0008 || coarse;

  const near = clamp(Math.round(pos), 0, N - 1);
  if (near !== cur) setActive(near);

  if (dirty || parallaxMoving) { render(); tiltPanel(); dirty = false; }

  // moving light: follows the pointer, with a slow ambient drift
  light.style.setProperty('--lx', ((.5 + mx * .35 + Math.sin(t * .0003) * .08) * 100).toFixed(1) + '%');
  light.style.setProperty('--ly', ((.32 + my * .25 + Math.cos(t * .00025) * .06) * 100).toFixed(1) + '%');

  if (pMoved) { updateSpecular(); pMoved = false; }
  stepDock(dt);
  stepFx(dt, t);
  requestAnimationFrame(frame);
}

addEventListener('resize', () => { fitTitles(); sizeFx(); dirty = true; pMoved = true; setActive(cur); });
fitTitles();
if (document.fonts && document.fonts.ready) document.fonts.ready.then(fitTitles);
setActive(0);
render(); tiltPanel(); updateSpecular();
requestAnimationFrame(frame);
})();
</script>
</body>
</html>
