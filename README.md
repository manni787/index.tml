# index.tml
My Shops Introduction Page
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Manjeet Garments</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <div class="background-overlay">

    <header>
      <h1>🧥 Manjeet Garments 🧢</h1>
      <p>Wholesale Garments From Delhi, Kolkata, And Tripura</p>
    </header>

    <section class="highlights">
      <div class="highlight">✅ Trusted by retailers since 2005</div>
      <div class="highlight">🧺 Bulk orders welcome</div>
      <div class="highlight">🚚 Delivery support available</div>
    </section>

    <section class="gallery">
      <h2>🛍️ Our Products</h2>
      <div class="product-card reveal">
        <img src="product1.jpg" alt="Boys Clothing Set" />
        <h3>Boys Summer Set</h3>
        <p>Comfortable & stylish wear</p>
      </div>
      <div class="product-card reveal">
        <img src="product2.jpg" alt="Girls Clothing Set" />
        <h3>Girls Skirt & Top</h3>
        <p>Elegant & colorful combo</p>
      <div class="product-card reveal">
        <img src="product3.jpg" alt="Boys Clothing Set" />
        <h3>Girls Skirt Set</h3>
        <p>Beautiful And Gorgeous Set</p>
      </div>
    </section>

    <footer>
      <p>📍 24/40, Shop No. 2, Street in Kiran Hotel, Shivaji Market, Bijlighar, AGRA</p>
      <p>📲 Contact Naresh Bhai: <a href="https://wa.me/919690516431" target="_blank">WhatsApp</a></p>
      <p>&copy; 2024 Manjeet Garments</p>
    </footer>

    
    <a href="https://wa.me/919690516431" class="floating-whatsapp" target="_blank">💬</a>
  </div>

  <script>
    
    const reveals = document.querySelectorAll('.reveal');
    window.addEventListener('scroll', () => {
      for (let i = 0; i < reveals.length; i++) {
        const windowHeight = window.innerHeight;
        const revealTop = reveals[i].getBoundingClientRect().top;
        if (revealTop < windowHeight - 100) {
          reveals[i].classList.add('active');
        }
      }
    });
  </script>
</body>
</html>

