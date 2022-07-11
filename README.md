# Flask-SQLAlchemyRESTful_API
This is a Advanced Flask API that connects to an sqlite3 Database and is used to perform 4 operations: GET, POST, DELETE and PUT

In the <a href="https://github.com/n-rohit/Flask-SQLAlchemyRESTful_API/tree/main/code">code</a> folder:
- The <a href="https://github.com/n-rohit/Flask-SQLAlchemyRESTful_API/tree/main/code/models">models</a> folder stores the Database Model related code for item, store and user.
- The <a href="https://github.com/n-rohit/Flask-SQLAlchemyRESTful_API/tree/main/code/resources">resources</a> folder stores the item, store and user code related to the GET, POST, PUT and DELETE operations for the API.
- The <a href="https://github.com/n-rohit/Flask-SQLAlchemyRESTful_API/blob/main/code/app.py">app.py</a> file is where the URLs for performing the 4 RESTful operations are defined.
- The <a href="https://github.com/n-rohit/Flask-SQLAlchemyRESTful_API/blob/main/code/security.py">security.py</a> file is used to provide Authentication and Validation to the UserModel.
- The <a href="https://github.com/n-rohit/Flask-SQLAlchemyRESTful_API/blob/main/code/db.py">db.py</a> file is used to Implement SQLAlchemy through the db variable
- The <a href="https://github.com/n-rohit/Flask-SQLAlchemyRESTful_API/blob/main/code/data.db">data.db</a> file stores all the Database Tables when app.py is executed.




<i>This is an improved and a more organized version of the <a href="https://github.com/n-rohit/Flask-SQLRESTful_API">Flask-SQLRESTful_API</a> Code.</i>
