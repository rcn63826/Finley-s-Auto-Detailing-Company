<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <title>Finley's Auto Detailing Company</title>
    <style>
        /* Global styles */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            color: #333;
        }
        header {
            background-color: #1a1a1a;
            padding: 20px;
            color: white;
            text-align: center;
        }
        header h1 {
            margin: 0;
        }
        nav {
            margin: 20px 0;
        }
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
        }
        .cta {
            background: url('https://example.com/car-detailing.jpg') no-repeat center center/cover;
            height: 400px;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
            color: white;
        }
        .cta h2 {
            font-size: 3rem;
        }
        .cta p {
            font-size: 1.2rem;
        }
        .services, .testimonials {
            padding: 50px 20px;
            text-align: center;
        }
        .services h2, .testimonials h2 {
            margin-bottom: 20px;
        }
        .services .service-item {
            display: inline-block;
            width: 30%;
            padding: 15px;
            margin: 10px;
            background-color: #f4f4f4;
            border-radius: 5px;
        }
        .testimonials .testimonial-item {
            margin-bottom: 20px;
            background-color: #e6e6e6;
            padding: 20px;
            border-radius: 5px;
        }
        .contact-form {
            padding: 50px 20px;
            text-align: center;
        }
        .contact-form form {
            display: inline-block;
            text-align: left;
        }
        .contact-form label, .contact-form input, .contact-form textarea {
            display: block;
            width: 100%;
            margin-bottom: 15px;
        }
        .contact-form input, .contact-form textarea {
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        footer {
            background-color: #1a1a1a;
            color: white;
            padding: 20px;
            text-align: center;
        }
        footer a {
            color: #ffa500;
            text-decoration: none;
        }
    </style>
</head>
<body>

    <!-- Header Section -->
    <header>
        <h1>Finley's Auto Detailing Company</h1>
        <nav>
            <a href="#services">Services</a>
            <a href="#testimonials">Testimonials</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <!-- Call-to-action Section -->
    <section class="cta">
        <div>
            <h2>High-Quality Auto Detailing Services</h2>
            <p>We ensure every customer is satisfied with their car's showroom finish.</p>
        </div>
    </section>

    <!-- Services Section -->
    <section id="services" class="services">
        <h2>Our Services</h2>
        <div class="service-item">
            <h3>Exterior Detailing</h3>
            <p>Polishing, waxing, and cleaning your car to perfection.</p>
        </div>
        <div class="service-item">
            <h3>Interior Detailing</h3>
            <p>Thorough interior cleaning for a fresh and pristine finish.</p>
        </div>
        <div class="service-item">
            <h3>Full Detailing Package</h3>
            <p>Complete inside and outside detailing for a showroom-ready vehicle.</p>
        </div>
    </section>

    <!-- Testimonials Section -->
    <section id="testimonials" class="testimonials">
        <h2>Customer Testimonials</h2>
        <div class="testimonial-item">
            <p>"Finley's Auto Detailing transformed my car! It looks brand new. Highly recommended!"</p>
            <h4>- Sarah K.</h4>
        </div>
        <div class="testimonial-item">
            <p>"Amazing attention to detail. Finley's team did an excellent job!"</p>
            <h4>- John P.</h4>
        </div>
        <div class="testimonial-item">
            <p>"Best detailing service I've ever experienced. My car has never looked better."</p>
            <h4>- Emily R.</h4>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="contact-form">
        <h2>Contact Us</h2>
        <form action="mailto:finley@autodetailing.com" method="post" enctype="text/plain">
            <label for="name">Your Name</label>
            <input type="text" id="name" name="name" required>

            <label for="email">Your Email</label>
            <input type="email" id="email" name="email" required>

            <label for="message">Message</label>
            <textarea id="message" name="message" rows="4" required></textarea>

            <input type="submit" value="Send Message">
        </form>
    </section>

    <!-- Footer Section -->
    <footer>
        <p>&copy; 2024 Finley's Auto Detailing Company. All Rights Reserved.</p>
        <p><a href="https://www.instagram.com/finleysdetailing" target="_blank">Follow us on Instagram</a></p>
    </footer>

</body>
</html>
