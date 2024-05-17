python -m venv env

source env/Scripts/activate

pip install django==3.0.7

python -m pip install --upgrade pip

django-admin startproject carzone .

python manage.py runserver

python manage.py startapp pages  # it will create pages dir in project
