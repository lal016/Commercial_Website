# Ex02-Commercial Website

## AIM
To create a commercial website using CSS Flexbox.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for Homepage, Products / Services, About Us, Contact Details and User Account.

### STEP 5
Include social media links at the footer with copyright information.

### STEP 6
Define global styles for fonts, colors, and layout.

### STEP 7
Style the header, navigation bar, and sections.

### STEP 8
Use Flexbox for layout design.

### STEP 9
Add hover effects and transitions for interactivity.

### STEP 10
Add Images and Media.

### STEP 11
Use optimized images for a professional look.

### STEP 12
Open the HTML file in a browser to check layout and functionality.

### STEP 13
Fix styling issues and refine content placement.

### STEP 14
Deploy the website.

### STEP 15
Upload to GitHub Pages for free hosting.

## PROGRAM
### HTML:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>LUMORA | Modern Living</title>

    <!-- Link the external CSS file -->
    <link rel="stylesheet" href="style.css">
</head>

<body>

    <!-- Navigation Bar -->
    <header class="navbar">

        <a href="#home" class="logo">LUMORA</a>

        <nav>
            <ul class="nav-links">
                <li><a href="#home">Home</a></li>
                <li><a href="#collections">Collections</a></li>
                <li><a href="#products">Products</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>

        <a href="#products" class="nav-button">Explore Store</a>

    </header>

    <!-- Hero Section -->
    <section class="hero" id="home">

        <div class="hero-content">
            <h1>Make Your Space Feel Like Home.</h1>

            <p>
                Discover thoughtfully designed furniture and lifestyle
                essentials that bring comfort, beauty and simplicity
                into your everyday life.
            </p>

            <a href="#collections" class="button">Explore Collections</a>
        </div>

        <div class="hero-image">
            <img
                src="images/image1.png"
                alt="Modern living room">
        </div>

    </section>

    <!-- Benefits Section -->
    <section class="section benefits">

        <div class="benefit-card">
            <div class="benefit-icon">🚚</div>
            <h3>Free Delivery</h3>
            <p>Enjoy free delivery on eligible orders.</p>
        </div>

        <div class="benefit-card">
            <div class="benefit-icon">🌿</div>
            <h3>Sustainable Living</h3>
            <p>Discover designs inspired by natural living.</p>
        </div>

        <div class="benefit-card">
            <div class="benefit-icon">✨</div>
            <h3>Premium Quality</h3>
            <p>Beautiful products designed for everyday comfort.</p>
        </div>

        <div class="benefit-card">
            <div class="benefit-icon">💬</div>
            <h3>Customer Support</h3>
            <p>We're here to help with your shopping experience.</p>
        </div>

    </section>

    <!-- Collections Section -->
    <section class="section" id="collections">

        <div class="section-heading">
            <h2>Explore Our Collections</h2>
            <p>Find something special for every corner of your home.</p>
        </div>

        <div class="collection-grid">

            <div class="collection-card">
                <img
                    src="images/image1.png"
                    alt="Living room furniture">

                <div class="collection-info">
                    <h3>Living Room</h3>
                    <p>Comfortable sofas, tables and relaxing essentials.</p>
                </div>
            </div>

            <div class="collection-card">
                <img
                    src="images/image2.png"
                    alt="Bedroom interior">

                <div class="collection-info">
                    <h3>Bedroom</h3>
                    <p>Create a peaceful place to rest and recharge.</p>
                </div>
            </div>

            <div class="collection-card">
                <img
                    src="images/image3.png"
                    alt="Dining room interior">

                <div class="collection-info">
                    <h3>Dining Room</h3>
                    <p>Make every meal feel warm and memorable.</p>
                </div>
            </div>

            <div class="collection-card">
                <img
                    src="images/image4.png"
                    alt="Decorative lighting">

                <div class="collection-info">
                    <h3>Lighting</h3>
                    <p>Add warmth and character with elegant lighting.</p>
                </div>
            </div>

            <div class="collection-card">
                <img
                    src="images/image5.png"
                    alt="Modern workspace">

                <div class="collection-info">
                    <h3>Workspace</h3>
                    <p>Design a comfortable and productive workspace.</p>
                </div>
            </div>

            <div class="collection-card">
                <img
                    src="images/image6.png"
                    alt="Home decoration">

                <div class="collection-info">
                    <h3>Home Decor</h3>
                    <p>Small details that make your home unique.</p>
                </div>
            </div>

        </div>

    </section>

    <!-- Products Section -->
    <section class="section products" id="products">

        <div class="section-heading">
            <h2>Our Best Sellers</h2>
            <p>Discover some of our most-loved home essentials.</p>
        </div>

        <div class="product-grid">

            <div class="product-card">
                <img
                    src="images/image7.png"
                    alt="Comfortable sofa">

                <div class="product-info">
                    <h3>Cloud Comfort Sofa</h3>
                    <p>A comfortable sofa for your everyday relaxation.</p>
                    <span class="price">₹24,999</span>
                    <span class="old-price">₹29,999</span>
                    <br>
                    <a href="#contact" class="product-button">View Details</a>
                </div>
            </div>

            <div class="product-card">
                <img
                    src="images/image8.png"
                    alt="Wooden bed">

                <div class="product-info">
                    <h3>Oakwood Bed</h3>
                    <p>A simple wooden bed for a peaceful bedroom.</p>
                    <span class="price">₹32,499</span>
                    <span class="old-price">₹37,999</span>
                    <br>
                    <a href="#contact" class="product-button">View Details</a>
                </div>
            </div>

            <div class="product-card">
                <img
                    src="images/image9.png"
                    alt="Study desk">

                <div class="product-info">
                    <h3>Minimal Study Desk</h3>
                    <p>A practical desk for work, study and creativity.</p>
                    <span class="price">₹8,499</span>
                    <span class="old-price">₹10,999</span>
                    <br>
                    <a href="#contact" class="product-button">View Details</a>
                </div>
            </div>

            <div class="product-card">
                <img
                    src="images/image4.png"
                    alt="Table lamp">

                <div class="product-info">
                    <h3>Glow Table Lamp</h3>
                    <p>Soft lighting for a warm and relaxing atmosphere.</p>
                    <span class="price">₹2,499</span>
                    <span class="old-price">₹3,299</span>
                    <br>
                    <a href="#contact" class="product-button">View Details</a>
                </div>
            </div>

            <div class="product-card">
                <img
                    src="images/image10.png"
                    alt="Accent chair">

                <div class="product-info">
                    <h3>Relax Accent Chair</h3>
                    <p>A stylish chair for reading and relaxation.</p>
                    <span class="price">₹6,999</span>
                    <span class="old-price">₹8,499</span>
                    <br>
                    <a href="#contact" class="product-button">View Details</a>
                </div>
            </div>

            <div class="product-card">
                <img
                    src="images/image11.png"
                    alt="Home accessories">

                <div class="product-info">
                    <h3>Nature Decor Set</h3>
                    <p>Decorative pieces to complete your interior.</p>
                    <span class="price">₹1,899</span>
                    <span class="old-price">₹2,499</span>
                    <br>
                    <a href="#contact" class="product-button">View Details</a>
                </div>
            </div>

            <div class="product-card">
                <img
                    src="images/image12.png"
                    alt="Coffee table">

                <div class="product-info">
                    <h3>Classic Coffee Table</h3>
                    <p>A practical centerpiece for your living room.</p>
                    <span class="price">₹5,499</span>
                    <span class="old-price">₹6,999</span>
                    <br>
                    <a href="#contact" class="product-button">View Details</a>
                </div>
            </div>

            <div class="product-card">
                <img
                    src="images/image13.png"
                    alt="Modern home decor">

                <div class="product-info">
                    <h3>Modern Decor Collection</h3>
                    <p>Thoughtful accents for a beautiful home.</p>
                    <span class="price">₹3,499</span>
                    <span class="old-price">₹4,499</span>
                    <br>
                    <a href="#contact" class="product-button">View Details</a>
                </div>
            </div>

        </div>

    </section>

    <!-- Offer Section -->
    <section class="offer">

        <h2>A Little More Comfort, A Little Less Price</h2>

        <p>
            Explore selected home essentials and enjoy special
            introductory offers on our featured collection.
        </p>

        <a href="#products" class="button">Discover Offers</a>

    </section>

    <!-- About Section -->
    <section class="section about" id="about">

        <div class="about-image">
            <img
                src="images/image14.png"
                alt="Modern home interior">
        </div>

        <div class="about-content">
            <h2>Designed for the Way You Live</h2>

            <p>
                At LUMORA, we believe your home should reflect your
                personality and make everyday life more comfortable.
            </p>

            <p>
                Our collection brings together modern design,
                thoughtful details and practical solutions for
                different living spaces.
            </p>

            <p>
                From comfortable furniture to beautiful decorative
                pieces, we help you create a space that feels like you.
            </p>

            <a href="#collections" class="button">Explore Our Story</a>
        </div>

    </section>

    <!-- Why Choose Us Section -->
    <section class="section why-us">

        <div class="section-heading">
            <h2>Why Choose LUMORA?</h2>
            <p>Small details make a big difference in your home.</p>
        </div>

        <div class="why-grid">

            <div class="why-card">
                <h3>Thoughtful Design</h3>
                <p>
                    Carefully selected styles that complement
                    modern homes and everyday living.
                </p>
            </div>

            <div class="why-card">
                <h3>Comfort First</h3>
                <p>
                    Practical products designed to make your
                    living space more comfortable.
                </p>
            </div>

            <div class="why-card">
                <h3>Style for Everyone</h3>
                <p>
                    Explore different styles to suit your
                    preferences and personal space.
                </p>
            </div>

            <div class="why-card">
                <h3>Customer Care</h3>
                <p>
                    We aim to make discovering your next
                    favourite home item simple and enjoyable.
                </p>
            </div>

        </div>

    </section>

    <!-- Testimonials Section -->
    <section class="section">

        <div class="section-heading">
            <h2>What Our Customers Say</h2>
            <p>A few sample reviews for our demonstration website.</p>
        </div>

        <div class="testimonial-grid">

            <div class="testimonial-card">
                <div class="stars">★★★★★</div>
                <p>
                    "The simple designs and warm colours make it
                    easy to imagine a beautiful home."
                </p>
                <h4>— Priya S.</h4>
            </div>

            <div class="testimonial-card">
                <div class="stars">★★★★★</div>
                <p>
                    "I love the clean layout and the variety of
                    furniture and decor ideas."
                </p>
                <h4>— Arjun K.</h4>
            </div>

            <div class="testimonial-card">
                <div class="stars">★★★★★</div>
                <p>
                    "The collection makes finding inspiration for
                    a modern living space enjoyable."
                </p>
                <h4>— Meera R.</h4>
            </div>

        </div>

    </section>

    <!-- Footer -->
    <footer class="footer" id="contact">

        <div class="footer-grid">

            <div class="footer-column">
                <h3>LUMORA</h3>

                <p>
                    Thoughtfully designed furniture and lifestyle
                    essentials for beautiful everyday living.
                </p>

                <p>Make your space feel like home.</p>
            </div>

            <div class="footer-column">
                <h3>Quick Links</h3>

                <ul>
                    <li><a href="#home">Home</a></li>
                    <li><a href="#collections">Collections</a></li>
                    <li><a href="#products">Products</a></li>
                    <li><a href="#about">About Us</a></li>
                </ul>
            </div>

            <div class="footer-column">
                <h3>Customer Service</h3>

                <ul>
                    <li><a href="#contact">Contact Us</a></li>
                    <li><a href="#contact">Shipping Information</a></li>
                    <li><a href="#contact">Returns and Refunds</a></li>
                    <li><a href="#contact">Frequently Asked Questions</a></li>
                </ul>
            </div>

            <div class="footer-column">
                <h3>Contact Information</h3>

                <p>Email: hello@lumora.example</p>
                <p>Phone: +91 98765 43210</p>
                <p>Working Hours: Monday–Saturday</p>
                <p>10:00 AM – 6:00 PM</p>
            </div>

        </div>

        
        <div class="footer-bottom">
            <p>
                &copy; 2026 LUMORA. All rights reserved.
                Designed for a CSS Flexbox practical project.
            </p>

           <p>Developed by: LAL RHIDHISHAN R</p>
           <p>Register Number: 212225100022</p>
        </div>

    </footer>

</body>
</html>
```
### CSS:
```
/* General Styles */

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    background-color: #faf9f6;
    color: #333;
    line-height: 1.6;
}

a {
    text-decoration: none;
    color: inherit;
}

img {
    width: 100%;
    display: block;
    object-fit: cover;
}


/* Navigation Bar */

.navbar {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 20px 8%;
    background-color: #fff;
    border-bottom: 1px solid #eee;
    flex-wrap: wrap;
    gap: 15px;
}

.logo {
    font-size: 30px;
    font-weight: bold;
    color: #344b3b;
    letter-spacing: 3px;
}

.nav-links {
    display: flex;
    gap: 25px;
    list-style: none;
    flex-wrap: wrap;
}

.nav-links a {
    font-size: 14px;
    color: #444;
}

.nav-links a:hover {
    color: #8b6f47;
}

.nav-button {
    background-color: #344b3b;
    color: white;
    padding: 10px 18px;
    font-size: 14px;
}


/* Buttons */

.button {
    display: inline-block;
    padding: 13px 25px;
    background-color: #344b3b;
    color: white;
    border: none;
    cursor: pointer;
}

.button:hover {
    background-color: #506b56;
}


/* Hero Section */

.hero {
    min-height: 500px;
    padding: 70px 8%;
    display: flex;
    align-items: center;
    justify-content: space-between;
    gap: 40px;
    background-color: #e9e8df;
    flex-wrap: wrap;
}

.hero-content {
    flex: 1 1 350px;
}

.hero-content h1 {
    font-size: 52px;
    line-height: 1.2;
    color: #344b3b;
    margin-bottom: 20px;
}

.hero-content p {
    font-size: 17px;
    color: #666;
    margin-bottom: 30px;
    max-width: 500px;
}

.hero-image {
    flex: 1 1 350px;
}

.hero-image img {
    height: 350px;
    border-radius: 5px;
}


/* Common Section Styles */

.section {
    padding: 70px 8%;
}

.section-heading {
    text-align: center;
    margin-bottom: 40px;
}

.section-heading h2 {
    font-size: 34px;
    color: #344b3b;
    margin-bottom: 10px;
}

.section-heading p {
    color: #777;
}


/* Benefits Section */

.benefits {
    display: flex;
    justify-content: space-between;
    gap: 25px;
    flex-wrap: wrap;
    background-color: #fff;
}

.benefit-card {
    flex: 1 1 200px;
    text-align: center;
    padding: 20px;
}

.benefit-card h3 {
    color: #344b3b;
    margin-bottom: 8px;
}

.benefit-card p {
    color: #777;
    font-size: 14px;
}

.benefit-icon {
    font-size: 35px;
    margin-bottom: 10px;
}


/* Collections Section */

.collection-grid {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 25px;
}

.collection-card {
    flex: 1 1 250px;
    max-width: 350px;
    background-color: white;
    overflow: hidden;
}

.collection-card img {
    height: 230px;
    transition: transform 0.3s;
}

.collection-card:hover img {
    transform: scale(1.04);
}

.collection-info {
    padding: 20px;
    text-align: center;
}

.collection-info h3 {
    color: #344b3b;
    margin-bottom: 8px;
}

.collection-info p {
    color: #777;
    font-size: 14px;
}


/* Products Section */

.products {
    background-color: #f0efe8;
}

.product-grid {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 25px;
}

.product-card {
    flex: 1 1 220px;
    max-width: 280px;
    background-color: white;
    padding-bottom: 20px;
    transition: transform 0.3s;
}

.product-card:hover {
    transform: translateY(-5px);
}

.product-card img {
    height: 230px;
}

.product-info {
    padding: 15px;
}

.product-info h3 {
    color: #344b3b;
    font-size: 18px;
    margin-bottom: 5px;
}

.product-info p {
    font-size: 13px;
    color: #777;
    margin-bottom: 10px;
}

.price {
    color: #8b6f47;
    font-weight: bold;
    font-size: 18px;
}

.old-price {
    color: #999;
    text-decoration: line-through;
    font-size: 13px;
    margin-left: 8px;
}

.product-button {
    display: inline-block;
    margin-top: 12px;
    padding: 9px 15px;
    background-color: #344b3b;
    color: white;
    font-size: 13px;
}


/* Offer Section */

.offer {
    padding: 65px 8%;
    text-align: center;
    background-color: #344b3b;
    color: white;
}

.offer h2 {
    font-size: 35px;
    margin-bottom: 12px;
}

.offer p {
    margin-bottom: 25px;
    color: #e4e8e2;
}

.offer .button {
    background-color: white;
    color: #344b3b;
}


/* About Section */

.about {
    display: flex;
    align-items: center;
    justify-content: space-between;
    gap: 40px;
    flex-wrap: wrap;
}

.about-image {
    flex: 1 1 300px;
}

.about-image img {
    height: 350px;
    border-radius: 5px;
}

.about-content {
    flex: 1 1 300px;
}

.about-content h2 {
    font-size: 34px;
    color: #344b3b;
    margin-bottom: 20px;
}

.about-content p {
    color: #666;
    margin-bottom: 15px;
}


/* Why Choose Us Section */

.why-us {
    background-color: #e9e8df;
}

.why-grid {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 25px;
}

.why-card {
    flex: 1 1 220px;
    background-color: white;
    padding: 25px;
    text-align: center;
}

.why-card h3 {
    color: #344b3b;
    margin-bottom: 10px;
}

.why-card p {
    font-size: 14px;
    color: #777;
}


/* Testimonials Section */

.testimonial-grid {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 25px;
}

.testimonial-card {
    flex: 1 1 250px;
    background-color: white;
    padding: 25px;
    border: 1px solid #eee;
}

.testimonial-card p {
    color: #666;
    font-style: italic;
    margin-bottom: 15px;
}

.testimonial-card h4 {
    color: #344b3b;
}

.stars {
    color: #b18b45;
    margin-bottom: 10px;
}


/* Footer Section */

.footer {
    background-color: #26372b;
    color: white;
    padding: 50px 8% 20px;
}

.footer-grid {
    display: flex;
    justify-content: space-between;
    gap: 35px;
    flex-wrap: wrap;
    margin-bottom: 35px;
}

.footer-column {
    flex: 1 1 180px;
}

.footer-column h3 {
    margin-bottom: 15px;
    color: #e3d6b8;
}

.footer-column p {
    font-size: 14px;
    color: #d0d5d0;
    margin-bottom: 10px;
}

.footer-column ul {
    list-style: none;
}

.footer-column li {
    margin-bottom: 8px;
    font-size: 14px;
    color: #d0d5d0;
}

.footer-column a:hover {
    color: #e3d6b8;
}

.footer-bottom {
    text-align: center;
    border-top: 1px solid #506052;
    padding-top: 20px;
    font-size: 13px;
    color: #d0d5d0;
}


/* Tablet Responsive Design */

@media (max-width: 768px) {

    .navbar {
        flex-direction: column;
        text-align: center;
    }

    .nav-links {
        justify-content: center;
        gap: 15px;
    }

    .hero {
        text-align: center;
        padding: 50px 6%;
    }

    .hero-content h1 {
        font-size: 38px;
    }

    .hero-content p {
        margin-left: auto;
        margin-right: auto;
    }

    .hero-image img {
        height: 280px;
    }

    .section {
        padding: 50px 6%;
    }

    .section-heading h2 {
        font-size: 28px;
    }

    .offer h2 {
        font-size: 28px;
    }

    .about {
        text-align: center;
    }

    .about-image img {
        height: 280px;
    }
}


/* Mobile Responsive Design */

@media (max-width: 480px) {

    .logo {
        font-size: 25px;
    }

    .nav-links {
        gap: 10px;
    }

    .nav-links a {
        font-size: 12px;
    }

    .hero-content h1 {
        font-size: 32px;
    }

    .section-heading h2,
    .about-content h2 {
        font-size: 25px;
    }

    .collection-card,
    .product-card {
        max-width: 100%;
    }

    .offer h2 {
        font-size: 24px;
    }
}
```

## OUTPUT

output_img/image.png

output_img/image-1.png

output_img/image-2.png

output_img/image-3.png

output_img/image-4.png

## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
