# Ionic Django Integration Section

To get Django ready, be sure to do the following:

### Pull Django Backend
```
$ mkdir dev
$ cd dev
$ mkdir backend
$ cd backend
$ git clone https://github.com/codingforentrepreneurs/Django-Angular-Ionic/ .
$ pipenv install --python python3.6
$ pipenv install -r requirements.txt
$ pipenv install django-cors-headers
$ pipenv install coreapi
$ pipenv shell
$ cd src
$ python manage.py runserver
```
