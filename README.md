## Initialization

1. Run `pip install -r requirements.txt`
2. Login into the mysql and run `CREATE DATABASE sluphur`
3. Now, import dp by running `mysql -u <your_mysql_username> -p sulphur > sulphur.sql`
4. Change USER and PASSWORD to your mysql user and password in the sulphur/settings.py
5. Run `python manage.py migrate`
6. Now, start your server using `python manage.py runserver`
