# PROPER STEPS TO SETUP

Pre-Setup
1. pip install virtualenv

Setup
1. Clone/Download this project
2. cd into the project directory
3. rm -rf .git (this will un-init the project so that we can link it to your heroku later)
4. source venv/bin/activate
5. pip install flask gunicorn

Heroku
1. Go to https://dashboard.heroku.com/apps
2. Create new app <----- take note of the project name

Push
1. git init
2. git add .
3. git commit -m "init"
4. heroku login
5. heroku git:remote -a {your-project-name} <---- use heroku project name
6. git push heroku master
