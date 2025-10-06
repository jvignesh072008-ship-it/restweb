# Ex.07 Restaurant Website
## Date:4/10/2025

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
index.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Taste Haven Restaurant</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <!-- Header Section -->
  <header>
    <div class="logo">Taste Haven</div>
    <nav>
      <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#menu">Menu</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <!-- Hero Section -->
  <section id="home" class="hero">
    <div class="hero-text">
      <h1>Welcome to Taste Haven</h1>
      <p>Delicious meals, cozy vibes, unforgettable taste.</p>
      <a href="#menu" class="btn">Explore Menu</a>
    </div>
  </section>

  <!-- Menu Section -->
  <section id="menu" class="menu">
    <h2>Our Menu</h2>
    <div class="menu-container">
      <div class="menu-item">
        <img src="https://source.unsplash.com/400x300/?pizza" alt="Pizza">
        <h3>Margherita Pizza</h3>
        <p>Fresh mozzarella, tomatoes, and basil.</p>
        <span>₹350</span>
      </div>
      <div class="menu-item">
        <img src="https://source.unsplash.com/400x300/?burger" alt="Burger">
        <h3>Classic Burger</h3>
        <p>Juicy beef patty with cheese and veggies.</p>
        <span>₹250</span>
      </div>
      <div class="menu-item">
        <img src="https://source.unsplash.com/400x300/?pasta" alt="Pasta">
        <h3>Italian Pasta</h3>
        <p>Creamy Alfredo sauce with garlic bread.</p>
        <span>₹300</span>
      </div>
    </div>
  </section>

  <!-- About Section -->
  <section id="about" class="about">
    <h2>About Us</h2>
    <p>
      At Taste Haven, we serve food made with love and passion. 
      Our chefs craft every dish with fresh ingredients to bring you a world of flavors.
    </p>
  </section>

  <!-- Contact Section -->
  <section id="contact" class="contact">
    <h2>Contact Us</h2>
    <p>📍 123 Food Street, Chennai, India</p>
    <p>📞 +91 98765 43210</p>
    <p>✉ info@tastehaven.com</p>
  </section>

  <!-- Footer -->
  <footer>
    <p>© 2025 Taste Haven Restaurant | All Rights Reserved</p>
  </footer>
</body>
</html>

style.css

/* General Styles */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'Poppins', sans-serif;
}

body {
  color: #333;
  background-color: #fff;
}

/* Header */
header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  background: #2c2c2c;
  padding: 15px 50px;
  position: sticky;
  top: 0;
  z-index: 10;
}

.logo {
  color: #f8c02d;
  font-size: 1.8em;
  font-weight: bold;
}

nav ul {
  list-style: none;
  display: flex;
  gap: 25px;
}

nav a {
  color: white;
  text-decoration: none;
  font-weight: 500;
}

nav a:hover {
  color: #f8c02d;
}

/* Hero Section */
.hero {
  background: url('https://source.unsplash.com/1600x900/?restaurant,food') center/cover no-repeat;
  color: white;
  height: 90vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.hero-text {
  background-color: rgba(0, 0, 0, 0.6);
  padding: 30px;
  border-radius: 15px;
}

.hero h1 {
  font-size: 3em;
  margin-bottom: 10px;
}

.hero p {
  font-size: 1.2em;
  margin-bottom: 20px;
}

.btn {
  background: #f8c02d;
  color: #000;
  padding: 10px 20px;
  text-decoration: none;
  border-radius: 30px;
  font-weight: bold;
}

.btn:hover {
  background: #ffdd57;
}

/* Menu Section */
.menu {
  padding: 60px 20px;
  text-align: center;
  background-color: #f7f7f7;
}

.menu h2 {
  margin-bottom: 40px;
  font-size: 2em;
}

.menu-container {
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
  gap: 30px;
}

.menu-item {
  background: white;
  border-radius: 15px;
  width: 300px;
  padding: 15px;
  box-shadow: 0 4px 10px rgba(0,0,0,0.1);
  transition: transform 0.3s;
}

.menu-item:hover {
  transform: scale(1.05);
}

.menu-item img {
  width: 100%;
  border-radius: 15px;
  margin-bottom: 10px;
}

.menu-item h3 {
  color: #f8c02d;
}

.menu-item span {
  display: block;
  margin-top: 5px;
  font-weight: bold;
  color: #333;
}

/* About Section */
.about {
  padding: 60px 20px;
  text-align: center;
}

.about h2 {
  font-size: 2em;
  margin-bottom: 20px;
}

/* Contact Section */
.contact {
  padding: 60px 20px;
  background: #2c2c2c;
  color: white;
  text-align: center;
}

.contact h2 {
  color: #f8c02d;
  margin-bottom: 15px;
}

.contact p {
  margin-bottom: 8px;
}

/* Footer */
footer {
  background: #111;
  color: #ccc;
  text-align: center;
  padding: 15px 0;
  font-size: 0.9em;
}

```


## OUTPUT:
<img width="1920" height="1080" alt="Screenshot 2025-10-06 112114" src="https://github.com/user-attachments/assets/de7b128b-b67d-4057-827a-7d200a58b4ad" />
<img width="1900" height="419" alt="Screenshot 2025-10-06 112128" src="https://github.com/user-attachments/assets/0d00718e-dd80-47d2-aac0-0c6a57e8b9ee" />
<img width="1892" height="240" alt="Screenshot 2025-10-06 112230" src="https://github.com/user-attachments/assets/ffa2dc2f-867d-4f93-86bc-98a1dc0d08f3" />
<img width="1906" height="355" alt="Screenshot 2025-10-06 112247" src="https://github.com/user-attachments/assets/c1004af8-3a44-4e68-b46b-05b9bb615b37" />






## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
