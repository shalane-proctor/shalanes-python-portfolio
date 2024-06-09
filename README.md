# shalanes-python-portfolio
This repo is my amazing awesome portfolio page to showcase my accomplishments and growth as a developer

## Table of Contents
- [Introduction](#introduction)
- [Technologies](#technologies)
- [Setup](#setup)
- [Features](#features)
- [Status](#status)
- [Sources](#sources)
- [Contact](#contact)
- [License](#license)

## Introduction
This is my portfolio page to showcase my accomplishments and growth as a developer. I will be updating this page as I learn new technologies and build new projects.

## Technologies
- Python 
- FastAPI
- Heroku Deployment & Database
- Frontend: https://github.com/shalane-proctor/shalanes-amazing-portfolio
- Frontend Deployment, Vercel: https://shalanes-amazing-portfolio-h79bte4xt-shalane-proctors-projects.vercel.app/

## Setup
To run this project, install it locally using pip:
- Set up a new Python environment:  
  - Create a new Python virtual environment:
```python3 -m venv env```
  - Activate the virtual environment: 
```source venv/bin/activate```
<!--- 
THIS SECTION IS FOR FUTURE REFERENCE ON NEW PROJECTS

- Create a new file named main.py and add the following code:
```
from fastapi import FastAPI

app = FastAPI()

@app.get("/")
def read_root():
return {"Hello": "World"}
```
  - Install FastAPI: ```pip install fastapi```
  - Install Uvicorn: ```pip install uvicorn```
  - Install SQLAlchemy, an SQL toolkit and ORM: ```pip install SQLAlchemy```
  - Install asyncpg, a library to interact with PostgreSQL: ```pip install asyncpg```
  - Install Gunicorn: ```pip install gunicorn```
- Generate a requirements.txt file with the command: ```pip freeze > requirements.txt```
- Create a new file named Procfile in the root directory and add the following line: web: gunicorn -w 4 -k uvicorn.workers.UvicornWorker main:app

--->
- Install the required packages:
  - Install Requirements: ```pip install -r requirements.txt```


- Run the project: ```uvicorn main:app --reload```
## Features
