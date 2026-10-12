# amman-traders
Amman Traders – Sales &amp; Service, Palani
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Amman Traders | Sales & Service</title>

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            color: #183153;
            background: #f4f8ff;
            line-height: 1.6;
        }

        header {
            background: #0756a8;
            color: white;
            padding: 22px 8%;
            display: flex;
            justify-content: space-between;
            align-items: center;
            flex-wrap: wrap;
            gap: 12px;
        }

        header h1 {
            font-size: 27px;
        }

        header p {
            font-size: 13px;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 8px;
            font-weight: bold;
        }

        .hero {
            text-align: center;
            padding: 85px 20px;
            background: linear-gradient(135deg, #0756a8, #43a5ff);
            color: white;
        }

        .hero h2 {
            font-size: 42px;
            margin-bottom: 15px;
        }

        .hero p {
            font-size: 18px;
            margin-bottom: 25px;
        }

        .button {
            display: inline-block;
            background: white;
            color: #0756a8;
            padding: 12px 24px;
            margin: 6px;
            border-radius: 6px;
            text-decoration: none;
            font-weight: bold;
        }

        section {
            padding: 55px 8%;
            text-align: center;
        }

        section h2 {
            color: #0756a8;
            margin-bottom: 25px;
            font-size: 30px;
        }

        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(190px, 1fr));
            gap: 20px;
        }

        .card {
            background: white;
            padding: 25px 15px;
            border-radius: 12px;
            box-shadow: 0 4px 15px #18315312;
        }

        .card .icon {
            font-size: 42px;
            margin-bottom: 10px;
        }

        .card h3 {
            margin-bottom: 8px;
        }

        #about, #contact {
            background: white;
        }

        .contact-button {
            display: inline-block;
            background: #0756a8;
            color: white;
            padding: 12px 24px;
            margin: 10px;
            border-radius: 6px;
            text-decoration: none;
            font-weight: bold;
        }

        footer {
            background: #07366b;
            color: white;
            padding: 22px;
            text-align: center;
        }

        @media (max-width: 600px) {
            header {
                justify-content: center;
                text-align: center;
            }

            .hero h2 {
                font-size: 30px;
            }

            nav {
                text-align: center;
            }
        }
    </style>
</head>

<body>

<header>
    <div>
        <h1>AMMAN TRADERS</h1>
        <p>Home Appliances | Sales & Service</p>
    </div>

    <nav>
        <a href="#home">Home</a>
        <a href="#products">Products</a>
        <a href="#services">Services</a>
        <a href="#contact">Contact</a>
    </nav>
</header>

<div class="hero" id="home">
    <h2>Welcome to Amman Traders</h2>
    <p>Your Trusted Home Appliance Sales & Service Centre in Palani</p>
    <a href="#products" class="button">View Products</a>
    <a href="#services" class="button">Our Services</a>
</div>

<section id="products">
    <h2>Our Products</h2>

    <div class="grid">
        <div class="card">
            <div class="icon">🥤</div>
            <h3>Mixers</h3>
            <p>Home mixer appliances.</p>
        </div>

        <div class="card">
            <div class="icon">⚙️</div>
            <h3>Grinders</h3>
            <p>Home grinding appliances.</p>
        </div>

        <div class="card">
            <div class="icon">🔥</div>
            <h3>Gas Stoves</h3>
            <p>Cooking appliances.</p>
        </div>

        <div class="card">
            <div class="icon">🍲</div>
            <h3>Pressure Cookers</h3>
            <p>Kitchen essentials.</p>
        </div>

        <div class="card">
            <div class="icon">🌀</div>
            <h3>Ceiling Fans</h3>
            <p>Home ventilation products.</p>
        </div>

        <div class="card">
            <div class="icon">☕</div>
            <h3>Electric Kettles</h3>
            <p>Everyday kitchen appliances.</p>
        </div>

        <div class="card">
            <div class="icon">🚿</div>
            <h3>Water Heaters</h3>
            <p>Hot water appliances.</p>
        </div>
    </div>
</section>

<section id="services">
    <h2>Our Repair Services</h2>

    <div class="grid">
        <div class="card">
            <h3>Mixer & Grinder Service</h3>
            <p>Repair and maintenance.</p>
        </div>

        <div class="card">
            <h3>Gas Stove Service</h3>
            <p>Inspection and maintenance.</p>
        </div>

        <div class="card">
            <h3>Cooker Service</h3>
            <p>Appliance care and servicing.</p>
        </div>

        <div class="card">
            <h3>Fan Service</h3>
            <p>Ceiling fan maintenance.</p>
        </div>

        <div class="card">
            <h3>Kettle Service</h3>
            <p>Electric kettle repairs.</p>
        </div>

        <div class="card">
            <h3>Water Heater Service</h3>
            <p>Water heater maintenance.</p>
        </div>
    </div>
</section>

<section id="about">
    <h2>About Amman Traders</h2>
    <p>
        Amman Traders is a home appliance sales and service shop
        in Palani, Tamil Nadu. We help customers with home appliances,
        repairs and maintenance.
    </p>
</section>

<section id="contact">
    <h2>Contact Us</h2>
    <p><strong>Amman Traders – Sales & Service</strong></p>
    <p>Location: Palani, Tamil Nadu</p>
    <p>Contact us for product and service enquiries.</p>

    <!-- Add your phone and WhatsApp number here later. -->

    <a class="contact-button"
       href="https://www.google.com/maps/search/?api=1&query=Amman+Traders+Palani"
       target="_blank" rel="noopener">
       Find Us on Google Maps
    </a>
</section>

<footer>
    <p>© 2026 Amman Traders | Sales & Service | Palani</p>
</footer>

</body>
</html>
```
