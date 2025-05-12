<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>FinDataIQ Global</title>
  <style>
    /* Basic CSS Reset */
    * { box-sizing: border-box; margin: 0; padding: 0; }
    body { font-family: Arial, sans-serif; color: #333; line-height: 1.6; }

    /* Navigation Bar */
    nav {
      background-color: #1e3a8a;
      color: white;
      padding: 1rem;
      position: sticky;
      top: 0;
    }
    .container {
      max-width: 1200px;
      margin: 0 auto;
    }
    .nav-content {
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    .nav-title {
      font-size: 1.5rem;
      font-weight: bold;
    }
    .nav-links {
      display: flex;
      list-style: none;
    }
    .nav-links li {
      margin-left: 1.5rem;
    }
    .nav-links a {
      color: white;
      text-decoration: none;
    }
    .nav-links a:hover {
      color: #f59e0b;
    }

    /* Sections */
    section {
      padding: 4rem 1rem;
    }
    .bg-gray {
      background-color: #f3f4f6;
    }
    .text-center {
      text-align: center;
    }
    h2 {
      font-size: 2.5rem;
      color: #1e3a8a;
      margin-bottom: 1rem;
    }
    p {
      color: #4b5563;
      margin-bottom: 2rem;
    }
    .button {
      background-color: #1e3a8a;
      color: white;
      padding: 0.5rem 1.5rem;
      border-radius: 0.25rem;
      text-decoration: none;
    }
    .button:hover {
      background-color: #f59e0b;
    }

    /* Services Grid */
    .services-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 1.5rem;
    }
    .service-card {
      background-color: white;
      padding: 1.5rem;
      border-radius: 0.25rem;
      box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    }
    .service-card h3 {
      font-size: 1.25rem;
      color: #1e3a8a;
      margin-bottom: 0.5rem;
    }

    /* News Section */
    .news-item {
      background-color: white;
      padding: 1rem;
      border-radius: 0.25rem;
      box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
      margin-bottom: 1rem;
    }
    .news-item h3 {
      font-size: 1.125rem;
      color: #1e3a8a;
    }
    .news-item .date {
      font-size: 0.875rem;
      color: #6b7280;
    }

    /* Contact Form */
    .contact-form {
      max-width: 500px;
      margin: 0 auto;
    }
    .contact-form label {
      display: block;
      color: #1e3a8a;
      font-weight: bold;
      margin-bottom: 0.5rem;
    }
    .contact-form input,
    .contact-form textarea {
      width: 100%;
      padding: 0.5rem;
      border: 1px solid #d1d5db;
      border-radius: 0.25rem;
      margin-bottom: 1rem;
    }
    .contact-form button {
      background-color: #1e3a8a;
      color: white;
      padding: 0.5rem 1.5rem;
      border: none;
      border-radius: 0.25rem;
      cursor: pointer;
    }
    .contact-form button:hover {
      background-color: #f59e0b;
    }

    /* Footer */
    footer {
      background-color: #1e3a8a;
      color: white;
      text-align: center;
      padding: 1rem;
    }
    footer a {
      color: white;
      text-decoration: none;
    }
    footer a:hover {
      color: #f59e0b;
    }
  </style>
</head>
<body>
  <!-- Navigation -->
  <nav>
    <div class="container nav-content">
      <div>
        <span class="nav-title">FinDataIQ Global</span>
      </div>
      <ul class="nav-links">
        <li><a href="#home">Home</a></li>
        <li><a href="#news">News</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </div>
  </nav>

  <!-- Home Section -->
  <section id="home" class="bg-gray text-center">
    <h2>Empowering Your Financial Future</h2>
    <p>FinDataIQ Global delivers expert financial solutions tailored to your needs.</p>
    <p>FinDataIQ stands for <strong>Financial Data Intelligence Quotient</strong>. We are dedicated to providing intelligent financial solutions to help you navigate the complexities of the financial world. Our team of experts is here to assist you with bookkeeping, reconciliations, consultations, and financial planning.</p>
    <a href="#contact" class="button">Get Started</a>
  </section>

  <!-- Services Section -->
  <section class="container">
    <h2 class="text-center">Our Services</h2>
    <div class="services-grid">
      <div class="service-card">
        <h3>Bookkeeping</h3>
        <p>Accurate and timely bookkeeping services to keep your finances organized.</p>
      </div>
      <div class="service-card">
        <h3>Reconciliations</h3>
        <p>Ensure your accounts are balanced and discrepancies are resolved.</p>
      </div>
      <div class="service-card">
        <h3>Consultations</h3>
        <p>Expert advice on financial strategies and compliance.</p>
      </div>
      <div class="service-card">
        <h3>Financial Planning</h3>
        <p>Personalized strategies for your financial future.</p>
      </div>
    </div>
  </section>

  <!-- News Section -->
  <section id="news" class="container">
    <h2>Latest Financial News</h2>
    <div class="news-item">
      <h3>Market Update: Stocks Rise</h3>
      <p>Global markets show positive trends.</p>
      <p class="date">Source: Mock Source | May 12, 2025</p>
    </div>
    <div class="news-item">
      <h3>GST Rates Revised</h3>
      <p>New GST rates effective from June 2025.</p>
      <p class="date">Source: Mock Source | May 12, 2025</p>
    </div>
    <div class="news-item">
      <h3>New Tax Regulations Announced</h3>
      <p>The government has introduced new tax regulations for the upcoming fiscal year.</p>
      <p class="date">Source: Mock Source | May 13, 2025</p>
    </div>
    <div class="news-item">
      <h3>Financial Planning Tips for 2025</h3>
      <p>Experts share top tips for financial planning in the new year.</p>
      <p class="date">Source: Mock Source | May 14, 2025</p>
    </div>
  </section>

  <!-- Contact Section -->
  <section id="contact" class="container">
    <h2 class="text-center">Contact Us</h2>
    <form class="contact-form">
      <label>Name</label>
      <input type="text" required>
      <label>Email</label>
      <input type="email" required>
      <label>Message</label>
      <textarea rows="4" required></textarea>
      <button type="submit">Send Message</button>
    </form>
    <p class="text-center">
      Or contact us via <a href="mailto:info@findataiq.com">info@findataiq.com</a> or WhatsApp at <a href="https://wa.me/919495138171">+919495138171</a>.
    </p>
  </section>

  <!-- Footer -->
  <footer>
    <p>© 2025 FinDataIQ Global. All rights reserved.</p>
    <p>
      Email: <a href="mailto:info@findataiq.com">findataiq.business@gmail.com</a> | WhatsApp: <a href="https://wa.me/919495138171">+919495138171</a>
    </p>
  </footer>

  <!-- Smooth Scrolling Script -->
  <script>
    document.querySelectorAll('a[href^="#"]').forEach(anchor => {
      anchor.addEventListener('click', function (e) {
        e.preventDefault();
        document.querySelector(this.getAttribute('href')).scrollIntoView({
          behavior: 'smooth'
        });
      });
    });
  </script>
</body>
</html>
