<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>KEIV and PREVAN Synergy | Stationery Supplies Nairobi</title>
    <style>
        /* COLOR PALETTE & DESIGN SYSTEM */
        :root {
            --blue: #0033aa;
            --red: #dd2222;
            --white: #ffffff;
            --light-gray: #f8f9fa;
            --dark: #1a1a1a;
            --shadow: rgba(0, 0, 0, 0.1);
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Roboto, Helvetica, Arial, sans-serif;
            scroll-behavior: smooth;
        }

        body {
            color: var(--dark);
            background-color: var(--white);
            line-height: 1.6;
        }

        /* NAVIGATION BAR */
        header {
            background-color: var(--white);
            box-shadow: 0 2px 10px var(--shadow);
            position: fixed;
            width: 100%;
            top: 0;
            z-index: 1000;
        }

        .nav-container {
            max-width: 1200px;
            margin: 0 auto;
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 15px 20px;
        }

        .logo {
            font-size: 24px;
            font-weight: 800;
            color: var(--blue);
            letter-spacing: 0.5px;
        }

        .logo span {
            color: var(--red);
        }

        nav ul {
            display: flex;
            list-style: none;
        }

        nav ul li {
            margin-left: 25px;
        }

        nav ul li a {
            text-decoration: none;
            color: var(--dark);
            font-weight: 600;
            font-size: 15px;
            transition: color 0.3s ease;
        }

        nav ul li a:hover {
            color: var(--blue);
        }

        /* HERO SECTION */
        .hero {
            background: linear-gradient(135deg, var(--blue) 60%, var(--red) 100%);
            color: var(--white);
            min-height: 75vh;
            display: flex;
            align-items: center;
            text-align: center;
            padding: 100px 20px 60px;
        }

        .hero-content {
            max-width: 800px;
            margin: 0 auto;
        }

        .hero h1 {
            font-size: 48px;
            font-weight: 800;
            margin-bottom: 20px;
            line-height: 1.2;
        }

        .hero p {
            font-size: 20px;
            margin-bottom: 35px;
            opacity: 0.9;
        }

        .btn {
            display: inline-block;
            background-color: var(--white);
            color: var(--blue);
            padding: 14px 35px;
            text-decoration: none;
            font-weight: 700;
            border-radius: 5px;
            transition: all 0.3s ease;
            border: 2px solid var(--white);
            box-shadow: 0 4px 10px rgba(0,0,0,0.15);
        }

        .btn:hover {
            background-color: transparent;
            color: var(--white);
            box-shadow: none;
        }

        /* SECTION UTILITIES */
        section {
            padding: 80px 20px;
        }

        .section-title {
            font-size: 36px;
            font-weight: 700;
            margin-bottom: 50px;
            text-align: center;
            position: relative;
            color: var(--blue);
        }

        .section-title::after {
            content: '';
            display: block;
            width: 50px;
            height: 4px;
            background-color: var(--red);
            margin: 12px auto 0;
            border-radius: 2px;
        }

        /* PRODUCTS SECTION */
        .products {
            max-width: 1200px;
            margin: 0 auto;
        }

        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
            gap: 30px;
        }

        .card {
            background: var(--white);
            padding: 35px 25px;
            border-radius: 8px;
            box-shadow: 0 5px 20px rgba(0,0,0,0.05);
            border-top: 4px solid var(--blue);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
            text-align: center;
        }

        .card:hover {
            transform: translateY(-5px);
            box-shadow: 0 8px 25px rgba(0,0,0,0.1);
        }

        .card h3 {
            margin-bottom: 15px;
            font-size: 20px;
            color: var(--dark);
        }

        .card p {
            font-size: 15px;
            color: #666;
        }

        /* ABOUT SECTION */
        .about {
            background-color: var(--light-gray);
        }

        .about-content {
            max-width: 800px;
            margin: 0 auto;
            text-align: center;
            font-size: 18px;
            color: #444;
            

            /*VISSION AND MISSION ADDED*/
            
        }

        /* CONTACT SECTION */
        .contact {
            max-width: 1200px;
            margin: 0 auto;
            text-align: center;
        }

        .contact p {
            font-size: 18px;
            margin-bottom: 30px;
            color: #555;
        }

        .contact-info {
            display: inline-flex;
            flex-direction: column;
            gap: 20px;
            font-size: 18px;
            text-align: left;
            background: var(--light-gray);
            padding: 30px 40px;
            border-radius: 8px;
            border-left: 5px solid var(--red);
        }

        .contact-info div {
            display: flex;
            align-items: center;
            gap: 10px;
        }

        .contact-info strong {
            color: var(--blue);
        }

        /* FOOTER */
        footer {
            background-color: var(--white);
            color: var(--dark);
            text-align: center;
            padding: 25px 20px;
            font-size: 14px;
            border-top: 5px solid var(--red);
        }

        /* MOBILE RESPONSIVENESS */
        @media (max-width: 768px) {
            .nav-container {
                flex-direction: column;
                gap: 15px;
            }
            nav ul li {
                margin: 0 12px;
            }
            .hero h1 {
                font-size: 34px;
            }
            .hero p {
                font-size: 16px;
            }
            .contact-info {
                padding: 20px;
                width: 100%;
            }
        }
    </style>
</head>
<body>

    <!-- NAVIGATION HEADER -->
    <header>
        <div class="nav-container">
            <div class="logo">KEIV & PREVAN <span>SYNERGY</span></div>
            <nav>
                <ul>
                    <li><a href="#home">Home</a></li>
                    <li><a href="#products">Products</a></li>
                    <li><a href="#about">About Us</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <!-- HERO SECTION -->
    <section id="home" class="hero">
        <div class="hero-content">
            <h1>Premium Stationery Supplies for Corporate & Education</h1>
            <p>Your trusted partner for high-quality office and school essentials based in CBD, Nairobi.</p>
            <a href="#contact" class="btn">Get a Quote</a>
        </div>
    </section>

    <!-- PRODUCTS SECTION -->
    <section id="products" class="products">
        <h2 class="section-title">Our Premium Products</h2>
        <div class="grid">
            <div class="card">
                <h3>Paper & Notebooks</h3>
                <p>High-grade printing papers (A4, A3), school exercise books, office pads, and specialized ledger books.</p>
            </div>
            <div class="card">
                <h3>Writing Instruments</h3>
                <p>Durable pens, pencils, permanent markers, highlighters, and whiteboard markers from top brands.</p>
            </div>
            <div class="card">
                <h3>Filing & Storage</h3>
                <p>Heavy-duty lever arch files, clear folders, suspension files, and document storage boxes.</p>
            </div>
            <div class="card">
                <h3>Office Desk Tools</h3>
                <p>Premium staplers, punch machines, heavy-duty calculators, paper cutters, and adhesive tapes.</p>
            </div>
        </div>
    </section>

    <!-- ABOUT SECTION -->
    <section id="about" class="about">
        <div class="about-content">
            <h2 class="section-title">About Our Company</h2>
            <p>KEIV and PREVAN Synergy is a premier distributor of commercial, institutional, and personal stationery supplies in Kenya. Operating from CBD, Nairobi, we cater specifically to corporate offices, academic institutions, government bodies, and small businesses. We pride ourselves on delivering excellent service, reliable wholesale inventory management, and competitive pricing.</p>
           
           <h1>Vision </h1> 
To be a leading and trusted provider of quality stationery, modern office equipment, and workplace solutions, recognized for reliability, innovation, and exceptional customer service.
<h2>Mission</h2>
To supply high-quality stationery items and modern office equipment that meet the diverse needs of businesses, institutions, and individuals. We are committed to providing reliable products, competitive prices, timely delivery, and excellent customer service while building long-term relationships with our clients and suppliers.
      
</div>
    </section>

    <!-- CONTACT SECTION -->
    <section id="contact" class="contact">
        <h2 class="section-title">Get in Touch</h2>
        <p>Reach out to us today to fulfill your bulk orders or daily stationeries requirements.</p>
        <div class="contact-info">
            <div>📍 <strong>Location:</strong> JKUAT Towers , Nairobi</div>
            <div>📞 <strong>Phone:</strong> +254 721279233</div>
            <div>✉️ <strong>Email:</strong> keivprevan@gmail.com</div>
        </div>
        <div>💬 <strong>WhatsApp:</strong> +254 721279233</div>
        <div> <a href="https://wa.me/254721279233" target="_blank">Chat with us on WhatsApp</a></div>
        <button
    </section>

    <!-- FOOTER -->
    <footer>
        <p>&copy; 2026 KEIV and PREVAN Synergy. All Rights Reserved. Located at JKUAT Towers, Nairobi.</p>
    </footer>

</body>
</html>
