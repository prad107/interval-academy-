# interval-academy-
forex academy 
[README.md](https://github.com/user-attachments/files/23737478/README.md)

A Pen created on CodePen.

Original URL: [https://codepen.io/Shabirah-Newton/pen/pvyvmqp](https://codepen.io/Shabirah-Newton/pen/pvyvmqp).

[LICENSE.txt](https://github.com/user-attachments/files/23737482/LICENSE.txt)
The MIT License (MIT)

Copyright (c) 2025 Prada   (https://codepen.io/Shabirah-Newton/pen/pvyvmqp)

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER 
EALINGS IN THE<!DOCTYPE html>[index.html](https://github.com/user-attachments/files/23737704/index.html)
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Interval Traders Academy</title>
  <!-- Google Fonts -->
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;700&family=Roboto:wght@400;500&display=swap" rel="stylesheet">
  <style>
    /* Global Styles */
    body {
      font-family: 'Roboto', sans-serif;
      margin: 0;
      padding: 0;
      background-color: #0f0f0f;
      color: #fff;
    }
    h1, h2, h3 {
      font-family: 'Playfair Display', serif;
      margin: 0.5em 0;
      color: #ffcc00;
    }
    nav {
      background-color: #1a1a1a;
      padding: 1em;
      text-align: center;
    }
    nav a {
      color: #ffcc00;
      margin: 0 1em;
      font-weight: bold;
    }
    .container {
      width: 90%;
      max-width: 1200px;
      margin: 0 auto;
      padding: 2em 0;
    }
    .btn {
      display: inline-block;
      background-color: #ffcc00;
      color: #1a1a1a;
      padding: 0.7em 1.5em;
      margin: 1em 0;
      border-radius: 5px;
      font-weight: bold;
    }
    .grid {
      display: grid;
      gap: 2em;
    }
    .courses, .blog-posts, .instructors {
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    }
    .card {
      background: #1a1a1a;
      padding: 1.5em;
      border-radius: 10px;
      box-shadow: 0 4px 10px rgba(255,204,0,0.3);
    }
    footer {
      background-color: #1a1a1a;
      color: #fff;
      text-align: center;
      padding: 2em 0;
    }
    img {
      max-width: 100%;
      border-radius: 10px;
    }
    .qr-codes {
      display: flex;
      gap: 1em;
      margin-top: 1em;
    }
    .qr-codes img {
      width: 120px;
      height: 120px;
    }
  </style>
</head>
<body>

  <!-- Navigation -->
  <nav>
    <a href="#home">Home</a>
    <a href="#courses">Courses</a>
    <a href="#about">About</a>
    <a href="#blog">Blog</a>
    <a href="#contact">Contact</a>
  </nav>

  <!-- Home Section -->
  <section id="home" class="container">
    <h1>Welcome to Interval Traders Academy</h1>
    <p style="font-size: 1.2em; font-family: 'Playfair Display', serif;">
      Master Forex, Stocks, and Crypto trading with expert guidance and easy-to-follow lessons.
    </p>
    <img src="images/welcome-banner.jpg" alt="Interval Traders Academy">
    <p>Scan QR to join our Telegram or WhatsApp channels:</p>
    <div class="qr-codes">
      <a href="https://t.me/FX0998"><img src="images/qr-telegram.png" alt="Telegram QR"></a>
      <a href="https://wa.me/256760099777"><img src="images/qr-whatsapp.png" alt="WhatsApp QR"></a>
    </div>
    <a href="#courses" class="btn">Explore Courses</a>
  </section>

  <!-- Courses Section -->
  <section id="courses" class="container">
    <h2>Our Courses</h2>
    <div class="grid courses">
      <div class="card">
        <h3>Forex Trading</h3>
        <p>Learn currency trading from basics to advanced strategies.</p>
        <p><strong>Price:</strong> $15 USD</p>
        <a href="#contact" class="btn">Enroll Now</a>
      </div>
      <div class="card">
        <h3>Stocks Trading</h3>
        <p>Master stock market techniques and investment strategies.</p>
        <p><strong>Price:</strong> $20 USD</p>
        <a href="#contact" class="btn">Enroll Now</a>
      </div>
      <div class="card">
        <h3>Crypto Trading</h3>
        <p>Understand cryptocurrency markets and trading fundamentals.</p>
        <p><strong>Price:</strong> $25 USD</p>
        <a href="#contact" class="btn">Enroll Now</a>
      </div>
    </div>
  </section>

  <!-- About Section -->
  <section id="about" class="container">
    <h2>About Us</h2>
    <p>
      Interval Traders Academy is dedicated to making trading simple and accessible.
      Our experienced instructors guide you step by step, whether you’re a beginner or advanced trader.
    </p>
    <h3>Our Mission</h3>
    <p>To empower individuals to achieve financial literacy and success through trading.</p>
    <h3>Instructors</h3>
    <div class="grid instructors">
      <div class="card">
        <img src="images/instructor1.jpg" alt="Instructor 1">
        <h4>Auson FX</h4>
        <p>Lead Forex Instructor with 10+ years of trading experience.</p>
      </div>
      <div class="card">
        <img src="images/instructor2.jpg" alt="Instructor 2">
        <h4>Jane Doe</h4>
        <p>Stocks and Crypto Specialist guiding beginners to advanced skills.</p>
      </div>
    </div>
  </section>

  <!-- Blog Section -->
  <section id="blog" class="container">
    <h2>Trading Blog</h2>
    <div class="grid blog-posts">
      <div class="card">
        <h3>Top Forex Strategies in 2025</h3>
        <p>Discover the most effective strategies used by professional traders today.</p>
        <a href="#" class="btn">Read More</a>
      </div>
      <div class="card">
        <h3>Crypto Market Trends</h3>
        <p>Stay updated on Bitcoin, Ethereum, and altcoin trends with our insights.</p>
        <a href="#" class="btn">Read More</a>
      </div>
    </div>
  </section>

  <!-- Contact Section -->
  <section id="contact" class="container">
    <h2>Contact Us</h2>
    <p>Telegram: <a href="https://t.me/Intervaltraders">@Intervaltraders</a></p>
    <p>Phone: +256 760 099 777 | +256 743 488 943</p>
    <p>Location: Kampala, Uganda</p>
    <p>Scan QR to join our channels:</p>
    <div class="qr-codes">
      <a href="https://t.me/FX0998"><img src="images/qr-telegram.png" alt="Telegram QR"></a>
      <a href="https://wa.me/256760099777"><img src="images/qr-whatsapp.png" alt="WhatsApp QR"></a>
    </div>
  </section>

  <!-- Footer -->
  <footer>
    <p>&copy; 2025 Interval Traders Academy. All rights reserved.</p>
  </footer>

</body>[index.html](https://github.com/user-attachments/files/23737707/index.html)<!DOCTYPE html>
<html lang="en">

  <head>
    <meta charset="UTF-8">
    <title>Untitled</title>
    

  </head>
    
  <body>
  <!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Interval Traders Academy</title>
  <!-- Google Fonts -->
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;700&family=Roboto:wght@400;500&display=swap" rel="stylesheet">
  <style>
    /* Global Styles */
    body {
      font-family: 'Roboto', sans-serif;
      margin: 0;
      padding: 0;
      background-color: #0f0f0f;
      color: #fff;
    }
    h1, h2, h3 {
      font-family: 'Playfair Display', serif;
      margin: 0.5em 0;
      color: #ffcc00;
    }
    nav {
      background-color: #1a1a1a;
      padding: 1em;
      text-align: center;
    }
    nav a {
      color: #ffcc00;
      margin: 0 1em;
      font-weight: bold;
    }
    .container {
      width: 90%;
      max-width: 1200px;
      margin: 0 auto;
      padding: 2em 0;
    }
    .btn {
      display: inline-block;
      background-color: #ffcc00;
      color: #1a1a1a;
      padding: 0.7em 1.5em;
      margin: 1em 0;
      border-radius: 5px;
      font-weight: bold;
    }
    .grid {
      display: grid;
      gap: 2em;
    }
    .courses, .blog-posts, .instructors {
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    }
    .card {
      background: #1a1a1a;
      padding: 1.5em;
      border-radius: 10px;
      box-shadow: 0 4px 10px rgba(255,204,0,0.3);
    }
    footer {
      background-color: #1a1a1a;
      color: #fff;
      text-align: center;
      padding: 2em 0;
    }
    img {
      max-width: 100%;
      border-radius: 10px;
    }
    .qr-codes {
      display: flex;
      gap: 1em;
      margin-top: 1em;
    }
    .qr-codes img {
      width: 120px;
      height: 120px;
    }
  </style>
</head>
<body>

  <!-- Navigation -->
  <nav>
    <a href="#home">Home</a>
    <a href="#courses">Courses</a>
    <a href="#about">About</a>
    <a href="#blog">Blog</a>
    <a href="#contact">Contact</a>
  </nav>

  <!-- Home Section -->
  <section id="home" class="container">
    <h1>Welcome to Interval Traders Academy</h1>
    <p style="font-size: 1.2em; font-family: 'Playfair Display', serif;">
      Master Forex, Stocks, and Crypto trading with expert guidance and easy-to-follow lessons.
    </p>
    <img src="images/welcome-banner.jpg" alt="Interval Traders Academy">
    <p>Scan QR to join our Telegram or WhatsApp channels:</p>
    <div class="qr-codes">
      <a href="https://t.me/FX0998"><img src="images/qr-telegram.png" alt="Telegram QR"></a>
      <a href="https://wa.me/256760099777"><img src="images/qr-whatsapp.png" alt="WhatsApp QR"></a>
    </div>
    <a href="#courses" class="btn">Explore Courses</a>
  </section>

  <!-- Courses Section -->
  <section id="courses" class="container">
    <h2>Our Courses</h2>
    <div class="grid courses">
      <div class="card">
        <h3>Forex Trading</h3>
        <p>Learn currency trading from basics to advanced strategies.</p>
        <p><strong>Price:</strong> $15 USD</p>
        <a href="#contact" class="btn">Enroll Now</a>
      </div>
      <div class="card">
        <h3>Stocks Trading</h3>
        <p>Master stock market techniques and investment strategies.</p>
        <p><strong>Price:</strong> $20 USD</p>
        <a href="#contact" class="btn">Enroll Now</a>
      </div>
      <div class="card">
        <h3>Crypto Trading</h3>
        <p>Understand cryptocurrency markets and trading fundamentals.</p>
        <p><strong>Price:</strong> $25 USD</p>
        <a href="#contact" class="btn">Enroll Now</a>
      </div>
    </div>
  </section>

  <!-- About Section -->
  <section id="about" class="container">
    <h2>About Us</h2>
    <p>
      Interval Traders Academy is dedicated to making trading simple and accessible.
      Our experienced instructors guide you step by step, whether you’re a beginner or advanced trader.
    </p>
    <h3>Our Mission</h3>
    <p>To empower individuals to achieve financial literacy and success through trading.</p>
    <h3>Instructors</h3>
    <div class="grid instructors">
      <div class="card">
        <img src="images/instructor1.jpg" alt="Instructor 1">
        <h4>Auson FX</h4>
        <p>Lead Forex Instructor with 10+ years of trading experience.</p>
      </div>
      <div class="card">
        <img src="images/instructor2.jpg" alt="Instructor 2">
        <h4>Jane Doe</h4>
        <p>Stocks and Crypto Specialist guiding beginners to advanced skills.</p>
      </div>
    </div>
  </section>

  <!-- Blog Section -->
  <section id="blog" class="container">
    <h2>Trading Blog</h2>
    <div class="grid blog-posts">
      <div class="card">
        <h3>Top Forex Strategies in 2025</h3>
        <p>Discover the most effective strategies used by professional traders today.</p>
        <a href="#" class="btn">Read More</a>
      </div>
      <div class="card">
        <h3>Crypto Market Trends</h3>
        <p>Stay updated on Bitcoin, Ethereum, and altcoin trends with our insights.</p>
        <a href="#" class="btn">Read More</a>
      </div>
    </div>
  </section>

  <!-- Contact Section -->
  <section id="contact" class="container">
    <h2>Contact Us</h2>
    <p>Telegram: <a href="https://t.me/Intervaltraders">@Intervaltraders</a></p>
    <p>Phone: +256 760 099 777 | +256 743 488 943</p>
    <p>Location: Kampala, Uganda</p>
    <p>Scan QR to join our channels:</p>
    <div class="qr-codes">
      <a href="https://t.me/FX0998"><img src="images/qr-telegram.png" alt="Telegram QR"></a>
      <a href="https://wa.me/256760099777"><img src="images/qr-whatsapp.png" alt="WhatsApp QR"></a>
    </div>
  </section>

  <!-- Footer -->
  <footer>
    <p>&copy; 2025 Interval Traders Academy. All rights reserved.</p>
  </footer>

</body>
</html>
    
  </body>
  
</html>


</html>
