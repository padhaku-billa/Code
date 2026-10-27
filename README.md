<!DOCTYPE html>
<kumarrajesh21317@gmail lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>Code Club</title>
<link href="https://fonts.googleapis.com/css2?family=Sora:wght@400;600;700&display=swap" rel="stylesheet">
<style>
:root{--bg:#eef1f1;--sf:#fff;--tx:#041421;--mu:#4c7275;--ac:#2a6b66;--ln:#cdd5d6;--ink:#041421;--deep:#052530;--sea:#86b9b0;--mist:#d1d5d6;box-sizing:border-box;padding-top:env(safe-area-inset-top,0px);padding-bottom:env(safe-area-inset-bottom,0px)}
@media(prefers-color-scheme:dark){:root:not([data-theme="light"]){--bg:#041421;--sf:#072a35;--tx:#e4ecec;--mu:#9fbfbc;--ac:#86b9b0;--ln:#14414b}}
:root[data-theme="dark"]{--bg:#041421;--sf:#072a35;--tx:#e4ecec;--mu:#9fbfbc;--ac:#86b9b0;--ln:#14414b}
*{box-sizing:inherit}[hidden]{display:none!important}
html{scroll-padding-top:env(safe-area-inset-top,0px)}
body{margin:0;background:var(--bg);color:var(--tx);font:400 16px/1.6 Sora,system-ui,-apple-system,"Segoe UI",sans-serif}
body::before{content:"";position:fixed;inset:0 0 auto;height:env(safe-area-inset-top,0px);z-index:10;background:var(--ink)}
header{position:sticky;top:env(safe-area-inset-top,0px);z-index:11;background:var(--ink);color:var(--mist);display:flex;align-items:center;gap:12px;padding:10px 20px}
.logo{display:flex;align-items:center;gap:8px;font-weight:700;color:var(--mist);text-decoration:none;white-space:nowrap}
.logo svg{width:20px;height:20px;fill:var(--sea)}
nav{display:flex;gap:4px;margin-left:auto;overflow-x:auto}
nav a{padding:8px 12px;border-radius:8px;color:var(--mist);text-decoration:none;font-size:15px;white-space:nowrap}
nav a:hover{color:var(--sea)}nav a[aria-current]{background:var(--deep);color:var(--sea)}
#th{background:none;border:1px solid #14414b;color:var(--mist);border-radius:8px;width:36px;height:36px;cursor:pointer;font-size:16px}
a:focus-visible,button:focus-visible,input:focus-visible,select:focus-visible,textarea:focus-visible{outline:2px solid var(--sea);outline-offset:2px}
.w{max-width:1040px;margin:0 auto;padding:48px 20px}
h1,h2,h3{line-height:1.15;letter-spacing:-.02em;margin:0 0 .5em}h2{font-size:clamp(1.7rem,4vw,2.3rem)}h3{font-size:1.1rem;margin:0}
p{max-width:62ch;margin:0 0 1em}.mu{color:var(--mu)}
.hero{position:relative;overflow:hidden;color:var(--mist);background:radial-gradient(ellipse at 75% 0,#0b3a45 0,var(--deep) 40%,var(--ink) 85%)}
.hero .w{position:relative;z-index:1;padding-block:clamp(60px,12vw,120px)}
.hero h1{font-size:clamp(2.2rem,6.4vw,4rem);max-width:15ch}
.hero p{font-size:1.1rem;color:#b9cccb}
.hero svg{position:absolute;right:0;top:0;height:100%;width:min(52%,440px)}
.bolt{fill:none;stroke:var(--sea);stroke-width:2.2;stroke-linejoin:round;stroke-linecap:round;filter:drop-shadow(0 0 7px #86b9b0);opacity:.2;animation:bz 9s 1.2s infinite}
.hero::after{content:"";position:absolute;inset:0;background:var(--sea);opacity:0;pointer-events:none;animation:fl 9s 1.2s infinite}
@keyframes bz{0%,92%,100%{opacity:.2}93%{opacity:1}94%{opacity:.3}95%{opacity:.95}97%{opacity:.2}}
@keyframes fl{0%,92%,100%{opacity:0}93%{opacity:.16}94%{opacity:0}95%{opacity:.1}96%{opacity:0}}
@media(prefers-reduced-motion:reduce){.bolt,.hero::after{animation:none}}
.btns{display:flex;flex-wrap:wrap;gap:12px;margin-top:24px}
.b{display:inline-block;padding:11px 20px;border-radius:10px;border:1px solid var(--sea);background:var(--sea);color:var(--ink);font:600 15px Sora,system-ui,sans-serif;cursor:pointer;text-decoration:none}
.b.g{background:none;color:var(--sea)}.b:hover{filter:brightness(1.1)}
#hs{margin-top:28px;font-size:.95rem;color:var(--sea)}
.f{display:grid;grid-template-columns:repeat(auto-fit,minmax(230px,1fr));gap:28px;margin-top:24px}
.f div{border-left:3px solid var(--ac);padding-left:16px}.f p{margin:6px 0 0;color:var(--mu)}
.band{background:var(--deep);color:var(--mist)}.band .w{padding-block:36px;display:flex;flex-wrap:wrap;gap:16px;align-items:center;justify-content:space-between}.band p{margin:0}
.fm{display:grid;grid-template-columns:repeat(auto-fit,minmax(210px,1fr));gap:14px;background:var(--sf);border:1px solid var(--ln);border-radius:14px;padding:20px;margin:20px 0 32px}
.fm .full{grid-column:1/-1}label{display:grid;gap:4px;font-size:14px;font-weight:600}
input,select,textarea{font:inherit;font-weight:400;color:var(--tx);background:var(--bg);border:1px solid var(--ln);border-radius:8px;padding:10px;width:100%}
textarea{min-height:96px;resize:vertical}
.bar{display:flex;flex-wrap:wrap;gap:12px;align-items:center;margin-bottom:18px}.bar input{flex:1 1 200px;width:auto}.bar select{width:auto}
.mg{display:grid;grid-template-columns:repeat(auto-fill,minmax(250px,1fr));gap:16px}
.m{background:var(--sf);border:1px solid var(--ln);border-radius:14px;padding:18px;display:flex;flex-direction:column;gap:10px}
.m p{margin:0;font-size:.95rem}.top{display:flex;align-items:center;gap:12px}