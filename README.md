# Project name

## Table of contents
-[Project members](#project-members)
-[API Endpoints](#api-endpoints)
-[Project description](#project-description)


## Project description
This is a common e-commerce app that can be accepted a real working programm.
You can 

# API Endpoints

This document outlines the available endpoints for interacting with the API.

## Base URL

The base URL for all endpoints is: `https://127.0.0.1:8000/api/`

## Authentication

Authentication is required for certain endpoints. 
## Endpoints

### Products

- **GET /products/**
  - Retrieve a list of all products.
- **GET /product/{pid}/**
  - Retrieve details of a specific product by its ID.

### Categories

- **GET /categories/**
  - Retrieve a list of all product categories.
- **GET /category/{cid}/**
  - Retrieve products within a specific category by its ID.

### Vendors

- **GET /vendors/**
  - Retrieve a list of all vendors.
- **GET /vendor/{vid}/**
  - Retrieve details of a specific vendor by its ID.

### Tags

- **GET /products/tag/{tag_slug}/**
  - Retrieve products associated with a specific tag.

### Reviews

- **POST /ajax-add-review/{pid}/**
  - Add a review for a specific product.

### Cart

- **POST /add-to-cart/**
  - Add items to the cart.
- **GET /cart/**
  - Retrieve the current contents of the cart.
- **DELETE /delete-from-cart/**
  - Delete an item from the cart.
- **PUT /update-cart/**
  - Update the quantity of an item in the cart.

### Checkout

- **POST /api/create_checkout_session/{oid}/**
  - Create a checkout session for an order.
- **POST /save_checkout_info/**
  - Save checkout information.
- **GET /checkout/{oid}/**
  - Proceed to checkout for an order.

### Payments

- **POST /payment-completed/{oid}/**
  - Handle successful payment completion.
- **GET /payment-failed/**
  - Handle payment failure.

### User

- **GET /dashboard/**
  - Retrieve user dashboard information.
- **GET /dashboard/order/{id}/**
  - Retrieve details of a specific order.
- **POST /make-default-address/**
  - Make an address the default for the user.

### Wishlist

- **GET /wishlist/**
  - Retrieve user's wishlist.
- **POST /add-to-wishlist/**
  - Add a product to the wishlist.
- **DELETE /remove-from-wishlist/**
  - Remove a product from the wishlist.

### Contact

- **POST /contact/**
  - Send a contact message.

### Miscellaneous

- **POST /ajax-contact-form/**
  - Handle submission of an AJAX contact form.
- **GET /about_us/**
  - Retrieve information about the company.
- **GET /purchase_guide/**
  - Retrieve a purchasing guide.
- **GET /privacy_policy/**
  - Retrieve the privacy policy.
- **GET /terms_of_service/**
  - Retrieve the terms of service.


## Project members

|Member name|ID|
|---|---|
|Magzhan Akhmadi|22B030517|
|Sadanova Dana|22B030583|
|Biksultanov Diaz|22B030530|