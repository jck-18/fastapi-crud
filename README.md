# FastAPI CRUD Application

This is a simple CRUD (Create, Read, Update, Delete) API built using FastAPI and PostgreSQL, following the principles of test-driven development. The project is based on the [TestDriven.io FastAPI CRUD tutorial](https://testdriven.io/blog/fastapi-crud/) and is intended to help me understand the basics of asynchronous backend development, API design, testing, and containerization.

## Features

- Asynchronous API built with FastAPI  
- PostgreSQL integration for persistent data storage  
- RESTful endpoints for managing items  
- Pydantic for data validation and serialization  
- Pytest for unit and integration testing  
- Docker and Docker Compose for environment setup and portability  

## Tech Stack

- FastAPI  
- PostgreSQL  
- SQLAlchemy with Databases  
- Pydantic  
- Pytest  
- Docker and Docker Compose  

## Getting Started

### 1. Clone the Repository

    git clone https://github.com/your-username/fastapi-crud-app.git
    cd fastapi-crud-app

### 2. Copy the Example Environment File

    cp .env.example .env

### 3. Build and Run the App with Docker

    docker-compose up --build

### 4. Run Tests

    docker-compose exec web pytest

### 5. Access the API

Once running, visit the following in your browser:
- Swagger UI: http://localhost:8000/docs
- ReDoc: http://localhost:8000/redoc

## Project Structure

    .
    ├── app/
    │   ├── main.py          # FastAPI app entry point
    │   ├── db.py            # Database connection
    │   ├── models.py        # SQLAlchemy models
    │   ├── schemas.py       # Pydantic schemas
    │   └── crud.py          # CRUD logic
    ├── tests/               # Test cases using Pytest
    ├── Dockerfile
    ├── docker-compose.yml
    ├── .env.example
    └── README.md

## Current Status

This is a work-in-progress learning project. I am currently exploring how to extend the API, write meaningful tests, and deploy the service using a cloud platform. This project is helping me strengthen my understanding of backend API development and cloud-ready applications.

## Credits

Based on the tutorial by Michael Herman at TestDriven.io  
Tutorial link: https://testdriven.io/blog/fastapi-crud/

