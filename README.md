# Python Tutorial For Flask

> This is a tutorial I went through while going through the Bottega course.

## Start the server
- Run the following commands in your terminal while in the `hello_flask` folder.
```
$ pipenv shell
(hello_flask) python app.py
```
- If you get an error saying it doesn't know about a package, you might need to install the packages, or you might not be in your `pipenv shell`
```
$ pipenv shell
(hello_flask) pipenv install
(hello_flask) python app.py
```

## Dependencies

- Flask
  - https://flask.palletsprojects.com/en/1.1.x/
- Flask SQLAlchemy
  - https://flask-sqlalchemy.palletsprojects.com/en/2.x/
- Flask Marshmallow
  - https://flask-marshmallow.readthedocs.io/en/latest/
- Marshmallow-sqlalchemy
  - https://marshmallow-sqlalchemy.readthedocs.io/en/latest/