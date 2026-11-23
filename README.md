This is based on the tutorial at https://flask.palletsprojects.com/en/stable/tutorial/

Note that the init-db did not seem to work so you can use 'sqlite3 <flaskr.sqlite schema.sql' which should do the same thing. Or run sqlite3 and manually create the tables. Also make sure the flaskr.sqlite is in the instance directory.
