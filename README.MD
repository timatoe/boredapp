# Bored App
Bored App is a web application whose purpose is to inform the users of the application when all the users are feeling bored at same time.

## Environment Setup
- Bored app is built using Flask, Flask recommends using the latest version of Python (and supports Python 3.6 and newer)
- Clone the repository and create a `venv` folder within. (do not commit the `venv` folder to the repository)
``` python3 -m venv venv ```
- Activiate the environment
``` . venv/bin/activate ```
- Install Flask
``` pip install Flask ```
- Tell the terminal the application to work with by exporting the `FLASK_APP` environment variable
``` export FLASK_APP=boredapp.py
flask run ```
- Open `http://127.0.0.1:5000/` in your browser


