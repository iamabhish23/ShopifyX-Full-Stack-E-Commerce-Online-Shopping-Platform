
# ShopifyX: Full-Stack E-Commerce Online Shopping Platform

Welcome to ShopifyX, a powerful e-commerce platform designed to provide a seamless online shopping experience.

## Overview

ShopifyX comes equipped with a range of features to enhance your e-commerce journey, including seamless user authentication, an intuitive admin dashboard, efficient product management, product reviews, online delivery, secure payments, and dynamic sales analytics.

## Getting Started

Follow these steps to get started with ShopifyX:

### 1. Clone the Repository

```bash
git clone [repository-url]
cd ShopifyX

#Install Dependencies

For Backend - `npm i`

For Frontend - `cd frontend` `npm i`
```

### 2. Env Variables

Make sure to create a `config.env` file in the `backend/config` directory and add the following essential variables to use the app:

```bash
PORT=
DB_URI=
STRIPE_API_KEY=
STRIPE_SECRET_KEY=
JWT_SECRET=
JWT_EXPIRE=
COOKIE_EXPIRE=
SMTP_SERVICE=
SMTP_MAIL=
SMTP_PASSWORD=
SMTP_HOST=
SMTP_PORT=
CLOUDINARY_NAME=
CLOUDINARY_API_KEY=
CLOUDINARY_API_SECRET=
```

### 3. Configuration

Navigate to the `config` directory and configure the settings, including database connections and payment gateways.

### 4. Run the Application Locally

Now, you're ready to run the application locally. In the project root directory, run:

```bash
npm start
```

This will start the development server. Open your web browser and visit [http://localhost:3000](http://localhost:3000) to access ShopifyX.
