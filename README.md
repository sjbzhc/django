Start

#Installation
Install pip

pip3 install pipenv

pipenv install django

Use local interpreter: pipenv shell

#Create project
django-admin startproject djangotest

#Run
python manage.py runserver

#Select interpreter
get the path with pipenv --venv
Command + Shift + P >Select Interpreter
Enter interpreter path:
    path/bin/python
    
#Debug
    Click on debug
    Click on create a launch.json file
    Select Django

#Create new app
python manage.py startapp [name of app]