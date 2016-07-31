# simple_api_dj
demonstrate using django and djangorestframework

How to setup

1. git clone <this-git-url>
2. create virtualenv with requirements file
  2.1 virtualenv env-simple-api && activate env-simple-api
  2.2 pip install -r requrements.txt
3. run needed task
  3.1 python manage.py makemigrations && python manage.py migrate
  3.2 python manage.py createsuperuser # follow instruction
  3.3 python manage.py runserver
  
How to use

curl or http to localhost:8000/users/
