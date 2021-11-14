## Setup database
- $ psql -U admin -h localhost -p 5432 -d postgres 

## Configure
- add psycopg2-binary==2.9.2 to requirements.txt
- $ pip3 install -r requirements.txt
- add database environment variables to .env file
- update DATABASES in settings.py
- create user model and update settings.py
- create migrations and migrate
- create superuser
- register User model in users/admin.py
- check /admin
