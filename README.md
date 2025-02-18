# Full-Stack FastAPI & React Example

This repository provides a comprehensive example of building a full-stack web application using FastAPI for the backend and React for the frontend. It demonstrates how to integrate these two powerful technologies to create modern, responsive web applications.

## Project Overview

This project aims to showcase:

*   A well-structured FastAPI backend with API endpoints.
*   A React frontend with a clear component-based architecture.
*   Seamless communication between the frontend and backend using HTTP requests.
*   A simple example application that demonstrates basic CRUD operations.
*   Example Docker and Docker Compose file.

# Getting Started

Follow these steps to get the project up and running on your local machine:

## Prerequisites

Before you begin, ensure you have the following installed:

*   Python 3.7+
*   Node.js and npm (or yarn)
*   Docker (optional, but recommended for easy deployment)

## Installation

1.  Clone the repository:

    ```bash
    git clone https://github.com/JeremyTsaii/fastapi-react-fullstack-example.git
    cd fastapi-react-fullstack-example
    ```

2.  **Backend Setup (FastAPI):**

    ```bash
    cd backend
    python -m venv venv
    source venv/bin/activate  # On Linux/macOS
    # venv\Scripts\activate  # On Windows
    pip install -r requirements.txt
    ```

3.  **Frontend Setup (React):**

    ```bash
    cd ../frontend
    npm install  # or yarn install
    ```

## Running the Application

1.  **Backend (FastAPI):**

    ```bash
    cd ../backend
    uvicorn main:app --reload
    ```

2.  **Frontend (React):**

    ```bash
    cd ../frontend
    npm start  # or yarn start
    ```

3.  **Accessing the Application:**

    *   The React frontend will typically be accessible at `http://localhost:3000`.
    *   The FastAPI backend API endpoints will be accessible at `http://localhost:8000`. You can view the interactive API documentation at `http://localhost:8000/docs`.  See the [FastAPI documentation](https://fastapi.tiangolo.com/) for more details.

## Key Technologies

*   [FastAPI](https://fastapi.tiangolo.com/): A modern, high-performance, web framework for building APIs with Python 3.7+ based on standard Python type hints.
*   [React](https://reactjs.org/): A JavaScript library for building user interfaces.
*   [Uvicorn](https://www.uvicorn.org/): An ASGI server implementation for running Python web applications.
*   [Docker](https://www.docker.com/): A platform for building, shipping, and running applications in containers.
