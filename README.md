# Ex.07 Restaurant Website
## Date:08.10.2025

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
style.css
/* style.css */
body {
  margin: 0;
  font-family: Arial, sans-serif;
  background-color: #fdf6f0;
  color: #333;
}

header {
  background-color: #f53506;
  color: rgb(244, 241, 241);
  padding: 20px;
  text-align: center;
}

nav a {
  color: rgb(244, 239, 239);
  margin: 0 15px;
  text-decoration: none;
}

.banner img {
  width: 100%;
  height: auto;
}

section.content {
  padding: 40px;
  text-align: center;
}

.menu-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 20px;
  padding: 40px;
}

.menu-item {
  background-color: #f8f1f1;
  border: 1px solid #131313;
  padding: 15px;
  border-radius: 10px;
  text-align: center;
}

.menu-item img {
  width: 100%;
  height: 150px;
  object-fit: cover;
  border-radius: 10px;
}

.admin-grid {
  display: flex;
  flex-wrap: wrap;
  gap: 20px;
  padding: 40px;
  justify-content: center;
}

.admin-card {
  width: 200px;
  background-color: #6f6e6e;
  padding: 15px;
  border-radius: 10px;
  text-align: center;
  border: 1px solid #0b0b0b;
}

.admin-card img {
  width: 100%;
  height: 180px;
  object-fit: cover;
  border-radius: 10px;
}

.contact-info {
  padding: 40px;
  text-align: center;
  line-height: 1.8;
}

footer {
  background-color: #333;
  color: white;
  text-align: center;
  padding: 10px;
}
menu.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Menu - Our Restaurant</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Our Menu</h1>
    <nav>
      <a href="home.html">Home</a>
      <a href="menu.html">Menu</a>
      <a href="administration.html">Administration</a>
      <a href="contact.html">Contact Us</a>
    </nav>
  </header>

  <section class="menu-grid">
   
    <div class="menu-item">
      <img src="briyani.jpg" alt="Briyani">
      <h3>Briyani </h3>
      <p>Biryani is a savory mixed rice dish, layered with spices and meat or vegetables, steamed together for a flavorful meal. It's a celebrated dish with Persian origins that evolved in India under the Mughals.</p>
    </div>
    <div class="menu-item">
      <img src="Burger.jpg" alt="Burger">
      <h3>Beef Burger</h3>
      <p>A classic burger features a meat or veggie patty, often with cheese and sauce, served in a bun with various toppings like lettuce and onions. Prices for burgers vary significantly by restaurant and ingredients. </p>
    </div>
    <div class="menu-item">
      <img src="pasta.jpg" alt="Pasta">
      <h3>Pasta Aifredo</h3>
      <p>Pasta is a beloved Italian staple made from flour and water, sometimes with eggs, shaped into diverse forms like spaghetti or penne. Boiled until perfectly al dente, it serves as a versatile foundation for a vast array of dishes.</p>
    </div>
    <div class="menu-item">
      <img src="Caesar salad.jpg" alt="Salad">
      <h3>Caesar Salad</h3>
      <p>Crisp romaine lettuce, garlic croutons, and savory Parmesan cheese are tossed in a zesty dressing of egg, lemon, olive oil, and Worcestershire sauce, creating a timeless classic with a rich history.  </p>
    </div>
    <div class="menu-item">
      <img src="sushi.jpg" alt="Sushi">
      <h3>Sushi Rolls</h3>
      <p>Sushi rolls are a versatile Japanese dish featuring seasoned rice and various fillings like fresh seafood or vegetables rolled in seaweed. These popular maki rolls are a healthy, delicious, and visually appealing way to enjoy Japanese cuisine.</p> 

    </div>
    <div class="menu-item">
      <img src="chicken with naan.jpg" alt="naan">
      <h3>Chicken With Naan </h3>
      <p>A tender and flavorful chicken curry is paired with freshly baked, fluffy naan bread, creating a classic and comforting combination that is perfect for any meal . The marinated chicken is simmered in a rich, aromatic sauce, which is ideal for soaking up with the warm, soft naan</p>
    </div>
    <div class="menu-item">
      <img src="Dosa.jpg" alt="Dosa">
      <h3>Cheese Dosa</h3>
      <p>A savory and crisp golden crepe filled with a generous layer of hot, melted cheese. This modern twist on the classic South Indian dosa is a delicious and addictive dish enjoyed by all ages.</p>
    </div>
    <div class="menu-item">
      <img src="spring roll.jpg" alt="spring roll">
      <h3>Veggie Spring Rolls</h3>
      <p>Veggie Spring Rolls: A crispy, golden-fried appetizer filled with a savory mix of stir-fried cabbage, carrots, and other fresh vegetables. Served with your choice of dipping sauce, these handheld delights offer a delightful crunch and flavorful experience.</p>
    </div>
    <div class="menu-item">
      <img src="Pizza.jpg" alt="Pizza">
      <h3>Margherita Pizza</h3>
      <p>The classic Margherita Pizza features a simple yet flavorful combination of rich tomato sauce, fresh mozzarella, fragrant basil, and a drizzle of extra virgin olive oil, all on a hand-stretched pizza dough.</p>
    </div>
    <div class="menu-item">
      <img src="BBQ.jpg" alt="BBQ Chicken Wings">
      <h3>BBQ Chicken Wings</h3>
      <p>Tender, slow-cooked chicken wings coated in a sweet and tangy barbecue sauce and caramelized to perfection. These flavor-packed wings are perfect for a crowd-pleasing appetizer or a satisfying meal.</p>
    </div>
    <div class="menu-item">
      <img src="Brownie.jpg" alt="Cholcolate Browni With ice Cream">
      <h3>Cholcolate Browni With ice Cream</h3>
      <p>Indulge in our decadent Chocolate Brownie, served warm and gooey, topped with a generous scoop of rich vanilla ice cream. This classic dessert delivers a perfect contrast of textures and temperatures in every delightful bite. A sublime treat that's sure to satisfy any sweet tooth.</p>
    </div>
    <div class="menu-item">
      <img src="Juice.jpg" alt="juice">
      <h3>French Juice</h3>
      <p>A menu item labeled "French Juice" would typically suggest a high-quality, fresh-pressed fruit juice, perhaps with a classic French twist. It might also imply the inclusion of unique or seasonally-sourced ingredients, a practice favored in French cuisine.</p>
    </div>
  </section>

  <footer>
    <p>&copy; 2025. Designed by  Karthik </p>
  </footer>
</body>
</html>
home.html


<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Home - Food Fantasia </title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1> Food Fantasia </h1>
    <nav>
      <a href="home.html">Home</a>
      <a href="menu.html">Menu</a>
      <a href="administration.html">Administration</a>
      <a href="contact.html">Contact Us</a>
    </nav>
  </header>

  <section class="banner">
    <img src="banaer kkk.jpg" alt="Delicious Food Banner">
  </section>
  

  <section class="content">
    <h2>Welcome!</h2>
    <p>Discover the best food in town, made with passion and fresh ingredients.</p>
  </section>

  <footer>
    <p>&copy; 2025. Designed by karthik</p>
  </footer>
</body>
</html>

menu.html 
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Menu - Our Restaurant</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Our Menu</h1>
    <nav>
      <a href="home.html">Home</a>
      <a href="menu.html">Menu</a>
      <a href="administration.html">Administration</a>
      <a href="contact.html">Contact Us</a>
    </nav>
  </header>

  <section class="menu-grid">
   
    <div class="menu-item">
      <img src="briyani.jpg" alt="Briyani">
      <h3>Briyani </h3>
      <p>Biryani is a savory mixed rice dish, layered with spices and meat or vegetables, steamed together for a flavorful meal. It's a celebrated dish with Persian origins that evolved in India under the Mughals.</p>
    </div>
    <div class="menu-item">
      <img src="Burger.jpg" alt="Burger">
      <h3>Beef Burger</h3>
      <p>A classic burger features a meat or veggie patty, often with cheese and sauce, served in a bun with various toppings like lettuce and onions. Prices for burgers vary significantly by restaurant and ingredients. </p>
    </div>
    <div class="menu-item">
      <img src="pasta.jpg" alt="Pasta">
      <h3>Pasta Aifredo</h3>
      <p>Pasta is a beloved Italian staple made from flour and water, sometimes with eggs, shaped into diverse forms like spaghetti or penne. Boiled until perfectly al dente, it serves as a versatile foundation for a vast array of dishes.</p>
    </div>
    <div class="menu-item">
      <img src="Caesar salad.jpg" alt="Salad">
      <h3>Caesar Salad</h3>
      <p>Crisp romaine lettuce, garlic croutons, and savory Parmesan cheese are tossed in a zesty dressing of egg, lemon, olive oil, and Worcestershire sauce, creating a timeless classic with a rich history.  </p>
    </div>
    <div class="menu-item">
      <img src="sushi.jpg" alt="Sushi">
      <h3>Sushi Rolls</h3>
      <p>Sushi rolls are a versatile Japanese dish featuring seasoned rice and various fillings like fresh seafood or vegetables rolled in seaweed. These popular maki rolls are a healthy, delicious, and visually appealing way to enjoy Japanese cuisine.</p> 

    </div>
    <div class="menu-item">
      <img src="chicken with naan.jpg" alt="naan">
      <h3>Chicken With Naan </h3>
      <p>A tender and flavorful chicken curry is paired with freshly baked, fluffy naan bread, creating a classic and comforting combination that is perfect for any meal . The marinated chicken is simmered in a rich, aromatic sauce, which is ideal for soaking up with the warm, soft naan</p>
    </div>
    <div class="menu-item">
      <img src="Dosa.jpg" alt="Dosa">
      <h3>Cheese Dosa</h3>
      <p>A savory and crisp golden crepe filled with a generous layer of hot, melted cheese. This modern twist on the classic South Indian dosa is a delicious and addictive dish enjoyed by all ages.</p>
    </div>
    <div class="menu-item">
      <img src="spring roll.jpg" alt="spring roll">
      <h3>Veggie Spring Rolls</h3>
      <p>Veggie Spring Rolls: A crispy, golden-fried appetizer filled with a savory mix of stir-fried cabbage, carrots, and other fresh vegetables. Served with your choice of dipping sauce, these handheld delights offer a delightful crunch and flavorful experience.</p>
    </div>
    <div class="menu-item">
      <img src="Pizza.jpg" alt="Pizza">
      <h3>Margherita Pizza</h3>
      <p>The classic Margherita Pizza features a simple yet flavorful combination of rich tomato sauce, fresh mozzarella, fragrant basil, and a drizzle of extra virgin olive oil, all on a hand-stretched pizza dough.</p>
    </div>
    <div class="menu-item">
      <img src="BBQ.jpg" alt="BBQ Chicken Wings">
      <h3>BBQ Chicken Wings</h3>
      <p>Tender, slow-cooked chicken wings coated in a sweet and tangy barbecue sauce and caramelized to perfection. These flavor-packed wings are perfect for a crowd-pleasing appetizer or a satisfying meal.</p>
    </div>
    <div class="menu-item">
      <img src="Brownie.jpg" alt="Cholcolate Browni With ice Cream">
      <h3>Cholcolate Browni With ice Cream</h3>
      <p>Indulge in our decadent Chocolate Brownie, served warm and gooey, topped with a generous scoop of rich vanilla ice cream. This classic dessert delivers a perfect contrast of textures and temperatures in every delightful bite. A sublime treat that's sure to satisfy any sweet tooth.</p>
    </div>
    <div class="menu-item">
      <img src="Juice.jpg" alt="juice">
      <h3>French Juice</h3>
      <p>A menu item labeled "French Juice" would typically suggest a high-quality, fresh-pressed fruit juice, perhaps with a classic French twist. It might also imply the inclusion of unique or seasonally-sourced ingredients, a practice favored in French cuisine.</p>
    </div>
  </section>

  <footer>
    <p>&copy; 2025. Designed by  Karthik </p>
  </footer>
</body>
</html>
contact.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Contact Us - Food zone </title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

  <header>
    <h1>Contact Us</h1>
    <nav>
      <a href="home.html">Home</a>
      <a href="menu.html">Menu</a>
      <a href="administration.html">Administration</a>
      <a href="contact.html">Contact Us</a>
    </nav>
  </header>

  <section class="contact-info">
    <h2> for more details </h2>
    <p> 📍  <strong>Address:</strong> 123 Food Street, Delhi main road, Delhi City </p>
    <p> 📞  <strong>Phone:</strong> 6383016619</p>
    <p> ✉  <strong>Email:</strong> kishor63a2gmail.com</p>
  </section>
  <footer>
    <p>&copy; 2025. Designed by  kishor</p>
  </footer>

</body>
</html>
administeration.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Administration - Our Restaurant</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Our Administration</h1>
    <nav>
      <a href="home.html">Home</a>
      <a href="menu.html">Menu</a>
      <a href="administration.html">Administration</a>
      <a href="contact.html">Contact Us</a>
    </nav>
  </header>

  <section class="admin-grid">
    <div class="admin-card">
      <img src="damu.jpg" alt="Admin 1">
      <h3>Dmanu</h3>
      <p>Manager</p>
    </div>
    <div class="admin-card">
      <img src="chef koushik.jpg" alt="Admin 2">
      <h3>koshik</h3>
      <p>Head Chef</p>
    </div>
    <div class="admin-card">
      <img src="girl chef 2.jpg" alt="Admin 3">
      <h3>Clare Smyth</h3>
      <p>Assistant Chef</p>
    </div>
    <div class="admin-card">
      <img src="girl chef1.jpg" alt="Admin 4">
      <h3>Dominique Crenm </h3>
      <p>Cashier</p>
    </div>
    <div class="admin-card">
      <img src="chef 1.jpg" alt="Admin 5">
      <h3>Godon Ramsay</h3>
      <p>Inventory Manager</p>
    </div>
    <div class="admin-card">
      <img src="chef 2.jpg" alt="Admin 6">
      <h3>Vikas Khanna</h3>
      <p>Customer Service</p>
    </div>
  </section>

  <footer>
    <p>&copy; 2025. Designed by Karthik</p>
  </footer>
</body>
</html>
```

## OUTPUT:

![alt text](IMG-20251015-WA0010.jpg)

![alt text](IMG-20251015-WA0011.jpg)
![alt text](IMG-20251015-WA0012.jpg)

![alt text](IMG-20251015-WA0009.jpg)

![alt text](<Screenshot (34).png>)


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
