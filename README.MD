
# A litle api built with Django REST Framwork

in order to learn this new technologi (yeah it's new for me), i tryied to make up an API using django and folowing the step of the [official documentaion of Django Rest FrameWork](https://www.django-rest-framework.org/tutorial/quickstart/).  So this repo is just an implementation of what they said here.

## How to use ?

to use this, you have to follow theses simplest steps :
- clone the repo (first make sure you have installed all the requirement listed in [requirement.txt](https://github.com/hermanno18/test_django_REST_API/blob/main/requirements.txt)
- open you terminal and run : `python3 manage.py makemigrations` followed by `python3 manage.py migrate` to set your local database
- from here, you can now ;
    - symply run your server
    - add Super User (with whom you will add/access datas in the database) using the command : `python manage.py createsuperuser --email admin@example.com --username admin` (note tha you will replace the usename (default: admin) and thye email (default: admin@example.com) by any others
    - you can also just request your server using the browser (at the adress : http://127.0.0.1:8000/users/ or http://127.0.0.1:8000/groups/) or using the bash or any other application

## got issues ?

please, just mention it in the [issues sections](https://github.com/hermanno18/test_django_REST_API/issues) or you can take a look on the [official documentaion of Django Rest FrameWork](https://www.django-rest-framework.org/tutorial/quickstart/)

# thanks !