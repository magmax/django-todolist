django-todolist
===============
-----------
A simple "ToDo List", built in Django and used to help and show the awesomeness of the django,
to the folks in the Python tutorial, at [Evolux](http://evolux.net.br) and [Multmeio](http://www.multmeio.com.br).

How to install e config
===============
-----------
#### Follow the steps:

1. Star this and Follow us;
2. Clone or Download this repo;
3. Install [pip](http://www.pip-installer.org/en/latest/) or [easy_install](http://pythonhosted.org/distribute/easy_install.html);
4. Install the project dependencies;
    - ```pip install -r requirements.txt``` in your root project folder.
5. Setup the ```DATABASES``` confs, inside the [settings](https://github.com/multmeio/django-todolist/blob/master/todolist/settings.py#L20) file. Sqlite example database is already provided.
6. Migrate your database's  schema, use the South's command called **migrate**
    - ```python manage.py migrate```
7. Run the tests.
    - ```python manage.py test core```
8. Run your project:
    - ```python manage.py runserver```
9. See in the localhost;
    - ```127.0.0.1:8000```

- You can change the *port* what django will run your project:
    - ```python manage.py runserver 8080``` --> ```127.0.0.1:8080```
