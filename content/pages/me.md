*  Create a new environment, and install Django into it `pipenv install django` 
*  Enter into that virtual environment with the command `pipenv shell`. You should see the command prompt change slightly
*  Start a new Django Project `django-admin startproject project .`
*  If not prompted by VS Code, install pylint for this project `pipenv install pylint`  + create  `.pylintrc` 
*  Run the initial migrations for the app, to create all the default tables `python manage.py migrate`
*  Start the App `python manage.py runserver`
*  Visit the landing page at `localhost:8000` to check all is running successfully
* Create a super user for the admin app, `python manage.py createsuperuser` answer prompts using sensible defaults
* Navigate to the admin site at `localhost:8000/admin` and login in with your super user credentials 