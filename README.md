# CodeAlpha Simple Ecommerce Store

A simple, lightweight ecommerce store built with HTML, CSS, and JavaScript. This project demonstrates core ecommerce functionality including product browsing, shopping cart management, user authentication, and checkout.

## 📋 Features

- **Product Catalog** - Browse products with descriptions and prices
- **Shopping Cart** - Add/remove items and view cart total
- **User Authentication** - Login and registration system
- **Product Details Page** - View detailed information about individual products
- **Responsive Design** - Clean and simple UI with centered layout
- **Cart Management** - Track items and calculate totals

## 📁 Project Structure

```
CodeAlpha_SimpleEcommerceStore/
├── index.html          # Main homepage with product listings
├── product.html        # Individual product details page
├── cart.html          # Shopping cart management page
├── login.html         # User login page
├── register.html      # User registration page
├── style.css          # Styling for all pages
└── script.js          # JavaScript functionality
```

## 🎨 Pages Overview

### 1. **index.html** - Home Page
- Navigation menu with links to all pages
- Product grid displaying available items
- Each product card includes:
  - Product image (placeholder)
  - Product name
  - Price in rupees (₹)
  - "Add to Cart" button

**Products Featured:**
- T-Shirt - ₹499
- Shoes - ₹999
- Watch - ₹1499

### 2. **product.html** - Product Details
- Detailed view of a single product
- Large product image
- Product description: "Comfortable Cotton T-Shirt"
- Price display
- "Add to Cart" button

### 3. **cart.html** - Shopping Cart
- View all items added to cart
- Display product names and individual prices
- Calculate total bill
- Shopping cart layout showing:
  - T-Shirt - ₹499
  - Shoes - ₹999
  - Total = ₹1498
- "Place Order" button to proceed to checkout

### 4. **register.html** - User Registration
- User registration form with fields:
  - Name input
  - Email input
  - Password input
  - "Register" button

### 5. **login.html** - User Login
- User login form with fields:
  - Email input
  - Password input
  - "Login" button

## 🎯 Styling (style.css)

### Global Styles
```css
body {
  text-align: center;
  font-family: Arial;
}
```

### Component Styles
- **Product Cards** - 1px solid black border, 20px padding, 20px margin
- **Buttons** - Green background with white text, 10px padding, no border
- **Navigation** - 10px margin
- **Links** - No text decoration

## ⚙️ JavaScript Functionality (script.js)

### addToCart() Function
- Triggered when "Add to Cart" button is clicked
- Shows alert: "Product Added to cart successfully"
- Currently displays confirmation message

```javascript
function addToCart() {
  alert("Product Added to cart successfully");
}
```

## 🚀 How to Use

1. **Clone the repository**
   ```bash
   git clone https://github.com/natchatradsvct-hash/CodeAlpha_SimpleEcommerceStore.git
   ```

2. **Open in a browser**
   - Open `index.html` in your web browser
   - Navigate through the pages using the menu links

3. **Browse Products**
   - View available products on the home page
   - Click on products to view details
   - Add items to cart

4. **Manage Cart**
   - Visit cart.html to see your shopping items
   - View the total price
   - Place your order

5. **User Accounts**
   - Register for a new account via register.html
   - Login with your credentials via login.html

## 💡 Features to Enhance

- Persistent cart storage using localStorage
- Backend database integration for user accounts
- Payment gateway integration
- Product filtering and search
- Product reviews and ratings
- Order history tracking
- Inventory management
- Email notifications

## 🛠️ Technologies Used

- **HTML5** - Page structure and layout
- **CSS3** - Styling and design
- **JavaScript (Vanilla)** - Interactive functionality

## 📝 Notes

- Product images currently use placeholder URLs
- Cart functionality shows alerts but doesn't persist data
- User authentication is form-based (no backend validation yet)
- Prices are displayed in Indian Rupees (₹)

## 👤 Author

Created for CodeAlpha - Simple Ecommerce Store Project

## 📄 License

This project is open source and available under the MIT License.

---

**Last Updated:** June 2026
**Repository:** [CodeAlpha_SimpleEcommerceStore](https://github.com/natchatradsvct-hash/CodeAlpha_SimpleEcommerceStore)
