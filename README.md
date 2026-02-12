# Ex02 Commercial Website
## Date: 02.02.2026
## Name: Balaji A 
## RegNo: 212223040023

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
```
<!doctype html>
<html lang="en">

<head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
    <!-- Fav Icon -->
    <link rel="icon" href="images/logo.png" type="image/gif" sizes="16x16">
    <!-- Google fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Abel&display=swap" rel="stylesheet">
    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.0/css/bootstrap.min.css"
        integrity="sha384-9aIt2nRpC12Uk9gS9baDl411NQApFmC26EwAOH8WgZl5MYYxFfc+NcPb1dKGj7Sk" crossorigin="anonymous">
    <!-- Main css -->
    <link rel="stylesheet" href="style.css">
    <title>HOT GADGETS</title>
</head>

<body>
    <main class="container">
        <!-- Header start  -->
        <header>
            <nav class="navbar navbar-expand-lg navbar-light fill">
                <a class="navbar-brand" href="#"><img src="images/logo.png" alt=""></a>
                <button class="navbar-toggler" type="button" data-toggle="collapse"
                    data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false"
                    aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon"></span>
                </button>

                <div class="collapse navbar-collapse" id="navbarSupportedContent">
                    <ul class="navbar-nav ml-auto">
                        <li class="nav-item active">
                            <a class="nav-link" href="#">Home</a>
                        </li>
                        <li class="nav-item active">
                            <a class="nav-link" href="#">Product</a>
                        </li>
                        <li class="nav-item active">
                            <a class="nav-link" href="#">About Us</a>
                        </li>
                        <li class="nav-item active">
                            <a class="nav-link" href="#">Contact Us</a>
                        </li>
                    </ul>
                </div>
            </nav>
        </header>
        <!-- Header end  -->

        <!-- Mack book pro start -->

        <section id="mack-book">
            <div id="carouselExampleIndicators" class="carousel slide" data-ride="carousel">
                <ol class="carousel-indicators">
                    <li data-target="#carouselExampleIndicators" data-slide-to="0" class="active"></li>
                    <li data-target="#carouselExampleIndicators" data-slide-to="1"></li>
                    <li data-target="#carouselExampleIndicators" data-slide-to="2"></li>
                </ol>
                <div class="carousel-inner">
                    <div class="carousel-item active">
                        <div class="row">
                            <div class="col-md-6 mack d-flex flex-column justify-content-center">
                                <h1>MackBook Pro</h1>
                                <p>Experience the power of the new MacBook Pro. With its retina display and
                                    lightning-fast processor, it's the ultimate tool for creative professionals.</p>
                                <a class="mack-btn">Buy Now
                                    <svg width="1em" height="1em" viewBox="0 0 16 16" class="bi bi-arrow-right"
                                        fill="currentColor" xmlns="http://www.w3.org/2000/svg">
                                        <path fill-rule="evenodd"
                                            d="M10.146 4.646a.5.5 0 0 1 .708 0l3 3a.5.5 0 0 1 0 .708l-3 3a.5.5 0 0 1-.708-.708L12.793 8l-2.647-2.646a.5.5 0 0 1 0-.708z" />
                                        <path fill-rule="evenodd"
                                            d="M2 8a.5.5 0 0 1 .5-.5H13a.5.5 0 0 1 0 1H2.5A.5.5 0 0 1 2 8z" />
                                    </svg>
                                </a>
                            </div>
                            <div class="col-md-6">
                                <img src="images/banner-products/product-1.png" alt="" class="img-fluid">
                            </div>
                        </div>
                    </div>
                    <div class="carousel-item">
                        <div class="row">
                            <div class="col-md-6 mack">
                                <h1>Alexa</h1>
                                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Et illum in iste rerum
                                    perferendis suscipit ipsa commodi, dolores laborum iusto sequi, incidunt voluptas
                                    eos est molestiae temporibus minima corporis voluptatibus!</p>
                                <a class="mack-btn">Buy Now
                                    <svg width="1em" height="1em" viewBox="0 0 16 16" class="bi bi-arrow-right"
                                        fill="currentColor" xmlns="http://www.w3.org/2000/svg">
                                        <path fill-rule="evenodd"
                                            d="M10.146 4.646a.5.5 0 0 1 .708 0l3 3a.5.5 0 0 1 0 .708l-3 3a.5.5 0 0 1-.708-.708L12.793 8l-2.647-2.646a.5.5 0 0 1 0-.708z" />
                                        <path fill-rule="evenodd"
                                            d="M2 8a.5.5 0 0 1 .5-.5H13a.5.5 0 0 1 0 1H2.5A.5.5 0 0 1 2 8z" />
                                    </svg>
                                </a>
                            </div>
                            <div class="col-md-6">
                                <img src="images/banner-products/slider-1.png" alt="" class="img-fluid">
                            </div>
                        </div>
                    </div>
                    <div class="carousel-item">
                        <div class="row">
                            <div class="col-md-6 mack">
                                <h1>JBU</h1>
                                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Et illum in iste rerum
                                    perferendis suscipit ipsa commodi, dolores laborum iusto sequi, incidunt voluptas
                                    eos est molestiae temporibus minima corporis voluptatibus!</p>
                                <a class="mack-btn">Buy Now
                                    <svg width="1em" height="1em" viewBox="0 0 16 16" class="bi bi-arrow-right"
                                        fill="currentColor" xmlns="http://www.w3.org/2000/svg">
                                        <path fill-rule="evenodd"
                                            d="M10.146 4.646a.5.5 0 0 1 .708 0l3 3a.5.5 0 0 1 0 .708l-3 3a.5.5 0 0 1-.708-.708L12.793 8l-2.647-2.646a.5.5 0 0 1 0-.708z" />
                                        <path fill-rule="evenodd"
                                            d="M2 8a.5.5 0 0 1 .5-.5H13a.5.5 0 0 1 0 1H2.5A.5.5 0 0 1 2 8z" />
                                    </svg>
                                </a>
                            </div>
                            <div class="col-md-6">
                                <img src="images/banner-products/slider-3.png" alt="" class="img-fluid">
                            </div>
                        </div>
                    </div>
                </div>
            </div>

        </section>
        <!-- End -->

        <!-- Smart Phone start  -->
        <section id="smartphone">
            <div class="container">
                <div class="smartphone-header">
                    <div class="row">
                        <div class="col-md-6">
                            <h1>SmartPhones</h1>
                        </div>
                        <div class="col-md-6 text-right">
                            <h5>See All</h5>
                        </div>
                    </div>
                </div>
                <div class="row justify-content-center">
                    <div class="col-md-4">
                        <div class="card text-center h-100 shadow-sm border-0">
                            <img src="images/phone/phone-2.png" class="card-img-top" alt="...">
                            <div class="card-body d-flex flex-column">
                                <h5 class="card-title"><b>iPhone 11 Pro</b></h5>
                                <p class="card-text">Triple-camera system with Night mode, Portrait mode, and 4K video.
                                    The most powerful iPhone yet.</p>
                                <h5><b>₹1,25,000</b></h5>
                                <div class="mt-auto">
                                    <a href="#" class="btn smartphone-btn">BUY NOW
                                        <svg width="1em" height="1em" viewBox="0 0 16 16" class="bi bi-arrow-right"
                                            fill="currentColor" xmlns="http://www.w3.org/2000/svg">
                                            <path fill-rule="evenodd"
                                                d="M10.146 4.646a.5.5 0 0 1 .708 0l3 3a.5.5 0 0 1 0 .708l-3 3a.5.5 0 0 1-.708-.708L12.793 8l-2.647-2.646a.5.5 0 0 1 0-.708z" />
                                            <path fill-rule="evenodd"
                                                d="M2 8a.5.5 0 0 1 .5-.5H13a.5.5 0 0 1 0 1H2.5A.5.5 0 0 1 2 8z" />
                                        </svg>
                                    </a>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="col-md-4">
                        <div class="card text-center h-100 shadow-sm border-0">
                            <img src="images/phone/phone-3.png" class="card-img-top" alt="...">
                            <div class="card-body d-flex flex-column">
                                <h5 class="card-title"><b>Samsung Galaxy Note10+</b></h5>
                                <p class="card-text">Power designed to keep up with you. Cinematic Infinity Display and
                                    professional-grade camera.</p>
                                <h5><b>₹1,10,000</b></h5>
                                <div class="mt-auto">
                                    <a href="#" class="btn smartphone-btn">BUY NOW
                                        <svg width="1em" height="1em" viewBox="0 0 16 16" class="bi bi-arrow-right"
                                            fill="currentColor" xmlns="http://www.w3.org/2000/svg">
                                            <path fill-rule="evenodd"
                                                d="M10.146 4.646a.5.5 0 0 1 .708 0l3 3a.5.5 0 0 1 0 .708l-3 3a.5.5 0 0 1-.708-.708L12.793 8l-2.647-2.646a.5.5 0 0 1 0-.708z" />
                                            <path fill-rule="evenodd"
                                                d="M2 8a.5.5 0 0 1 .5-.5H13a.5.5 0 0 1 0 1H2.5A.5.5 0 0 1 2 8z" />
                                        </svg>
                                    </a>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="col-md-4">
                        <div class="card text-center h-100 shadow-sm border-0">
                            <img src="images/phone/phone-1.png" class="card-img-top" alt="...">
                            <div class="card-body d-flex flex-column">
                                <h5 class="card-title"><b>Redmi Note 8</b></h5>
                                <p class="card-text">48MP Quad camera all-star. High-performance octa-core processor for
                                    seamless gaming.</p>
                                <h5><b>₹60,000</b></h5>
                                <div class="mt-auto">
                                    <a href="#" class="btn smartphone-btn">BUY NOW
                                        <svg width="1em" height="1em" viewBox="0 0 16 16" class="bi bi-arrow-right"
                                            fill="currentColor" xmlns="http://www.w3.org/2000/svg">
                                            <path fill-rule="evenodd"
                                                d="M10.146 4.646a.5.5 0 0 1 .708 0l3 3a.5.5 0 0 1 0 .708l-3 3a.5.5 0 0 1-.708-.708L12.793 8l-2.647-2.646a.5.5 0 0 1 0-.708z" />
                                            <path fill-rule="evenodd"
                                                d="M2 8a.5.5 0 0 1 .5-.5H13a.5.5 0 0 1 0 1H2.5A.5.5 0 0 1 2 8z" />
                                        </svg>
                                    </a>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        <!-- End  -->

        <!-- Laptop start  -->

        <section id="laptop">
            <div class="container">
                <div class="laptop-header">
                    <div class="row">
                        <div class="col-md-6">
                            <h1>Laptop</h1>
                        </div>
                        <div class="col-md-6 text-right">
                            <h5>See All</h5>
                        </div>
                    </div>
                </div>
                <div class="row justify-content-center">
                    <div class="col-md-4">
                        <div class="card text-center h-100 shadow-sm border-0">
                            <img src="images/laptop/product-1.png" class="card-img-top" alt="...">
                            <div class="card-body d-flex flex-column">
                                <h5 class="card-title"><b>Asus VivoBook</b></h5>
                                <p class="card-text">Express yourself with the bold VivoBook S15. Thin, light, and
                                    available in striking colors.</p>
                                <h5><b>₹1,70,000</b></h5>
                                <div class="mt-auto">
                                    <a href="#" class="btn laptop-btn">BUY NOW
                                        <svg width="1em" height="1em" viewBox="0 0 16 16" class="bi bi-arrow-right"
                                            fill="currentColor" xmlns="http://www.w3.org/2000/svg">
                                            <path fill-rule="evenodd"
                                                d="M10.146 4.646a.5.5 0 0 1 .708 0l3 3a.5.5 0 0 1 0 .708l-3 3a.5.5 0 0 1-.708-.708L12.793 8l-2.647-2.646a.5.5 0 0 1 0-.708z" />
                                            <path fill-rule="evenodd"
                                                d="M2 8a.5.5 0 0 1 .5-.5H13a.5.5 0 0 1 0 1H2.5A.5.5 0 0 1 2 8z" />
                                        </svg>
                                    </a>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="col-md-4">
                        <div class="card text-center h-100 shadow-sm border-0">
                            <img src="images/laptop/product-2.png" class="card-img-top" alt="...">
                            <div class="card-body d-flex flex-column">
                                <h5 class="card-title"><b>Razer Blade 15</b></h5>
                                <p class="card-text">The world's smallest 15.6-inch gaming laptop. Action-packed
                                    gameplay with 144Hz display.</p>
                                <h5><b>₹2,50,000</b></h5>
                                <div class="mt-auto">
                                    <a href="#" class="btn laptop-btn">BUY NOW
                                        <svg width="1em" height="1em" viewBox="0 0 16 16" class="bi bi-arrow-right"
                                            fill="currentColor" xmlns="http://www.w3.org/2000/svg">
                                            <path fill-rule="evenodd"
                                                d="M10.146 4.646a.5.5 0 0 1 .708 0l3 3a.5.5 0 0 1 0 .708l-3 3a.5.5 0 0 1-.708-.708L12.793 8l-2.647-2.646a.5.5 0 0 1 0-.708z" />
                                            <path fill-rule="evenodd"
                                                d="M2 8a.5.5 0 0 1 .5-.5H13a.5.5 0 0 1 0 1H2.5A.5.5 0 0 1 2 8z" />
                                        </svg>
                                    </a>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="col-md-4">
                        <div class="card text-center h-100 shadow-sm border-0">
                            <img src="images/laptop/product-3.png" class="card-img-top" alt="...">
                            <div class="card-body d-flex flex-column">
                                <h5 class="card-title"><b>Xiaomi Mi Notebook</b></h5>
                                <p class="card-text">Performance meets style. Full metal body, dedicated graphics, and a
                                    stunning display.</p>
                                <h5><b>$999</b></h5>
                                <div class="mt-auto">
                                    <a href="#" class="btn laptop-btn">BUY NOW
                                        <svg width="1em" height="1em" viewBox="0 0 16 16" class="bi bi-arrow-right"
                                            fill="currentColor" xmlns="http://www.w3.org/2000/svg">
                                            <path fill-rule="evenodd"
                                                d="M10.146 4.646a.5.5 0 0 1 .708 0l3 3a.5.5 0 0 1 0 .708l-3 3a.5.5 0 0 1-.708-.708L12.793 8l-2.647-2.646a.5.5 0 0 1 0-.708z" />
                                            <path fill-rule="evenodd"
                                                d="M2 8a.5.5 0 0 1 .5-.5H13a.5.5 0 0 1 0 1H2.5A.5.5 0 0 1 2 8z" />
                                        </svg>
                                    </a>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- End  -->

        <!-- Categories Start -->

        <section id="categories">
            <div class="container">
                <div class="row text-center">
                    <div class="col-md-12">
                        <h1>Categories</h1>
                        <hr>
                    </div>
                </div>
                <div class="row align-items-center mb-5">
                    <div class="col-md-6">
                        <div class="d-flex flex-wrap justify-content-between align-items-center">
                            <div class="category-item mb-4 text-center p-3 shadow-sm rounded">
                                <img src="images/Categories/bag.png" alt="" class="img-fluid mb-3">
                                <h3>Bag</h3>
                            </div>
                            <div class="category-item mb-4 text-center p-3 shadow-sm rounded">
                                <img src="images/Categories/perfume.png" alt="" class="img-fluid mb-3">
                                <h3 class="mt-2">Beauty</h3>
                            </div>
                            <div class="category-item mb-4 text-center p-3 shadow-sm rounded">
                                <img src="images/Categories/shoe.png" alt="" class="img-fluid mb-3">
                                <h3>Shoes</h3>
                            </div>
                        </div>
                    </div>
                    <div class="col-md-6 text-center">
                        <img src="images/Categories/pale-order.png" alt="" class="img-fluid">
                    </div>
                </div>
            </div>
        </section>

        <!-- End -->

        <!-- Footer start  -->
        <footer class="mt-5 pb-4">
            <div class="container">
                <div class="row mb-5">
                    <div class="col-md-4 mb-4">
                        <img src="images/logo.png" alt="HOT GADGETS" class="mb-3" style="max-width: 150px;">
                        <p class="text-muted">Hot Gadgets is your premium destination for the latest technology. We
                            bring you the best in laptops, smartphones, and accessories.</p>
                    </div>
                    <div class="col-md-4 mb-4">
                        <h4 class="font-weight-bold mb-3">Quick Links</h4>
                        <ul class="list-unstyled footer-links">
                            <li><a href="#">Home</a></li>
                            <li><a href="#">Product</a></li>
                            <li><a href="#">About Us</a></li>
                            <li><a href="#">Contact Us</a></li>
                        </ul>
                    </div>
                    <div class="col-md-4 mb-4">
                        <h4 class="font-weight-bold mb-3">Contact Info</h4>
                        <ul class="list-unstyled footer-contact">
                            <li><span class="mr-2">📍</span> 123 Tech Street, Silicon Valley, CA</li>
                            <li><span class="mr-2">📧</span> support@hotgadgets.com</li>
                            <li><span class="mr-2">📞</span> 6380684400</li>
                        </ul>
                    </div>
                </div>
                <!-- Copyright Bar -->
                <div class="row border-top pt-4">
                    <div class="col-md-12 text-center text-muted">
                        <p class="mb-0">&copy; 2026 Hot Gadgets. All rights reserved. Designed by Balaji.</p>
                    </div>
                </div>
            </div>
        </footer>
        <!-- End  -->
    </main>

    <!-- Optional JavaScript -->
    <!-- jQuery first, then Popper.js, then Bootstrap JS -->
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"
        integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj"
        crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.0/dist/umd/popper.min.js"
        integrity="sha384-Q6E9RHvbIyZFJoft+2mJbHaEWldlvI9IOYy5n3zV9zzTtmI3UksdQRVvoxMfooAo"
        crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.0/js/bootstrap.min.js"
        integrity="sha384-OgVRvuATP1z7JjHLkuOU7Xw704+h835Lr+6QL9UvYjZE3Ipu6Tp75j7Bh/kR0JKI"
        crossorigin="anonymous"></script>
</body>

</html>
```
```
body {
    font-family: 'Abel', sans-serif;
    font-size: large;
    background-color: rgb(255, 239, 239);
}

h1,
h2,
h3,
h4,
h5,
h6,
p {
    cursor: pointer;
}



/* Header nav start  */

a.nav-link {
    margin-right: 20px;
    font-weight: 700;
}

.navbar-light .navbar-nav .active>.nav-link:hover {
    color: #ffffff;
}

nav.fill ul li a.nav-link {
    transition: all .5s;
}

nav.fill ul li a.nav-link:after {
    text-align: left;
    content: '.';
    margin: 0;
    opacity: 0;
}

nav.fill ul li a.nav-link:hover {
    color: white;
    z-index: 1;
}

nav.fill ul li a.nav-link:hover:after {
    z-index: -10;
    animation: fill 1s forwards;
    opacity: 1;
}

nav.fill ul li a.nav-link {
    position: relative;
}

nav.fill ul li a.nav-link:after {
    position: absolute;
    bottom: 0;
    left: 0;
    right: 0;
    margin: auto;
    width: 0%;
    content: '.';
    color: transparent;
    background: #aaa;
    height: 1px;
}

/* End  */


/* section Mack book start  */

section#mack-book {
    margin-bottom: 100px;
}

.carousel-indicators li {
    width: 20px;
    height: 8px;
    border: none;
    border-radius: 4px;
    background-color: #CECECE;
}

.carousel-indicators li.active {
    width: 35px;
    height: 10px;
    border-radius: 8px;
    background-image: linear-gradient(145deg, #f1c40f, #e67e22);
}

.mack {
    padding: 10% 4%;
    display: flex;
    /* Flexbox trigger */
    flex-direction: column;
    justify-content: center;
    /* Vertical alignment */
    align-items: flex-start;
    /* Horizontal alignment */
}

.mack h1 {
    font-size: 3.5rem;
    /* Larger, more impressive heading */
    font-weight: 700;
    margin-bottom: 20px;
}

.mack p {
    margin-bottom: 30px;
    font-size: 1.1rem;
    line-height: 1.6;
    color: #555;
    max-width: 90%;
}

.mack a.mack-btn {
    font-weight: bold;
    background-color: black;
    color: white;
    border: 2px solid black;
    padding: 12px 30px;
    /* Refined padding */
    border-radius: 30px;
    /* Pill shape for modern look */
    text-transform: uppercase;
    transition: all 0.3s ease;
    cursor: pointer;
    display: inline-flex;
    align-items: center;
    gap: 10px;
    /* Gap between text and icon */
    box-shadow: 0 4px 15px rgba(0, 0, 0, 0.2);
    /* Premium shadow */
}

.mack a.mack-btn:hover {
    background-color: #333;
    border-color: #333;
    transform: translateY(-2px);
    /* Subtle lift */
    box-shadow: 0 6px 20px rgba(0, 0, 0, 0.3);
    color: white;
}

svg.bi.bi-arrow-right {
    color: white;
    font-size: 20px;
    transition: .5s;
}

a.mack-btn:hover svg.bi.bi-arrow-right {
    transform: rotate(-180deg);
    color: black;
}

/* End  */

/* section Smart phone start  */

section#smartphone {
    margin-bottom: 100px;
}

.smartphone-header {
    margin-bottom: 50px;
}

.smartphone-header h5 {
    font-weight: bold;
    cursor: pointer;
    background: -webkit-linear-gradient(145deg, #f1c40f, #e67e22);
    -webkit-background-clip: text;
    background-clip: text;
    -webkit-text-fill-color: transparent;
}

/* Shared Button Styles */
.btn-buy {
    font-weight: bold;
    background-color: black;
    color: white;
    border: 2px solid black;
    padding: 10px 25px;
    border-radius: 30px;
    text-transform: uppercase;
    transition: all 0.3s ease;
    cursor: pointer;
    display: inline-flex;
    align-items: center;
    gap: 8px;
}

.btn-buy:hover {
    background-color: #333;
    border-color: #333;
    color: white;
    transform: translateY(-2px);
    box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
}

.smartphone-btn,
.laptop-btn {
    /* Extending shared button style logic if we want to keep specific classes, 
       but for now we can just style them identically or use the shared class logic in HTML if we changed it. 
       Since HTML uses smartphone-btn and laptop-btn, we target them. */
    font-weight: bold;
    background-color: black;
    color: white;
    border: 2px solid black;
    padding: 10px 25px;
    border-radius: 30px;
    text-transform: uppercase;
    transition: all 0.3s ease;
    cursor: pointer;
    display: inline-flex;
    align-items: center;
    gap: 8px;
}

.smartphone-btn:hover,
.laptop-btn:hover {
    background-color: #333;
    border-color: #333;
    color: white;
    transform: translateY(-2px);
    box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
}

.smartphone-btn:hover svg.bi-arrow-right,
.laptop-btn:hover svg.bi-arrow-right {
    transform: translateX(5px);
    /* Move arrow forward instead of rotate */
}

/* Card Styling */
.card {
    border: none;
    border-radius: 15px;
    box-shadow: 0 10px 30px rgba(0, 0, 0, 0.08);
    /* Soft shadow */
    transition: all 0.4s ease;
    overflow: hidden;
    background: #fff;
    margin-bottom: 30px;
    /* Gap between rows/mobile */
}

.card:hover {
    transform: translateY(-10px);
    box-shadow: 0 20px 40px rgba(0, 0, 0, 0.15);
}

.card-img-top {
    padding: 20px;
    transition: transform 0.4s ease;
}

.card:hover .card-img-top {
    transform: scale(1.05);
    /* Subtle zoom */
}

.card-title {
    font-weight: 800;
    margin-bottom: 15px;
}

.card-text {
    color: #6c757d;
    font-size: 0.95rem;
    line-height: 1.5;
    margin-bottom: 20px;
}

/* Section Header */
.section-header h1,
.smartphone-header h1,
.laptop-header h1 {
    font-weight: 800;
    margin-bottom: 0;
}

.section-header h5,
.smartphone-header h5,
.laptop-header h5 {
    color: #e67e22;
    cursor: pointer;
    font-weight: 600;
    text-transform: uppercase;
    letter-spacing: 1px;
}

/* Categories start  */

hr {
    width: 130px;
    background-image: linear-gradient(145deg, #f1c40f, #e67e22);
    height: 10px;
    border: none;
    border-radius: 50px;
    margin-bottom: 50px;
}

.categories-card {
    /* Deprecated class, keeping if needed or redirecting to new styles */
}

.category-item {
    background: white;
    width: 45%;
    /* Allowing 2 items per row or adjusting flex behavior */
    transition: all 0.3s ease;
    cursor: pointer;
}

/* Specific adjustment for the 3 items layout. 
   We have 3 items in a flex container. 
   Let's make them stack naturally or distinct.
   Actually, the requirement was "Left Item... holding three category boxes... clean column". 
   Let's adjust HTML to column if needed or keep grid. 
   The user said "clean column with consistent vertical gaps".
   My HTML above used `d-flex flex-wrap`. Let's correct it with CSS to be column if intended, 
   or maybe I should have made them `d-flex flex-column` in HTML?
   Wait, the user said "Left Item... holding three category boxes".
   I will use CSS to ensure they look good.
*/

.category-item {
    width: 100%;
    /* Full width in the left column wrapper */
    display: flex;
    align-items: center;
    justify-content: flex-start;
    gap: 20px;
    padding: 20px;
    margin-bottom: 20px;
}

.category-item:hover {
    transform: translateX(10px);
    box-shadow: 0 10px 20px rgba(0, 0, 0, 0.1);
}

.category-item img {
    max-width: 80px;
    margin-bottom: 0 !important;
    /* override mb-3 if needed */
}

.category-item h3 {
    margin: 0;
    font-size: 1.5rem;
    font-weight: 700;
}

.mt-5 {
    margin-top: 6rem !important;
}

/* End  */

/* Footer  */
/* Footer */
footer {
    background-color: #fff;
    padding-top: 80px;
    padding-bottom: 20px;
}

.footer-links li {
    margin-bottom: 10px;
}

.footer-links a {
    color: #555;
    text-decoration: none;
    transition: color 0.3s ease;
}

.footer-links a:hover {
    color: #e67e22;
}

.footer-contact li {
    margin-bottom: 10px;
    color: #555;
}

/* End  */

/* Nav animation */

@keyframes fill {
    0% {
        width: 0%;
        height: 1px;
    }

    50% {
        width: 100%;
        height: 1px;
    }

    100% {
        width: 100%;
        height: 100%;
        background: #333;
    }
}

@-webkit-keyframes fill {
    0% {
        width: 0%;
        height: 1px;
    }

    50% {
        width: 100%;
        height: 1px;
    }

    100% {
        width: 100%;
        height: 100%;
        background: #333;
    }
}
```


## OUTPUT
<img width="1815" height="916" alt="image" src="https://github.com/user-attachments/assets/0290b0fd-bf88-461e-9a7b-b38d7c8e068e" />
<img width="1840" height="907" alt="image" src="https://github.com/user-attachments/assets/e11b2904-2648-42cd-8c1f-80f06f446996" />
<img width="1824" height="914" alt="image" src="https://github.com/user-attachments/assets/f64afd80-b527-4e11-be92-0d2b5779ffcd" />
<img width="1838" height="914" alt="image" src="https://github.com/user-attachments/assets/9031b710-47ce-4950-b08a-7165fd0ede71" />
<img width="1842" height="892" alt="image" src="https://github.com/user-attachments/assets/11dcdade-74cd-4c1c-bd62-84a1c6bebae1" />


## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
