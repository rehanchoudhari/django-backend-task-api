# django-backend-task-api

## Overview

Django Task API is a RESTful API built using Django and Django REST framework for managing tasks.

## Features

- Create, Read, Update, and Delete tasks
- Mark tasks as completed or incompleted
- API endpoints for managing tasks

## Prerequisites

- Python 3.x
- Django
- Django REST framework

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/rehanchoudhari/django-backend-task-api.git
   cd django-backend-task-api


Create a virtual environment: 

python -m venv venv
source venv/bin/activate  # On Linux/Mac
# Or on Windows: .\venv\Scripts\activate



Install dependencies: 

pip install -r requirements.txt


Apply migrations:

python manage.py migrate


Run the development server:

python manage.py runserver

The API will be available at http://localhost:8000/api/task/

API Endpoints
List Tasks: GET /api/task/todo/
Create Task: POST /api/task/todo/
Retrieve Task: GET /api/task/todo/{task_id}/
Update Task: PUT /api/task/todo/{task_id}/
Delete Task: DELETE /api/task/todo/{task_id}/
