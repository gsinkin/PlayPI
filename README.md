PlayPI
======

Playtime API.


Getting Started for Development
-------------------------------
1. Create a virtual environment (e.g. virtualenv --no-site-packages playpi)
2. Activate your virtual environment (e.g. source ~/playpi/bin/activate)
3. Install project dependencies (pip install -r requirements)
4. Create a local postgres user (createuser playpi -U postgres)
5. Create a local postgres database (createdb playpi\_db -U playpi)
6. Run the server (python manage.py runserver)
