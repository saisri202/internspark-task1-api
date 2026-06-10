# InternSpark Task 1 - RESTful API

This project is a RESTful CRUD API built using Node.js, Express.js, MongoDB, and Mongoose.

## Features

* Create product
* Get all products
* Get single product
* Update product
* Delete product
* Mongoose schema validation
* Error handling middleware
* Basic logging using Morgan
* Environment variables using dotenv

## Technologies Used

* Node.js
* Express.js
* MongoDB Atlas
* Mongoose
* dotenv
* cors
* morgan
* nodemon

## API Endpoints

| Method | Endpoint            | Description              |
| ------ | ------------------- | ------------------------ |
| GET    | `/`                 | Test API                 |
| POST   | `/api/products`     | Create product           |
| GET    | `/api/products`     | Get all products         |
| GET    | `/api/products/:id` | Get single product       |
| PUT    | `/api/products/:id` | Update product           |
| PATCH  | `/api/products/:id` | Partially update product |
| DELETE | `/api/products/:id` | Delete product           |

## Setup Instructions

```bash
npm install
npm run dev
```

## Environment Variables

Create a `.env` file and add:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string_here
```

## Sample Product JSON

```json
{
  "name": "Laptop",
  "price": 50000,
  "category": "Electronics",
  "inStock": true
}
```

## Author

Chandra Sai Sri
