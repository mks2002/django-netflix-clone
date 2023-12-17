# django-netflix-clone
A simple full-stack clone of Netflix website using Django.


## Demo
https://morning-tree-7095.fly.dev/

If you're already familiar with Django, you don't need to follow the tutorial.
Just follow these few step:

## Setup the project
- `virtualenv venv` (make sure you have `virtualenv` installed)
- `source venv/bin/activate`
- `pip install -r requirements.txt`
- `python manage.py migrate`

## Load fixtures (Optional)
- `python manage.py loaddata netflix/fixtures/initial.json`

## Create superuser (Optional)
- `python manage.py createsuperuser`


## Start the developement server
- `python manage.py runserver`

## Run tests
- `python manage.py test`
