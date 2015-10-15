# classical-ragas
Repo for the DBMS app

# Important Instructions
1. Please don't commit directly to the master branch so as to have at least one instance of the code which works.
2. Please commit by making your own branches and sending PR's from there. [Help on making branches](https://help.github.com/articles/creating-and-deleting-branches-within-your-repository/) [Help on creating PR](https://help.github.com/articles/creating-a-pull-request/)
3. Merge PR's only when sure that the code works.

## How to run the app
```
pip install -r requirements.txt
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver
```