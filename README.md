# Blog API

A Django-based Blog Application developed as part of my Python Backend Development Industrial Attachment at BD Calling Academy.

## Project Overview

A simple blog application built using Python and Django.

## Features

- Manage blog posts through Django Admin.
- Store post titles and descriptions.
- Display blog posts on the homepage.
- Database operations using Django ORM.

## Technologies Used

- Python
- Django
- SQLite
- HTML
- python-dotenv

## Project Structure

    blog_api/
    ├── blog/
    │   ├── migrations/
    │   ├── templates/
    │   │   └── home.html
    │   ├── admin.py
    │   ├── models.py
    │   ├── urls.py
    │   └── views.py
    ├── config/
    │   ├── settings.py
    │   ├── urls.py
    │   ├── asgi.py
    │   └── wsgi.py
    ├── .gitignore
    ├── manage.py
    ├── requirements.txt
    └── README.md

## Installation

### 1. Clone the repository

    git clone https://github.com/mdsagurali/blog_api.git
    cd blog_api

### 2. Create virtual environment

    python -m venv venv
    source venv/bin/activate

### 3. Install dependencies

    pip install -r requirements.txt

### 4. Configure environment variables

Create a `.env` file in the project root:

    SECRET_KEY=your-secret-key

### 5. Run migrations

    python manage.py migrate

### 6. Create superuser

    python manage.py createsuperuser

### 7. Start development server

    python manage.py runserver

Homepage: http://127.0.0.1:8000/

Admin: http://127.0.0.1:8000/admin/

## Author

**Md Sagur Ali**

GitHub: https://github.com/mdsagurali

LinkedIn: https://www.linkedin.com/in/mdsagurali/
