# Django Project Template

The clean, fast and right way to start a new Django powered website.

## Getting Started

Setup project environment with [virtualenv](https://virtualenv.pypa.io) and [pip](https://pip.pypa.io).

```bash
$ virtualenv project-env
$ source project-env/bin/activate

$ git clone https://github.com/juanifioren/django-project-template.git your-project-name
$ cd your-project-name/
$ pip install -r requirements.txt
$ cp settings_custom.py.edit settings_custom.py
$ python manage.py migrate
$ python manage.py runserver
```

Also you may want to change the name of the `projectname` module. Remember to update it inside this files `projectname/settings.py`, `manage.py` and `uwsgi.py`.
