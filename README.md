# Django on Docker - Django, Postgres & Docker

- This project is about a custom BoilerPLate for Django with docker and Postgres
- Uses [Toturial Site ](https://testdriven.io/blog/dockerizing-django-with-postgres-gunicorn-and-nginx/)trends

## Dependencies

- Django 3.8
- Postgres 12
- Docker

To run the Docker Image, run:

```json
docker-compose up -d --build
docker-compose exec web python manage.py migrate --noinput
docker-compose exec web python manage.py createsuperuser
```
