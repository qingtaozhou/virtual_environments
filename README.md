### in project1:
```
python -m venv env
source env/bin/activate
pip list
pip install pandas
pip freeze
pip freeze > requirements.txt
deactivate
```

### in project2:
```
python -m venv env
source env/bin/activate
pip install -r requirements.txt
pip list
deactivate
```
