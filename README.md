<!doctype html>
<html ⚡>
  <head>
    <meta charset="utf-8">
    <title>Landing Page AMP Modern</title>
    <link rel="canonical" href="https://www.websitekamu.com/">
    <meta name="viewport" content="width=device-width,minimum-scale=1,initial-scale=1">
    <script async src="https://cdn.ampproject.org/v0.js"></script>
    <!-- AMP Carousel -->
    <script async custom-element="amp-carousel" src="https://cdn.ampproject.org/v0/amp-carousel-0.2.js"></script>
    <!-- AMP Form -->
    <script async custom-element="amp-form" src="https://cdn.ampproject.org/v0/amp-form-0.1.js"></script>
    <!-- Font -->
    <link href="https://fonts.googleapis.com/css2?family=Open+Sans:wght@400;700&display=swap" rel="stylesheet">
    <!-- Boilerplate -->
    <style amp-boilerplate>
      body{-webkit-animation:-amp-start 8s steps(1,end) 0s 1 normal both;-moz-animation:-amp-start 8s steps(1,end) 0s 1 normal both;-ms-animation:-amp-start 8s steps(1,end) 0s 1 normal both;animation:-amp-start 8s steps(1,end) 0s 1 normal both}
      @-webkit-keyframes -amp-start{from{visibility:hidden}to{visibility:visible}}
      @-moz-keyframes -amp-start{from{visibility:hidden}to{visibility:visible}}
      @-ms-keyframes -amp-start{from{visibility:hidden}to{visibility:visible}}
      @keyframes -amp-start{from{visibility:hidden}to{visibility:visible}}
    </style>
    <noscript>
      <style amp-boilerplate>
        body{-webkit-animation:none;-moz-animation:none;-ms-animation:none;animation:none}
      </style>
    </noscript>
    <!-- Custom CSS -->
    <style amp-custom>
.social-icons {
  margin-top: 10px;
}
.social-icons a {
  display: inline-block;
  margin: 0 8px;
  transition: transform 0.3s ease;
}
.social-icons a:hover {
  transform: scale(1.2);
}
.social-icons amp-img {
  vertical-align: middle;
}
/* Tombol CTA Biasa */
.cta-button {
  display: inline-block;
  padding: 14px 24px;
  background: #00cc66;
  color: #fff;
  text-decoration: none;
  border-radius: 6px;
  font-size: 18px;
  font-weight: bold;
  transition: background 0.3s ease;
}
.cta-button:hover {
  background: #00994d;
}

/* Domain Card */
.domain-card {
  max-width: 400px;
  margin: 20px auto;
  background: #ffffff;
  border: 2px solid #00cc66;
  border-radius: 8px;
  text-align: center;
  box-shadow: 0 2px 8px rgba(0,0,0,0.1);
  transition: transform 0.3s ease;
}
.domain-card:hover {
  transform: scale(1.05);
}
.domain-card a {
  display: flex;
  align-items: center;
  justify-content: center;
  padding: 15px;
  text-decoration: none;
}
.domain-card .domain-text {
  font-size: 18px;
  color: #00cc66;
  margin-left: 12px;
  font-weight: bold;
}

/* Ribbon Banner */
.ribbon-container {
  background: #123456;
  color: #fff;
  padding: 14px 20px;
  text-align: center;
  font-size: 18px;
  font-weight: bold;
  position: relative;
}
.ribbon-container::before,
.ribbon-container::after {
  content: "";
  position: absolute;
  bottom: -10px;
  border-width: 10px;
  border-style: solid;
  border-color: #123456 transparent transparent transparent;
}
.ribbon-container::before {
  left: 10px;
}
.ribbon-container::after {
  right: 10px;
}
.ribbon-container a {
  color: #fff;
  text-decoration: none;
}
.ribbon-container a:hover {
  text-decoration: underline;
}

/* Efek Kelap-Kelip */
.kelap-kelip {
  animation: blink 1s infinite;
}
@keyframes blink {
  0%, 100% {
    background-color: #00cc66;
  }
  50% {
    background-color: #ff0000;
  }
}
      body {
        font-family: 'Open Sans', sans-serif;
        background: #f4f4f4;
        margin: 0;
        padding: 0;
        color: #333;
      }
      header {
        background: #00cc66;
        color: #fff;
        padding: 40px 20px;
        text-align: center;
      }
      header h1 {
        margin: 0;
        font-size: 32px;
      }
      .carousel-container {
        max-width: 900px;
        margin: 20px auto;
      }
      .form-container {
        max-width: 500px;
        margin: 30px auto;
        background: #fff;
        padding: 25px;
        border-radius: 8px;
        box-shadow: 0 2px 6px rgba(0,0,0,0.1);
      }
      .form-container h2 {
        margin-top: 0;
        color: #00cc66;
      }
      form input, form button {
        width: 100%;
        padding: 12px;
        margin: 10px 0;
        box-sizing: border-box;
        border: 1px solid #ff0000;
        border-radius: 4px;
      }
      form button {
        background: #00cc66;
        color: #fff;
        font-weight: bold;
        border: none;
        cursor: pointer;
        transition: background 0.3s ease;
      }
      form button:hover {
        background: #00994d;
      }
      footer {
        text-align: center;
        padding: 20px;
        font-size: 14px;
        color: #777;
      }
	  body {
  font-family: 'Open Sans', sans-serif;
  background: #f4f4f4;
  margin: 0;
  padding: 0;
  color: #333;
}

header {
  background: #RRGGBB;
  color: #fff;
  padding: 40px 20px;
  text-align: center;
  
}

header h1 {
  margin: 0;
  font-size: 32px;
}

.carousel-container {
  max-width: 900px;
  margin: 20px auto;
}

.form-container {
  max-width: 500px;
  margin: 30px auto;
  background: #fff;
  padding: 25px;
  border-radius: 8px;
  box-shadow: 0 2px 6px rgba(0,0,0,0.1);
}

.form-container h2 {
  margin-top: 0;
  color: #123456;
}

form input, form button {
  width: 100%;
  padding: 12px;
  margin: 10px 0;
  box-sizing: border-box;
  border: 1px solid #ddd;
  border-radius: 4px;
}

form button {
  background: #6ecf9f; /* hijau lembut */
  color: #fff;
  font-weight: bold;
  border: none;
  cursor: pointer;
  transition: background 0.3s ease;
}

form button:hover {
  background: #5bb78a;
}

footer {
  text-align: center;
  padding: 20px;
  font-size: 14px;
  color: #777;
}

.social-icons {
  margin-top: 10px;
}

.social-icons a {
  display: inline-block;
  margin: 0 8px;
  transition: transform 0.3s ease;
}

.social-icons a:hover {
  transform: scale(1.2);
}

.social-icons amp-img {
  vertical-align: middle;
}
<p style="color: #FF0000;">Teks Merah</p> <!-- Merah -->
<p style="color: #00FF00;">Teks Hijau</p> <!-- Hijau -->
<p style="color: #0000FF;">Teks Biru</p> <!-- Biru -->

.domain-card {
  max-width: 400px;
  margin: 20px auto;
  background: #ffffff;
  border: 2px solid #00cc66;
  border-radius: 8px;
  text-align: center;
  box-shadow: 0 2px 8px rgba(0,0,0,0.1);
  transition: transform 0.3s ease;
}
.domain-card:hover {
  transform: scale(1.05);
}
.domain-card a {
  display: flex;
  align-items: center;
  justify-content: center;
  padding: 15px;
  text-decoration: none;
}
.domain-card .domain-text {
  font-size: 18px;
  color: #00cc66;
  margin-left: 12px;
  font-weight: bold;
}

.ribbon-container {
  background: #123456;
  color: #fff;
  padding: 14px 20px;
  text-align: center;
  font-size: 18px;
  font-weight: bold;
  position: relative;
}
.ribbon-container::before,
.ribbon-container::after {
  content: "";
  position: absolute;
  bottom: -10px;
  border-width: 10px;
  border-style: solid;
  border-color: #123456 transparent transparent transparent;
}
.ribbon-container::before {
  left: 10px;
}
.ribbon-container::after {
  right: 10px;
}
.ribbon-container a {
  color: #fff;
  text-decoration: none;
}
.ribbon-container a:hover {
  text-decoration: underline;
}
/* Tombol CTA Biasa */
.cta-button {
  display: inline-block;
  padding: 14px 24px;
  background: #00cc66;
  color: #fff;
  text-decoration: none;
  border-radius: 6px;
  font-size: 18px;
  font-weight: bold;
  transition: background 0.3s ease;
}
.cta-button:hover {
  background: #00994d;
}

/* Domain Card */
.domain-card {
  max-width: 400px;
  margin: 20px auto;
  background: #ffffff;
  border: 2px solid #00cc66;
  border-radius: 8px;
  text-align: center;
  box-shadow: 0 2px 8px rgba(0,0,0,0.1);
  transition: transform 0.3s ease;
}
.domain-card:hover {
  transform: scale(1.05);
}
.domain-card a {
  display: flex;
  align-items: center;
  justify-content: center;
  padding: 15px;
  text-decoration: none;
}
.domain-card .domain-text {
  font-size: 18px;
  color: #00cc66;
  margin-left: 12px;
  font-weight: bold;
}

/* Ribbon Banner */
.ribbon-container {
  background: #123456;
  color: #fff;
  padding: 14px 20px;
  text-align: center;
  font-size: 18px;
  font-weight: bold;
  position: relative;
}
.ribbon-container::before,
.ribbon-container::after {
  content: "";
  position: absolute;
  bottom: -10px;
  border-width: 10px;
  border-style: solid;
  border-color: #123456 transparent transparent transparent;
}
.ribbon-container::before {
  left: 10px;
}
.ribbon-container::after {
  right: 10px;
}
.ribbon-container a {
  color: #fff;
  text-decoration: none;
}
.ribbon-container a:hover {
  text-decoration: underline;
}

/* Efek Kelap-Kelip */
.kelap-kelip {
  animation: blink 1s infinite;
}
@keyframes blink {
  0%, 100% {
    background-color: #00cc66;
  }
  50% {
    background-color: #ff0000;
  }
  body {
        font-family: 'Open Sans', sans-serif;
        margin: 0;
        padding: 0;
        color: #fff;
        background: linear-gradient(-45deg, #1a2a6c, #b21f1f, #fdbb2d, #1a2a6c);
        background-size: 400% 400%;
        animation: gradientBG 12s ease infinite;
      }

      header {
        text-align: center;
        padding: 50px 20px;
        background-color: rgba(0, 0, 0, 0.4);
        backdrop-filter: blur(4px);
        border-bottom: 2px solid #fff;
      }

      header h1 {
        font-size: 32px;
        margin: 0;
        animation: fadeIn 2s ease-out;
      }

      .main-content {
        text-align: center;
        padding: 40px 20px;
        animation: slideUp 1.5s ease-out;
      }

      .cta-button {
        display: inline-block;
        padding: 14px 30px;
        background-color: #00cc66;
        color: #fff;
        font-size: 18px;
        font-weight: bold;
        border-radius: 8px;
        text-decoration: none;
        margin-top: 30px;
        animation: blink 1s infinite;
      }

      /* ANIMASI */

      @keyframes gradientBG {
        0% {background-position: 0% 50%;}
        50% {background-position: 100% 50%;}
        100% {background-position: 0% 50%;}
      }

      @keyframes fadeIn {
        from {opacity: 0; transform: translateY(-20px);}
        to {opacity: 1; transform: translateY(0);}
      }

      @keyframes slideUp {
        from {opacity: 0; transform: translateY(40px);}
        to {opacity: 1; transform: translateY(0);}
      }

      @keyframes blink {
        0%, 100% { background-color: #00cc66; }
        50% { background-color: #ff0000; }
      }
    </style>
  </head>
  <body>
    <header>
      <h1>𝙿𝚛𝚘𝚖𝚘 𝚂𝚙𝚎𝚜𝚒𝚊𝚕 𝙳𝚊𝚏𝚝𝚊𝚛 𝚂𝚎𝚔𝚊𝚛𝚊𝚗𝚐</h1>
      <p>𝙳𝚊𝚙𝚊𝚝𝚔𝚊𝚗 𝚋𝚘𝚗𝚞𝚜 𝚖𝚎𝚖𝚋𝚎𝚛 𝚋𝚊𝚛𝚞 𝚑𝚊𝚗𝚢𝚊 𝚑𝚊𝚛𝚒 𝚒𝚗𝚒！</p>
    </header>
    <div class="carousel-container">
      <amp-carousel width="900" height="400" layout="responsive" type="slides">
        <amp-img src="https://olg777.dataklmsad903.site/images/banner-desktop/4/c19XWIljlnJzkSqa.webp" width="900" height="400" layout="responsive" alt="Slide 1"></amp-img>
        <amp-img src="https://olg777.dataklmsad903.site/images/banner-desktop/2/Cghl8SfWbp6nCX9Z.jpg" width="900" height="400" layout="responsive" alt="Slide 2"></amp-img>
        <amp-img src="https://olg777.dataklmsad903.site/images/setting-promo/1/XwdHq19T6UEagmG7.jpg" width="900" height="400" layout="responsive" alt="Slide 3"></amp-img>
      </amp-carousel>
    </div>
   </head>
   <div class="domain-card kelap-kelip">
  <a href="https://olg777one.com/mobile/" target="_blank">
    <amp-img src="https://upload.wikimedia.org/wikipedia/commons/8/84/Example.svg"
             width="24"
             height="24"
             layout="fixed"
             alt="Ikon Website"></amp-img>
    <span class="domain-text">𝖔𝖑𝖌777𝖔𝖓𝖊.𝖈𝖔𝖒</span>
  </a>
</div>
<div class="ribbon-container kelap-kelip">
  <a href="https://olg777one.com/mobile/masuk" target="_blank">
    🎯 𝙺𝚕𝚒𝚔 𝚍𝚒 𝚜𝚒𝚗𝚒 𝚞𝚗𝚝𝚞𝚔 𝙼𝚊𝚜𝚞𝚔
  </a>
</div>
  <div class="ribbon-container">
  <a href="https://olg777one.com/mobile/daftar" target="_blank">
    🎯 𝙺𝚕𝚒𝚔 𝚍𝚒 𝚜𝚒𝚗𝚒 𝚞𝚗𝚝𝚞𝚔 𝕯𝖆𝖋𝖙𝖆𝖗
  </a>
</div>

    <footer>
  <p>Layanan terbaik 24 jam</p>
  <div class="social-icons">
    <a href="https://api.whatsapp.com/send/?phone=%2B6287845991907&text&type=phone_number&app_absent=0" target="_blank">
      <amp-img src="https://www.nopcommerce.com/images/thumbs/0015520_livechat-live-chat-plugin.jpeg"
               width="24" height="24" alt="Facebook"></amp-img>
    </a>
    <a href="https://wa.me/6281234567890" target="_blank">
      <amp-img src="https://upload.wikimedia.org/wikipedia/commons/6/6b/WhatsApp.svg"
               width="24" height="24" alt="WhatsApp"></amp-img>
    </a>
  </div>
  <p>&copy; 2025 Fast Respon. 𝐴𝑙𝑙 𝑟𝑖𝑔ℎ𝑡𝑠 𝑟𝑒𝑠𝑒𝑟𝑣𝑒𝑑.</p>
</footer

  </body>
</html>
