# kheti
Kheti-Unati is a web-based platform designed to empower farmers by providing them with tools to grow crops suited to their area's conditions and to sell their produce directly to consumers. The platform is built using HTML, CSS, JavaScript, and PHP, and aims to bridge the gap between farmers and buyers, ensuring better prices for farmers and fresh produce for buyers.

Features
Crop Suitability: Helps farmers determine which crops are best suited to their area's climatic and soil conditions.
Marketplace: Allows farmers to list their produce for sale and buyers to browse and purchase fresh produce directly from farmers.
User Registration and Login: Secure registration and login system for both farmers and buyers.
Profile Management: Farmers and buyers can manage their profiles, including personal details, crop listings, and purchase history.
Search Functionality: Buyers can search for specific crops or browse through categories.
Responsive Design: Ensures the platform is accessible and user-friendly on all devices, including desktops, tablets, and smartphones.
Technologies Used
Frontend:

HTML: For the basic structure of the web pages.
CSS: For styling and layout.
JavaScript: For interactive elements and client-side validation.
Backend:

PHP: For server-side scripting and interaction with the database.
MySQL: For storing user data, crop listings, and transaction records.
Installation
To set up Kheti-Unati on your local machine, follow these steps:

Clone the repository:

git clone https://github.com/yourusername/kheti-unati.git
Navigate to the project directory:

cd kheti-unati
Set up the database:

Create a MySQL database named kheti_unati.
Import the provided SQL file to set up the required tables:
mysql -u yourusername -p kheti_unati < database/kheti_unati.sql
Configure the database connection:

Open config.php and update the database connection details:
<?php
$servername = "localhost";
$username = "yourusername";
$password = "yourpassword";
$dbname = "kheti_unati";
?>
Start the local server:

If you are using XAMPP, MAMP, or WAMP, place the project folder in the htdocs directory and start the server.
If using a built-in PHP server, run:
php -S localhost:8000
Access the platform: Open your web browser and go to http://localhost/kheti-unati or http://localhost:8000.

Usage
Register: Sign up as either a farmer or a buyer.
Login: Use your credentials to log in.
Profile Setup: Complete your profile details.
For Farmers:
Use the crop suitability tool to find the best crops for your area.
List your crops for sale in the marketplace.
For Buyers:
Browse or search for crops.
Purchase crops directly from farmers.
