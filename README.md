# python_django

# 初始化
```commandline
pip install django

python -m django --version

django-admin startproject mysite.

python manage. py startapp job_application

python manage. py runserver
```

# Set up database models
```commandline
models.py 
    Create your models here.
mysite/settings.py
    INSTALLED_APPS  add app_name job_application
    
python manage.py makemigrations

 python manage.py migrate 

```