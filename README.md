# Ex.07 Restaurant Website
## Date:28/04/25

## AIM:
To develop a static Restaurant website to display the food items and services provided by them.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:
```
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>GOKUL's Restraunt</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css"
        integrity="sha512-iBBXm8fW90+nuLcSKlbmrPcLa0OT92xO1BIsZ+ywDWZCvqsWgccV3gFoRBv0z+8dLJgyAHIhR35VZc2oM/gI1w=="
        crossorigin="anonymous" referrerpolicy="no-referrer" />
    <link rel="stylesheet" href="C:\Users\admin\Desktop\SEM 1\WEB DEV\resto\Untitled-1.css" />
</head>

<body>
    <nav class="navbar">
        <div class="navbar-container container">
            <input type="checkbox" name="" id="">
            <div class="hamburger-lines">
                <span class="line line1"></span>
                <span class="line line2"></span>
                <span class="line line3"></span>
            </div>
            <ul class="menu-items">
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#food">Category</a></li>
                <li><a href="#food-menu">Menu</a></li>
                <li><a href="#testimonials">Testimonial</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
            <h1 class="logo">Goku Eats</h1>
        </div>
    </nav>
    <section class="showcase-area" id="showcase">
        <div class="showcase-container">
            <h1 class="main-title" id="home">Eat Right Food</h1>
            <p>Eat Healty, it is good for our health.</p>
            <a href="#food-menu" class="btn btn-primary">Menu</a>
        </div>
    </section>

    <section id="about">
        <div class="about-wrapper container">
            <div class="about-text">
                <p class="small">About Us</p>
                <h2>We've beem making healthy food last for 10 years</h2>
                <p>
                bringing you the taste you trust and the quality you deserve. 
                With a perfect blend of passion, experience, and care, we craft meals that are wholesome, delicious, and memorable.
                 Every dish tells our story of commitment to health and flavor—nourishing lives for over a decade and counting.
                </p>
            </div>
            <div class="about-img">
                <img src="https://i.postimg.cc/mgpwzmx9/about-photo.jpg" alt="food" />
            </div>
        </div>
    </section>
    <section id="food">
        <h2>Types of food</h2>
        <div class="food-container container">
            <div class="food-type fruits">
                <div class="img-container">
                    <img src="https://i.postimg.cc/yxThVPXk/food1.jpg" alt="error" />
                    <div class="img-content">
                        <h3>fruits</h3>
                        <a href="https://en.wikipedia.org/wiki/Fruit" class="btn btn-primary" target="blank">learn
                            more</a>
                    </div>
                </div>
            </div>
            <div class="food-type vegetables">
                <div class="img-container">
                    <img src="https://i.postimg.cc/Nffm6Rkk/food2.jpg" alt="error" />
                    <div class="img-content">
                        <h3>vegetables</h3>
                        <a href="https://en.wikipedia.org/wiki/Vegetable" class="btn btn-primary" target="blank">learn
                            more</a>
                    </div>
                </div>
            </div>
            <div class="food-type grains">
                <div class="img-container">
                    <img src="https://i.postimg.cc/76ZwsPsd/food3.jpg" alt="error" />
                    <div class="img-content">
                        <h3>grains</h3>
                        <a href="https://en.wikipedia.org/wiki/Grain" class="btn btn-primary" target="blank">learn
                            more</a>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <section id="food-menu">
        <h2 class="food-menu-heading">Food Menu</h2>
        <div class="food-menu-container container">
            <div class="food-menu-item">
                <div class="food-img">
                    <img src="https://i.postimg.cc/wTLMsvSQ/food-menu1.jpg" alt="" />
                </div>
                <div class="food-description">
                    <h2 class="food-titile">Salad</h2>
                    <p>
                        It’s often served with a side of whole-grain bread
                        This refreshing and nutritious dish is a Mediterranean favorite!
                    </p>
                    <p class="food-price">Price: &#8377; 250</p>
                </div>
            </div>

            <div class="food-menu-item">
                <div class="food-img">
                    <img src="https://i.postimg.cc/sgzXPzzd/food-menu2.jpg" alt="error" />
                </div>
                <div class="food-description">
                    <h2 class="food-titile">oatmeal</h2>
                    <p>
                        A base of oatmeal, yogurt, or blended smoothie
                    </p>
                    <p class="food-price">Price: &#8377; 600</p>
                </div>
            </div>
            <div class="food-menu-item">
                <div class="food-img">
                    <img src="https://i.postimg.cc/8zbCtYkF/food-menu3.jpg" alt="" />
                </div>
                <div class="food-description">
                    <h2 class="food-titile">Avocado and Mango Salsa</h2>
                    <p>
                        A refreshing mix of diced avocado, mango, onion, cilantro, and lime juice, perfect as a dip or topping.

                    </p>
                    <p class="food-price">Price: &#8377; 320</p>
                </div>
            </div>
            <div class="food-menu-item">
                <div class="food-img">
                    <img src="https://i.postimg.cc/Yq98p5Z7/food-menu4.jpg" alt="" />
                </div>
                <div class="food-description">
                    <h2 class="food-titile">Baklava</h2>
                    <p>
                        A rich Middle Eastern pastry layered with nuts like walnuts and pistachios, soaked in sweet syrup.

                    </p>
                    <p class="food-price">Price: &#8377; 270</p>
                </div>
            </div>
            <div class="food-menu-item">
                <div class="food-img">
                    <img src="https://i.postimg.cc/KYnDqxkP/food-menu5.jpg" alt="" />
                </div>
                <div class="food-description">
                    <h2 class="food-titile">Berry Compote</h2>
                    <p>
                        A mix of fresh or frozen berries 
                        (like strawberries, blueberries, and raspberries)
                         cooked down with a little honey or lemon juice for sweetness and tang.
                    </p>
                    <p class="food-price">Price: &#8377; 150</p>
                </div>
            </div>
            <div class="food-menu-item">
                <div class="food-img">
                    <img src="https://i.postimg.cc/Jnxc8xQt/food-menu6.jpg" alt="" />
                </div>
                <div class="food-description">
                    <h2 class="food-titile">Mixed Fruit Salad</h2>
                    <p>
                        Combine grapes , Serve the salad with a slice of whole grain bread
                        along with a variety of other fruits like apples, oranges, berries, and kiwi for a burst of vitamins and antioxidants.
                    </p>
                    <p class="food-price">Price: &#8377; 400</p>
                </div>
            </div>
        </div>
    </section>
    <section id="testimonials">
        <h2 class="testimonial-title">What Our Customers Say</h2>
        <div class="testimonial-container container">
            <div class="testimonial-box">
                <div class="customer-detail">
                    <div class="customer-photo">
                        <img src="https://i.postimg.cc/5Nrw360Y/male-photo1.jpg" alt="" />
                        <p class="customer-name">Deva</p>
                    </div>
                </div>
                <div class="star-rating">
                    <span class="fa fa-star checked"></span>
                    <span class="fa fa-star checked"></span>
                    <span class="fa fa-star checked"></span>
                    <span class="fa fa-star checked"></span>
                    <span class="fa fa-star checked"></span>
                </div>
                <p class="testimonial-text">
                   veggies are very fresh to have 
                </p>

            </div>
            <div class="testimonial-box">
                <div class="customer-detail">
                    <div class="customer-photo">
                        <img src="https://i.postimg.cc/sxd2xCD2/female-photo1.jpg" alt="" />
                        <p class="customer-name">Rama</p>
                    </div>
                </div>
                <div class="star-rating">
                    <span class="fa fa-star checked"></span>
                    <span class="fa fa-star checked"></span>
                    <span class="fa fa-star checked"></span>
                    <span class="fa fa-star checked"></span>
                    <span class="fa fa-star checked"></span>
                </div>
                <p class="testimonial-text">
                    good food along with nutritious content 
                </p>

            </div>
            <div class="testimonial-box">
                <div class="customer-detail">
                    <div class="customer-photo">
                        <img src="https://i.postimg.cc/fy90qvkV/male-photo3.jpg" alt="" />
                        <p class="customer-name">Varadha</p>
                    </div>
                </div>
                <div class="star-rating">
                    <span class="fa fa-star checked"></span>
                    <span class="fa fa-star checked"></span>
                    <span class="fa fa-star checked"></span>
                    <span class="fa fa-star checked"></span>
                    <span class="fa fa-star checked"></span>
                </div>
                <p class="testimonial-text">
                   Best spot for health cautious people
                </p>

            </div>
        </div>
    </section>
    <section id="contact">
        <div class="contact-container container">
            <div class="contact-img">
                <img src="https://i.postimg.cc/1XvYM67V/restraunt2.jpg" alt="" />
            </div>

            <div class="form-container">
                <h2>Contact Us</h2>
                <input type="text" placeholder="Your Name" />
                <input type="email" placeholder="E-Mail" />
                <textarea cols="30" rows="6" placeholder="Type Your Message"></textarea>
                <a href="#" class="btn btn-primary">Submit</a>
            </div>
        </div>
    </section>
    <footer id="footer">
        <h2>Restraunt &copy; all rights reserved  
            Designed & Developed by GOKUL
        </h2>
    </footer>

    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
    <script src="C:\Users\admin\Desktop\SEM 1\WEB DEV\resto\$(document).js"></script>

</html>

</body>

</html>
```

## OUTPUT:
![398009410-4515a587-b463-45df-b633-9d6dacdaa380](https://github.com/user-attachments/assets/64c8d603-b75a-4f26-a210-08b1291bc012)
![398009419-71b78824-e3bb-40cc-bbb4-3c2596d19889](https://github.com/user-attachments/assets/a8c295cd-e2a5-47f6-be4d-ee6acba354ca)
![screenshot1](https://github.com/user-attachments/assets/37688319-60ed-4986-adf3-cf4f8b990411)
![screenshot2](https://github.com/user-attachments/assets/e9ac1dad-e270-4f9b-abfc-3a7ab6e9c32b)



## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
