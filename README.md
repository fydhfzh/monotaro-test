# monotaro-test

## General Guide
To run this app, you need to use Python (I'm using Python 3.12.0) and pip along with venv to isolate the environment during the development. I provide the requirements.txt file for all the package needed for running this application.

Create virtual environment first using venv before you install the related packages inside requirements.txt file
```
python -m venv env
```
and activate current environment by running this command below:
```
.\env\Scripts\activate.bat # Command Prompt
.\env\Scripts\activate.ps1 # Powershell
source ./env/bin/Activate # Linux / MacOS
```
After activating the environment, you can install the requirement by using this command:
```
pip install -r requirements.txt
```
Running this application would require you to access the ```manage.py``` file inside the ```app``` directory, so do ```cd app``` and run: 
```
python manage.py makemigrations
python manage.py migrate
python manage.py runserver
```
