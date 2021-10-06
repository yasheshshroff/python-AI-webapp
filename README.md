# Python-AI-webapp
A simple Python AI web app in Flask

Set the following env variables:
- On Bash/Zsh
    - `export FLASK_APP=app.py`
    - `export FLASK_ENV=development`

Modified from [this](https://docs.microsoft.com/en-us/learn/modules/python-flask-build-ai-web-app/2-flask-fundamentals) reference.

Recommended patterns from [Flask](https://flask.palletsprojects.com/en/1.1.x/patterns/packages/#simple-packages) tutorial:
- Flask app can be in the root folder as `app.py`
- For larger projects, recommended pattern is to have it as `app/__init__.py`
- This requires a `setup.py` file, which has been created
