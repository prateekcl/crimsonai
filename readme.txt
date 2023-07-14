##### Setup
pip3 install pipenv 
pip3 install sqlite3

#create folder for project
mkdir project_tracker
cd project_tracker

#activate env
pipenv install django

# create a django project
django-admin startproject project_tracker


#create database tables
python manage.py makemigrations
python manage.py migrate



##### Deploy and Run

-> activate the environment using

D:\source-code\project_tracker>pipenv shell


-> run the django server using
python manage.py runserver 9000

-> use url in browser
http://127.0.0.1:9000/projects/