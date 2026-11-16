# Django Project

## 1. Project Description
This project is developed using Python and Django. It is a web-based application designed to provide the required functionality through a simple and user-friendly interface.

## 2. Technologies Used
- Python
- Django
- HTML
- CSS
- JavaScript
- SQLite Database
- Visual Studio Code
- Git and GitHub

## 3. Project Structure

```text
DjangoProject/
│
├── manage.py
├── requirements.txt
├── db.sqlite3
│
├── project/
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
│
└── app/
    ├── models.py
    ├── views.py
    ├── urls.py
    └── templates/
```

## 4. Prerequisites

Before running this project, install:

- Python
- pip
- Visual Studio Code
- Git

## 5. Installation and Setup

### Step 1: Clone the Repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

### Step 2: Open the Project Folder

```bash
cd YOUR_PROJECT_FOLDER
```

### Step 3: Create a Virtual Environment

```bash
python -m venv venv
```

### Step 4: Activate the Virtual Environment

For Windows:

```bash
venv\Scripts\activate
```

### Step 5: Install Dependencies

```bash
pip install -r requirements.txt
```

### Step 6: Apply Database Migrations

```bash
python manage.py makemigrations
python manage.py migrate
```

### Step 7: Run the Django Development Server

```bash
python manage.py runserver
```

### Step 8: Open the Application

Open your browser and visit:

```text
http://127.0.0.1:8000/
```

## 6. Git Commands

To save and upload future changes:

```bash
git add .
git commit -m "Updated project"
git push
```

## 7. Author

**Name:** Mariatt Joseph

**Course:** Master of Computer Applications (MCA)

## 8. License

This project is developed for educational purposes.
