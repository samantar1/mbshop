<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MP SHOP - Sneaker Store</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <nav>
          <img src="logo.png.png" alt="MP SHOP Logo">
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#collections">Collections</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="hero">
        <div class="hero-content">
            <h1>MP SHOP</h1>
            <p>We provide the newest sneakers for your style</p>
            <a href="#contact" class="btn">Get Started</a>
        </div>
    </section>

    <section id="about">
        <div class="container">
            <h2>About Us</h2>
            <p>OUR GOAL IS TO MAKE THE CUSTOMER HAPPY.</p>
        </div>
    </section>

    <section id="collections">
        <div class="container">
          <h2>Our Collections</h2>
          <div class="collections-wrapper">
            <div class="collection">
              <img src="download (1).png" alt="Collection">
              <h3>Collection 1</h3>
              <a href="collection1.html" class="btn">View Collection</a>
            </div>
            <div class="collection">
              <img src="download.jpeg" alt="Collection">
              <h3>Collection 2</h3>
              <a href="collection2.html" class="btn">View Collection</a>
            </div>
            <div class="collection">
              <img src="download.png" alt="Collection">
              <h3>Collection 3</h3>
              <a href="collection3.html" class="btn">View Collection</a>
            </div>
          </div>
        </div>
      </section>
      

    <section id="contact">
        <div class="container">
            <h2>Contact Us</h2>
            <p>Contact us today! Our team is ready to answer any questions you have.</p>
            <form action="#" method="POST" id="contact-form">
                <input type="text" name="name" placeholder="Your Name" required>
                <input type="email" name="email" placeholder="Your Email" required>
                <textarea name="message" placeholder="Your Message" required></textarea>
                <button type="submit" class="btn">Submit</button>
            </form>
        </div>
    </section>

    <footer>
        <p>&copy; 2023 MP SHOP. All rights reserved.</p>
    </footer>

    <script>
        // JavaScript code goes here
        document.getElementById('contact-form').addEventListener('submit', function(event) {
            event.preventDefault();
            // Add your form submission logic here
            // For example, you can send the form data to a server using AJAX
        });
    </script>
</body>
</html>
