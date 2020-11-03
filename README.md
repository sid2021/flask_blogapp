[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://ancient-ocean-25199.herokuapp.com/)

# Flask blog app

This is a web blog application utilizing Python Flask framework for backend as well as a little bit of JavaScript for the frontend side. App is build with _Test-Driven Development (TDD)_ in mind for which it utilizes **pytest**.

App is based on [Flaskr - Intro to Flask, Test-Driven Development, and JavaScript tutorial](https://github.com/mjhea0/flaskr-tdd).

For your convenience app is also deployed to Heroku.

## Built With

- [Flask](https://flask.palletsprojects.com/en/1.1.x/)
- [SQLAlchemy](https://www.sqlalchemy.org/)
- [SQLite](https://www.sqlite.org/index.html)
- [Bootstrap](https://getbootstrap.com/)
- [Jinja](https://jinja.palletsprojects.com/en/2.11.x/)
- [Pytest](https://docs.pytest.org/en/stable/)
- HTML5
- CSS3

## Installation

```
$ git clone https://github.com/sid2021/flask-blogapp.git
$ cd flask-blogapp
```

If you want to use virtualenv (on Windows):

```
$ python3 -m venv env
$ venv\Scripts\activate
```

If you want to use virtualenv (on MacOS/Linux):

```
$ python -m venv venv
$ source env/bin/activate
```

Install dependencies, set FLASK-APP environment variable and run app (on Windows):

```
$ pip install -r requirements.txt
$ $env:FLASK_APP="project/app.py"
$ flask run
```
