# 🛒 E-commerce Backend API

This is a backend API built for an e-commerce platform using **Node.js**, **Express.js**, and **MongoDB**. It supports product creation, listing, filtering, and more.

---

## 🚀 Tech Stack

- Node.js  
- Express.js  
- MongoDB  
- Mongoose  
- Cloudinary (for image upload)

---

## 📦 Installation (Run Locally)

### 1. Clone the Repository

```bash
git clone https://dredsoft-labs-admin@bitbucket.org/dredsoft-labs/ecommerce.git


cd ecommerce
npm install
npm install react-material-ui-carousel --save --legacy-peer-deps

PORT=4000
MONGO_URI=<your-mongo-uri>
CLOUDINARY_NAME=<your-cloudinary-name>
CLOUDINARY_API_KEY=<your-cloudinary-api-key>
CLOUDINARY_SECRET=<your-cloudinary-secret>

npm start

Visit the application in your browser:
http://localhost:3000


Get All Products
GET /api/v1/products

Get Product by ID
GET /api/v1/product/:id

Filter Products by Category
GET /api/v1/products?category=Apparel

Create a New Product (Admin Only)
POST /api/v1/admin/product/new

{
  "name": "Test Product",
  "price": 59.99,
  "description": "Nice one",
  "category": "Apparel",
  "brandname": "Nike",
  "logo": "<base64 image>",
  "images": ["<base64 image>"],
  "specifications": ["{\"key\":\"Size\",\"value\":\"M\"}"]
}
