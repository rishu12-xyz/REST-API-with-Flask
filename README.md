# Flask REST API – User Management

## Overview
This Flask application provides a REST API to manage user data. It supports basic CRUD operations:
- **GET** all users or a specific user
- **POST** a new user
- **PUT** to update a user
- **DELETE** a user

## How to Run

1. Install Flask:
```bash
pip install Flask
```

2. Start the server:
```bash
python app.py
```

3. Use Postman, Curl, or browser to test:

### Endpoints:
- `GET /users` → List all users
- `GET /users/<id>` → Get user by ID
- `POST /users` → Add new user (requires JSON: `{ "name": "X", "email": "Y" }`)
- `PUT /users/<id>` → Update user info
- `DELETE /users/<id>` → Delete user

## Example POST (using Curl):
```bash
curl -X POST -H "Content-Type: application/json" -d '{"name":"Charlie", "email":"charlie@example.com"}' http://127.0.0.1:5000/users
```

## Output
JSON responses for each operation.

## Key Concepts
- REST API development
- HTTP Methods: GET, POST, PUT, DELETE
- In-memory data management
# Flask REST API – User Management

## Overview
This Flask application provides a REST API to manage user data. It supports basic CRUD operations:
- **GET** all users or a specific user
- **POST** a new user
- **PUT** to update a user
- **DELETE** a user

## How to Run

1. Install Flask:
```bash
pip install Flask
```

2. Start the server:
```bash
python app.py
```

3. Use Postman, Curl, or browser to test:

### Endpoints:
- `GET /users` → List all users
- `GET /users/<id>` → Get user by ID
- `POST /users` → Add new user (requires JSON: `{ "name": "X", "email": "Y" }`)
- `PUT /users/<id>` → Update user info
- `DELETE /users/<id>` → Delete user

## Example POST (using Curl):
```bash
curl -X POST -H "Content-Type: application/json" -d '{"name":"Charlie", "email":"charlie@example.com"}' http://127.0.0.1:5000/users
```

## Output
JSON responses for each operation.

## Key Concepts
- REST API development
- HTTP Methods: GET, POST, PUT, DELETE
- In-memory data management

## Postman Collection

You can test this API using the included Postman Collection file:
📁 `User_API_Postman_Collection.json`

### How to Use:
1. Open Postman.
2. Click **Import** > **Upload Files**.
3. Select `User_API_Postman_Collection.json`.
4. Use the pre-configured requests to test:
   - GET all users
   - GET user by ID
   - POST new user
   - PUT update user
   - DELETE user  
