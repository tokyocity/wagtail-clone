"# wagtail-clone"

pip install wagtail
pip show wagtail
wagtail start blog
pip install -r requirements.txt
python manage.py makemigratinos
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver

python manage.py startapp images
