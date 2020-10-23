web: gunicorn project.wsgi --log-file -
web: gunicorn project.wsgi:application --log-file - --log-level debug
python manage.py collectstatic --noinput
manage.py migrate
