# Project Responsive Web Design using Bootstrap
## Date:21/05/2025

## AIM:
To create a simplified clone of Dribbble (https://dribbble.com/) landing page.


## DESIGN STEPS:

### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

### Step 5:
Create a HTML file and include the needed Bootstrap components.

### Step 6:
Publish the website in the LocalHost.

## PROGRAM :
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Restaurant Website</title>
    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet">
    <style>
        .hero {
            background: url("KFC\ EPIC\ Campaign.jpeg") no-repeat center center/cover;
            color: white;
            text-align: center;
            padding: 100px 20px;
        }
        .menu-item img {
            height: 200px; /* Increased height for better visibility */
            object-fit: cover;
            margin: 0 auto; /* Center the images */
            display: block; /* Ensure images are block elements */
        }
        .footer {
            background-color: #343a40;
            color: white;
        }
        .menu-section {
            background-color: #f8f9fa; /* Light background for the menu section */
        }
    </style>
</head>
<body>
    <!-- Navigation Bar -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <div class="container-fluid">
            <a class="navbar-brand" href="#">Desert Hunters</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav">
                    <li class="nav-item">
                        <a class="nav-link active" aria-current="page" href="#home">Home</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#menu">Menu</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="about.html">About Us</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="contact.html">Contact</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <div class="hero">
        <h1>Welcome to Desert Hunters</h1>
        <p>Experience the best food in town!</p>
    </div>

    <!-- Menu Section -->
    <section id="menu" class="py-5 menu-section">
        <div class="container">
            <h2 class="text-center mb-4">Our Menu</h2>
            <div class="row g-4">
                
                <div class="col-md-4 menu-item">
                    <div class="card">
                        <img src="image copy 2.png" class="card-img-top" alt="Dish 2">
                        <div class="card-body">
                            <h5 class="card-title">Pasta Primavera</h5>
                            <p class="card-text">Delicious pasta tossed with seasonal vegetables.</p>
                        </div>
                    </div>
                </div>
                
                <div class="col-md-4 menu-item">
                    <div class="card">
                        <img src="image copy.png" class="card-img-top" alt="Dish 1">
                        <div class="card-body">
                            <h5 class="card-title">Grilled Chicken</h5>
                            <p class="card-text">Juicy grilled chicken served with fresh vegetables.</p>
                        </div>
                    </div>
                </div>
                
                <div class="col-md-4 menu-item">
                    <div class="card">
                        <img src="image copy 5.png" class="card-img-top" alt="Dish 5">
                        <div class="card-body">
                            <h5 class="card-title">Margherita Pizza</h5>
                            <p class="card-text">Wood-fired pizza topped with fresh mozzarella.</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-4 menu-item">
                    <div class="card">
                        <img src="image copy 4.png" class="card-img-top" alt="Dish 4">
                        <div class="card-body">
                            <h5 class="card-title">Caesar Salad</h5>
                            <p class="card-text">Crisp romaine lettuce with Caesar dressing.</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-4 menu-item">
                    <div class="card">
                        <img src="image copy 6.png" class="card-img-top" alt="Dish 6">
                        <div class="card-body">
                            <h5 class="card-title">Tiramisu</h5>
                            <p class="card-text">Classic Italian dessert with coffee and mascarpone.</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-4 menu-item">
                    <div class="card">
                        <img src="image copy 7.png" class="card-img-top" alt="Dish 7">
                        <div class="card-body">
                            <h5 class="card-title">Steak Frites</h5>
                            <p class="card-text">Grilled steak served with crispy fries.</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-4 menu-item">
                    <div class="card">
                        <img src="image copy 8.png" class="card-img-top" alt="Dish 8">
                        <div class="card-body">
                            <h5 class="card-title">Seafood Paella</h5>
                            <p class="card-text">Spanish-style rice with fresh seafood.</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-4 menu-item">
                    <div class="card">
                        <img src="image copy 3.png" class="card-img-top" alt="Dish 3">
                        <div class="card-body">
                            <h5 class="card-title">Classic Burger</h5>
                            <p class="card-text">Our signature burger with fresh ingredients.</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-4 menu-item">
                    <div class="card">
                        <img src="image copy 9.png" class="card-img-top" alt="Dish 9">
                        <div class="card-body">
                            <h5 class="card-title">Cheesecake</h5>
                            <p class="card-text">Creamy cheesecake with a graham cracker crust.</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- About Us Section -->
    <section id="about" class="py-5 bg-light">
        <div class="container">
            <h2 class="text-center mb-4">About Us</h2>
            <p class="text-center">At Desert Hunters, we believe in serving fresh, high-quality food made with love. Established in 2020, we have been a favorite spot for locals and tourists alike. Come and enjoy our cozy atmosphere, exceptional service, and a menu crafted with passion.</p>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-5">
        <div class="container">
            <h2 class="text-center mb-4">Contact Us</h2>
            <p class="text-center">Have questions or want to make a reservation? Reach out to us!</p>
            <p class="text-center">Phone: 123-456-7890 | Email: info@deliciouseats.com</p>
            <p class="text-center">Address: 143 Main Street, Rocky City, FC goa</p>
        </div>
    </section>

    <!-- Footer -->
    <footer class="footer text-center p-3">
        <p>&copy;RAHUL RIO S SINCE 2024</p>
    </footer>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About Us</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>
    <div class="container py-5">
        <h1 class="text-center mb-4">About Us</h1>
        <p>Welcome to Desert Hunters! Established in 2006, our restaurant has been serving fresh and high-quality food to our beloved community. Our chefs are passionate about crafting dishes that not only taste amazing but also leave a lasting impression. From cozy ambiance to exceptional customer service, we are here to make your dining experience unforgettable. Thank you for choosing us!</p>
        <p>Come visit us and discover the taste of love and dedication in every bite!</p>
    </div>
    <footer class="text-center py-3 bg-light">
        <p>&copy;RAHUL RIO S SINCE 2006</p>
    </footer>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>
    <div class="container py-5">
        <h1 class="text-center mb-4">Contact Us</h1>
        <p class="text-center">Have questions or want to make a reservation? Reach out to us!</p>
        <p class="text-center">Phone: 123-456-7890 | Email: info@deserthunters.com</p>
        <p class="text-center">Address: 143 Middle Street, Rocky City, FC goa</p>
    </div>
    <footer class="text-center py-3 bg-light">
        <p>&copy; RAHUL RIO S SINCE 2024</p>
    </footer>
</body>
</html>

```
## OUTPUT:
![image (1)-1](https://github.com/user-attachments/assets/3f9f5a8f-d0c1-42a6-ae93-0487921096d4)
![image-1 (1)](https://github.com/user-attachments/assets/268731f1-d914-4d3d-bffa-89dac8b83461)
![image-2 (1)](https://github.com/user-attachments/assets/c359ff1c-6173-43a3-848f-aec11b83fda0)
![image-3](https://github.com/user-attachments/assets/a4251aa4-8553-47a6-b73f-c598e98e953c)



## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
