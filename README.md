# product-page
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>SuperTech Wireless Headphones</title>
  <link rel="stylesheet" href="task1.css">
</head>
<body>

  <header class="header">
    <div class="logo">SuperTech</div>
    <nav>
      <ul>
        <li><a href="#">Home</a></li>
        <li><a href="#">Shop</a></li>
        <li><a href="#">About</a></li>
        <li><a href="#">Contact</a></li>
      </ul>
    </nav>
  </header>

  <section class="product-section">
    <div class="product-left">
      <img src="headset.jpg" alt="SuperTech Wireless Headphones" class="product-image">
    </div>
    <div class="product-right">
      <h1>SuperTech Wireless Headphones</h1>
      <p class="subtitle">Experience the Future of Sound with Unmatched Comfort</p>
      <ul class="features">
        <li>Crystal-clear sound quality</li>
        <li>Active noise cancellation</li>
        <li>Up to 30 hours of battery life</li>
        <li>Comfortable, adjustable ear cups</li>
      </ul>
      <p class="price">$199.99</p>
      <button class="cta-button">Buy Now</button>
    </div>
  </section>

  <section class="testimonials">
    <h2>What Our Customers Are Saying</h2>
    <p>"Best headphones I’ve ever owned! The sound is incredible, and they’re super comfortable!" — Sarah M.</p>
    <p>"I love the noise cancellation feature; it makes my workday so much more productive!" — John D.</p>
    <p>"Worth every penny! The battery life is impressive, and they look sleek too." — Amy K.</p>
  </section>

  <footer class="footer">
    <div class="footer-left">
      <ul>
        <li><a href="#">Shop</a></li>
        <li><a href="#">Blog</a></li>
        <li><a href="#">About</a></li>
        <li><a href="#">FAQ</a></li>
      </ul>
    </div>
    <div class="footer-middle">
      <a href="#">Instagram</a>
      <a href="#">Facebook</a>
      <a href="#">Twitter</a>
      <a href="#">YouTube</a>
    </div>
    <div class="footer-right">
      <p>Email: support@supertech.com</p>
      <p>Phone: 1-800-123-4567</p>
    </div>
  </footer>

</body>
</html>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #ff7700;
    color: #333;
  }
  
  
  .header {
    background-color: #222;
    color: white;
    padding: 10px 20px;
    display: flex;
    justify-content: space-between;
    align-items: center;
  }
  
  .header .logo {
    font-size: 24px;
    font-weight: bold;
  }
  
  .header nav ul {
    list-style: none;
    margin: 0;
    padding: 0;
    display: flex;
  }
  
  .header nav ul li {
    margin-right: 20px;
  }
  
  .header nav ul li a {
    color: white;
    text-decoration: none;
    font-size: 16px;
  }
  
  .header nav ul li a:hover {
    text-decoration: underline;
  }
  
  
  .product-section {
    display: flex;
    justify-content: space-between;
    padding: 50px 20px;
    background-color: white;
    margin: 20px 0;
  }
  
  .product-left {
    flex: 1;
    padding-right: 20px;
  }
  
  .product-image {
    max-width: 100%;
    height: auto;
    object-fit: cover; 
    border-radius: 8px;
  }
  
  .product-right {
    flex: 1;
    padding-left: 20px;
  }
  
  .product-right h1 {
    font-size: 32px;
    margin-bottom: 10px;
  }
  
  .product-right .subtitle {
    font-size: 18px;
    margin-bottom: 20px;
    color: #555;
  }
  
  .features {
    list-style: none;
    padding: 0;
    margin: 0;
  }
  
  .features li {
    font-size: 16px;
    margin-bottom: 10px;
  }
  
  .price {
    font-size: 24px;
    font-weight: bold;
    color: #222;
    margin-top: 20px;
  }
  
  .cta-button {
    background-color: #ff5722;
    color: white;
    border: none;
    padding: 12px 25px;
    font-size: 18px;
    cursor: pointer;
    margin-top: 20px;
    border-radius: 5px;
    transition: background-color 0.3s;
  }
  
  .cta-button:hover {
    background-color: #e64a19;
  }
  
  
  .testimonials {
    background-color: #fff;
    padding: 40px 20px;
    text-align: center;
  }
  
  .testimonials h2 {
    font-size: 28px;
    margin-bottom: 20px;
  }
  
  .testimonials p {
    font-size: 16px;
    margin-bottom: 10px;
  }
  
 
  .footer {
    background-color: #222;
    color: white;
    padding: 30px 20px;
    display: flex;
    justify-content: space-between;
  }
  
  .footer-left, .footer-middle, .footer-right {
    flex: 1;
  }
  
  .footer-left ul {
    list-style: none;
    padding: 0;
  }
  
  .footer-left ul li {
    margin-bottom: 10px;
  }
  
  .footer-left ul li a {
    color: white;
    text-decoration:none;
  }

  .footer-left ul li a:hover{
    text-decoration: underline;
  }
  
  .footer-middle a {
    display: block;
    color: white;
    margin-bottom: 10px;
    text-decoration: none;
  }
  
  .footer-middle a:hover {
    text-decoration: underline;
  }
  
  .footer-right p {
    font-size: 16px;
    margin-bottom: 5px;
  }
  
 
  @media (max-width: 768px) {
    .product-section {
      flex-direction: column;
      align-items: center;
    }
  
    .product-left, .product-right {
      padding: 0;
      margin-bottom: 20px;
    }
  
    .footer {
      flex-direction: column;
      align-items: center;
      text-align: center;
    }
  }
