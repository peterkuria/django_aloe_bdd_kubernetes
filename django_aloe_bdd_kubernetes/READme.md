# Behavior-Driven Development with Django and Aloe

## Want to use this project?

1. Fork/Clone/ or start afresh from local PC/ MAC

$ django-admin startproject django_aloe_bdd_kubernetes

$ cd django_aloe_bdd_kubernetes
$ ls django_aloe_bdd_kubernetes

# to view the project

PS C:\Users\peter\source\repos\django_aloe_bdd_kubernetes>

1. Create and activate a virtualenv

$ pipenv --three
$ pipenv shell




1. Install the requirements

$ pipenv install aloe-django==0.1.3, Django==2.1.7, djangorestframework==3.9.2


1. Run the tests:

    ```
    $ cd django_aloe_bdd_kubernetes
    $ python manage.py harvest
    ```


    ## Django app

django-admin startproject projectname

django-admin startproject django-app01

$ django-admin startproject projectname
django-admin startproject mysite
ls 

CD mysite

python manage.py startapp hello

ls

CD hello



## to run the django server from the parent directory: this way python will know the route

mysite$
$ python manage.py runserver


## create models without testing

$ python manage.py makemigrations



under project urls.py, edit and add a route connector such as:
path('app1', include('app1.urls')),

==========================================================
