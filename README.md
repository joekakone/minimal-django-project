# Minimal Web App with Django
Hello, I'm Joseph Konka, Python enthousiast. In this porject, I'm building a Minimal Webapp with Django and Deploy it on Heroku. You can see the result [here](https://minimal-django-app-jk.herokuapp.com)

## Features
1. Build Webapp with Django
2. Deploy on Heroku

## Setup environment
```sh
python3 -m venv env
source env/bin/activate
pip install -r requirements.txt
```

## Launch
```sh
python3 manage.py runserver
gunicorn app:app
```