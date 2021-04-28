#Project Description

The Project is built on Python-Django Framework

The Project is combination of Django CRUD Operation, Django CMS, and Django Rest Framework.

The Project Contains Signup and Login with Django Forms.

The Project is based on User and Product. where a user/admin can add multiple users and its multiple products.
The user/admin can add, update , delete the Products.
The User/Admin Can add Django cms plugins and can also add Custom Plugins.

The Project also have rest APIs where user can list, add, update, delete, search and filter the Products

##Prerequisites

- Python 3 or greater versions
- MySql

### Recommended tools

Creating a virtual python environment dedicated for this application is strongly recommended to prevent your local system from breaking unexpectedly.

$ pyenv install 3.6.9
$ pyenv virtualenv 3.6.9 environment_name

### Setting up

1. Prep MySQL user for this application.

    mysql

        mysql> CREATE SCHEMA database_name CHARACTER SET utf8mb4;
        mysql> GRANT ALL PRIVILEGES ON databse_name.* TO 'root'@'localhost';
        mysql> FLUSH PRIVILEGES;


2. Clone repository from master branch and confirm virtual env.

        $ cd folder_name
        $ python --version
        

3. Run `pip install -r requirements.txt`



4. Run following django **management** commands.

        $ python ./manage.py migrate

5. python manage.py createsuperuser
        
6. Run `python ./manage.py runserver` and visit http://localhost:8000

7. Run http://127.0.0.1:8000/en/showUser/ to see list of users, perform CRUD operations

8. Run http://127.0.0.1:8000/en/showProduct/ to see list of users and perform CRUD operations

9. Run http://127.0.0.1:8000/en/api/ to see Django Rest APIs and peroform CRUD operations, searching, Sorting & Filters

10. You can add Django cms plugins into the Website.
