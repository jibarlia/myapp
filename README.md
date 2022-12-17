# My App
Django boilerplate application


## create default admin user

1- set local environment variables in root folder  

export DJANGO_DB_NAME=myapp;  
export DJANGO_DB_PASSWORD=<custom_passw>;  
export DJANGO_SETTINGS_MODULE=myapp.settings  
export DJANGO_DB_USER=<app_user>;  

2- Run the command and follow the instructions:  

python manage.py createsuperuser 