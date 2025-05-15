<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Brikely - Expert Home Services</title>
  <style>
    /* Reset some default styles */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      line-height: 1.6;
      background-color: #f9fbfd;
      color: #333;
      padding-top: 60px; /* for fixed nav */
    }

    /* Navigation */
    nav {
      position: fixed;
      top: 0;
      width: 100%;
      background-color: #e3f2fd;
      box-shadow: 0 2px 4px rgba(0,0,0,0.1);
      z-index: 1000;
    }

    nav ul {
      display: flex;
      justify-content: center;
      list-style: none;
      padding: 15px 0;
    }

    nav ul li {
      margin: 0 20px;
    }

    nav ul li a {
      text-decoration: none;
      color: #1565c0;
      font-weight: 600;
      transition: color 0.3s ease;
    }

    nav ul li a:hover {
      color: #0d47a1;
    }

    /* Main content */
    main {
      max-width: 900px;
      margin: 40px auto;
      padding: 0 20px;
      background-color: #ffffff;
      border-radius: 8px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.05);
      padding-bottom: 40px;
    }

    main header h1 {
      color: #0d47a1;
      margin-bottom: 20px;
      font-size: 2.4rem;
      text-align: center;
    }

    main section {
      margin-bottom: 30px;
    }

    main section h2, main section h3, main section h4 {
      color: #1976d2;
      margin-bottom: 12px;
    }

    main section p {
      font-size: 1.05rem;
      color: #444;
    }

    main section ul {
      list-style-type: disc;
      margin-left: 20px;
      color: #555;
    }

    main section ul li {
      margin-bottom: 10px;
      font-weight: 500;
    }

    a {
      color: #1565c0;
      text-decoration: none;
    }

    a:hover {
      text-decoration: underline;
    }

    /* Footer */
    footer {
      text-align: center;
      padding: 20px 10px;
      background-color: #e3f2fd;
      color: #1565c0;
      font-weight: 600;
      box-shadow: inset 0 1px 0 rgba(255,255,255,0.7);
      margin-top: 60px;
    }

    /* Responsive */
    @media (max-width: 600px) {
      nav ul {
        flex-direction: column;
      }
      nav ul li {
        margin: 10px 0;
      }
      main {
        margin: 20px 10px;
      }
    }
  </style>
</head>
<body>
  <nav>
    <ul>
      <li><a href="#services">Services</a></li>
      <li><a href="#expertise">Expertise</a></li>
      <li><a href="#why-brikely">Why Brikely?</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
  </nav>

  <main>
    <header>
      <h1>Brikely: Premier Home Services in London and Manchester</h1>
    </header>

    <section id="services">
      <h2>Comprehensive Home Services</h2>
      <p>
        Brikely offers an extensive range of professional home improvement solutions including flooring, painting, insulation, cleaning, electrical, and plumbing services. 
        Our team of experts is committed to enhancing your property with precision, care, and unmatched expertise.
      </p>
    </section>

    <section id="expertise">
      <h2>Unmatched Expertise in <a href="https://brikely.com/" target="_blank" rel="noopener noreferrer">Home Renovation</a></h2>
      <p>
        With years of experience, Brikely excels in delivering innovative and reliable <a href="https://brikely.com/" target="_blank" rel="noopener noreferrer">home renovation</a> services. 
        We focus on transforming your living spaces through quality workmanship and contemporary design tailored to your unique vision.
      </p>
      <h3>Our Key Services Include:</h3>
      <ul>
        <li>Durable and stylish flooring options</li>
        <li>High-quality interior and exterior painting</li>
        <li>Energy-efficient insulation solutions</li>
        <li>Comprehensive home and yard cleaning</li>
        <li>Certified electrical installations and repairs</li>
        <li>Reliable plumbing maintenance and upgrades</li>
      </ul>
    </section>

    <section id="why-brikely">
      <h2>Why Choose Brikely?</h2>
      <ul>
        <li><strong>Experienced Professionals:</strong> Skilled and certified tradespeople dedicated to excellence.</li>
        <li><strong>Customer-Centric Approach:</strong> Transparent communication and personalized service.</li>
        <li><strong>Competitive Pricing:</strong> High-quality results delivered within your budget.</li>
        <li><strong>Local Knowledge:</strong> Deep understanding of London and Manchester market requirements.</li>
        <li><strong>End-to-End Solutions:</strong> Simplified project management from start to finish.</li>
      </ul>
    </section>

    <section id="contact">
      <h2>Get Started with Brikely Today</h2>
      <p>
        Ready to transform your home? Contact Brikely’s expert team to schedule a consultation and discover tailored solutions that meet your needs with professionalism and style.
      </p>
    </section>
  </main>

  <footer>
    &copy; 2025 Brikely | Trusted Home Services in London & Manchester
  </footer>
</body>
</html>
