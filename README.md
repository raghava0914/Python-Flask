if any migrations delete the migrations file from project re create by this cmds and clear the database cmds and keep it empty 



cmd make your dir change to the download project
pip install Flask-Migrate
flask db init
flask db migrate -m "Initial migration."
flask db upgrade


if you dont have any error of migrations
start your pakage installtions by this cmd
pip install -r requirements.txt

To Run this project 
flask db init
flask db migrate -m "Initial migration."
flask db upgrade
python run.py


****![image](https://github.com/raghava0914/Python-Flask/assets/143807508/293bfce1-2187-489c-98db-ab0fb7f2d414)

![image](https://github.com/raghava0914/Python-Flask/assets/143807508/58ea7266-1160-4b54-8112-3b9a45cbefd7)
