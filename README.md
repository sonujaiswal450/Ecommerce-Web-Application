# E-Commerce Web Application
An e-commerce web application built using PHP, HTML, CSS, MySQL, and XAMPP, providing a full shopping experience including product browsing, cart management, and order processing.

# Features
 User Authentication: Sign up, log in, and manage user profiles.
 Product Management: View products, add to cart, and checkout.
 Cart Functionality: Add, update, and remove products in the cart.
 Admin Panel: Manage products, categories, orders, and users (if applicable).
 Payment System:Add only Cash On Delivery
 Order Management: Track order history and order status.
# Technologies Used
 Frontend: HTML, CSS
 Backend: PHP
 Database: MySQL (managed with XAMPP)
 Server: XAMPP
 Installation
# To run this project locally, follow these steps:

# 1.Clone the repository:
  git clone https://github.com/sonujaiswal450/Ecommerce-Web-Application.git

# 2.Start XAMPP:
 Make sure Apache and MySQL are running in XAMPP.
# 3.Set up the Database:
 Open phpMyAdmin (http://localhost/phpmyadmin).
 Create a new database named ecommerce.
 Import the provided SQL file (database/ecommerce.sql) to set up tables.
# 4.Configure Database Connection:
 Open config.php and update the following lines to match your local environment:
 define('DB_SERVER', 'localhost');
 define('DB_USERNAME', 'root');  // default for XAMPP
 define('DB_PASSWORD', '');      // default for XAMPP
 define('DB_DATABASE', 'ecommerce');
# 5.Run the Application:

# Visit http://localhost/projectdone/ in your web browser.
