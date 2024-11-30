# E-Commerce Backend API

This is a backend API for an e-commerce platform, developed using **Node.js** and **MongoDB**. The API provides essential functionalities for managing users, products, categories, orders, payments, and more, to power the frontend of an e-commerce application. It includes features like user authentication, authorization, product management, order processing, and category management.

## Features

- **User Management**: Create, update, delete, and manage user accounts with password reset and email verification functionality.
- **Authentication**: JWT-based authentication to handle user login, logout, and token refresh.
- **Product Management**: Admins can create, update, delete, and view products. Users can browse all available products.
- **Category Management**: Admins can manage categories to organize products effectively.
- **Order Management**: Users and admins can create, update, delete, and view orders.
- **Payment Integration**: Secure payment processing with token generation for transaction handling.

## Routes and Endpoints

- **General Routes**:
  - `/test`: Health check
  - `/seed`: Seed initial data

- **User Routes**:
  - `/register`: Create a user
  - `/login`: User login
  - `/profile`: Get user profile
  - `/update-password`: Update user password
  - `/forget-password`: Request a password reset

- **Product Routes**:
  - `/products`: Get all products
  - `/products/:id`: Get a single product by ID
  - `/products`: Create, update, and delete products (Admin only)

- **Order Routes**:
  - `/orders`: Create and view orders
  - `/orders/:id`: Update or delete specific orders (Admin only)

- **Category Routes**:
  - `/categories`: Manage categories (Admin only)

## Technologies Used

- **Node.js** for backend development
- **Express.js** for routing
- **MongoDB** for database management
- **JWT** for authentication
- **Bcrypt** for password hashing

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/vijay-tech-colab/e-commerce-backend.git
