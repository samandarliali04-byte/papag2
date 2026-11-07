<!DOCTYPE html>
<html lang="ru">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0, viewport-fit=cover">
<meta name="theme-color" content="#292622">
<meta name="description" content="papağ — азербайджанская кухня на живом огне: плов, кутабы, пити, мангал и настоящее гостеприимство.">
<title>papağ — азербайджанский ресторан</title>

<!-- PWA Manifest & Icons -->
<link rel="manifest" href="data:application/manifest+json;charset=utf-8,%7B%22name%22%3A%22papa%C4%9F%22%2C%22short_name%22%3A%22papa%C4%9F%22%2C%22start_url%22%3A%22.%22%2C%22display%22%3A%22standalone%22%2C%22background_color%22%3A%22%23292622%22%2C%22theme_color%22%3A%22%23292622%22%7D">
<link rel="icon" href="data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCA1MTIgNTEyIiB3aWR0aD0iNTEyIiBoZWlnaHQ9IjUxMiI+CiAgPHJlY3Qgd2lkdGg9IjUxMiIgaGVpZ2h0PSI1MTIiIGZpbGw9IiMyOTI2MjIiLz4KICA8ZyB0cmFuc2Zvcm09InRyYW5zbGF0ZSgxMDYgMTA2KSBzY2FsZSg3LjUpIiBmaWxsPSJub25lIiBzdHJva2U9IiNkOGNiYjgiIHN0cm9rZS13aWR0aD0iMC43NSIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIj4KICAgIDxwYXRoIGQ9Ik05IDMxIEwxMC41IDE3IEMxMSAxMiAxNCA4IDIwIDggQzI2IDggMjkgMTIgMjkuNSAxNyBMMzEgMzEiLz4KICAgIDxwYXRoIGQ9Ik03IDMxIEgzMyIvPgogICAgPHBhdGggZD0iTTEyIDE0IFExNCAxMS41IDE2IDE0IFExOCAxMS41IDIwIDE0IFEyMiAxMS41IDI0IDE0IFEyNiAxMS41IDI4IDE0Ii8+CiAgICA8cGF0aCBkPSJNMTMgMjAgUTE1IDE3LjUgMTcgMjAgUTE5IDE3LjUgMjEgMjAgUTIzIDE3LjUgMjUgMjAgUTI3IDE3LjUgMjcuNSAyMCIvPgogICAgPHBhdGggZD0iTTExIDI2IFExMyAyMy41IDE1IDI2IFExNyAyMy41IDE5IDI2IFEyMSAyMy41IDIzIDI2IFEyNSAyMy41IDI3IDI2IFEyOSAyMy41IDMwIDI2Ii8+CiAgPC9nPgo8L3N2Zz4K" type="image/svg+xml">
<link rel="apple-touch-icon" href="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAALQAAAC0CAIAAACyr5FlAAAQAElEQVR4AexdB1gU1xZWAZWylKVERcWOxvjU6HuK0Zho1Ghs2CJ2MWJXBAtdenVBEFAENWisib0kwUYSCyYYNYmJJjZAQNrSFERMeP/ORD6UXSJknZk7e/Odb7xzz517zv3Pv/fO3DNDmnTr0oEKRUApAk0a0f8oAioQoORQAQytbtSIkoOyQCUClBwqoaEKSg7KAZUIUHKohIYqKDkawAFNuYSSQ1Mi3YBxUnI0ADRNuYSSQ1Mi3YBxUnI0ADRNuYSSQ1Mi3YBxUnI0ADRNuYSSQ1Mi3YBxqpUcDbBPLxEwApQcAg4O365RcvAdAQHbp+QQcHD4do2Sg+8ICNg+JYeAg8O3a5QcfEdAwPYpOfgOjoDtU3IIODh8u0bJwXcEBGyfkkPAweHbNUoOviMgYPuUHAIODt+uUXLwHQEB26fkEHBw+HZNuOTgGxlqn34rSzmgGgE6c6jGRuM1lBwaTwHVAFByqMZG4zWUHBpPAdUAUHKoxkbjNZQcoqKAegdDyaFePEXVGyWHqMKp3sFQcqgXT1H1RskhqnCqdzCUHOrFU1S9UXKIKpzqHQwlh3rxFFVvGkIOUcWMs8FQcnAGNXmGKDnIixlnHlNycAY1eYYoOciLGWceU3JwBjV5hig5yIsZZx5TcnAGNXGG6Nvn5IWMO4/pzMEd1sRZouQgLmTcOUzJwR3WxFnSXHI0a6rzpnXHgTZ9x3w4ZMaUcUsdZnqsXgRBAaeohKqbdcemOjrEBVVdDmsWORDp/3S3njZ5TKCX0854WYCXs/NSe/uZkyaOGzF0sE2fXj0gKOAUlVAFejl/lrA+wMvJbuLoHt2tdXS01YU7Ef1oCjkwT0yxHfXp5lAftxWTx4/sZt1JR1s7/UHW5dTrX53+ds8Xx2MTdvuvj4WgsPfACVRClZGZraONCabTlAmjfN1WJG4KmTz+w+bNmhIR2n/vpPjJoa2tPXrE+3GRfnaTRus2b1ZSWno+JTV6y077pa4r1voHR8TFbd+7/9DJU+fOX7n6CwSFfQdPoBKq5Wv80CwmficuKSl5pKurO23y2Nhw35HDBmtraf179AXeg8jJYW4qlQW4zJs12cjQENNA5NzP5yxykW3cduabS4WFxa8SGzQ7nXwJl8xdshaXZ2Y9NDE2dJjzcajfWlOp8av0QG4bMZMDt5MRQW5tW7dKS8+UbdyKaSD5/PdVVVUNi9Zff1Xh8mVr/NBVWkZme6vWEYFuMNGw3oi4SrTkGDtqiJ+7o76+Hu4eHF0DzqdcUUs8wC105egSgG4lEgNfN8dRw99TS88C7ESc5Fgyf8bc6ZO0tLR27DmEu4fXgTu63bH3sLa21vzZUxbPm/46TPDepwjJMWHM8A/eG1BZWRkWGX/o+KnXB/GhY0kw8ezZn8OGvGM7etjrM8RXz2IjB7Yxpk8ZCzQjNyde/P4qCq9VYCIqLhEmZnw87k3rTiiISURFDjNTkzWODk2aNDly8syFlB+5idN3F1OPfXkWRl2cFsABboxyY0Wd5ODG4zqsYOdbX0/311u3E3cfrKOZ2lWf7jpw4+YfEgP9hfZ2au+cxw7FQ463unXp+VbXp08r8aiJnwpMsz0r6jtzpuPP/3d01+6NlZWVnE+xvf/uL377h90v1N8gAAAAAElFTkSuQmCC">

<!-- Preconnect for Fonts -->
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:wght@300&family=Manrope:wght@500;700&display=swap" rel="stylesheet">

<style>
:root{
  --parchment:#d8cbb8;--linen:#bfb4a3;--stone:#b6ab9c;--walnut:#978e81;
  --espresso:#615b53;--onyx:#2c2c2c;--roast:#292622;--saffron:#d49653;
  --serif:'Cormorant Garamond',Georgia,'Times New Roman',serif;
  --sans:'Manrope',system-ui,-apple-system,'Segoe UI',Roboto,sans-serif;
  --ease:cubic-bezier(0.25,0.46,0.45,0.94);
  --pad:48px
}
*{box-sizing:border-box;margin:0;padding:0;-webkit-tap-highlight-color:transparent}
html{scroll-behavior:smooth}
body{font-family:var(--sans);font-weight:500;font-size:14px;line-height:1.4;letter-spacing:-0.01em;background:var(--parchment);color:var(--onyx);-webkit-font-smoothing:antialiased;user-select:none}
body.lock{overflow:hidden}
body.has-cart{padding-bottom:88px}
button,input,textarea,select{font:inherit;color:inherit;letter-spacing:inherit}
button{cursor:pointer;background:none;border:0}
a{color:inherit;text-decoration:none}
a:hover{text-decoration:underline;text-underline-offset:4px}
img{max-width:100%;display:block;pointer-events:none}
ul{list-style:none}
.hidden{display:none!important}
:focus-visible{outline:2px solid currentColor;outline-offset:3px}
.orn *{vector-effect:non-scaling-stroke}
.cap{font-size:12px;line-height:1.3;letter-spacing:-0.012em;text-transform:uppercase}

/* ---------- BUTTONS ---------- */
.btn{display:inline-flex;align-items:center;justify-content:center;gap:10px;padding:20px 28px;border:1px solid currentColor;border-radius:3px;background:transparent;font-size:14px;line-height:1;font-weight:500;letter-spacing:-0.01em;text-transform:uppercase;cursor:pointer;transition:background-color .4s var(--ease),color .4s var(--ease)}
.btn:hover{text-decoration:none}
.btn:disabled{opacity:.5;cursor:not-allowed}
.btn-light{color:var(--parchment)}
.btn-light:hover{background:var(--parchment);color:var(--roast)}
.btn-dark{color:var(--onyx)}
.btn-dark:hover{background:var(--onyx);color:var(--parchment)}
.btn-sm{padding:14px 20px;min-height:44px}
.btn-block{width:100%}
.icon-btn{position:relative;display:inline-flex;align-items:center;justify-content:center;width:44px;height:44px;color:inherit;border-radius:3px}
.nl{display:inline-flex;align-items:center;min-height:44px;font-size:14px;line-height:1;text-transform:uppercase;letter-spacing:-0.01em;color:inherit}

/* ---------- HERO ---------- */
.hero{position:relative;overflow:hidden;display:flex;flex-direction:column;min-height:860px;padding:0 var(--pad) 48px;background:var(--roast);color:var(--parchment)}
.hero-slides,.hero-slide{position:absolute;inset:0}
.hero-slide{background-size:cover;background-position:center;opacity:0;transition:opacity 1s var(--ease)}
.hero-slide.active{opacity:1}
.hero-shade{position:absolute;inset:0;background:linear-gradient(180deg,rgba(41,38,34,.55),rgba(41,38,34,.88))}
.hero-orn{position:absolute;right:-200px;top:30px;width:1000px;height:1000px;opacity:.14;pointer-events:none;color:var(--parchment)}
.site-nav{position:relative;z-index:5;display:flex;align-items:center;flex-wrap:wrap;gap:16px 40px;padding-top:24px}
.logo{display:inline-flex;color:var(--parchment)}
.nav-links{display:flex;align-items:center;gap:32px;flex-grow:1}
.nav-right{display:flex;align-items:center;gap:8px;margin-left:auto}
.langs{display:flex;align-items:center}
.lang-btn{min-width:36px;min-height:44px;font-size:12px;letter-spacing:-0.012em;color:var(--parchment);opacity:.75}
.lang-btn.active{opacity:1;font-weight:700;text-decoration:underline;text-decoration-color:var(--saffron);text-decoration-thickness:2px;text-underline-offset:6px}
.cart-badge{position:absolute;top:2px;right:0;min-width:18px;height:18px;padding:0 4px;border-radius:3px;background:var(--parchment);color:var(--roast);font-size:11px;font-weight:700;line-height:18px;text-align:center;display:none}
.nav-right .nav-reserve{margin-left:16px}
.menu-btn{display:none}
.hero-main{position:relative;z-index:2;flex-grow:1;display:flex;flex-direction:column;justify-content:flex-end;padding-top:120px}
.hero-meta{display:flex;justify-content:space-between;flex-wrap:wrap;gap:8px 24px}
.wordmark{margin:16px 0 0;padding-top:.08em;font-family:var(--sans);font-weight:500;font-size:clamp(84px,13.8vw,199px);line-height:.9;letter-spacing:-0.016em;text-transform:uppercase;color:var(--parchment)}
.hero-rule{height:1px;background:var(--espresso);margin-top:32px}
.hero-bottom{display:flex;justify-content:space-between;align-items:flex-end;flex-wrap:wrap;gap:32px 48px;margin-top:32px}
.hero-copy{max-width:540px;display:flex;flex-direction:column;gap:28px}
.hero-copy p{max-width:400px;font-size:15px;line-height:1.4}
.hero-actions{display:flex;flex-wrap:wrap;gap:12px}
.slider-ctrl{display:flex;align-items:center;gap:16px}
.slide-count{min-width:56px;text-align:center}
.arrow-btn{width:44px;height:44px;border:1px solid var(--parchment);border-radius:3px;color:var(--parchment);display:inline-flex;align-items:center;justify-content:center;transition:background-color .4s var(--ease),color .4s var(--ease)}
.arrow-btn:hover{background:var(--parchment);color:var(--roast)}
.hero-dots{display:flex;gap:6px}
.hero-dot{width:24px;height:2px;padding:0;background:var(--walnut);position:relative}
.hero-dot:before{content:"";position:absolute;left:0;right:0;top:-20px;bottom:-20px}
.hero-dot.active{background:var(--saffron)}

/* ---------- MARQUEE ---------- */
.marquee{overflow:hidden;border-bottom:1px solid var(--stone)}
.mq{display:flex;width:max-content;padding:28px 0;animation:mq 27s linear infinite}
.mq-half{display:flex;align-items:center;flex-shrink:0;gap:48px;padding-right:48px;font-family:var(--serif);font-weight:300;font-size:clamp(40px,4.5vw,65px);line-height:1;letter-spacing:-0.04em;text-transform:uppercase;white-space:nowrap}
@keyframes mq{from{transform:translateX(0)}to{transform:translateX(-50%)}}

/* ---------- SECTIONS ---------- */
.section{padding:clamp(80px,11vw,150px) var(--pad)}
.hl{height:1px;background:var(--stone);margin:0 var(--pad)}
.h2{margin-top:28px;font-family:var(--serif);font-weight:300;font-size:clamp(44px,5.2vw,69px);line-height:.9;letter-spacing:-0.04em;text-transform:uppercase}
.h2-xl{font-size:clamp(56px,8vw,115px);line-height:.85}
.split{display:flex;flex-wrap:wrap;align-items:flex-start;gap:48px 64px}
.split>.split-l{flex:1 1 520px;min-width:0}
.split>.split-r{flex:1 1 360px;max-width:520px;padding-top:34px;display:flex;flex-direction:column;gap:16px}
.split-r p{font-size:15px;line-height:1.4}
.principles{display:flex;flex-wrap:wrap;gap:40px 48px;margin-top:clamp(64px,8vw,110px)}
.principle{flex:1 1 280px;min-width:0;border-top:1px solid var(--stone);padding-top:24px}
.principle h3{margin:20px 0 12px;font-family:var(--serif);font-weight:300;font-size:32px;line-height:1;letter-spacing:-0.035em;text-transform:uppercase}
.principle p{font-size:14px}

/* ---------- MENU ---------- */
.menu-head{display:flex;flex-wrap:wrap;align-items:flex-end;justify-content:space-between;gap:32px 48px}
.menu-head p{max-width:320px;font-size:15px}
.menu-bar{position:sticky;top:0;z-index:40;display:flex;align-items:center;justify-content:space-between;flex-wrap:wrap;gap:8px 32px;margin:56px calc(var(--pad) * -1) 0;padding:0 var(--pad);background:var(--parchment);border-bottom:1px solid var(--stone)}
.tabs{display:flex;gap:8px 32px;flex:1 1 auto;min-width:0;overflow-x:auto;scrollbar-width:none}
.tabs::-webkit-scrollbar{display:none}
.tab{flex-shrink:0;white-space:nowrap;min-height:56px;border-bottom:2px solid transparent;margin-bottom:-1px;font-size:14px;text-transform:uppercase;letter-spacing:-0.01em;color:var(--onyx);transition:border-color .4s var(--ease)}
.tab:hover{border-bottom-color:var(--onyx)}
.tab.active{font-weight:700;border-bottom-color:var(--saffron)}
.tools{display:flex;align-items:center;gap:20px;flex:0 1 auto}
.search{position:relative;width:280px}
.search input{width:100%;height:44px;padding:0 40px 0 14px;background:transparent;border:1px solid var(--onyx);border-radius:3px;font-size:14px;outline:none}
.search input::placeholder{color:var(--espresso);opacity:1}
.search input:focus-visible{outline:2px solid var(--onyx);outline-offset:3px}
.search-clear{position:absolute;right:0;top:0;width:44px;height:44px;display:none;align-items:center;justify-content:center}
.results-count{white-space:nowrap}
.dishes-grid{display:grid;grid-template-columns:repeat(3,minmax(0,1fr));gap:64px 24px;margin-top:56px;min-height:300px}
.grid-note{grid-column:1/-1;padding:56px 0;display:flex;flex-direction:column;align-items:flex-start;gap:20px;font-size:15px}
.dish-card{display:flex;flex-direction:column;gap:16px;animation:fade .4s var(--ease) both}
@keyframes fade{from{opacity:0}to{opacity:1}}
.dish-image{position:relative;display:block;width:100%;aspect-ratio:1/1;background:var(--linen);overflow:hidden;border-radius:0}
.dish-image img{width:100%;height:100%;object-fit:cover;transition:transform .4s var(--ease), opacity .3s ease;opacity:0}
.dish-image img.loaded{opacity:1}
.dish-image:hover img{transform:scale(1.03)}
.dish-ph{position:absolute;inset:0;display:flex;align-items:center;justify-content:center;color:var(--walnut)}
.dish-ph svg{width:38%;height:auto}
.tag{position:absolute;left:16px;top:16px;padding:6px 10px;border:1px solid var(--onyx);border-radius:3px;background:var(--parchment);font-size:12px;line-height:1;text-transform:uppercase}
.dish-head{display:flex;justify-content:space-between;align-items:baseline;gap:16px}
.dish-name{font-family:var(--serif);font-weight:300;font-size:32px;line-height:1;letter-spacing:-0.035em;text-transform:uppercase}
.dish-name button{text-align:left;text-transform:inherit;font-family:inherit;font-weight:inherit;font-size:inherit;line-height:inherit;letter-spacing:inherit}
.dish-name button:hover{text-decoration:underline;text-underline-offset:5px}
.dish-price{font-weight:700;font-size:14px;white-space:nowrap}
.dish-description{font-size:14px}
.dish-bottom{margin-top:auto}
.stepper{display:flex;align-items:center;justify-content:space-between;height:52px;border:1px solid var(--onyx);border-radius:3px;overflow:hidden}
.stepper button{width:56px;height:100%;font-size:20px;transition:background-color .4s var(--ease),color .4s var(--ease)}
.stepper button:hover{background:var(--onyx);color:var(--parchment)}
.stepper span{font-weight:700}

/* ---------- ATMOSPHERE ---------- */
.atmo{background:var(--roast);color:var(--parchment)}
.atmo .cap{color:var(--walnut)}
.atmo .h2{font-size:clamp(72px,8vw,115px);line-height:.85;color:var(--parchment)}
.atmo .h2 span{display:block}
.atmo-grid{display:flex;flex-wrap:wrap;align-items:flex-end;justify-content:space-between;gap:64px}
.atmo-l{flex:1 1 520px;min-width:0}
.atmo-r{flex:1 1 360px;max-width:520px;display:flex;flex-direction:column;gap:28px}
.atmo-photo{aspect-ratio:4/3;border:1px solid var(--espresso);background:center/cover no-repeat}
.atmo-r p{font-size:15px}
.atmo-r .btn{align-self:flex-start}

/* ---------- FOOTER ---------- */
.footer{padding:clamp(64px,8vw,110px) var(--pad) 36px;background:var(--roast);color:var(--parchment)}
.footer .cap{color:var(--walnut)}
.footer-top{display:flex;flex-wrap:wrap;justify-content:space-between;gap:48px 64px}
.footer-lead{flex:1 1 360px;max-width:560px;min-width:0}
.footer-lead p{margin-top:24px;font-family:var(--serif);font-weight:300;font-size:50px;line-height:.9;letter-spacing:-0.03em;text-transform:uppercase}
.footer-cols{display:flex;flex-wrap:wrap;gap:40px 64px}
.footer-col{display:flex;flex-direction:column;gap:4px;align-items:flex-start}
.footer-col .cap{margin-bottom:12px}
.footer-rule{height:1px;background:var(--espresso);margin-top:72px}
.footer-mark{margin-top:40px;padding-top:.08em;font-weight:500;font-size:clamp(84px,13.8vw,199px);line-height:.9;letter-spacing:-0.016em;text-transform:uppercase}
.footer-bottom{display:flex;flex-wrap:wrap;justify-content:space-between;gap:12px 24px;margin-top:40px}

/* ---------- OVERLAY / DRAWER / MODAL ---------- */
.overlay{position:fixed;inset:0;z-index:80;background:rgba(41,38,34,.72);opacity:0;visibility:hidden;transition:opacity .4s var(--ease),visibility .4s}
.overlay.show{opacity:1;visibility:visible}
.drawer{position:fixed;z-index:90;top:0;right:0;bottom:0;width:min(340px,86vw);padding:20px 28px;background:var(--roast);color:var(--parchment);transform:translateX(100%);visibility:hidden;transition:transform .4s var(--ease),visibility .4s;overflow-y:auto}
.drawer.open{transform:translateX(0);visibility:visible}
.drawer-close{margin-left:auto;display:flex}
.drawer li{border-bottom:1px solid var(--espresso)}
.drawer li a,.drawer li button{display:flex;align-items:center;width:100%;min-height:60px;text-align:left;font-size:14px;text-transform:uppercase;letter-spacing:-0.01em}
.modal{position:fixed;z-index:100;left:50%;top:50%;width:min(520px,calc(100vw - 32px));max-height:calc(100vh - 32px);overflow:auto;padding:56px 32px 32px;background:var(--parchment);color:var(--onyx);border:1px solid var(--onyx);border-radius:0;transform:translate(-50%,-48%);opacity:0;visibility:hidden;pointer-events:none;transition:opacity .4s var(--ease),transform .4s var(--ease),visibility .4s}
.modal.show{opacity:1;visibility:visible;pointer-events:auto;transform:translate(-50%,-50%)}
.modal-close{position:absolute;top:8px;right:8px}
.modal-title{font-family:var(--serif);font-weight:300;font-size:40px;line-height:.95;letter-spacing:-0.035em;text-transform:uppercase;margin-bottom:24px}
.modal-intro{font-size:14px;margin-bottom:24px}
.info-row{display:flex;justify-content:space-between;align-items:baseline;gap:24px;padding:18px 0;border-top:1px solid var(--stone)}
.info-row:last-of-type{border-bottom:1px solid var(--stone)}
.info-val{text-align:right;font-size:14px}
.info-val a{text-decoration:underline;text-underline-offset:4px}
.modal-actions{display:grid;gap:12px;margin-top:24px}
.dish-modal-img{aspect-ratio:4/3;background:var(--linen);margin-bottom:20px;overflow:hidden}
.dish-modal-img img{width:100%;height:100%;object-fit:cover}
.modal-price{font-weight:700;font-size:16px;margin-bottom:12px}
.modal-desc{font-size:14px;margin-bottom:24px}

/* ---------- FORMS ---------- */
.form-grid{display:grid;grid-template-columns:1fr 1fr;gap:16px}
.field{margin-bottom:16px}
.form-grid .field{margin-bottom:0}
.field.full{grid-column:1/-1}
.field label{display:block;margin-bottom:8px}
.fld{display:block;width:100%;height:52px;padding:0 14px;background:transparent;border:1px solid var(--onyx);border-radius:3px;font-size:14px;outline:none;user-select:text}
.fld:focus-visible{outline:2px solid var(--onyx);outline-offset:3px}
textarea.fld{height:auto;min-height:84px;padding:14px;resize:vertical}
.fld::placeholder{color:var(--espresso);opacity:1}
.form-note{margin-top:16px;font-size:13px}

/* ---------- CART ---------- */
.sheet{position:fixed;z-index:110;left:50%;bottom:0;width:min(680px,100%);max-height:92vh;overflow-y:auto;padding:12px 28px 32px;background:var(--parchment);color:var(--onyx);border:1px solid var(--onyx);border-bottom:0;border-radius:0;transform:translate(-50%,105%);visibility:hidden;transition:transform .4s var(--ease),visibility .4s}
.sheet.open{transform:translate(-50%,0);visibility:visible}
.sheet-head{position:sticky;top:0;z-index:2;display:flex;align-items:center;justify-content:space-between;padding:8px 0 16px;background:var(--parchment)}
.sheet-title{font-family:var(--serif);font-weight:300;font-size:40px;line-height:.95;letter-spacing:-0.035em;text-transform:uppercase}
.cart-empty{padding:40px 0;font-size:15px}
.cart-row{display:flex;align-items:center;justify-content:space-between;gap:16px;padding:16px 0;border-top:1px solid var(--stone)}
.cart-row-name{font-weight:700;font-size:14px}
.cart-row-sub{margin-top:4px;font-size:13px}
.mini{display:flex;align-items:center;gap:6px;flex-shrink:0}
.mini button{width:44px;height:44px;border:1px solid var(--onyx);border-radius:3px;font-size:18px;transition:background-color .4s var(--ease),color .4s var(--ease)}
.mini button:hover{background:var(--onyx);color:var(--parchment)}
.mini span{min-width:24px;text-align:center;font-weight:700}
.cart-total{display:flex;justify-content:space-between;align-items:baseline;padding:20px 0;border-top:1px solid var(--onyx);font-weight:700;font-size:16px}
.checkout-title{margin:8px 0 20px;font-family:var(--serif);font-weight:300;font-size:32px;line-height:1;letter-spacing:-0.035em;text-transform:uppercase}
.seg{display:grid;grid-template-columns:1fr 1fr;gap:8px}
.seg button{min-height:48px;padding:0 12px;border:1px solid var(--onyx);border-radius:3px;font-size:13px;text-transform:uppercase;transition:background-color .4s var(--ease),color .4s var(--ease)}
.seg button[aria-pressed="true"]{background:var(--onyx);color:var(--parchment)}
.clear-cart{display:block;margin:20px auto 0;min-height:44px;text-decoration:underline;text-underline-offset:4px;font-size:13px}
.cart-bar{position:fixed;z-index:70;left:50%;bottom:16px;transform:translateX(-50%);display:none;align-items:center;justify-content:space-between;width:min(560px,calc(100% - 32px));min-height:56px;padding:0 20px;border:1px solid var(--parchment);border-radius:3px;background:var(--onyx);color:var(--parchment);font-size:14px;font-weight:700;text-transform:uppercase;text-align:left}
.toast{position:fixed;z-index:150;left:50%;bottom:92px;transform:translateX(-50%);max-width:calc(100% - 32px);padding:14px 20px;background:var(--onyx);color:var(--parchment);border-radius:3px;font-size:13px;text-align:center;opacity:0;pointer-events:none;transition:opacity .4s var(--ease)}
.toast.show{opacity:1}

/* ---------- RESPONSIVE ---------- */
@media(max-width:1100px){
  .search{width:220px}
}
@media(max-width:900px){
  :root{--pad:20px}
  .nav-links,.nav-reserve{display:none!important}
  .menu-btn{display:inline-flex}
  .hero{min-height:760px;padding-bottom:32px}
  .hero-orn{width:700px;height:700px;right:-260px}
  .dishes-grid{grid-template-columns:repeat(2,minmax(0,1fr))}
  .menu-bar{position:static;flex-direction:column;align-items:stretch;padding-top:8px}
  .tools{order:-1;padding-top:8px}
  .search{flex:1 1 auto;width:auto}
  .tabs{width:100%}
  .footer-lead p{font-size:40px}
}
@media(max-width:600px){
  .hero-main{padding-top:80px}
  .slider-ctrl{width:100%;justify-content:space-between}
  .dishes-grid{grid-template-columns:1fr;gap:32px;margin-top:32px}
  .dish-card{display:grid;grid-template-columns:128px minmax(0,1fr);gap:4px 16px;align-items:start}
  .dish-info{display:flex;flex-direction:column;gap:10px;min-width:0}
  .dish-name{font-size:24px}
  .dish-description{font-size:13px}
  .tag{left:8px;top:8px;padding:4px 8px;font-size:11px}
  .modal{padding:56px 20px 24px}
  .modal-title,.sheet-title{font-size:34px}
  .sheet{padding:8px 20px 28px}
  .form-grid{grid-template-columns:1fr}
  .field.full{grid-column:auto}
  .info-row{flex-direction:column;gap:6px}
  .info-val{text-align:left}
}
@media(min-width:601px){
  .dish-info{display:contents}
}
/* ---------- РЕЖИМ ПРИЛОЖЕНИЯ (установлено на телефон) ---------- */
.app-tabs{display:none}
.install-hidden{display:none!important}
.info-row.step{flex-direction:row!important;gap:16px!important}
.info-row.step .info-val{text-align:left}
body.standalone{overscroll-behavior-y:none}
body.standalone .site-nav{padding-top:calc(24px + env(safe-area-inset-top))}
@media(max-width:900px){
  body.standalone{padding-bottom:calc(64px + env(safe-area-inset-bottom))}
  body.standalone.has-cart{padding-bottom:calc(132px + env(safe-area-inset-bottom))}
  body.standalone .app-tabs{display:grid;grid-template-columns:repeat(4,1fr);position:fixed;z-index:75;left:0;right:0;bottom:0;padding-bottom:env(safe-area-inset-bottom);background:var(--roast);color:var(--parchment);border-top:1px solid var(--espresso)}
  .app-tabs a,.app-tabs button{position:relative;display:flex;flex-direction:column;align-items:center;justify-content:center;gap:4px;min-height:64px;font-size:11px;line-height:1;text-transform:uppercase;letter-spacing:-0.012em;color:inherit}
  .app-tabs .cart-badge{top:8px;right:calc(50% - 22px)}
  body.standalone .cart-bar{bottom:calc(76px + env(safe-area-inset-bottom))}
  body.standalone .toast{bottom:calc(144px + env(safe-area-inset-bottom))}
}
@media(prefers-reduced-motion:reduce){
  html{scroll-behavior:auto}
  *,*::before,*::after{animation:none!important;transition:none!important}
}
</style>
</head>

<body>
<div class="overlay" id="overlay" data-act="close"></div>

<!-- DRAWER (мобильное меню) -->
<nav class="drawer" id="drawer" role="dialog" aria-modal="true" aria-label="Menu">
  <button class="icon-btn drawer-close" type="button" data-act="close" data-i18n-aria="close">
    <svg width="22" height="22" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.2" aria-hidden="true"><path d="M5 5l14 14M19 5L5 19"/></svg>
  </button>
  <ul>
    <li><a href="#story" data-act="close" data-i18n="nav.about"></a></li>
    <li><a href="#menu" data-act="close" data-i18n="nav.menu"></a></li>
    <li><button type="button" data-open="delivery" data-i18n="nav.delivery"></button></li>
    <li><button type="button" data-open="reserve" data-i18n="reserve"></button></li>
    <li><button type="button" data-open="contacts" data-i18n="nav.contacts"></button></li>
    <li><button type="button" data-act="cart" data-i18n="nav.cart"></button></li>
    <li class="js-install install-hidden"><button type="button" data-act="install" data-i18n="install.btn"></button></li>
  </ul>
</nav>

<!-- МОДАЛЬНОЕ ОКНО -->
<div class="modal" id="infoModal" role="dialog" aria-modal="true" aria-labelledby="modalTitle">
  <button class="icon-btn modal-close" type="button" data-act="close" data-i18n-aria="close">
    <svg width="22" height="22" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.2" aria-hidden="true"><path d="M5 5l14 14M19 5L5 19"/></svg>
  </button>
  <h2 class="modal-title" id="modalTitle"></h2>
  <div id="modalBody"></div>
</div>

<!-- HERO -->
<header class="hero" id="top">
  <div class="hero-slides" id="heroSlides" aria-hidden="true"></div>
  <div class="hero-shade"></div>
  <svg class="hero-orn orn" aria-hidden="true" viewBox="0 0 200 200" fill="none" stroke="currentColor" stroke-width="1">
    <circle cx="100" cy="100" r="98"/><circle cx="100" cy="100" r="84.85"/>
    <rect x="40" y="40" width="120" height="120"/><rect x="40" y="40" width="120" height="120" transform="rotate(45 100 100)"/>
    <circle cx="100" cy="100" r="60"/>
    <rect x="58" y="58" width="84" height="84"/><rect x="58" y="58" width="84" height="84" transform="rotate(45 100 100)"/>
    <circle cx="100" cy="100" r="42"/>
    <rect x="80" y="80" width="40" height="40"/><rect x="80" y="80" width="40" height="40" transform="rotate(45 100 100)"/>
  </svg>

  <div class="site-nav">
    <a class="logo" href="#top" aria-label="papağ">
      <svg width="40" height="40" viewBox="0 0 40 40" fill="none" stroke="currentColor" stroke-width="1" aria-hidden="true">
        <path d="M9 31 L10.5 17 C11 12 14 8 20 8 C26 8 29 12 29.5 17 L31 31"/>
        <path d="M7 31 H33"/>
        <path d="M12 14 Q14 11.5 16 14 Q18 11.5 20 14 Q22 11.5 24 14 Q26 11.5 28 14"/>
        <path d="M13 20 Q15 17.5 17 20 Q19 17.5 21 20 Q23 17.5 25 20 Q27 17.5 27.5 20"/>
        <path d="M11 26 Q13 23.5 15 26 Q17 23.5 19 26 Q21 23.5 23 26 Q25 23.5 27 26 Q29 23.5 30 26"/>
      </svg>
    </a>
    <div class="nav-links">
      <a class="nl" href="#story" data-i18n="nav.about"></a>
      <a class="nl" href="#menu" data-i18n="nav.menu"></a>
      <button class="nl" type="button" data-open="delivery" data-i18n="nav.delivery"></button>
      <button class="nl" type="button" data-open="contacts" data-i18n="nav.contacts"></button>
    </div>
    <div class="nav-right">
      <div class="langs">
        <button class="lang-btn" type="button" data-lang="aze" lang="az" aria-label="Azərbaycan dili">AZ</button>
        <button class="lang-btn active" type="button" data-lang="rus" lang="ru" aria-label="Русский язык">RU</button>
        <button class="lang-btn" type="button" data-lang="eng" lang="en" aria-label="English">EN</button>
      </div>
      <button class="icon-btn" id="cartBtn" type="button" data-act="cart">
        <svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.2" aria-hidden="true"><path d="M5 8h14l-1 12H6L5 8z"/><path d="M9 8V6a3 3 0 016 0v2"/></svg>
        <span class="cart-badge" id="cartBadge">0</span>
      </button>
      <button class="btn btn-light btn-sm nav-reserve" id="reserveTop" type="button" data-open="reserve" data-i18n="reserve"></button>
      <button class="icon-btn menu-btn" id="menuBtn" type="button" data-act="drawer">
        <svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.2" aria-hidden="true"><path d="M4 8h16M4 16h16"/></svg>
      </button>
    </div>
  </div>

  <div class="hero-main">
    <div class="hero-meta">
      <span class="cap">Baku, Azərbaycan</span>
      <span class="cap" data-i18n="meta"></span>
    </div>
    <h1 class="wordmark">papağ</h1>
    <div class="hero-rule"></div>
    <div class="hero-bottom">
      <div class="hero-copy">
        <p data-i18n="desc"></p>
        <div class="hero-actions">
          <button class="btn btn-light" type="button" data-open="reserve" data-i18n="reserveTable"></button>
          <a class="btn btn-light" href="#menu" data-i18n="viewMenu"></a>
        </div>
      </div>
      <div class="slider-ctrl">
        <button class="arrow-btn" type="button" data-act="slide" data-d="-1" data-i18n-aria="prevSlide">
          <svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.2" aria-hidden="true"><path d="M15 5l-7 7 7 7"/></svg>
        </button>
        <span class="cap slide-count" id="heroCount" aria-live="off">01 / 03</span>
        <button class="arrow-btn" type="button" data-act="slide" data-d="1" data-i18n-aria="nextSlide">
          <svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.2" aria-hidden="true"><path d="M9 5l7 7-7 7"/></svg>
        </button>
        <div class="hero-dots" id="heroDots"></div>
      </div>
    </div>
  </div>
</header>

<!-- БЕГУЩАЯ СТРОКА -->
<div class="marquee" aria-hidden="true"><div class="mq" id="marqueeTrack"></div></div>

<!-- О НАС -->
<section class="section" id="story">
  <div class="split">
    <div class="split-l">
      <div class="cap" data-i18n="story.tag"></div>
      <h2 class="h2" data-i18n="story.title"></h2>
    </div>
    <div class="split-r" id="storyText"></div>
  </div>
  <div class="principles" id="values"></div>
</section>

<div class="hl"></div>

<!-- МЕНЮ -->
<main class="section" id="menu">
  <div class="menu-head">
    <div>
      <div class="cap" data-i18n="menu.eyebrow"></div>
      <h2 class="h2 h2-xl" data-i18n="menu.title"></h2>
    </div>
    <p data-i18n="menu.intro"></p>
  </div>

  <div class="menu-bar">
    <div class="tabs" id="categoryList" role="group" data-i18n-aria="menu.categoriesLabel"></div>
    <div class="tools">
      <div class="search">
        <input id="dishSearch" type="search" autocomplete="off" data-i18n-ph="menu.search" data-i18n-aria="menu.searchLabel">
        <button class="search-clear" id="searchClear" type="button" data-act="clear-search" data-i18n-aria="menu.clearSearch">
          <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.4" aria-hidden="true"><path d="M5 5l14 14M19 5L5 19"/></svg>
        </button>
      </div>
      <div class="cap results-count" id="resultsCount" aria-live="polite"></div>
    </div>
  </div>

  <div class="dishes-grid" id="dishesList" aria-live="polite"></div>
</main>

<!-- АТМОСФЕРА -->
<section class="section atmo">
  <div class="atmo-grid">
    <div class="atmo-l">
      <div class="cap" data-i18n="atmo.eyebrow"></div>
      <h2 class="h2"><span data-i18n="atmo.l1"></span><span data-i18n="atmo.l2"></span><span data-i18n="atmo.l3"></span></h2>
    </div>
    <div class="atmo-r">
      <div class="atmo-photo" id="atmoPhoto" role="img" data-i18n-aria="atmo.photoAlt"></div>
      <p data-i18n="atmo.text"></p>
      <a class="btn btn-light" href="#menu" data-i18n="atmo.cta"></a>
    </div>
  </div>
</section>

<!-- ФУТЕР -->
<footer class="footer">
  <div class="footer-top">
    <div class="footer-lead">
      <div class="cap">papağ · Baku</div>
      <p data-i18n="footer"></p>
    </div>
    <div class="footer-cols">
      <div class="footer-col">
        <div class="cap" data-i18n="navTitle"></div>
        <a class="nl" href="#story" data-i18n="nav.about"></a>
        <a class="nl" href="#menu" data-i18n="nav.menu"></a>
        <button class="nl" type="button" data-open="reserve" data-i18n="reserve"></button>
        <button class="nl" type="button" data-open="delivery" data-i18n="nav.delivery"></button>
        <button class="nl js-install install-hidden" type="button" data-act="install" data-i18n="install.btn"></button>
      </div>
      <div class="footer-col" id="footerContact"></div>
    </div>
  </div>
  <div class="footer-rule"></div>
  <div class="footer-mark" aria-hidden="true">papağ</div>
  <div class="footer-bottom">
    <span class="cap">© <span id="yearNow"></span> papağ</span>
    <span class="cap">Baku, Azərbaycan</span>
  </div>
</footer>

<!-- Нижняя панель: видна только в установленном приложении на телефоне -->
<nav class="app-tabs" aria-label="App">
  <a href="#top">
    <svg width="22" height="22" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.2" aria-hidden="true"><path d="M4 11l8-7 8 7v9H4z"/></svg>
    <span data-i18n="home"></span>
  </a>
  <a href="#menu">
    <svg width="22" height="22" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.2" aria-hidden="true"><path d="M5 4v7a3 3 0 003 3v6M8 4v6M11 4v7a3 3 0 01-3 3M17 4c-2 2-2 6 0 8v8"/></svg>
    <span data-i18n="nav.menu"></span>
  </a>
  <button type="button" data-act="cart">
    <svg width="22" height="22" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.2" aria-hidden="true"><path d="M5 8h14l-1 12H6L5 8z"/><path d="M9 8V6a3 3 0 016 0v2"/></svg>
    <span data-i18n="nav.cart"></span>
    <span class="cart-badge" id="tabBadge">0</span>
  </button>
  <button type="button" data-open="contacts">
    <svg width="22" height="22" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.2" aria-hidden="true"><path d="M5 4h4l2 5-2.5 1.5a11 11 0 005 5L15 13l5 2v4a1 1 0 01-1 1C10.7 20 4 13.3 4 5a1 1 0 011-1z"/></svg>
    <span data-i18n="nav.contacts"></span>
  </button>
</nav>

<button class="cart-bar" id="cartBar" type="button" data-act="cart">
  <span id="cartBarLeft"></span>
  <span id="cartBarRight"></span>
</button>

<!-- КОРЗИНА -->
<div class="sheet" id="cartSheet" role="dialog" aria-modal="true" aria-labelledby="cartTitle">
  <div class="sheet-head">
    <h2 class="sheet-title" id="cartTitle"></h2>
    <button class="icon-btn" type="button" data-act="close" data-i18n-aria="close">
      <svg width="22" height="22" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.2" aria-hidden="true"><path d="M5 5l14 14M19 5L5 19"/></svg>
    </button>
  </div>
  <div id="cartBody"></div>
</div>

<div class="toast" id="toast" role="status" aria-live="polite"></div>

<script>
"use strict";

/* =====================================================
   НАСТРОЙКИ РЕСТОРАНА
   Пустая строка = пункт не показывается на сайте.
   ===================================================== */
const CONFIG={
  whatsapp:"994507777777",        // только цифры, с кодом страны
  reservePhone:"+994507777777",
  deliveryPhone:"+994125550000",
  instagram:"",                   // например "papag.baku" (без @)
  email:"",
  address:"",
  hours:"",
  currency:"AZN"
};

/* ФОТОГРАФИИ */
const SLIDES=[
  "https://images.unsplash.com/photo-1552566626-52f8b828add9?auto=format&fit=crop&w=1500&q=85",
  "https://images.unsplash.com/photo-1559339352-11d035aa65de?auto=format&fit=crop&w=1500&q=85",
  "https://images.unsplash.com/photo-1414235077428-338989a2e8c0?auto=format&fit=crop&w=1500&q=85"
];
const ATMO_IMAGE="https://images.unsplash.com/photo-1514933651103-005eec06c04b?auto=format&fit=crop&w=1400&q=90";

/* SUPABASE */
const SUPABASE_URL="https://egsrzotgeriqictngmqg.supabase.co";
const SUPABASE_ANON_KEY="sb_publishable_hAJEaZbb0P3hvVm12y-Z4Q_EkFNCp-6";

/* ПЕРЕВОДЫ */
const LANG={
rus:{
  reserve:"Забронировать",reserveTable:"Забронировать стол",viewMenu:"Смотреть меню",home:"Главная",
  install:{btn:"Установить приложение",title:"Установка приложения",
    intro:"Добавьте papağ на главный экран телефона — оно откроется как обычное приложение.",
    steps:["Нажмите «Поделиться» в Safari (квадрат со стрелкой).","Выберите «На экран “Домой”».","Нажмите «Добавить»."],
    other:"В Chrome: меню ⋮ → «Установить приложение».",done:"Приложение установлено"},
  meta:"Азербайджанская кухня",
  desc:"Азербайджанская кухня на живом огне. Плов в шафране, кутабы с зеленью, пити в глиняном горшочке и чай армуду — так, как принято у нас дома.",
  close:"Закрыть",prevSlide:"Предыдущий слайд",nextSlide:"Следующий слайд",navTitle:"Навигация",
  nav:{about:"О нас",menu:"Меню",delivery:"Доставка",contacts:"Контакты",cart:"Корзина"},
  marquee:["Огонь","Чай","Гость","Плов","Кутабы","Пити"],
  story:{
    tag:"О нас · Haqqımızda",title:"Честь гостю — наша традиция",
    paragraphs:[
      "Папаха в Азербайджане — знак чести и достоинства. Мы назвали ресторан в её честь и дали себе одно обещание: каждый, кто садится за наш стол, чувствует себя почётным гостем.",
      "Мы готовим азербайджанскую кухню без компромиссов: огонь мангала, шафран, свежая зелень и блюда, которые никто не торопит."
    ],
    values:[
      ["01","Огонь","Мангал, саж и глиняный горшок. Готовим на живом огне, как принято в азербайджанском доме."],
      ["02","Продукт","Баранина, зелень, овощи, шафран. Простые вещи, которым мы не позволяем быть средними."],
      ["03","Гостеприимство","Чай армуду при встрече, неспешная подача и стол, за которым не хочется смотреть на часы."]
    ]
  },
  menu:{
    eyebrow:"Восточная кухня",title:"Наше меню",
    intro:"Соберите заказ из любимых блюд и отправьте его нам в WhatsApp.",
    search:"Найти блюдо...",searchLabel:"Поиск блюд",clearSearch:"Очистить поиск",categoriesLabel:"Категории меню",
    add:"Добавить",hit:"Хит",found:"Найдено блюд",
    loading:"Загружаем меню...",error:"Не удалось загрузить меню. Проверьте соединение.",retry:"Повторить",
    empty:"Меню скоро появится.",noResults:"Ничего не найдено. Попробуйте другое название.",
    categories:{all:"Все",starters:"Закуски",soups:"Супы",salads:"Салаты",mains:"Основные блюда",desserts:"Десерты",drinks:"Напитки"}
  },
  atmo:{eyebrow:"Атмосфера · Atmosfer",l1:"Огонь.",l2:"Чай.",l3:"Гость.",
    text:"Вечер у нас начинается с горячего чая и заканчивается тогда, когда вам захочется. Мы никуда не торопим.",
    cta:"Выбрать блюда",photoAlt:"Атмосфера ресторана"},
  c:{
    yourOrder:"Ваш заказ",empty:"Корзина пока пуста",total:"Итого",clear:"Очистить корзину",checkout:"Оформление",
    name:"Ваше имя",phone:"Номер телефона",orderType:"Как получить заказ?",delivery:"Доставка",pickup:"Самовывоз",
    address:"Адрес доставки",addressPh:"Улица, дом, квартира, ориентир",comment:"Комментарий к заказу",
    commentPh:"Например: без лука, позвонить при доставке...",send:"Отправить заказ в WhatsApp",
    fill:"Заполните имя и корректный номер телефона.",addressRequired:"Укажите адрес доставки.",
    orderMessage:"Здравствуйте! Хочу оформить заказ:",deliveryWord:"Доставка",pickupWord:"Самовывоз",
    decrease:"Уменьшить",increase:"Увеличить",cart:"Корзина"
  },
  r:{
    title:"Бронирование",intro:"Заполните форму, чтобы отправить заявку на бронирование. Мы свяжемся с вами для подтверждения.",
    name:"Ваше имя",phone:"Номер телефона",date:"Дата посещения",time:"Время",guests:"Количество гостей",note:"Пожелания",
    notePh:"Например: стол у окна, детский стул...",submit:"Отправить заявку в WhatsApp",
    success:"Откроется WhatsApp — отправьте подготовленную заявку.",invalid:"Пожалуйста, заполните все обязательные поля.",
    message:"Здравствуйте! Хочу забронировать стол."
  },
  pages:{
    contacts:{title:"Контакты",reservation:"Бронирование",delivery:"Доставка",email:"Email",address:"Адрес",hours:"Часы работы",instagram:"Instagram",whatsapp:"Написать в WhatsApp"},
    delivery:{title:"Доставка",rows:[["Условия доставки","Стоимость и зона доставки уточняются при заказе."],["Время","Уточняйте у оператора."]],call:"Позвонить",whatsapp:"WhatsApp"}
  },
  footer:"Вкус, к которому хочется возвращаться.",contactTitle:"Контакты"
},
aze:{
  reserve:"Rezerv et",reserveTable:"Masa rezerv et",viewMenu:"Menyuya bax",home:"Əsas",
  install:{btn:"Tətbiqi quraşdır",title:"Tətbiqin quraşdırılması",
    intro:"papağ-ı telefonun ana ekranına əlavə edin — adi tətbiq kimi açılacaq.",
    steps:["Safari-də «Paylaş» düyməsinə basın (oxlu kvadrat).","«Ana ekrana əlavə et» seçin.","«Əlavə et» düyməsinə basın."],
    other:"Chrome-da: menyu ⋮ → «Tətbiqi quraşdır».",done:"Tətbiq quraşdırıldı"},
  meta:"Azərbaycan mətbəxi",
  desc:"Canlı odda bişmiş Azərbaycan mətbəxi. Zəfəranlı plov, göyərtili qutab, küpdə piti və armudu çayı — evimizdəki kimi.",
  close:"Bağla",prevSlide:"Əvvəlki slayd",nextSlide:"Növbəti slayd",navTitle:"Naviqasiya",
  nav:{about:"Haqqımızda",menu:"Menyu",delivery:"Çatdırılma",contacts:"Əlaqə",cart:"Səbət"},
  marquee:["Od","Çay","Qonaq","Plov","Qutab","Piti"],
  story:{
    tag:"Haqqımızda · О нас",title:"Qonağa hörmət — bizim ənənəmiz",
    paragraphs:[
      "Azərbaycanda papaq şərəf və ləyaqət rəmzidir. Restoranı onun adı ilə adlandırdıq və özümüzə bir söz verdik: süfrəmizə əyləşən hər kəs özünü əziz qonaq kimi hiss etməlidir.",
      "Azərbaycan mətbəxini güzəştsiz hazırlayırıq: manqal odu, zəfəran, təzə göyərti və heç kimin tələsdirmədiyi yeməklər."
    ],
    values:[
      ["01","Od","Manqal, sac və gil küp. Yeməkləri Azərbaycan evində olduğu kimi canlı odda bişiririk."],
      ["02","Məhsul","Quzu əti, göyərti, tərəvəz, zəfəran. Sadə şeylər, amma heç vaxt orta səviyyədə deyil."],
      ["03","Qonaqpərvərlik","Görüşdə armudu çayı, tələsməyən xidmət və saata baxmaq istəmədiyiniz süfrə."]
    ]
  },
  menu:{
    eyebrow:"Şərq mətbəxi",title:"Menyumuz",
    intro:"Sevdiyiniz yeməklərdən sifariş toplayın və bizə WhatsApp ilə göndərin.",
    search:"Yemək axtarın...",searchLabel:"Yemək axtarışı",clearSearch:"Axtarışı təmizlə",categoriesLabel:"Menyu kateqoriyaları",
    add:"Əlavə et",hit:"Seçim",found:"Yemək tapıldı",
    loading:"Menyu yüklənir...",error:"Menyunu yükləmək mümkün olmadı. Bağlantını yoxlayın.",retry:"Yenidən cəhd et",
    empty:"Menyu tezliklə əlavə olunacaq.",noResults:"Heç nə tapılmadı. Başqa söz yoxlayın.",
    categories:{all:"Hamısı",starters:"Qəlyanaltılar",soups:"Şorbalar",salads:"Salatlar",mains:"Əsas yeməklər",desserts:"Şirniyyatlar",drinks:"İçkilər"}
  },
  atmo:{eyebrow:"Atmosfer · Атмосфера",l1:"Od.",l2:"Çay.",l3:"Qonaq.",
    text:"Axşam isti çayla başlayır və istədiyiniz vaxt bitir. Biz heç yana tələsmirik.",
    cta:"Yeməkləri seç",photoAlt:"Restoranın atmosferi"},
  c:{
    yourOrder:"Sifarişiniz",empty:"Səbət hələ boşdur",total:"Cəmi",clear:"Səbəti təmizlə",checkout:"Rəsmiləşdirmə",
    name:"Adınız",phone:"Telefon nömrəniz",orderType:"Sifarişi necə əldə edəcəksiniz?",delivery:"Çatdırılma",pickup:"Özüm götürəcəyəm",
    address:"Çatdırılma ünvanı",addressPh:"Küçə, ev, mənzil, istiqamət",comment:"Sifariş haqqında qeyd",
    commentPh:"Məsələn: soğansız hazırlayın...",send:"Sifarişi WhatsApp-a göndər",
    fill:"Adınızı və düzgün telefon nömrənizi daxil edin.",addressRequired:"Çatdırılma ünvanını daxil edin.",
    orderMessage:"Salam! Sifariş vermək istəyirəm:",deliveryWord:"Çatdırılma",pickupWord:"Özüm götürəcəyəm",
    decrease:"Azalt",increase:"Artır",cart:"Səbət"
  },
  r:{
    title:"Masa rezervi",intro:"Masa rezervasiyası üçün formanı doldurun. Təsdiq üçün sizinlə əlaqə saxlayacağıq.",
    name:"Adınız",phone:"Telefon nömrəniz",date:"Tarix",time:"Saat",guests:"Qonaqların sayı",note:"Əlavə qeydlər",
    notePh:"Məsələn: pəncərə kənarında masa...",submit:"WhatsApp ilə rezervasiya göndər",
    success:"WhatsApp açılacaq. Zəhmət olmasa, müraciəti göndərin.",invalid:"Zəhmət olmasa, vacib xanaları doldurun.",
    message:"Salam! Masa rezerv etmək istəyirəm."
  },
  pages:{
    contacts:{title:"Əlaqə",reservation:"Rezerv",delivery:"Çatdırılma",email:"Email",address:"Ünvan",hours:"İş saatları",instagram:"Instagram",whatsapp:"WhatsApp-da yaz"},
    delivery:{title:"Çatdırılma",rows:[["Çatdırılma şərtləri","Qiymət və ərazi sifariş zamanı dəqiqləşdirilir."],["Vaxt","Operatordan dəqiqləşdirin."]],call:"Zəng et",whatsapp:"WhatsApp"}
  },
  footer:"Yenidən qayıtmaq istədiyiniz dad.",contactTitle:"Əlaqə"
},
eng:{
  reserve:"Reserve",reserveTable:"Reserve a table",viewMenu:"View menu",home:"Home",
  install:{btn:"Install app",title:"Install the app",
    intro:"Add papağ to your phone's home screen — it opens like a regular app.",
    steps:["Tap Share in Safari (the square with an arrow).","Choose “Add to Home Screen”.","Tap Add."],
    other:"In Chrome: menu ⋮ → “Install app”.",done:"App installed"},
  meta:"Azerbaijani cuisine",
  desc:"Azerbaijani cuisine cooked over live fire. Saffron plov, qutab with herbs, piti in a clay pot and armudu tea — the way we serve it at home.",
  close:"Close",prevSlide:"Previous slide",nextSlide:"Next slide",navTitle:"Navigation",
  nav:{about:"About us",menu:"Menu",delivery:"Delivery",contacts:"Contacts",cart:"Cart"},
  marquee:["Fire","Tea","Guest","Plov","Qutab","Piti"],
  story:{
    tag:"About us · Haqqımızda",title:"Honouring the guest is our tradition",
    paragraphs:[
      "In Azerbaijan the papakha is a symbol of honour and dignity. We named the restaurant after it and made ourselves one promise: everyone who sits at our table feels like a guest of honour.",
      "We cook Azerbaijani cuisine without compromise: charcoal fire, saffron, fresh herbs and dishes nobody rushes."
    ],
    values:[
      ["01","Fire","Mangal, saj and clay pot. We cook over live fire, the way it is done in an Azerbaijani home."],
      ["02","Produce","Lamb, herbs, vegetables, saffron. Simple things we never allow to be ordinary."],
      ["03","Hospitality","Armudu tea on arrival, an unhurried pace and a table where you never watch the clock."]
    ]
  },
  menu:{
    eyebrow:"Eastern cuisine",title:"Our menu",
    intro:"Build your order from your favourite dishes and send it to us on WhatsApp.",
    search:"Search dishes...",searchLabel:"Search dishes",clearSearch:"Clear search",categoriesLabel:"Menu categories",
    add:"Add",hit:"Signature",found:"Dishes found",
    loading:"Loading the menu...",error:"We could not load the menu. Please check your connection.",retry:"Try again",
    empty:"The menu will appear soon.",noResults:"No dishes found. Try another search.",
    categories:{all:"All",starters:"Starters",soups:"Soups",salads:"Salads",mains:"Main dishes",desserts:"Desserts",drinks:"Drinks"}
  },
  atmo:{eyebrow:"Atmosphere · Atmosfer",l1:"Fire.",l2:"Tea.",l3:"Guest.",
    text:"The evening begins with hot tea and ends whenever you like. We never rush you.",
    cta:"Choose dishes",photoAlt:"Restaurant atmosphere"},
  c:{
    yourOrder:"Your order",empty:"Your cart is empty",total:"Total",clear:"Clear cart",checkout:"Checkout",
    name:"Your name",phone:"Phone number",orderType:"How would you like to receive it?",delivery:"Delivery",pickup:"Pickup",
    address:"Delivery address",addressPh:"Street, building, apartment, directions",comment:"Order notes",
    commentPh:"For example: no onions, please call on arrival...",send:"Send order via WhatsApp",
    fill:"Please enter your name and a valid phone number.",addressRequired:"Please enter your delivery address.",
    orderMessage:"Hello! I would like to place an order:",deliveryWord:"Delivery",pickupWord:"Pickup",
    decrease:"Decrease",increase:"Increase",cart:"Cart"
  },
  r:{
    title:"Table reservation",intro:"Fill in the form to request a table reservation. We will contact you to confirm.",
    name:"Your name",phone:"Phone number",date:"Reservation date",time:"Time",guests:"Number of guests",note:"Additional requests",
    notePh:"For example: a table by the window...",submit:"Send reservation via WhatsApp",
    success:"WhatsApp will open. Please send the prepared request.",invalid:"Please complete all required fields.",
    message:"Hello! I would like to reserve a table."
  },
  pages:{
    contacts:{title:"Contacts",reservation:"Reservations",delivery:"Delivery",email:"Email",address:"Address",hours:"Opening hours",instagram:"Instagram",whatsapp:"Message on WhatsApp"},
    delivery:{title:"Delivery",rows:[["Delivery terms","Delivery fee and area are confirmed when ordering."],["Time","Please check with the operator."]],call:"Call",whatsapp:"WhatsApp"}
  },
  footer:"A taste worth coming back for.",contactTitle:"Contacts"
}
};

/* ---------- СОСТОЯНИЕ ---------- */
let DISHES=[];
let menuState="loading";          // loading | ready | error
let currentLang="rus";
let activeCategory="all";
let searchQuery="";
let orderType="delivery";
let cart={};
let savedCart={};
let slideIndex=0;
let slideTimer=null;
let currentModal=null;            // {type:"page",key} | {type:"dish",id}
let lastFocus=null;
const draft={customerName:"",customerPhone:"",customerAddress:"",customerComment:""};

const $=id=>document.getElementById(id);
const t=()=>LANG[currentLang];
const money=n=>`${n} ${CONFIG.currency}`;
const PHONE_RE=/^[+0-9()\-\s]{7,25}$/;
const get=(obj,path)=>path.split(".").reduce((o,k)=>(o==null?o:o[k]),obj);
function esc(v){
  return String(v).replace(/[&<>"']/g,c=>({"&":"&amp;","<":"&lt;",">":"&gt;",'"':"&quot;","'":"&#39;"}[c]));
}
const telHref=p=>"tel:"+String(p).replace(/[^+\d]/g,"");
const validWA=()=>/^\d{8,15}$/.test(CONFIG.whatsapp||"");

const ORN_SVG='<svg class="orn" viewBox="0 0 200 200" fill="none" stroke="currentColor" stroke-width="1" aria-hidden="true"><circle cx="100" cy="100" r="98"/><rect x="40" y="40" width="120" height="120"/><rect x="40" y="40" width="120" height="120" transform="rotate(45 100 100)"/></svg>';
const STAR_SVG='<svg class="orn" width="28" height="28" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1" aria-hidden="true"><rect x="5" y="5" width="14" height="14"/><rect x="5" y="5" width="14" height="14" transform="rotate(45 12 12)"/></svg>';

/* ---------- ДАННЫЕ ИЗ SUPABASE & КЕШИРОВАНИЕ ---------- */
function mapDish(item){
  const img=typeof item.image_url==="string"&&/^https?:\/\//i.test(item.image_url)?item.image_url:null;
  return{
    id:String(item.id),
    cat:item.category||"drinks",
    price:Number(item.price)||0,
    hit:Boolean(item.hit),
    img,
    t:{
      rus:[item.name_ru||"Блюдо",item.description_ru||item.description||""],
      aze:[item.name_az||item.name_ru||"Yemək",item.description_az||item.description||""],
      eng:[item.name_en||item.name_ru||"Dish",item.description_en||item.description||""]
    }
  };
}

function loadCachedDishes(){
  try{
    const cached=localStorage.getItem("papagDishesCache");
    if(cached){
      const parsed=JSON.parse(cached);
      if(Array.isArray(parsed)&&parsed.length){
        DISHES=parsed;
        menuState="ready";
        applySavedCart();
        renderCategories();
        renderMenu();
        renderMarquee();
        updateCartUI();
      }
    }
  }catch(e){}
}

async function fetchDishes(){
  loadCachedDishes();
  if(menuState!=="ready"){
    menuState="loading";
    renderMenu();
  }

  const controller=new AbortController();
  const timeoutId=setTimeout(()=>controller.abort(),8000); // 8 секунд таймаут

  try{
    const response=await fetch(`${SUPABASE_URL}/rest/v1/dishes?select=*`,{
      headers:{apikey:SUPABASE_ANON_KEY,Authorization:`Bearer ${SUPABASE_ANON_KEY}`},
      signal:controller.signal
    });
    clearTimeout(timeoutId);
    if(!response.ok)throw new Error("HTTP "+response.status);
    const data=await response.json();
    if(!Array.isArray(data))throw new Error("Unexpected response");
    
    DISHES=data.map(mapDish);
    try{localStorage.setItem("papagDishesCache",JSON.stringify(DISHES));}catch(e){}

    applySavedCart();
    menuState="ready";
  }catch(err){
    console.error("Ошибка загрузки меню:",err);
    if(!DISHES.length)menuState="error";
  }
  renderCategories();
  renderMenu();
  renderMarquee();
  updateCartUI();
}

/* ---------- КОРЗИНА: ХРАНЕНИЕ ---------- */
function loadSavedCart(){
  try{
    const raw=JSON.parse(localStorage.getItem("papagCart")||"{}");
    if(raw&&typeof raw==="object"&&!Array.isArray(raw))savedCart=raw;
  }catch(e){savedCart={};}
}
function applySavedCart(){
  DISHES.forEach(d=>{
    const q=Number(savedCart[d.id]);
    if(Number.isInteger(q)&&q>0&&q<100)cart[d.id]=q;
  });
}
function saveCart(){
  try{localStorage.setItem("papagCart",JSON.stringify(cart));}catch(e){}
}
const dishById=id=>DISHES.find(d=>d.id===id);
const dishName=d=>d.t[currentLang][0];
const dishDesc=d=>d.t[currentLang][1];
function cartTotals(){
  let count=0,sum=0;
  Object.entries(cart).forEach(([id,q])=>{
    const d=dishById(id);
    if(d){count+=q;sum+=q*d.price;}
  });
  return{count,sum};
}
function toast(message){
  const el=$("toast");
  el.textContent=message;
  el.classList.add("show");
  clearTimeout(toast.timer);
  toast.timer=setTimeout(()=>el.classList.remove("show"),2800);
}

/* ---------- ЯЗЫК ---------- */
function applyStatic(){
  document.querySelectorAll("[data-i18n]").forEach(el=>{const v=get(t(),el.dataset.i18n);if(typeof v==="string")el.textContent=v;});
  document.querySelectorAll("[data-i18n-ph]").forEach(el=>{const v=get(t(),el.dataset.i18nPh);if(typeof v==="string")el.placeholder=v;});
  document.querySelectorAll("[data-i18n-aria]").forEach(el=>{const v=get(t(),el.dataset.i18nAria);if(typeof v==="string")el.setAttribute("aria-label",v);});
}
function setLanguage(lang){
  if(!LANG[lang])return;
  currentLang=lang;
  try{localStorage.setItem("papagLang",lang);}catch(e){}
  document.documentElement.lang={rus:"ru",aze:"az",eng:"en"}[lang];
  document.querySelectorAll(".lang-btn").forEach(b=>{
    const on=b.dataset.lang===lang;
    b.classList.toggle("active",on);
    b.setAttribute("aria-pressed",on);
  });
  $("cartBtn").setAttribute("aria-label",t().c.cart);
  $("menuBtn").setAttribute("aria-label",t().nav.menu);
  applyStatic();
  renderCategories();
  renderMenu();
  renderMarquee();
  renderStory();
  renderFooter();
  updateCartUI();
  if(currentModal){
    if(currentModal.type==="page")openPage(currentModal.key);
    else openDish(currentModal.id);
  }
}

/* ---------- КАТЕГОРИИ ---------- */
function renderCategories(){
  $("categoryList").innerHTML=Object.entries(t().menu.categories).map(([key,label])=>
    `<button class="tab${key===activeCategory?" active":""}" type="button" data-cat="${esc(key)}" aria-pressed="${key===activeCategory}">${esc(label)}</button>`
  ).join("");
}
function filterMenu(category){
  activeCategory=category;
  renderCategories();
  renderMenu();
  const active=document.querySelector(".tab.active");
  if(active)active.scrollIntoView({inline:"center",block:"nearest",behavior:"smooth"});
}

/* ---------- МЕНЮ ---------- */
function controlHTML(id){
  const q=cart[id]||0;
  if(!q){
    return `<button class="btn btn-dark btn-block" type="button" data-qty="${esc(id)}" data-d="1">＋ ${esc(t().menu.add)}</button>`;
  }
  return `<div class="stepper"><button type="button" data-qty="${esc(id)}" data-d="-1" aria-label="${esc(t().c.decrease)}">−</button><span>${q}</span><button type="button" data-qty="${esc(id)}" data-d="1" aria-label="${esc(t().c.increase)}">+</button></div>`;
}
function refreshControls(id){
  document.querySelectorAll("[data-ctrl]").forEach(el=>{
    if(el.dataset.ctrl===id)el.innerHTML=controlHTML(id);
  });
}
function cardHTML(d){
  const name=esc(dishName(d));
  const desc=dishDesc(d);
  const media=d.img?`<img src="${esc(d.img)}" alt="" loading="lazy" onload="this.classList.add('loaded')">`:`<span class="dish-ph" aria-hidden="true">${ORN_SVG}</span>`;
  return `
    <article class="dish-card">
      <button class="dish-image" type="button" data-dish="${esc(d.id)}" aria-label="${name}">
        ${media}${d.hit?`<span class="tag">★ ${esc(t().menu.hit)}</span>`:""}
      </button>
      <div class="dish-info">
        <div class="dish-head">
          <h3 class="dish-name"><button type="button" data-dish="${esc(d.id)}">${name}</button></h3>
          <span class="dish-price">${esc(money(d.price))}</span>
        </div>
        ${desc?`<p class="dish-description">${esc(desc)}</p>`:""}
        <div class="dish-bottom" data-ctrl="${esc(d.id)}">${controlHTML(d.id)}</div>
      </div>
    </article>`;
}
function note(message,withRetry){
  return `<div class="grid-note"><p>${esc(message)}</p>${withRetry?`<button class="btn btn-dark btn-sm" type="button" data-act="retry">${esc(t().menu.retry)}</button>`:""}</div>`;
}
function filteredDishes(){
  const q=searchQuery.trim().toLocaleLowerCase();
  return DISHES.filter(d=>{
    const catOk=activeCategory==="all"||d.cat===activeCategory;
    const hay=[d.id,...Object.values(d.t).flat()].join(" ").toLocaleLowerCase();
    return catOk&&(!q||hay.includes(q));
  });
}
function renderMenu(){
  const grid=$("dishesList");
  const count=$("resultsCount");
  if(menuState==="loading"){count.textContent="";grid.innerHTML=note(t().menu.loading);return;}
  if(menuState==="error"){count.textContent="";grid.innerHTML=note(t().menu.error,true);return;}
  if(!DISHES.length){count.textContent="";grid.innerHTML=note(t().menu.empty);return;}
  const list=filteredDishes();
  count.textContent=`${t().menu.found}: ${list.length}`;
  if(!list.length){grid.innerHTML=note(t().menu.noResults);return;}
  grid.innerHTML=list.map(cardHTML).join("");
  grid.querySelectorAll(".dish-image img").forEach(img=>{
    img.addEventListener("error",()=>{
      const ph=document.createElement("span");
      ph.className="dish-ph";
      ph.setAttribute("aria-hidden","true");
      ph.innerHTML=ORN_SVG;
      img.replaceWith(ph);
    },{once:true});
  });
}
function changeQty(id,delta){
  if(!dishById(id))return;
  const next=(cart[id]||0)+delta;
  if(next<=0)delete cart[id];
  else cart[id]=Math.min(next,99);
  saveCart();
  refreshControls(id);
  updateCartUI();
}
function clearSearch(){
  $("dishSearch").value="";
  searchQuery="";
  $("searchClear").style.display="none";
  renderMenu();
  $("dishSearch").focus();
}

/* ---------- БЕГУЩАЯ СТРОКА ---------- */
function renderMarquee(){
  let words=DISHES.slice(0,10).map(dishName);
  if(words.length<3)words=t().marquee.slice();
  const list=[];
  while(list.length<10)words.forEach(w=>list.push(w));
  const half=`<div class="mq-half">${list.map(w=>`<span>${esc(w)}</span>${STAR_SVG}`).join("")}</div>`;
  $("marqueeTrack").innerHTML=half+half;
}

/* ---------- О НАС / ФУТЕР ---------- */
function renderStory(){
  const s=t().story;
  $("storyText").innerHTML=s.paragraphs.map(p=>`<p>${esc(p)}</p>`).join("");
  $("values").innerHTML=s.values.map(v=>
    `<div class="principle"><div class="cap">${esc(v[0])}</div><h3>${esc(v[1])}</h3><p>${esc(v[2])}</p></div>`).join("");
}
function renderFooter(){
  const rows=[`<div class="cap">${esc(t().contactTitle)}</div>`];
  if(CONFIG.reservePhone)rows.push(`<a class="nl" href="${esc(telHref(CONFIG.reservePhone))}">${esc(CONFIG.reservePhone)}</a>`);
  if(CONFIG.address)rows.push(`<span class="nl">${esc(CONFIG.address)}</span>`);
  if(CONFIG.instagram)rows.push(`<a class="nl" href="https://www.instagram.com/${encodeURIComponent(CONFIG.instagram)}/" target="_blank" rel="noopener noreferrer">Instagram</a>`);
  rows.push(`<button class="nl" type="button" data-open="contacts">${esc(t().nav.contacts)}</button>`);
  $("footerContact").innerHTML=rows.join("");
}
function goToStory(){
  closeAll();
  $("story").scrollIntoView({behavior:"smooth",block:"start"});
}

/* ---------- СЛОИ: drawer / modal / sheet ---------- */
function focusFirst(panel){
  setTimeout(()=>{
    const el=panel.querySelector("input,select,textarea,button,a[href]");
    if(el)el.focus({preventScroll:true});
  },60);
}
function setLayer(name){
  const wasOpen=document.body.classList.contains("lock");
  if(!wasOpen&&name)lastFocus=document.activeElement;
  $("drawer").classList.toggle("open",name==="drawer");
  $("infoModal").classList.toggle("show",name==="modal");
  $("cartSheet").classList.toggle("open",name==="sheet");
  $("overlay").classList.toggle("show",!!name);
  document.body.classList.toggle("lock",!!name);
  if(name!=="modal")currentModal=null;
  if(name){
    focusFirst({drawer:$("drawer"),modal:$("infoModal"),sheet:$("cartSheet")}[name]);
  }else if(lastFocus&&typeof lastFocus.focus==="function"){
    try{lastFocus.focus({preventScroll:true});}catch(e){}
    lastFocus=null;
  }
}
function closeAll(){setLayer(null);}
function toggleDrawer(){
  if($("drawer").classList.contains("open"))closeAll();
  else setLayer("drawer");
}

/* ---------- СТРАНИЦЫ В МОДАЛЬНОМ ОКНЕ ---------- */
function infoRow(label,valueHTML){
  return `<div class="info-row"><span class="cap">${esc(label)}</span><span class="info-val">${valueHTML}</span></div>`;
}
function showModal(title,html){
  $("modalTitle").textContent=title;
  $("modalBody").innerHTML=html;
  setLayer("modal");
}
function waLink(label){
  return validWA()?`<a class="btn btn-dark" href="https://wa.me/${CONFIG.whatsapp}" target="_blank" rel="noopener noreferrer">${esc(label)}</a>`:"";
}
function openPage(key){
  const p=t().pages;
  if(key==="contacts"){
    let rows="";
    if(CONFIG.reservePhone)rows+=infoRow(p.contacts.reservation,`<a href="${esc(telHref(CONFIG.reservePhone))}">${esc(CONFIG.reservePhone)}</a>`);
    if(CONFIG.deliveryPhone)rows+=infoRow(p.contacts.delivery,`<a href="${esc(telHref(CONFIG.deliveryPhone))}">${esc(CONFIG.deliveryPhone)}</a>`);
    if(CONFIG.email)rows+=infoRow(p.contacts.email,`<a href="mailto:${esc(CONFIG.email)}">${esc(CONFIG.email)}</a>`);
    if(CONFIG.address)rows+=infoRow(p.contacts.address,esc(CONFIG.address));
    if(CONFIG.hours)rows+=infoRow(p.contacts.hours,esc(CONFIG.hours));
    if(CONFIG.instagram)rows+=infoRow(p.contacts.instagram,`<a href="https://www.instagram.com/${encodeURIComponent(CONFIG.instagram)}/" target="_blank" rel="noopener noreferrer">@${esc(CONFIG.instagram)}</a>`);
    const wa=waLink(p.contacts.whatsapp);
    showModal(p.contacts.title,rows+(wa?`<div class="modal-actions">${wa}</div>`:""));
    currentModal={type:"page",key};
  }else if(key==="delivery"){
    const rows=p.delivery.rows.map(r=>infoRow(r[0],esc(r[1]))).join("");
    const actions=`<div class="modal-actions">${CONFIG.deliveryPhone?`<a class="btn btn-dark" href="${esc(telHref(CONFIG.deliveryPhone))}">${esc(p.delivery.call)}</a>`:""}${waLink(p.delivery.whatsapp)}</div>`;
    showModal(p.delivery.title,rows+actions);
    currentModal={type:"page",key};
  }else if(key==="install"){
    const i=t().install;
    const steps=i.steps.map((s,n)=>`<div class="info-row step"><span class="cap">${n+1}</span><span class="info-val">${esc(s)}</span></div>`).join("");
    showModal(i.title,`<p class="modal-intro">${esc(i.intro)}</p>${steps}<p class="form-note">${esc(i.other)}</p>`);
    currentModal={type:"page",key};
  }else if(key==="reserve"){
    showModal(t().r.title,reservationFormHTML());
    currentModal={type:"page",key};
    $("reservationForm").addEventListener("submit",submitReservation);
  }
}
function openDish(id){
  const d=dishById(id);
  if(!d)return;
  const name=dishName(d),desc=dishDesc(d);
  const media=d.img?`<div class="dish-modal-img"><img src="${esc(d.img)}" alt="${esc(name)}"></div>`:"";
  showModal(name,`${media}<div class="modal-price">${esc(money(d.price))}</div>${desc?`<p class="modal-desc">${esc(desc)}</p>`:""}<div data-ctrl="${esc(d.id)}">${controlHTML(d.id)}</div>`);
  currentModal={type:"dish",id};
  const img=$("modalBody").querySelector(".dish-modal-img img");
  if(img)img.addEventListener("error",()=>img.parentElement.remove(),{once:true});
}

/* ---------- КОРЗИНА ---------- */
function updateCartUI(){
  const{count,sum}=cartTotals();
  $("cartBadge").textContent=count;
  $("cartBadge").style.display=count?"block":"none";
  $("tabBadge").textContent=count;
  $("tabBadge").style.display=count?"block":"none";
  $("cartBar").style.display=count?"flex":"none";
  document.body.classList.toggle("has-cart",count>0);
  $("cartBarLeft").textContent=`${t().c.cart} · ${count}`;
  $("cartBarRight").textContent=money(sum);
  if($("cartSheet").classList.contains("open"))renderCartSheet();
}
function openCart(){
  setLayer("sheet");
  renderCartSheet();
}
function readDraft(){
  Object.keys(draft).forEach(id=>{const el=$(id);if(el)draft[id]=el.value;});
}
function renderCartSheet(){
  readDraft();
  const c=t().c;
  const{count,sum}=cartTotals();
  $("cartTitle").textContent=c.yourOrder;
  const body=$("cartBody");
  if(!count){
    body.innerHTML=`<div class="cart-empty">${esc(c.empty)}</div>`;
    return;
  }
  let rows="";
  Object.entries(cart).forEach(([id,q])=>{
    const d=dishById(id);
    if(!d)return;
    rows+=`
      <div class="cart-row">
        <div>
          <div class="cart-row-name">${esc(dishName(d))}</div>
          <div class="cart-row-sub">${esc(money(d.price))} × ${q} = ${esc(money(d.price*q))}</div>
        </div>
        <div class="mini">
          <button type="button" data-qty="${esc(id)}" data-d="-1" aria-label="${esc(c.decrease)}">−</button>
          <span>${q}</span>
          <button type="button" data-qty="${esc(id)}" data-d="1" aria-label="${esc(c.increase)}">+</button>
        </div>
      </div>`;
  });
  body.innerHTML=`
    ${rows}
    <div class="cart-total"><span>${esc(c.total)}</span><strong>${esc(money(sum))}</strong></div>
    <h3 class="checkout-title">${esc(c.checkout)}</h3>
    <form id="checkoutForm" novalidate>
      <div class="form-grid" style="margin-bottom:16px">
        <div class="field">
          <label class="cap" for="customerName">${esc(c.name)} *</label>
          <input class="fld" id="customerName" name="name" autocomplete="name" maxlength="60" required>
        </div>
        <div class="field">
          <label class="cap" for="customerPhone">${esc(c.phone)} *</label>
          <input class="fld" id="customerPhone" name="phone" type="tel" autocomplete="tel" maxlength="25" placeholder="+994..." required>
        </div>
      </div>
      <div class="field">
        <div class="cap" style="margin-bottom:8px">${esc(c.orderType)}</div>
        <div class="seg">
          <button type="button" data-otype="delivery" aria-pressed="${orderType==="delivery"}">${esc(c.delivery)}</button>
          <button type="button" data-otype="pickup" aria-pressed="${orderType==="pickup"}">${esc(c.pickup)}</button>
        </div>
      </div>
      <div class="field${orderType==="pickup"?" hidden":""}" id="addressField">
        <label class="cap" for="customerAddress">${esc(c.address)} *</label>
        <textarea class="fld" id="customerAddress" name="address" maxlength="250" placeholder="${esc(c.addressPh)}"></textarea>
      </div>
      <div class="field">
        <label class="cap" for="customerComment">${esc(c.comment)}</label>
        <textarea class="fld" id="customerComment" name="comment" maxlength="500" placeholder="${esc(c.commentPh)}"></textarea>
      </div>
      <button class="btn btn-dark btn-block" id="checkoutSubmitBtn" type="submit">${esc(c.send)}</button>
    </form>
    <button class="clear-cart" type="button" data-act="clear-cart">${esc(c.clear)}</button>`;
  Object.keys(draft).forEach(id=>{const el=$(id);if(el)el.value=draft[id];});
  $("checkoutForm").addEventListener("submit",submitOrder);
}
function setOrderType(type){
  orderType=type;
  renderCartSheet();
}
function submitOrder(event){
  event.preventDefault();
  const c=t().c;
  const btn=$("checkoutSubmitBtn");
  const name=$("customerName").value.trim();
  const phone=$("customerPhone").value.trim();
  const address=$("customerAddress")?$("customerAddress").value.trim():"";
  const comment=$("customerComment").value.trim();

  if(!name||!PHONE_RE.test(phone)){
    toast(c.fill);
    (!name?$("customerName"):$("customerPhone")).focus();
    return;
  }
  if(orderType==="delivery"&&!address){
    toast(c.addressRequired);
    $("customerAddress").focus();
    return;
  }
  const{sum}=cartTotals();
  const lines=Object.entries(cart).map(([id,q])=>{
    const d=dishById(id);
    return d?`• ${dishName(d)} × ${q} — ${money(d.price*q)}`:"";
  }).filter(Boolean);
  const message=[
    c.orderMessage,"",...lines,"",
    `${c.total}: ${money(sum)}`,"",
    `${c.name}: ${name}`,
    `${c.phone}: ${phone}`,
    `${c.orderType}: ${orderType==="delivery"?c.deliveryWord:c.pickupWord}`,
    orderType==="delivery"?`${c.address}: ${address}`:"",
    comment?`${c.comment}: ${comment}`:""
  ].filter(Boolean).join("\n");

  if(btn)btn.disabled=true;
  openWhatsApp(message);
  clearCart(); // Автоматическая очистка корзины после отправки
  setTimeout(()=>{const b=$("checkoutSubmitBtn");if(b)b.disabled=false;},2000);
}
function clearCart(){
  cart={};
  saveCart();
  renderMenu();
  updateCartUI();
}

/* ---------- БРОНИРОВАНИЕ ---------- */
function reservationFormHTML(){
  const r=t().r;
  const now=new Date();
  const today=new Date(now.getTime()-now.getTimezoneOffset()*60000).toISOString().split("T")[0];
  const guests=[...Array(10)].map((_,i)=>`<option value="${i+1}"${i===1?" selected":""}>${i+1}</option>`).join("")+`<option value="11+">11+</option>`;
  return `
    <p class="modal-intro">${esc(r.intro)}</p>
    <form id="reservationForm" novalidate>
      <div class="form-grid">
        <div class="field">
          <label class="cap" for="reserveName">${esc(r.name)} *</label>
          <input class="fld" id="reserveName" name="name" maxlength="60" autocomplete="name" required>
        </div>
        <div class="field">
          <label class="cap" for="reservePhone">${esc(r.phone)} *</label>
          <input class="fld" id="reservePhone" name="phone" type="tel" maxlength="25" placeholder="+994..." autocomplete="tel" required>
        </div>
        <div class="field">
          <label class="cap" for="reserveDate">${esc(r.date)} *</label>
          <input class="fld" id="reserveDate" name="date" type="date" min="${today}" required>
        </div>
        <div class="field">
          <label class="cap" for="reserveTime">${esc(r.time)} *</label>
          <input class="fld" id="reserveTime" name="time" type="time" required>
        </div>
        <div class="field full">
          <label class="cap" for="reserveGuests">${esc(r.guests)} *</label>
          <select class="fld" id="reserveGuests" name="guests" required>${guests}</select>
        </div>
        <div class="field full">
          <label class="cap" for="reserveNote">${esc(r.note)}</label>
          <textarea class="fld" id="reserveNote" name="note" maxlength="400" placeholder="${esc(r.notePh)}"></textarea>
        </div>
      </div>
      <button class="btn btn-dark btn-block" id="reserveSubmitBtn" type="submit" style="margin-top:20px">${esc(r.submit)}</button>
      <p class="form-note">${esc(r.success)}</p>
    </form>`;
}
function submitReservation(event){
  event.preventDefault();
  const r=t().r;
  const btn=$("reserveSubmitBtn");
  const name=$("reserveName").value.trim();
  const phone=$("reservePhone").value.trim();
  const date=$("reserveDate").value;
  const time=$("reserveTime").value;
  const guests=$("reserveGuests").value;
  const note=$("reserveNote").value.trim();

  if(!name||!phone||!date||!time||!guests||!PHONE_RE.test(phone)){
    toast(r.invalid);
    return;
  }
  const message=[
    r.message,"",
    `${r.name}: ${name}`,
    `${r.phone}: ${phone}`,
    `${r.date}: ${date}`,
    `${r.time}: ${time}`,
    `${r.guests}: ${guests}`,
    note?`${r.note}: ${note}`:""
  ].filter(Boolean).join("\n");

  if(btn)btn.disabled=true;
  openWhatsApp(message);
  closeAll();
  setTimeout(()=>{const b=$("reserveSubmitBtn");if(b)b.disabled=false;},2000);
}
function openWhatsApp(message){
  if(!validWA()){
    toast("Проверьте номер WhatsApp в настройках сайта.");
    return;
  }
  const url=`https://wa.me/${CONFIG.whatsapp}?text=${encodeURIComponent(message)}`;
  const opened=window.open(url,"_blank","noopener,noreferrer");
  if(!opened)window.location.href=url;
}

/* ---------- СЛАЙДЕР ---------- */
function initSlider(){
  $("heroSlides").innerHTML="";
  $("heroDots").innerHTML="";
  SLIDES.forEach((src,i)=>{
    const slide=document.createElement("div");
    slide.className="hero-slide"+(i===0?" active":"");
    slide.style.backgroundImage=`url("${src}")`;
    $("heroSlides").appendChild(slide);
    const dot=document.createElement("button");
    dot.type="button";
    dot.className="hero-dot"+(i===0?" active":"");
    dot.setAttribute("aria-label",`Slide ${i+1}`);
    dot.addEventListener("click",()=>{slideIndex=i;updateSlide();startSlider();});
    $("heroDots").appendChild(dot);
  });
  updateSlide();
}
function updateSlide(){
  document.querySelectorAll(".hero-slide").forEach((s,i)=>s.classList.toggle("active",i===slideIndex));
  document.querySelectorAll(".hero-dot").forEach((d,i)=>d.classList.toggle("active",i===slideIndex));
  const pad=n=>String(n).padStart(2,"0");
  $("heroCount").textContent=`${pad(slideIndex+1)} / ${pad(SLIDES.length)}`;
}
function moveSlide(direction){
  slideIndex=(slideIndex+direction+SLIDES.length)%SLIDES.length;
  updateSlide();
  startSlider();
}
function startSlider(){
  clearInterval(slideTimer);
  if(window.matchMedia("(prefers-reduced-motion: reduce)").matches)return;
  slideTimer=setInterval(()=>{slideIndex=(slideIndex+1)%SLIDES.length;updateSlide();},5500);
}
document.addEventListener("visibilitychange",()=>{
  if(document.hidden)clearInterval(slideTimer);
  else startSlider();
});

/* ---------- СОБЫТИЯ ---------- */
document.addEventListener("click",e=>{
  const target=e.target;
  if(!(target instanceof Element))return;

  const qty=target.closest("[data-qty]");
  if(qty){
    const id=qty.dataset.qty,d=Number(qty.dataset.d);
    const inCart=!!qty.closest("#cartBody");
    const inModal=!!qty.closest("#infoModal");
    changeQty(id,d);
    const root=inCart?$("cartBody"):[...document.querySelectorAll("[data-ctrl]")]
      .find(el=>el.dataset.ctrl===id&&!!el.closest("#infoModal")===inModal);
    if(root){
      const again=root.querySelector(`[data-qty][data-d="${d}"]`)||root.querySelector("[data-qty]");
      if(again)again.focus({preventScroll:true});
    }
    return;
  }
  const dish=target.closest("[data-dish]");
  if(dish){openDish(dish.dataset.dish);return;}
  const cat=target.closest("[data-cat]");
  if(cat){filterMenu(cat.dataset.cat);return;}
  const lang=target.closest("[data-lang]");
  if(lang){setLanguage(lang.dataset.lang);return;}
  const ot=target.closest("[data-otype]");
  if(ot){setOrderType(ot.dataset.otype);return;}
  const open=target.closest("[data-open]");
  if(open){openPage(open.dataset.open);return;}
  const act=target.closest("[data-act]");
  if(!act)return;
  switch(act.dataset.act){
    case "close":closeAll();break;
    case "cart":openCart();break;
    case "drawer":toggleDrawer();break;
    case "story":goToStory();break;
    case "retry":fetchDishes();break;
    case "slide":moveSlide(Number(act.dataset.d));break;
    case "clear-cart":clearCart();break;
    case "clear-search":clearSearch();break;
    case "install":installApp();break;
  }
});
$("dishSearch").addEventListener("input",e=>{
  searchQuery=e.target.value;
  $("searchClear").style.display=searchQuery?"flex":"none";
  renderMenu();
});
document.addEventListener("keydown",e=>{
  if(e.key==="Escape"){closeAll();return;}
  if(e.key!=="Tab")return;
  const panel=[$("infoModal"),$("cartSheet"),$("drawer")].find(p=>p.classList.contains("show")||p.classList.contains("open"));
  if(!panel)return;
  const items=[...panel.querySelectorAll("a[href],button,input,select,textarea")].filter(x=>!x.disabled&&x.offsetParent!==null);
  if(!items.length)return;
  const first=items[0],last=items[items.length-1];
  if(e.shiftKey&&document.activeElement===first){e.preventDefault();last.focus();}
  else if(!e.shiftKey&&document.activeElement===last){e.preventDefault();first.focus();}
});

/* ---------- УСТАНОВКА КАК ПРИЛОЖЕНИЯ (PWA) ---------- */
let deferredPrompt=null;
const isStandalone=window.matchMedia("(display-mode: standalone)").matches||window.navigator.standalone===true;
const isIOS=/iphone|ipad|ipod/i.test(navigator.userAgent)||(navigator.platform==="MacIntel"&&navigator.maxTouchPoints>1);
if(isStandalone)document.body.classList.add("standalone");
function updateInstallUI(){
  const show=!isStandalone&&(!!deferredPrompt||isIOS);
  document.querySelectorAll(".js-install").forEach(el=>el.classList.toggle("install-hidden",!show));
}
window.addEventListener("beforeinstallprompt",e=>{
  e.preventDefault();
  deferredPrompt=e;
  updateInstallUI();
});
window.addEventListener("appinstalled",()=>{
  deferredPrompt=null;
  updateInstallUI();
  toast(t().install.done);
});
async function installApp(){
  closeAll();
  if(deferredPrompt){
    const promptEvent=deferredPrompt;
    deferredPrompt=null;
    updateInstallUI();
    promptEvent.prompt();
    try{await promptEvent.userChoice;}catch(e){}
    return;
  }
  openPage("install");
}

/* ---------- ЗАПУСК ---------- */
updateInstallUI();
loadSavedCart();
initSlider();
$("yearNow").textContent=new Date().getFullYear();
$("atmoPhoto").style.backgroundImage=`url("${ATMO_IMAGE}")`;

let savedLang="rus";
try{
  const stored=localStorage.getItem("papagLang");
  if(LANG[stored])savedLang=stored;
}catch(e){}

setLanguage(savedLang);
startSlider();
fetchDishes();
</script>
</body>
</html>
