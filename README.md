# django-vscode-baseproject
Basic structure for django development in VSCode 

This is a django baseproject with settings for vscode already included.

## VSCode settings do the following:

### Hide django files and folders that are never really modified directly, such as:

• Migrations Folders

• \_\_init\_\_.py

• db.sqlite3

• manage.py

• requirements.txt

• \_\_pycache\_\_

• .vscode (Folder)

• venv


### Sets python path to "venv/bin/python"

### Enables unitest

## Cloning this baseproject

#### To clone this baseproject, do the following: 

Create the project directory using the terminal
```
mkdir ProjectName
cd ProjectName
```
Clone this repo
``` 
git clone https://github.com/jash-26/django-vscode-baseproject .
```
Create venv with pip files
```
python -m venv venv
pip install -r requirements.txt
```

Django development environment is now ready, you can run: 
```
./manage.py runserver
```

Virtual environment will be activated once you open a python file.

### Full command
```
mkdir ProjectName
cd ProjectName
git clone https://github.com/jash-26/django-vscode-baseproject .
python -m venv venv
pip install -r requirements.txt
./manage.py runserver
```






