# 📘 Assignment: Building REST APIs with FastAPI

## 🎯 Objective

In this assignment, students will learn how to build RESTful APIs using the FastAPI framework in Python. Students will practice creating endpoints, handling request data, and returning JSON responses.

## 📝 Tasks

### 🛠️ Create a Basic FastAPI Application

#### Description
Set up a FastAPI project and create a simple API with at least three endpoints that handle different HTTP methods.

#### Requirements
Completed program should:

- Install and configure FastAPI and Uvicorn
- Define at least one GET endpoint that returns a JSON response
- Define at least one POST endpoint that accepts JSON input and returns a response
- Include a root endpoint (`/`) that returns a welcome message
- Be runnable with `uvicorn main:app --reload`


### 🛠️ Add Data Validation with Pydantic

#### Description
Use Pydantic models to validate incoming request data and structure response data for your API.

#### Requirements
Completed program should:

- Define at least one Pydantic model for request data
- Validate that required fields are present in POST requests
- Return appropriate HTTP error responses (e.g., 422) for invalid input
- Include at least one optional field with a default value in a Pydantic model
