# djangotutorial
followind django tutorial step by step from the original site
## installation
1. Clone project
```
git pull git@github.com:sergegamb/djangotutorial.git
```
2. Deploy virtual environment
```
python -m venv venv
```
3. Install dependancies
```
pip install -r requirements.txt
```
4. Apply migrations
```
python manage.py migrate
```
5. Run development server
```
python manage.py runserver
```
## development
### part 1
The project was created and polls app started. First view was added and routing was set up.
### part 2
In part two we were working with database and migrations. We created our first model and played with django database api in a shell mode. Also we registered our model to admin part of the site
### part 3
In that part we were working with Django Template system and learn about rendring and some shortcuts
### part 4
In that part we create simple form to vote and switched our views to generic
### part 5
Part five introduce a test suite in Django
