# 🎨 Art Gallery - Laravel Powered Marketplace

A **full-featured art gallery marketplace** built with Laravel that allows artists to register, upload paintings, and manage listings, while customers can browse, favorite, and purchase artwork.

---

## 🚀 Features

- 🎭 **User Roles** – Separate dashboards for Artists and Customers  
- 🖼️ **Artwork Management** – Artists can post, edit, and delete paintings  
- 🛒 **E-commerce Support** – Customers can browse and buy artwork  
- 🔐 **Authentication** – Secure login & registration for both roles  
- ⚙️ **Admin Panel** – Manage users, artworks, and transactions

---

## 🛠️ Tech Stack

### Frontend
- HTML5  
- CSS3  
- JavaScript  
- Bootstrap

### Backend
- PHP  
- Laravel Framework  
- MySQL Database

### Tools
- Visual Studio Code  
- XAMPP (Apache, MySQL, PHP)

---

## 📦 Installation Guide

```bash
# Step 1: Clone the Repository
git clone https://github.com/your-username/art-gallery.git

# Step 2: Navigate into the project
cd art-gallery

# Step 3: Install dependencies
composer install
npm install && npm run dev

# Step 4: Setup environment
cp .env.example .env
php artisan key:generate

# Step 5: Configure .env with your database credentials

# Step 6: Run migrations
php artisan migrate

# Step 7: Start development server
php artisan serve

