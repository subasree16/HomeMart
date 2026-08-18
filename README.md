# HomeMart – Furniture & Decor

## Project Overview

HomeMart is a premium, responsive furniture and decor e-commerce front-end demo. It uses a local JavaScript catalogue and browser storage; no backend, database, or build process is required.

## Features

- 50 unique furniture and decor products across four room categories
- Product search, multi-filtering, sorting, and load more
- Detail pages with related products, wishlist, and quantity selection
- Persistent cart and wishlist with INR order calculations
- Simulated registration, login, account dashboard, checkout, orders and tracking
- Responsive mobile navigation, toast feedback, accessible forms, and image fallback handling

## Technologies Used

HTML5, CSS3, vanilla JavaScript, Font Awesome, Google Fonts, and `localStorage`.

## Project Structure

`index.html` homepage · `products.html` catalogue · `product.html` details · `cart.html` · `checkout.html` · `account.html` · `login.html` · `register.html` · `about.html` · `contact.html` · `products.js` catalogue · `script.js` shared functionality · `style.css` and `responsive.css` styling.

## Product Categories

Living Room, Bedroom, Dining & Kitchen, and Office & Decor, each with several subcategories.

## JavaScript Functionality

The shared script renders products, filters and sorts them, manages cart/wishlist state, validates forms, creates simulated orders, and provides responsive navigation and notifications.

## Local Storage

Uses `homemart_cart`, `homemart_wishlist`, `homemart_user`, `homemart_orders`, and `homemart_logged_in`. Reads are guarded against malformed saved data.

## Responsive Design

Layouts adapt for desktop, tablet, and small mobile screens with product grid, filters, checkout, and navigation adjustments.

## How to Run

Open this folder in VS Code and launch `index.html` with the Live Server extension. Any simple static local server works too.

## Screenshots

Add screenshots here after running the project locally.

## Deployment

Upload the folder to GitHub Pages, Netlify, or Vercel as a static site. No environment variables or build command are needed.

## Internship Task

Task ID: WD-EC-004  
Domain: E-Commerce Furniture  
Project: HomeMart – Furniture & Decor
