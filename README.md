# ICFOSS-task-
authentication page
## Overview
 This web page enable users to log in using their registered username and password , if user is not registered , they can register.
## Installation
1. **Clone the repository:**
2. **Set up a virtual environment:**
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```
3. **Apply database migrations:**
    ```bash
    python manage.py migrate
    ```
4. **Create a superuser (optional):**
    ```bash
    python manage.py createsuperuser
    ```
5. **Run the development server:**
    ```bash
    python manage.py runserver
    ```
6. Open your browser and go to `http://127.0.0.1:8000/` to see the project in action.

## Configuration
- **DATABASES:** - SQLite
