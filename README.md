## House-Pricing-App


Create a virtual environment for this project :
```
python -m venv ./venv
```

To activate the virtual environment:
```
.\venv\Scripts\activate
```

To list the working environment dependencies:
```
pip list
```

generate a text file listing all your project dependencies:
```
pip freeze > requirements.txt
```

Instead of having to install each dependency one by one, they could just run the code below to install all your dependencies within their own copy of the project.
```
pip install -r requirements.txt
``` 

Deactivate a Virtual Environment
```
deactivate
``` 

Run the flask app
```
python app.py
```