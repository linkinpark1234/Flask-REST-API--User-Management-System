##### User Management API

A RESTful API built using Flask, Flask-RESTful, and SQLAlchemy to perform CRUD operations on users.

# Features

* Create User
* Get All Users
* Get User by ID
* Update User
* Delete User

# Tech Stack

* Python
* Flask
* Flask-RESTful
* SQLAlchemy
* SQLite


# API Endpoints

| Method | Endpoint        | Description    |
| ------ | --------------- | -------------- |
| GET    | /api/users/     | Get all users  |
| POST   | /api/users/     | Create user    |
| GET    | /api/users/<id> | Get user by ID |
| PATCH  | /api/users/<id> | Update user    |
| DELETE | /api/users/<id> | Delete user    |

# Sample Request (POST)

```json
{
  "name": "John",
  "email": "john@example.com"
}
```

# Author
Vitthal Ganesh
