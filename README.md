# car-dealership
car dealership

pip install virtualenv

virtualenv venv

cd venv

scripts\activate

running scripts is disabled on this system => Powershell
Set-ExecutionPolicy RemoteSigned

pip install django

django-admin startproject dealership .

python manage.py runserver


git config --global user.name "Mona Lisa"

git config --global user.email "usnermae@gmail.com"
git config --global user.password ""

python manage.py startapp listings

python manage.py createsuperuser
