# url-shortener
Visit page: https://luna-url.herokuapp.com
A URL shortner using Flask, which takes a long URL and returns a short URL. 

Tutorial based on: https://www.freecodecamp.org/news/python-tutorial-how-to-create-a-url-shortener-using-flask/ 

## How to execute 
1. Install ```pipenv``` via ```pip install pipenv --user```.
2. Create a virtual environment and activate it using ```pipenv shell```. To deactivate the virtual environment, just use ```exit```.
3. Install require packages using ```pipenv install -r requirements.txt```.
4. Run the following Flask commands.
5. After run the database initilisation, a new folder called ```migrations``` will be created. This holds the setup necessary for Alembic to run migrations against the project. Inside the ```migrations``` folder, there will be a folder called ```versions``` which contains the migration scripts as they are created. 
6. Run ```python app.py```

### Flask commands
1. ```flask db init```: Initialize the database.
2. ```flask db migrate```: Migrate the new changes to the database (to be used everytime you make changes to the models).
3. ```flask db upgrade```: Upgrade the database to the latest version.