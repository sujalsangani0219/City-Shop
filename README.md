# Online Shop Website - City Shop

This project is an online shop website for selling and purchasing products. It includes a front-end built with **HTML, CSS, JavaScript**, and a back-end using **PHP** with a **MySQL** or **SQLite** database. This project features user registration and login, product browsing, a shopping cart, checkout system, and an admin panel for managing products, orders, and users.

**Live Demo**: [City Shop](https://sujalsangani0219.github.io/City-Shop/)

## Table of Contents

- [Features](#features)
- [Pages](#pages)
  - [1. Home Page](#1-home-page)
  - [2. Product Page](#2-product-page)
  - [3. Shopping Cart](#3-shopping-cart)
  - [4. Checkout Page](#4-checkout-page)
  - [5. User Registration and Login](#5-user-registration-and-login)
  - [6. Admin Panel](#6-admin-panel)
- [Technical Overview](#technical-overview)
  - [Frontend](#frontend)
  - [Backend](#backend)
  - [Database](#database)
- [Setup and Installation](#setup-and-installation)
- [Key Features](#key-features)

## Features

- User-friendly interface for browsing and buying products.
- Secure user authentication for registration, login, and session management.
- Shopping cart functionality with the ability to update product quantities and view the order summary.
- Payment gateway integration for processing orders.
- Admin panel to manage products, users, and orders.

## Pages

### 1. Home Page

The Home Page is the first page users see when they visit the website. It contains the following sections:

- **Header**: Includes the store logo, navigation menu (Home, Products, Cart, Login/Register), and a search bar.
- **Hero Section**: Displays a promotional banner or featured products, offering discounts or showcasing new arrivals.
- **Product Categories**: Lists various product categories (e.g., Electronics, Fashion, Home Appliances) for easy navigation.
- **Product Listing**: Displays a few top-selling or new products with their images, names, prices, and an “Add to Cart” button.
- **Footer**: Contains links to pages like Contact Us, About Us, Terms and Conditions, and social media icons.

### 2. Product Page

The Product Page displays details about a selected product:

- **Product Details**: Includes product image(s), name, price, description, specifications, and available stock.
- **Options**: Allows the user to select quantity, size (if applicable), or other product variants.
- **Buttons**: "Add to Cart" and "Buy Now" buttons for quick actions.
- **Customer Reviews**: Section for user-generated reviews and ratings of the product.
- **Related Products**: Recommends similar products to the user.

### 3. Shopping Cart

The Shopping Cart page shows all the items the user has added to their cart:

- Displays the product name, quantity, price, and total cost.
- Allows users to update the quantity or remove products.
- Shows the total amount payable with an option to proceed to checkout.

### 4. Checkout Page

The Checkout page allows users to complete their purchase:

- **Form**: Users input their shipping details and select payment methods (credit/debit card, PayPal, etc.).
- **Summary**: Displays a summary of the order, including product names, quantities, and the total price.
- **Promo Codes**: Option to apply discount codes before finalizing the purchase.

### 5. User Registration and Login

Users can create an account or log in using the following forms:

- **Register**: New users can sign up by providing their email, password, and other basic details.
- **Login**: Returning users can log in using their credentials.
- **User Profile**: After logging in, users can view their profile, order history, and update their information.

### 6. Admin Panel

The Admin Panel is designed for store administrators to manage the website:

- **Product Management**: Admins can add, update, or delete products. This includes uploading product images, setting prices, and adding product descriptions.
- **Order Management**: Admins can view and manage incoming orders, update order statuses, and communicate with customers.
- **User Management**: Admins can view registered users, block/unblock users, and update user information.

## Technical Overview

### Frontend

- **HTML**: The structure of the website, including the layout for product listings, shopping cart, and checkout pages.
- **CSS**: Styling the website with responsive design, typography, colors, and layout adjustments.
- **JavaScript**: Manages dynamic interactions, such as adding products to the cart, updating quantities, and validating forms.

### Backend

- **PHP**: Handles user authentication, product management, and order processing. 
  - **Product Management**: PHP scripts to retrieve product data from the database and display them on the front-end.
  - **User Authentication**: Login, registration, and session management.
  - **Order Processing**: Manages user orders, shopping cart sessions, and payment methods.
