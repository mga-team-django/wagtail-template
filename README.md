{% if False %}
# Django 1.11 Base Template #

## About ##

This template is used by developer at Mirounga

## Features ##

By default, this project template includes:

Wagtail:

- Wagtail 1.13

Migrations:

- Django built-in migrations

Caching:

- python-memcached

Admin:

- Includes django-debug-toolbar for development and production (enabled for superusers)

## How to use this project template to create your project ##

- Create your working environment and virtualenv
- Install Django 1.11
- pip install Django 1.11
- $ django-admin.py startproject --template https://github.com/mga-team-django/wagtail-template/archive/master.zip --extension py,html,md,rst projectname
- $ cd projectname
- By default dev environment use SQLite database
- $ pip install -r dev-requirements.txt
- $ python manage.py migrate
- $ python manage.py runserver

{% endif %}
# The {{ project_name|title }} Project #

## About ##

Describe your project here.

## Prerequisites ##

- Python 3.5 recommended
- pip
- virtualenv (virtualenvwrapper is recommended for use during development)

## Installation ##

Fill out with installation instructions for your project.


License
-------

Indicate your licence here
