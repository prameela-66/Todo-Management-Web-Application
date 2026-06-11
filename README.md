# Todo-Management-Web-Application

A full-stack task management web application built using Django and SQLite. The application allows users to create, update, delete, and track tasks efficiently.

## Features

* Create new tasks
* Edit existing tasks
* Delete tasks
* Mark tasks as completed
* Automatic completion timestamp tracking
* View active and completed tasks
* Persistent data storage using SQLite
* Clean and responsive user interface

## Tech Stack

* Python
* Django
* SQLite
* HTML
* CSS
* Django Templates

## Installation

1. Clone the repository:

```bash
git clone https://github.com/prameela-66/Todo-Management-Web-Application.git
```

2. Navigate to the project folder:

```bash
cd todo-app
```

3. Install dependencies:

```bash
pip install -r requirements.txt
```

4. Run migrations:

```bash
python manage.py migrate
```

5. Start the development server:

```bash
python manage.py runserver
```

6. Open your browser and visit:

```
http://127.0.0.1:8000/
```

## Project Structure

* Models: Task data management
* Views: Business logic
* Templates: User interface
* URLs: Route handling
* SQLite: Database storage

## Future Enhancements

* User authentication
* Task priorities
* Due dates and reminders
* Search and filtering
* REST API integration


