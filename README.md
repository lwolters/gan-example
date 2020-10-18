# Product Attributes Webscraper

## Virtual Environment
First of all, create a python virtual environment<br/>
https://docs.python.org/3/tutorial/venv.html#tut-venv
```
python3 -m venv gan-example-env
source gan-example-env/bin/activate
```

## Jupyter Notebook
Create kernel (for new environment) and connect it to Jupyter. 
```
source gan-example-env/bin/activate
pip install ipykernel --no-cache-dir
python -m ipykernel install --user --name=gan-example-env
```

There is no need to reinstall jupyter for each virtual environment, but if it's the first time.
Install as follows. 
```
source pae-env/bin/activate
pip install jupyter --no-cache-dir
jupyter notebook
```

## PyCharm
You can configure IntelliJ / Pycharm and set the interpreter correctly. (Settings menu, search for interpreter)
When done with a virtual environment, simple deactivate by:
```
deactivate
```
