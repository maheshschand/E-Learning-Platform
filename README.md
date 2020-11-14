# E-Learning Platform
E-Learning Platform created using Django framework.

## Features
- Creating, editing, deleting courses, modules and it's contents.
- Created a Content Management System (CMS).
- Built a student registration system.
- Manage student enrollment onto courses.
- Built a RESTful API for retrieving subjects, available courses and enroll on a course.
- Cached the content using Django cache framework.
- Monitored Memcached using the django-memcache-status

## Demo
[E-Learning Platform](https://elearning-suven.herokuapp.com/)

## Run project locally
1. Clone the project  
    ```bash
    git clone https://github.com/maheshschand/E-Learning-Platform.git 
    ```
2. Create a virtual evironment
    ```bash
    python -m venv venv
    ```
3. Activate your virtual environment  
    **For Windows**
    ```powershell
    cd venv\Scripts
    activate
    ```

    **For linux**
    ```bash
    source venv/bin/activate
    ```
    The shell prompt will include the name of the active virtual environment enclosed in parentheses, as follows:
    ```bash
    (venv) $
    ```
4. Locate the E-Learning-Platform folder and run the following command
    ```bash
    (venv) $ pip install -r requirements.txt
    ```
5. Migrate the database
    Run the following command to migrate the database.
    ```bash
    (venv) $ python manage.py migrate
    ```
6. Create a administrator account
    Run the following command to create a super user
    ```bash
    (venv) $ python manage.py createsuperuser
    ``` 
7. Run the development server
    Run the following command to turn on the development server
    ```bash
    (venv) $ python manage.py runserver
    ```
    Enter in the browser: http://127.0.0.1:8000