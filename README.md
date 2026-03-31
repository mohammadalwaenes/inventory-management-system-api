# 📦 Inventory Management System API

A powerful RESTful API for managing inventory operations including products, stock, categories, and transactions — built with Laravel.

---

## 🚀 Overview

This project is a backend API designed to handle all core inventory management operations for businesses. It provides a scalable and clean architecture to manage products, categories, stock levels, and related operations.

The system is designed following RESTful principles and Laravel best practices.

---

## ✨ Features

* 🔐 User Authentication (Register / Login / Logout)
* 📦 Product Management (CRUD operations)
* 🗂️ Category Management
* 📊 Stock & Inventory Tracking
* 🔄 Clean API structure (RESTful)
* 🧪 Database seeding with realistic data
* ⚡ Built with scalable backend architecture

---

## 🛠️ Tech Stack

* Laravel (Latest version)
* PHP
* MySQL
* Eloquent ORM
* Laravel Factories & Seeders

---

## 📂 Project Structure

```
app/
 ├── Models
 ├── Http/Controllers
routes/
 ├── api.php
database/
 ├── migrations
 ├── factories
 ├── seeders
```

---

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/mohammadalwaenes/inventory-management-system-api.git
cd inventory-management-system-api
```

### 2. Install dependencies

```bash
composer install
```

### 3. Setup environment

```bash
cp .env.example .env
php artisan key:generate
```

### 4. Configure database

Edit `.env` file:

```
DB_DATABASE=your_database
DB_USERNAME=root
DB_PASSWORD=
```

### 5. Run migrations & seeders

```bash
php artisan migrate --seed
```

### 6. Run server

```bash
php artisan serve
```

---

## 🔐 Authentication

This API uses **token-based authentication**.

### Endpoints:

* `POST /api/register`
* `POST /api/login`
* `POST /api/logout`

---

## 📚 API Endpoints

### 📦 Products

* `GET /api/products`
* `POST /api/products`
* `GET /api/products/{id}`
* `PUT /api/products/{id}`
* `DELETE /api/products/{id}`

### 🗂️ Categories

* `GET /api/categories`
* `POST /api/categories`

### 📊 Inventory

* Track product quantities
* Manage stock updates

---

## 🧪 Testing

You can test the API using:

* Postman
* Thunder Client (VS Code)

---

## 💡 What I Learned

* Building RESTful APIs with Laravel
* Migrating and upgrading legacy projects
* Handling authentication without heavy packages
* Designing relational databases (Products, Categories, Inventory)
* Using factories & seeders for realistic data

---

## 📌 Future Improvements

* Add role-based access control (Admin / User)
* Add reporting & analytics
* Integrate frontend dashboard
* Add API documentation (Swagger)

---

## 👨‍💻 Author

Mohammad Alwaenes

---

## ⭐ Support

If you like this project, please give it a ⭐ on GitHub!



