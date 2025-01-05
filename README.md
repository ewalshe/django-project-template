# Django Website Template 


```
poetry init
poetry config virtualenvs.in-project true --local
poetry env use 3.12
poetry add django
poetry add django-types django-stubs-ext
# poetry add --group dev pytest pytest-cov bandit black flake8 mypy pylint
poetry add --group dev pytest pytest-cov bandit black
poetry shell
emulate bash -c '. /Users/eamon/Code/Play/django-project-template/.venv/bin/activate'
poetry install
django-admin startproject django_website .
poetry run python3 manage.py startapp pages

```

Edit `django_website/settigns.py` and append "pages" to the INSTALLED_APPS list.
