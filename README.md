<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Leo Water Company | Clean Water, Delivered</title>

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: Arial, sans-serif;
      color: #123047;
      background: #f4fbff;
      line-height: 1.6;
    }

    header {<a class="button" href="#products">Order Here</a>
      background: #063b61;
      color: white;
      padding: 20px 8%;
      display: flex;
      justify-content: space-between;
      align-items: center;
      flex-wrap: wrap;
      gap: 12px;
    }

    header h1 {
      font-size: 25px;
    }

    nav a {
      color: white;
      text-decoration: none;
      margin-left: 18px;
    }

    .hero {
      background: linear-gradient(120deg, #075985, #38bdf8);
      color: white;
      text-align: center;
      padding: 85px 20px;
    }

    .hero h2 {
      font-size: 42px;
      margin-bottom: 15px;
    }

    .hero p {
      margin-bottom: 25px;
    }

    .button {
      display: inline-block;
      background: #ffffff;
      color: #075985;
      padding: 13px 25px;
      border-radius: 30px;
      text-decoration: none;
      font-weight: bold;
    }

    .section {
      padding: 60px 8%;
      text-align: center;
    }

    .section h2 {
      font-size: 30px;
      margin-bottom: 12px;
    }

    .products {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 22px;
      margin-top: 30px;
    }

    .product {
      background: white;
      padding: 30px 20px;
      border-radius: 14px;
      box-shadow: 0 4px 15px #12304712;
    }

    .product .emoji {
      font-size: 48px;
      margin-bottom: 12px;
    }

    .product h3 {
      margin-bottom: 10px;
    }

    .delivery {
      background: #e0f2fe;
    }

    .contact {
      background: #063b61;
      color: white;
    }

    .contact .button {
      background: #25d366;
      color: white;
      margin-top: 20px;
    }

    footer {
      background: #032b46;
      color: white;
      text-align: center;
      padding: 20px;
    }

    @media (max-width: 600px) {
      header {
        justify-content: center;
        text-align: center;
      }

      nav a {
        margin: 0 7px;
      }

      .hero h2 {
        font-size: 30px;
      }
    }
  </style>
</head>

<body>

  <header>
    <h1>💧 Leo Water Company</h1>

    <nav>
      <a href="#home">Home</a>
      <a href="#products">Products</a>
      <a href="#delivery">Delivery</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section class="hero" id="home">
    <h2>Pure Water. Better Living.</h2>
    <p>Reliable water supply and convenient delivery to your doorstep.</p>
    <a class="button" href="#products">Explore Our Products</a>
  </section>

  <section class="section" id="products">
    <h2>Our Products</h2>
    <p>Water solutions for homes and businesses.</p>

    <div class="products">

      <div class="product">
        <div class="emoji">💧</div>
        <h3>Drinking Water</h3>
        <p>Clean drinking water for everyday use.</p>
      </div>

      <div class="product">
        <div class="emoji">🫙</div>
        <h3>Dispenser Bottles</h3>
        <p>Convenient bottles for water dispensers.</p>
      </div>

      <div class="product">
        <div class="emoji">🚚</div>
        <h3>Water Delivery</h3>
        <p>Convenient delivery to your home or business.</p>
      </div>

    </div>
  </section>

  <section class="section delivery" id="delivery">
    <h2>Where We Deliver</h2>
    <p>We serve customers in Nakuru and Njoro, Kenya.</p>
    <p>Contact us to confirm delivery availability.</p>
  </section>

  <section class="section contact" id="contact">
    <h2>Ready to Place an Order?</h2>
    <p>Contact Leo Water Company on WhatsApp.</p>

    <!-- Replace 2547XXXXXXXX with your business WhatsApp number -->
    <a class="button"
       href="https://wa.me/2547XXXXXXXX?text=Hello%20Leo%20Water%20Company">
       Order on WhatsApp
    </a>
  </section>

  <footer>
    <p>© 2026 Leo Water Company. All rights reserved.</p>
  </footer>

</body>
</html>
<section class="section contact" id="contact">
  <h2>Ready to Place an Order?</h2>
  <p>Contact Leo Water Company on WhatsApp.</p>
  <a class="button" href="https://wa.me/2547XXXXXXXX?@media (max-width: 600px) {
  header h1 {
    font-size: 20px;
  }
  .hero h2 {<a class="button" href="https://wa.
    font-size: 28px;
  }
  .products {
    grid-template-columns: 1fr; /* Stack products vertically on small screens */
  }
}
