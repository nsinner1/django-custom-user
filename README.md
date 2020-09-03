# Intro to Django

## Django Customer User

Lab: 29 - Django Customer User

*Author: Natalie Sinner and Harry Potter*

----

## Description
Django does a great job at allowing to get started with a solid foundation. But a foundation is just the beginning. We still need to “build the house.”

One of the first things many developers need to do is have a custom user.

For this lab you’ll build your application from the very beginning with a Custom User model.

Feature Tasks and Requirements
create Django application from scratch that has a custom user model named CustomUser
Custom user should use email instead of username for signup / login
Application should work with Django Admin
Implementation Notes
Make sure to create custom user model before migrating data

---

### Getting Started
Clone this repository to your local machine.

```
$ git clone [https://github.com/nsinner1/django-custom-user]
```

### To run the program from VS Code:
Select ```File``` -> ```Open``` -> ```django_customer_user```

Next navigate to the location you cloned the Repository.

Double click on the ```django_customer_user``` directory.

Then select and open ```django_customer_user```

### To run in browser:
Locate directory in terminal

Activate virtual environment:

```
poetry init 
poetry shell
```
Once in virtual environment, run command:

```
python manage.py runserver
```

Once server is running, copy and paste URL: http://127.0.0.1:8000/

---

### Change Log
***[The change log will list any changes made to the code base. This includes any changes from TA/Instructor feedback]***  
1.2: *Added username and files along with HTML* - 2 Sept 2020  
1.1: *Set up scaffolding* - 2 Sept 2020  


------------------------------
For more information on Markdown: https://www.markdownguide.org/cheat-sheet