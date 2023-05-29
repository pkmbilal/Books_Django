
# Book Project

Its a small project created under Python Django. It acts as a small library with books informations.




## Requirements

- Python 3 or higher
- Django 4.2.1
## Prerequisites
- Install Python
```bash
  $ sudo apt install python3
```
- Create an environment
```bash
  $ python3 -m venv venv
```
- Activate environment
```bash
  source env/bin/activate
```
- Install dependencies
```bash
  $ (venv)  python -m pip install -r requirements.txt
```
- Make migrations
```bash
  $ (venv)  python3 manage.py makemigrations
```
- Migrate models
```bash
  $ (venv)  python3 manage.py migrate
```
- Run the project
```bash
  $ (venv)  python3 manage.py runserver
```