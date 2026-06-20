release: python manage.py migrate && python manage.py collectstatic --noinput
web: gunicorn fsib_website.wsgi
