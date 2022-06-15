# FastAPI-simple-crud-with-mysql

### About The Project
This simple project is adapted from [SQL (Relational) Databases](https://fastapi.tiangolo.com/tutorial/sql-databases/). Original tutorial includes only Create and Read operations. Delete operation has been added.

## Built With

* Python 3.10
* FastAPI
* MySQL

## Getting Started

### Prerequisites

Please see requirements.txt file for the required packages. Install the packages using pip.

Change the mysql user and password in the database.py file. SQLALCHEMY_DATABASE_URL variable includes the user and password. Just replace them.

Install and start mysql server. Create a database with the name of fastapiDB. 

### Deployment

1. Clone the repo and go to the deployment FastAPI-simple-crud-with-mysql.

2. Run the following commnad
```
uvicorn sql_app.main:app --reload
```

3. You can open your browser at http://127.0.0.1:8000/docs .
You will be able to interact with your FastAPI application, creating, reading and deleting data from a SQLite database
