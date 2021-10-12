# Django_test_site
Сайт с новостями на джанго
Running the Project Locally
First, clone the repository to your local machine:

git clone https://github.com/suhailvs/django-schools
Create Virtual Env and Install the requirements:

cd django-schools
python3 -m venv env
source ./env/bin/activate
pip install -r requirements.txt
Create the database and run the development server:

cd django_school
python manage.py migrate
python manage.py loaddata datas.json
python manage.py runserver
The project will be available at http://127.0.0.1:8000,
login: adm pass: adm
