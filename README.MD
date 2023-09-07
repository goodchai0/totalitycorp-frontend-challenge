# TotalityCorp E-Commerce Challenge

## Challenge Overview

Welcome to the TotalityCorp E-Commerce Challenge! This project represents an intermediate-level e-commerce website developed using React or a similar frontend framework/library. The challenge is designed to assess your skills in coding, UI design, logical thinking, user interaction, and critical problem-solving.

### Key Features

The website you will be building should replicate a fully functional shopping site with essential features, including:

- **Product Listing:** Display a wide range of products with details, images, and categories.
- **Cart Management:** Allow users to add and remove items from their shopping cart.
- **Checkout:** Implement a seamless checkout process for users to place orders.

## TotalityCorp Hiring Challenge

This project was created as part of a hiring challenge for TotalityCorp. It serves as an opportunity for you to showcase your development skills and demonstrate your ability to create a functioning e-commerce website.

## Getting Started

To begin working on this challenge, follow the instructions provided in the frontend and backend directories to set up and run the application. Ensure that you configure environment variables and dependencies as necessary.

Feel free to explore and customize the code to meet the challenge requirements. If you have any questions or need assistance, please refer to the documentation or contact the TotalityCorp hiring team.

## Project Structure

### Frontend

The frontend of the project is responsible for the user interface and client-side functionality.

- **public:** This directory contains static assets and configuration files.

  - **gif:** Directory for GIF files.
  - **images/product-images:** Directory for product images.
  - **favicon.ico:** This file is used as the website's icon in web browsers.
  - **index.html:** The main HTML file that serves as the entry point for the frontend application.
  - **logo192.png:** A smaller version of the app's logo (192x192 pixels).
  - **logo512.png:** A larger version of the app's logo (512x512 pixels).
  - **manifest.json:** Web app manifest file for configuring how the app appears when installed on a user's device.
  - **robots.txt:** A file used to control web crawlers.
  - **storebay-logo.jpg:** The project's logo image.

- **src:** This directory contains the JavaScript source code for the frontend application.
  - **actions:** Contains Redux actions, which are used for managing global application state.
  - **components:** Reusable React components that make up the user interface.
    - **Footer.js:** Footer component for displaying footer content.
    - **Header.js:** Header component for displaying the website's header.
    - **Loader.js:** A loader component for showing loading indicators.
    - **MainPageCategory.js:** Component for displaying main page categories.
    - **Message.js:** Component for displaying messages and alerts.
    - **Navbar.js:** Navbar component for site navigation.
    - **NavbarDropdown.js:** Dropdown menu component for the navbar.
    - **Pagination.js:** Component for pagination controls.
    - **Product.js:** Component for displaying individual product items.
    - **ProductDetailsUI.js:** UI component for product details.
    - **ProductReview.js:** Component for displaying product reviews.
    - **Rating.js:** Component for displaying product ratings.
    - **ScrollToTop.js:** Component for scrolling to the top of the page.
    - **Search.js:** Component for search functionality.
    - **Sidebar.js:** Sidebar component for site navigation.
    - **Stats.js:** Component for displaying statistics.
    - **Testimonials.js:** Component for displaying customer testimonials.
    - **userListScreen.js:** Screen for displaying a list of users.
  - **constants:** Contains application constants and configuration data.
  - **lib:** External libraries or utility functions used in the application.
  - **pages:** React components representing different pages of the application.
    - **AdminCreateProduct.js:** Page for creating new products in the admin panel.
    - **AdminEditUser.js:** Page for editing user information in the admin panel.
    - **AdminOrdersList.js:** Page for listing orders in the admin panel.
    - **AdminProductList.js:** Page for listing products in the admin panel.
    - **AdminUserList.js:** Page for listing users in the admin panel.
    - **Category.js:** Component for displaying product categories.
    - **CategoryPage.js:** Page for displaying products within a specific category.
    - **Homepage.js:** The main homepage of the e-commerce site.
    - **Login.js:** Page for user login.
    - **Payment.js:** Page for handling payments during checkout.
    - **PlaceOrder.js:** Page for placing an order.
    - **PostOrder.js:** Page for order confirmation.
    - **ProductScreen.js:** Page for displaying detailed product information.
    - **Profile.js:** User profile page.
    - **Shipping.js:** Page for managing shipping information during checkout.
    - **ShoppingCart.js:** Page for displaying and managing items in the shopping cart.
    - **Signup.js:** Page for user registration.
  - **reducers:** Redux reducers responsible for managing the application's state.
  - **App.css:** CSS styles specific to the application.
  - **App.js:** The main React application component that renders the app's structure.
  - **index.css:** Global CSS styles that apply to the entire application.
  - **index.js:** The entry point for the React application.
  - **store.js:** Configuration for the Redux store.
  - **capacitor.config.json:** Configuration file for Capacitor (if used for mobile app development).
  - **package-lock.json:** Auto-generated file to lock dependencies to specific versions.
  - **package.json:** Node.js project configuration file that lists project dependencies.
  - **postcss.config.js:** Configuration for PostCSS, a tool for processing CSS.
  - **tailwind.config.js:** Configuration for the Tailwind CSS framework (if used for styling).
  - **uploads:** Directory for storing uploaded files (e.g., user profile pictures).

### Backend

The backend of the project handles server-side logic and provides APIs for the frontend.

- **config:** Configuration files for the backend.
  - **db.js:** Database configuration file for connecting to the database server.
- **controllers:** Controllers responsible for handling various types of HTTP requests and managing business logic.

  - **orderController.js:** Controller for managing orders.
  - **productController.js:** Controller for managing products.
  - **searchController.js:** Controller for implementing search functionality.
  - **userController.js:** Controller for user-related operations.

- **data:** Sample data (for development and testing purposes).

  - **products.js:** JSON file containing sample product data.
  - **users.js:** JSON file containing sample user data.

- **middleware:** Middleware functions that can intercept and process requests before they reach the controller.

  - **authMiddleware.js:** Middleware for handling user authentication and authorization.
  - **errorMiddleware.js:** Middleware for handling errors and returning appropriate responses.

- **models:** Data models that define the structure of data objects stored in the database.

  - **orderModel.js:** Model for representing order data.
  - **productModel.js:** Model for representing product data.
  - **userModel.js:** Model for representing user data.

- **node_modules:** Node.js dependencies installed via npm (Node Package Manager).

- **routes:** Route handlers that define the API endpoints and the corresponding controller methods to execute.

  - **orderRoutes.js:** Defines routes for managing orders.
  - **productRoutes.js:** Defines routes for managing products.
  - **searchRoutes.js:** Defines routes for search functionality.
  - **uploadRoutes.js:** Defines routes for handling file uploads (if applicable).
  - **userRoutes.js:** Defines routes for user-related operations.

- **utils:** Utility functions that assist in various backend operations.

  - **apiFeatures.js:** Utility for handling advanced filtering, sorting, and pagination of data.
  - **generateToken.js:** Utility for generating authentication tokens.

- **README.md:** This README file containing information about the project structure and setup.

- **package-lock.json:** Auto-generated file that locks dependencies to specific versions to ensure consistent installations.

- **package.json:** Node.js project configuration file that lists project dependencies and scripts.

- **seeder.js:** Seeder script for populating the database with sample data (if applicable).

- **server.js:** The main entry point for the Node.js server, responsible for initializing and starting the server.

### How to start the project

## frondend-

npm i
npm start

## backend-

npm i
nodemon server.js
