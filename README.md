# Food Ordering Platform

Welcome to the Food Ordering Platform project! This repository aims to provide a robust backend and frontend solution for a seamless food ordering experience. The platform connects customers with a diverse array of restaurants, allowing for smooth order placement, real-time tracking, and secure payment processing.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Running the Project](#running-the-project)
- [API Documentation](#api-documentation)
- [Frontend Overview](#frontend-overview)
- [Contributing](#contributing)
- [License](#license)

## Features

### Backend
- **Restaurant Registration:** Restaurants can create profiles, upload menus, and specify operating hours.
- **Customer Authentication:** Secure customer registration and login functionality.
- **Menu Browsing:** Customers can view restaurant menus based on cuisine or location.
- **Order Placement:** Customers can place orders with selected restaurants and add items to their cart.
- **Real-time Order Tracking:** Customers and restaurants can track order status.
- **Payment Integration:** Secure payment processing with the Stripe API.
- **Order History:** Customers and restaurants can view their past order history.
- **Review and Rating System:** Customers can rate and review restaurants.
- **User Profile Management:** Customers can update their profiles, including contact information and delivery addresses.

### Frontend
- **Restaurant Listing and Search:** Users can filter restaurants based on cuisine, location, and rating.
- **Interactive Menu Browsing:** Browse menus, view item descriptions, and add items to the cart.
- **Order Tracking Visualization:** Display the order's progress in real-time.
- **User Authentication:** Registration, login, and account management flows.
- **Dynamic Shopping Cart:** Real-time cart management for adjusting quantities and checkout.
- **Review and Rating Submission:** Submit reviews and ratings for restaurants.

## Technologies Used

### Backend
- **Node.js**
- **Express.js**
- **MongoDB** with **Mongoose**
- **JWT Authentication**
- **Bcrypt** for secure password storage
- **Stripe** for payment processing

### Frontend
- **React.js**
- **Redux** for state management
- **React Router** for navigation
- **Axios** for API communication
- **CSS Modules** for styling

## Project Structure



API Documentation
User Routes
POST /api/auth/register: Register a new user.
POST /api/auth/login: Log in an existing user.
GET /api/auth/me: Get the current user's profile.
Restaurant Routes
POST /api/restaurants: Create a new restaurant.
GET /api/restaurants: Get a list of all restaurants.
GET /api/restaurants/:id: Get details of a specific restaurant.
PUT /api/restaurants/:id: Update a restaurant's details.
DELETE /api/restaurants/:id: Delete a restaurant.
Order Routes
POST /api/orders: Place a new order.
GET /api/orders: Get a list of all orders.
GET /api/orders/:id: Get details of a specific order.
PUT /api/orders/:id: Update an order's status.
Payment Routes
POST /api/payment/stripe: Process payment using Stripe.
Frontend Overview
The frontend provides a user-friendly interface for customers to browse restaurants, place orders, track their order status, and manage their profiles.

Restaurant Listing Page: Displays all restaurants with filters for sorting.
Menu Page: Allows customers to browse the restaurant's menu and add items to their cart.
Checkout Page: Facilitates the checkout process and handles payment.
Order Tracking Page: Displays the order's real-time status.
Contributing
Contributions are welcome! Please follow the contribution guidelines and ensure that your code adheres to the project's style and linting rules.

License
This project is licensed under the MIT License - see the LICENSE file for details.
