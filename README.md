# Ex.07 Restaurant Website

# AIM:
To develop a static Restaurant website to display the food items and services provided by them.

# DESIGN STEPS:
## Step 1:
Requirement collection.

## Step 2:
Creating the layout using HTML and CSS.

## Step 3:
Updating the sample content.

## Step 4:
Choose the appropriate style and color scheme.

## Step 5:
Validate the layout in various browsers.

## Step 6:
Validate the HTML code.

## Step 7:
Publish the website in the given URL.

# PROGRAM:
~~~
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Restaurant</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="banner">
          <h1> Southern spice</h1>
        </div>
        <nav>
            <ul>
                <li><a href="#menu">Menu</a></li>
                <li><a href="about us 1.html">Administration</a></li>
                <li><a href="#contact">Contact Us</a></li>
            </ul>
        </nav>
    </header>

    <section id="menu">
        <h2>Menu</h2>
        <div class="menu-items">
            <div class="menu-item">Tandoori chicken - ₹499<img src="C:\Users\admin\Documents\restaraunt\tandoori chicken.jpg"></div>
            <div class="menu-item">chicken briyani - ₹210<img src="C:\Users\admin\Documents\restaraunt\chicken briyani.jpg"></div>
            <div class="menu-item">chilli chicken - ₹265<img src="C:\Users\admin\Documents\restaraunt\chilli chicken.jpg"></div>
            <div class="menu-item">chicken momos - ₹299<img src="C:\Users\admin\Documents\restaraunt\chicken momos.jpeg"></div>
            <div class="menu-item">pasta - ₹100<img src="C:\Users\admin\Documents\restaraunt\pasta.jpg"></div>
            <div class="menu-item">Mutton briyani - ₹253<img src="C:\Users\admin\Documents\restaraunt\mutton briyani.jpg"></div>
            <div class="menu-item">Bread omelette - ₹105<img src="C:\Users\admin\Documents\restaraunt\bread omelette.jpg"></div>
            <div class="menu-item">Ice Cream - ₹60<img src="C:\Users\admin\Documents\restaraunt\ice cream.jpg"></div>
            <div class="menu-item">Tandoori roti - ₹40<img src="C:\Users\admin\Documents\restaraunt\tandoori roti.jpg"></div>
            <div class="menu-item">Chicken garlic kebab - ₹250<img src="C:\Users\admin\Documents\restaraunt\chicken kebabs.jpg"></div>
            <div class="menu-item">Sandwich - ₹90<img src="C:\Users\admin\Documents\restaraunt\sandwich.jpg"></div>
            <div class="menu-item">Pizza - ₹120<img src="C:\Users\admin\Documents\restaraunt\pizza.jpg"></div>
            <div class="menu-item">Mojito - ₹85<img src="C:\Users\admin\Documents\restaraunt\mojito.jpg"></div>
            <div class="menu-item">Milk shake - ₹150<img src="C:\Users\admin\Documents\restaraunt\milk shake.jpg"></div>
            <div class="menu-item">cake - ₹40<img src="C:\Users\admin\Documents\restaraunt\cake.jpg"></div>

        </div>
    </section>

    
    <footer>
        <p>&copy; 2024  southern spice - Designed by Vaishnavi</p>
    </footer>
</body>
</html>

body {
    font-family: Arial,Verdana,sans-serif;
    margin: 0;
    padding: 0;
    background-color: #1a1616e1;
}

header {
   background-image:  url("restaurant.jpg");
   background-repeat: no-repeat;
   width: 100%;
   height: 100%;
   background-size: contain;
   color: black;
   text-align: centre;
}

nav ul {
    list-style-type: none;
    padding: 10px;
    

}
.menu-item img{
    width: 250px;
    height: 250px;
    border-radius: 8px;
    
}

nav ul li {
    display: inline;
    margin: 10px 15px;
    text-align: center;
}

nav a {
    color: rgba(246, 234, 234, 0.908);
    text-decoration: none;
    text-align: center;
    font-size: x-small;
}

section {
    padding: 20px;
    margin: 20px;
    background-color: white;
    border-radius: 8px;
}

.menu-items {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
    gap: 10px;
}

.menu-item {
    background-color: #e7f3fe;
    padding: 10px;
    border-radius: 5px;
    text-align: center;
}

.admin {
    display: flex;
    flex-wrap: wrap;
    gap: 20px;
}

.admin-member {
    text-align: center;
    width: 150px;
}

.admin-member img {
    width: 100%;
    border-radius: 50%;
}

footer {
    text-align: center;
    padding: 10px;
    background-color: #333;
    color: white;
}

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Restaurant</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <section id="administration">
        <h2>Administration</h2>
        <div class="admin">
            <div class="admin-member">
                <img src="C:\Users\admin\Documents\restaraunt\female.jpg" alt="Admin 1">
                <p>rekha - Manager</p>
            </div>
            <div class="admin-member">
                <img src="C:\Users\admin\Documents\restaraunt\male.jpg" alt="Admin 2">
                <p>jhon - Chef</p>
            </div>
            <div class="admin-member">
                <img src="C:\Users\admin\Documents\restaraunt\male.jpg" alt="Admin 3">
                <p>rish - Waiter</p>
            </div>
            <div class="admin-member">
                <img src="C:\Users\admin\Documents\restaraunt\female.jpg" alt="Admin 4">
                <p>lilly - Hostess</p>
            </div>
            <div class="admin-member">
                <img src="C:\Users\admin\Documents\restaraunt\male.jpg" alt="Admin 5">
                <p>vishva - Bartender</p>
            </div>
            <div class="admin-member">
                <img src="C:\Users\admin\Documents\restaraunt\female.jpg" alt="Admin 6">
                <p>ritham - Accountant</p>
            </div>
        </div>
    </section>

    <section id="contact">
        <h2>Contact Us</h2>
        <p>Address: paradiser,west car street,chidambaram 608001</p>
        <p>Phone: 9080574723</p>
        <p>Email:  southernspice@gmail.com</p>
    </section>
</body>
~~~

# OUTPUT:
![restaurant](https://github.com/user-attachments/assets/eec7e65c-8c0d-47da-8d65-34d3af359a86)
![restaurant 3](https://github.com/user-attachments/assets/7132b8fe-e7b5-44d7-9775-6e20c4f16aa5)
![restaurant 2](https://github.com/user-attachments/assets/0970eff7-76d7-4ba0-9b70-63fe298a65ff)

# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
