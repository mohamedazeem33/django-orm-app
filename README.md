# Django ORM Web Application

## AIM
To develop a Django application to store and retrieve data from a database using Object Relational Mapping(ORM).

## DESIGN STEPS

### STEP 1:
Fork and Clone the Repositary in to your IDE

### STEP 2:
Create a Django project and an app and a superuser account the run the server.

### STEP 3:
Modify changes in settings and write ur code on models and admin and run the server.

### STEP 4:
Login in to admin using your Superuser account and populate the records.

## PROGRAM
```

from django.db import models
from django.contrib import admin
class Employee (models.Model):
   emp_id=models.CharField(primary_key=True,max_length=4,help_text='Employee ID')
   ename=models.CharField(max_length=50)
   post=models.CharField(max_length=20)
   salary=models.IntegerField()


class EmployeeAdmin(admin.ModelAdmin):
    list_display=('emp_id','ename','post','salary')

```

## OUTPUT
![django photo](https://github.com/mohamedazeem33/django-orm-app/assets/121040764/e4d2e249-ea2e-4c50-92d0-e0a44579edca)
![django output photo](https://github.com/mohamedazeem33/django-orm-app/assets/121040764/31f65f10-b41c-4c54-8667-c04bf4555251)





## RESULT
