```shell
mkvirtualenv django_todo
workon django_todo
pip install django
django-admin startproject todo_api .
python manage.py startapp todos
python manage.py migrate
# add app to settings
# create models
python manage.py makemigrations todos
python manage.py migrate todos

python manage.py createsuperuser
# create tests
python manage.py test
pip install djangorestframework
# add rest_framework to settings.py
# add api permissions
# create urls and views
pip install django-cors-headers
# add corsheaders to installed_apps
# add corsheaders.middleware.CorsMiddleware and django.middleware.common.CommonMiddleware to middleware
# create CORS_ORIGIN_WHITELIST = ('localhost:3000/')
```

