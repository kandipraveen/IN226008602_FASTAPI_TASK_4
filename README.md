# FastAPI Cart System – Internship Assignment

This project is developed as part of the February 2026 FastAPI Internship Training.

## Features
- Add products to cart
- Update quantity of existing cart items
- View cart with grand total
- Remove items from cart
- Checkout cart items
- View placed orders

## Technologies Used
- Python
- FastAPI
- Uvicorn
- Swagger UI

## API Endpoints
POST /cart/add – Add items to cart  
GET /cart – View cart details  
DELETE /cart/{product_id} – Remove item  
POST /cart/checkout – Checkout cart  
GET /orders – View orders

## Running the Project

Install dependencies

pip install fastapi uvicorn

Run the server

uvicorn main:app --reload

Open Swagger UI

http://127.0.0.1:8000/docs
