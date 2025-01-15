# ecommerce
Ecommerce site build in django using django oscar

# Django-Oscar Project Setup

This guide provides instructions for setting up and running a Django-Oscar project. Follow the steps below to get the project up and running.

---

## Prerequisites

Before starting, ensure you have the following installed:

- Python 3.8+  
- pip (Python package installer)  
- Virtualenv (optional but recommended)  
- Git (optional for cloning the repository)

---

## Setup Instructions

### 1. Clone the Repository
If you haven't already, clone the project repository:
```bash
git clone <repository-url>
cd <repository-folder>
```
### 2. Create and Activate a Virtual Environment
It's recommended to use a virtual environment to manage dependencies:
```bash 
# Create a virtual environment
python -m venv venv

# Activate the virtual environment
# On Windows:
venv\Scripts\activate
# On macOS/Linux:
source venv/bin/activate

```

### 3. Install Requirements
Install the dependencies from the requirements.txt file:
```bash
pip install -r requirements.txt
```

### 4. Use the Provided Database
The project comes with a pre-configured database file (db.sqlite3). Ensure it is in the root of your project directory.

If you make changes to models and need to update the database schema, apply migrations:
```bash
python manage.py makemigrations
python manage.py migrate
```

### 5. Run the Development Server
Start the Django development server:

```bash
python manage.py runserver
```
By default, the server will run at http://127.0.0.1:8000/.

