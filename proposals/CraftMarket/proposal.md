# CraftMarket — Project Proposal

**CodePath WEB103 Final Project — Option A**

**Tagline:** Discover handmade. Support independent creators.

## 1. Project Overview

CraftMarket is an Etsy-inspired online marketplace designed to connect independent creators with people interested in discovering unique, handmade, and personalized products.

The platform allows sellers to create shop profiles, publish and manage product listings, and showcase their creations. Buyers can explore products, browse categories, search for specific items, and save products to their favorites.

CraftMarket focuses on product discovery and seller visibility rather than implementing a complete e-commerce purchasing system.

## 2. Problem Statement

Independent artisans and small creative businesses often face challenges promoting their handmade products and reaching potential customers.

Building and maintaining an independent e-commerce website can require technical knowledge, time, and financial resources that some creators do not have.

At the same time, buyers looking for unique or personalized products may struggle to discover independent sellers and compare available products.

CraftMarket aims to make product discovery and seller visibility simpler through one accessible marketplace.

## 3. Description and Purpose

CraftMarket provides a centralized platform where independent sellers can showcase handmade products and buyers can discover items from multiple creators.

Sellers can create profiles describing their shops, publish products with descriptions, prices, and images, and manage their listings.

Buyers can browse products by category, search using keywords, filter by price, view product details, and save favorite products.

The purpose of CraftMarket is to support independent creators while offering buyers a convenient way to discover handmade goods.

The initial version will not include payment processing, shipping management, or order fulfillment.

## 4. Inspiration

CraftMarket is inspired by Etsy and the growing use of online marketplaces by independent creators and small businesses.

Many artisans produce jewelry, artwork, clothing, decorations, and personalized gifts but need accessible ways to present their products to potential customers.

The project explores how a simplified marketplace can help creators gain visibility while giving buyers a more organized product discovery experience.

## 5. Target Users

### Buyer

A user interested in discovering handmade products, exploring different sellers, searching product listings, and saving favorite items.

### Seller

An independent creator or small business owner who wants to establish a shop presence, publish product listings, and manage available products.

For the initial version, users will have a buyer or seller role. Sellers may also browse the marketplace, but seller-specific management actions will be restricted to their own listings.

## 6. Core Features

### Feature 1: User Registration and Login

Users can create an account and securely sign in to access their account features.

### Feature 2: User Roles

Users participate as buyers or sellers, with seller-specific permissions for managing shops and product listings.

### Feature 3: Seller Profiles

Sellers can create profiles describing their shops, including a shop name, description, and other basic information.

### Feature 4: Product Listings

Sellers can create product listings containing a product name, description, price, category, and image.

### Feature 5: Product Management

Sellers can edit and delete their own product listings to keep their storefronts accurate and up to date.

### Feature 6: Product Discovery

Buyers can browse products and explore available categories.

### Feature 7: Search and Filtering

Buyers can search for products using keywords and filter results by category or price.

### Feature 8: Favorites

Buyers can save products they are interested in and view their saved products in a favorites collection.

## 7. Proposed Technology Stack

**Frontend**
- React
- JavaScript
- HTML and CSS
- React Router

**Backend**
- Node.js
- Express.js
- RESTful API

**Database**
- PostgreSQL
- `pg` library for database communication

**Deployment**
- Render

**Authentication**
- Proposed secure username/email and password authentication, using password hashing and server-enforced authorization.

## 8. Proposed Database Relationships

### One-to-Many

- One seller can create multiple products.
- One category can contain multiple products.

### Many-to-Many

- One buyer can save multiple products.
- One product can be saved by multiple buyers.

A `favorites` join table connects users and products.

## 9. Proposed Custom Features

CraftMarket will target at least two features from the WEB103 custom feature requirements:

1. **Search, Filtering, and Sorting:** Buyers can filter product listings by category and price, and optionally sort results.
2. **Data Validation:** Product information is validated before creating or updating records, including required fields and valid prices.

These features will be implemented and verified during development.

## 10. Minimum Viable Product

The initial version will prioritize the eight selected core features:

1. User registration and login
2. Buyer and seller roles
3. Seller profiles
4. Product listings
5. Product management
6. Product discovery
7. Search and filtering
8. Favorites

Product images may initially be supplied through image URLs rather than uploaded directly to cloud storage.

Payment processing, checkout, shipping, messaging, seller reviews, and order management are outside the initial project scope.

## 11. Project Status

**Status:** Proposed — awaiting group evaluation and final selection.

All features described above are planned and have not yet been implemented.