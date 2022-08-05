release: python manage.py migrate
web: gunicorn qrtoolkitdordrecht.wsgi
heroku ps:scale web=1