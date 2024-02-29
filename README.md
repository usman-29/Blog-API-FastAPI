# Blog API with FastAPI and JWT Tokens

This project implements a Blog API using FastAPI, a modern, fast (high-performance), web framework for building APIs with Python 3.7+ based on standard Python type hints. This API leverages JWT (JSON Web Tokens) for secure authentication and authorization.

## Features

- **FastAPI**: Utilizes FastAPI for efficient and high-performance API development.
- **JWT Tokens**: Implements JWT tokens for secure authentication and authorization.
- **CRUD Operations**: Supports CRUD (Create, Read, Update, Delete) operations for managing blog posts.
- **User Authentication**: Provides endpoints for user authentication and management.
- **Data Validation**: Utilizes Pydantic models for data validation and serialization.

## Requirements

- Python 3.10+
- fastapi
- uvicorn
- sqlalchemy
- passlib
- bcrypt
- python-jose
- python-multipart

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/usman-29/Blog-API-FastAPI.git

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Set up virtual environment.

4. Run the application:

   ```bash
   uvicorn blog.main:app --reload
   ```

## Configuration

Ensure that you set up the necessary environment variables:

- `SECRET_KEY`: Secret key for JWT token encryption.
- `DATABASE_URL`: URL for connecting to the database.

## Usage

Once the application is running, you can access the API documentation and test the endpoints by navigating to `http://localhost:8000/docs`.


## Contributing

Contributions are welcome! Feel free to submit pull requests or open issues for any improvements or feature requests.

---

Feel free to reach out with any questions or feedback. Happy coding! 🚀