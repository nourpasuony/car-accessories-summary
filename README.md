# 🛠️Product Warranty Management Dashboard

## 📌 Project Overview

it is a complete warranty management system for products. Administrators can create product groups, generate and assign QR codes, and manage warranty information. Each product has a unique identification code, allowing customers to scan, register, and check warranty validity using a simple client interface.

## 🚀 Features

- **Admin Dashboard:** Create and manage product groups and individual products.
- **QR Code Generation:** Automatically generate and assign QR codes to product groups.
- **Unique Product Codes:** Each product has a unique identifier for warranty tracking.
- **Warranty Activation:** Customers can scan their product and register the warranty.
- **Warranty Verification:** Check the warranty expiration date in real time.
- **Client-Side Interface:** Clean and responsive UI for customer interaction and scanning.

## 🧰 Technologies Used

### 🔧 Backend

- **Node.js & Express.js** – Backend framework
- **MongoDB & Mongoose** – Database and ODM
- **JWT** – JSON Web Token for authentication
- **Bcrypt** – Password hashing
- **Cookie-parser** – Cookie handling
- **CORS** – Cross-origin requests
- **Validation.js** – Input validation
- **Multer** – File uploads
- **Swagger** – API documentation

### 💻 Frontend

- **React.js** – Frontend framework
- **Material-UI** – Component-based UI library
- **React Router DOM** – Client-side routing
- **Context API** – State management
- **Cookies** – Manage authentication state
- **@emotion/react** – Styling
- **Print.js** – Printing QR codes and receipts
- **Localization (i18n)** – Multi-language support

## 🖼️ Demo Screenshots

### 🔧 Admin Dashboard
![Admin Dashboard](./screenshots/dashboard.png)

### 📦 QR Code on Product
![QR Code](./screenshots/qr-code.png)

### 📝 Customer Registration Page
![Client Page](./screenshots/client-register.png)


### Backend Structure
├── src/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middlewares/
│   ├── services/
│   ├── utils/
├── .env
├── server.mjs

### Frontend Structure
├── src/
│   ├── assets/
│   ├── components/
│   ├── context/
│   ├── pages/
│   ├── routes/
│   ├── services/
│   ├── i18n/
│   ├── App.js
│   └── index.js

Note: The source code for this project cannot be published publicly due to intellectual property rights and ownership restrictions. The idea and implementation belong to the original stakeholders and are protected. This repository exists only for documentation and portfolio demonstration purposes.
