<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>Minimalist Planner – Bullet Journals</title>

<style>
    body {
        margin: 0;
        font-family: 'Poppins', sans-serif;
        background: #fff5f8;
        color: #333;
    }

    /* Pink Celestial Header */
    header {
        background: linear-gradient(135deg, #ffb6d9, #ff8fc7, #ffcee4);
        padding: 60px 20px;
        text-align: center;
        color: white;
        position: relative;
    }

    header::after {
        content: "✦ ✧ ✦";
        position: absolute;
        bottom: 20px;
        left: 50%;
        transform: translateX(-50%);
        font-size: 24px;
        letter-spacing: 8px;
        opacity: 0.7;
    }

    h1 {
        margin: 0;
        font-size: 48px;
        letter-spacing: 2px;
    }

    nav {
        display: flex;
        justify-content: center;
        gap: 30px;
        padding: 20px;
        background: white;
        position: sticky;
        top: 0;
    }

    nav a {
        text-decoration: none;
        font-size: 18px;
        color: #c74c7b;
        font-weight: 600;
    }

    section {
        padding: 60px 20px;
        max-width: 1000px;
        margin: auto;
    }

    h2 {
        color: #d14b86;
        font-size: 32px;
        border-bottom: 2px solid #ffc5dd;
        padding-bottom: 10px;
        margin-bottom: 30px;
    }

    /* Product Grid */
    .product-grid {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
        gap: 30px;
    }

    .product {
        background: white;
        border-radius: 12px;
        padding: 20px;
        box-shadow: 0px 4px 15px rgba(0,0,0,0.1);
        text-align: center;
        border: 2px dashed #ffc5dd;
    }

    .product img {
        width: 100%;
        height: 300px;
        object-fit: cover;
        border-radius: 10px;
    }

    .product h3 {
        color: #c34072;
    }

    .price {
        font-size: 20px;
        color: #d14b86;
        font-weight: bold;
    }

    button {
        padding: 12px 20px;
        border: none;
        background: #d14b86;
        color: white;
        border-radius: 8px;
        font-size: 16px;
        cursor: pointer;
        margin-top: 10px;
    }

    /* Blog */
    .blog-post {
        padding: 20px;
        background: white;
        border-radius: 10px;
        margin-bottom: 30px;
        border-left: 4px solid #ff8fc7;
    }

    /* Contact Section */
    .contact-box {
        background: white;
        padding: 25px;
        border-radius: 10px;
        box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }

    footer {
        text-align: center;
        padding: 20px;
        background: #ffcce4;
        margin-top: 50px;
    }
</style>

<script>
function orderNow(product){
    alert("Thank you for choosing " + product + 
          "! Please contact us on WhatsApp (+94 XX XXX XXXX) or Instagram (@minimalistplanner) to place your order.");
}
</script>
</head>

<body>

<header>
    <h1>Minimalist Planner</h1>
    <p>Your Celestial Bullet Journal Shop</p>
</header>

<nav>
    <a href="#products">Products</a>
    <a href="#pricing">Pricing</a>
    <a href="#blog">Blog</a>
    <a href="#contact">Contact</a>
</nav>

<section id="products">
    <h2>Our Bullet Journals</h2>

    <div class="product-grid">

        <div class="product">
            <img src="https://via.placeholder.com/400x300.png?text=Pink+Celestial+Bullet+Journal" />
            <h3>Pink Celestial Journal</h3>
            <p>Soft pink aesthetic with stars + moons. 120gsm paper.</p>
            <p class="price">Rs. 2,800</p>
            <button onclick="orderNow('Pink Celestial Journal')">Order Now</button>
        </div>

        <div class="product">
            <img src="https://via.placeholder.com/400x300.png?text=Minimalist+Weekly+Planner" />
            <h3>Minimalist Weekly Planner</h3>
            <p>Beige layout with elegant celestial icons.</p>
            <p class="price">Rs. 2,200</p>
            <button onclick="orderNow('Minimalist Weekly Planner')">Order Now</button>
        </div>

        <div class="product">
            <img src="https://via.placeholder.com/400x300.png?text=Daily+Productivity+Journal" />
            <h3>Daily Productivity Journal</h3>
            <p>Track habits, water, meals, goals in style.</p>
            <p class="price">Rs. 2,500</p>
            <button onclick="orderNow('Daily Productivity Journal')">Order Now</button>
        </div>

    </div>
</section>

<section id="pricing">
    <h2>Pricing</h2>

    <p><b>• Pink Celestial Journal:</b> Rs. 2,800</p>
    <p><b>• Minimalist Weekly Planner:</b> Rs. 2,200</p>
    <p><b>• Daily Productivity Journal:</b> Rs. 2,500</p>

    <p>Custom Orders Available ❤️ (Extra Rs. 500)</p>
</section>

<section id="blog">
    <h2>Blog & Tips</h2>

    <div class="blog-post">
        <h3>How to Start a Bullet Journal</h3>
        <p>Bullet journaling helps you organize your life beautifully. Start with simple layouts, habit trackers, and monthly spreads.</p>
    </div>

    <div class="blog-post">
        <h3>Why Celestial Planners Are Trendy</h3>
        <p>Stars and moons bring a calming aesthetic into planning. Pink celestial themes inspire creativity + balance.</p>
    </div>

    <div class="blog-post">
        <h3>Best Pens for Bullet Journaling</h3>
        <p>Fine liners, brush pens, and pastel highlighters create beautiful spreads without bleeding.</p>
    </div>
</section>

<section id="contact">
    <h2>Contact Us</h2>

    <div class="contact-box">
        <p><b>📍 Address:</b> Colombo, Sri Lanka</p>
        <p><b>📞 WhatsApp:</b> +94 xx xxx xxxx</p>
        <p><b>📧 Email:</b> minimalistplanner@gmail.com</p>
        <p><b>📸 Instagram:</b> @minimalistplanner</p>
        <p><b>🛍️ Orders:</b> Message us on WhatsApp or Instagram</p>
    </div>
</section>

<footer>
    © 2026 Minimalist Planner – Pink Celestial Bullet Journals
</footer>

</body>
</html>
 
