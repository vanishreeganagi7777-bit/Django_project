# Django_project
# Drinks API – Django REST Project

## Overview
This project is a simple RESTful API built using Django and Django REST Framework. It provides basic CRUD (Create, Read, Update, Delete) operations for managing drink data.

The project is structured to demonstrate backend API development, serialization, and database integration using SQLite.

---

## Features
- RESTful API endpoints
- CRUD operations for drinks
- Django ORM integration
- JSON-based responses
- Basic template rendering support

---

## Tech Stack
- Python
- Django
- Django REST Framework
- SQLite (default database)

---

## Project Structure
```
APIRdbms/
│
├── APIRdbms/        # Project configuration
│   ├── settings.py
│   ├── urls.py
│   └── ...
│
├── Drinks/          # Main app
│   ├── models.py
│   ├── views.py
│   ├── serializers.py
│   ├── templates/
│   └── migrations/
│
├── manage.py
└── db.sqlite3
```

---

## API Endpoints

| Method | Endpoint              | Description              |
|--------|----------------------|--------------------------|
| GET    | /get_drinks/         | Retrieve all drinks      |
| GET    | /get_drinks/<id>/    | Retrieve a single drink  |
| POST   | /get_drinks/         | Create a new drink       |
| PUT    | /get_drinks/<id>/    | Update a drink           |
| DELETE | /get_drinks/<id>/    | Delete a drink           |

---

## Installation & Setup

### 1. Clone the repository
```bash
git clone https://github.com/your-username/drinks-api.git
cd drinks-api
```

### 2. Create virtual environment
```bash
python -m venv env
```

### 3. Activate virtual environment

**Windows:**
```bash
env\Scripts\activate
```

**Mac/Linux:**
```bash
source env/bin/activate
```

### 4. Install dependencies
```bash
pip install django djangorestframework
```

### 5. Apply migrations
```bash
python manage.py migrate
```

### 6. Run the server
```bash
python manage.py runserver
```

---

## Usage

Once the server is running, access the API at:

```
http://127.0.0.1:8000/get_drinks/
```

You can use tools like Postman or a browser to test the endpoints.

---

## Future Improvements
- Add authentication (JWT / Token-based)
- Improve validation and error handling
- Add pagination
- Deploy to cloud (AWS / Render / Heroku)
- Add frontend integration

---

## License
This project is for educational purposes and can be modified or extended as needed.

---

## Author
Developed as part of academic coursework and backend practice.
