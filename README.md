# Ex.07 Restaurant Website
## Date:06.10.2025

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
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Restaurant Homepage</title>
  <style>
    body { font-family: Arial, sans-serif; margin: 0; padding: 0; }
    header { background: #b22222; color: white; padding: 20px; text-align: center; }
    nav { background: #333; display: flex; justify-content: center; }
    nav a { color: white; padding: 14px 20px; text-decoration: none; }
    nav a:hover { background: #ff6347; }
    section {padding: 60px; text-align: center; }
    footer { background: #333; color: white; text-align: center; padding: 15px;
    }
  </style>
</head>
<body>
  <header>
    <h1>🍴 SpiceHUb restaurant 🍴</h1>
    <p>Welcome to our restaurant</p>
  </header>

  <nav>
    
    <a href="menu.html">Menu</a>
    <a href="admin.html">Administration</a>
    <a href="contact.html">Contact</a>
  </nav>

  <section>
    <h2>Welcome</h2>
    <p>This is the homepage. Use the navigation above to view menu, administration, and contact pages.</p>
  </section>

  <footer>
    <p>&copy; 2025 SpiceHUB Restaurant | All Rights Reserved</p>
  </footer>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Menu</title>
  <style>
    body { font-family: Arial, sans-serif; margin: 0; padding: 0; }
    header { background: #b22222; color: white; padding: 20px; text-align: center; }
    nav { background: #333; display: flex; justify-content: center; }
    nav a { color: white; padding: 14px 20px; text-decoration: none; }
    nav a:hover { background: #ff6347; }
    .gallery { display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 20px; padding: 20px; }
    .gallery img { width: 100%; border-radius: 10px; box-shadow: 0 3px 6px rgba(0,0,0,0.2);
    .gallery h2 {
      color: #ed3a3a;
    }
     }
  </style>
</head>
<body>
  <header>
    <h1>Our Menu</h1>
  </header>

  <nav>
    <a href="home.html">Home</a>
    <a href="admin.html">Administration</a>
    <a href="contact.html">Contact</a>
  </nav>

  <div class="gallery">
    <h2>Burger</h2>
    <img src="food1.jpg" alt="Burger">
    <h2>Pizza</h2>
    <img src="food2.jpg" alt="Pizza">
    <h2>Pasta</h2>
    <img src="food3.jpg" alt="Pasta">
    <h2>Dessert</h2>
    <img src="food4.jpg" alt="Dessert">
    <h2>SandWich</h2>
    <img src="food5.jpg" alt="SandWich">
    <h2>Noodles</h2>
    <img src="food6.jpg" alt="Noodles">
  </div>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Administration</title>
  <style>
    body { font-family: Arial, sans-serif; margin: 0; padding: 0; }
    header { background: #b22222; color: white; padding: 20px; text-align: center; }
    nav { background: #333; display: flex; justify-content: center; }
    nav a { color: white; padding: 14px 20px; text-decoration: none; }
    nav a:hover { background: #ff6347; }
    .team { display: flex; justify-content: center; flex-wrap: wrap; gap: 20px; padding: 20px; }
    .member { text-align: center; }
    .member img { width: 180px; border-radius: 50%; }
  </style>
</head>
<body>
  <header>
    <h1>Administration</h1>
  </header>

  <nav>
    <a href="home.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="contact.html">Contact</a>
  </nav>

  <div class="team">
    <div class="member">
      <img src="chef1.jpg" alt="Chef">
      <p><b>Chef Frank</b></p>
    </div>
    <div class="member">
      <img src="chef2.jpg" alt="Chef">
      <p><b>Chef John</b></p>
    </div>
    <div class="member">
      <img src="chef3.jpg" alt="Chef">
      <p><b>Chef Mark</b></p>
    </div>
    <div class="member">
      <img src="chef4.jpg" alt="Chef">
      <p><b>Chef Antony</b></p>
    </div>
    <div class="member">
      <img src="manager.jpg" alt="Manager">
      <p><b>Manager Johan</b></p>
    <div class="member">
      <img src="asst-manager.jpg" alt="Asst-Manager">
      <p><b>Manager Josan</b></p>
    </div>
  </div>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Contact</title>
  <style>
    body { font-family: Arial, sans-serif; margin: 0; padding: 0; }
    header { background: #b22222; color: white; padding: 20px; text-align: center; }
    nav { background: #333; display: flex; justify-content: center; }
    nav a { color: white; padding: 14px 20px; text-decoration: none; }
    nav a:hover { background: #ff6347; }
    section { padding: 40px; text-align: center; }
  </style>
</head>
<body>
  <header>
    <h1>Contact Us</h1>
  </header>

  <nav>
    <a href="home.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="admin.html">Administration</a>
  </nav>

  <section>
    <p>📍 Address: 123 Main Street, Your City</p>
    <p>📞 Phone: +91 98765 43210</p>
    <p>📧 Email: contact@restaurant.com</p>
  </section>
</body>
</html>
```

## OUTPUT:
![alt text](<../Screenshot 2025-10-06 111651.png>)
![alt text](<../Screenshot 2025-10-06 111705.png>)
![alt text](<../Screenshot 2025-10-06 111720.png>)
![alt text](<../Screenshot 2025-10-06 111745.png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
