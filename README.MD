#Установка
python3.8 -m venv venv && source venv/bin/activate && pip install -r requirements.txt && python manage.py migrate && python manage.py runserver
#UI доступен по адресу http://localhost:8000/api