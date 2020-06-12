# Graduation Project

## fury-backend-python Web Application

### Getting Started

These instructions will get you a copy of the project up and running on your local machine for development purpose.

### Prerequisites
  ###Requirements
- pip 9.0.1 
- python 3.6

### Installing

You'll need to have a virtual environment installed on your machine

    pip3 install virtualenv
### Go to the directory where the manage.py file is located
Setup virtual environment

    virtualenv -p python3.6 .virtualenv

Activate virtual environment

    source .virtualenv/bin/activate

Install the requirements

    pip install -r requirements


If there are any errors try installing the packages manually:
- Update python to latest \n
- Update pip \n
- pip install django
-pip install django_rest_framework
Debug the rest :-#

    

Make migrations, createsuperuser and run the server

    python manage.py makemigrations
    python manage.py migrate
    python manage.py createsuperuser
    python manage.py runserver

### Built With

    Python - Programming language used
    django-rest-swagger - Used to generate documentation for all the endpoints
### End Points   

-/api/status: 
            - parameters:Hashtags: # ,UserHandle:@ 
