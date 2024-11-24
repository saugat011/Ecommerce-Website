# E-Commerce Website: Mobile Store

Welcome to the **Mobile Store E-commerce Website** repository! This project is a fully responsive e-commerce website designed to sell mobile phones. It is built using **HTML**, **CSS**, **JavaScript** for the frontend, and **PHP** for the backend.

## Project Structure

This project is organized into multiple folders and files that work together to provide an e-commerce shopping experience. Below is the folder structure:

- **admin**: Admin panel for managing products and users.
- **assets**: Contains images, icons, and other media used across the website.
- **build**: Compilation of front-end assets (minified files).
- **classes**: PHP classes for handling various functionalities.
- **database**: Database configurations and SQL queries.
- **dist**: Distribution files (e.g., bundled JavaScript, CSS).
- **inc**: Includes for header, footer, and other shared components.
- **libs**: External libraries integrated into the website.
- **plugins**: Plugins for enhanced functionality (e.g., carousels, lightboxes).
- **uploads**: Directory where user-uploaded files (e.g., product images) are stored.

### Key Files:
- **index.php**: Home page of the website.
- **about.php**: About page providing company details.
- **cart.php**: Cart page where users can view added products.
- **checkout.php**: Checkout page for finalizing orders.
- **products.php**: Displays available products for purchase.
- **login.php**: User login page.
- **registration.php**: User registration page.
- **my_account.php**: User account page for managing orders and profile.
- **config.php**: Configuration file for database connection and site settings.
- **privacy_policy.html**: Privacy policy page.

## Features

- **Fully Responsive**: The website is designed to work seamlessly across desktop, tablet, and mobile devices.
- **Product Catalog**: Users can browse various mobile phone products, view details, and add them to the cart.
- **User Authentication**: Provides login and registration functionality for users to manage their accounts and orders.
- **Shopping Cart**: Users can add products to the cart, view details, and proceed to checkout.
- **Admin Panel**: Admins can manage products, categories, and users from the backend.

## Languages & Technologies

- **Frontend**:
  - HTML
  - CSS (SCSS for styles)
  - JavaScript
- **Backend**:
  - PHP
- **Database**: MySQL (configured in `config.php`)

## Installation

To run this project locally, follow these steps:

1. Clone this repository:
   ```bash
   git clone https://github.com/saugat011/Ecommerce-Website.git
## Setup Instructions

1. **Set up a local server environment**  
   Use a local server environment like [XAMPP](https://www.apachefriends.org/index.html) or [WAMP](https://www.wampserver.com/en/).

2. **Place the project folder in the server directory**  
   - For **XAMPP**, place the project folder in the `htdocs` directory.
   - For **WAMP**, place the project folder in the `www` directory.

3. **Create a new database in MySQL**  
   - Open your MySQL database management tool (e.g., phpMyAdmin).
   - Create a new database for the project.
   - Import any provided SQL files from the `database` folder (if available).

4. **Update your database connection settings**  
   - Open the `config.php` file.
   - Update the database connection settings with your local database credentials.

5. **Access the website locally**  
   - Open your browser and navigate to `http://localhost/Ecommerce-Website/` to view the website.

## Demo

You can preview the website live here: [Mobile Store Demo](https://your-deployed-site-url.com)

## Contributing

Contributions are welcome! If you would like to contribute to this project, follow these steps:

1. **Fork the repository**  
   Fork this repository to your own GitHub account.

2. **Create a new branch**  
   Create a new branch for your feature:
   ```bash
   git checkout -b feature-branch

This README provides a clean, professional look while covering all the necessary details for your project. It includes installation instructions, project structure, and a clear explanation of the website's features.
