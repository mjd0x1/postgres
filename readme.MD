### Postgres Commands ###

### PSQL ###

*   \l

    List Databases

*   DROP DATABASE test;

    Delete a database

*  CREATE DATABASE test;

    Create a database
    
* \c test123

    Connect to a database

*   CREATE TABLE person (
        id INT NOT NULL PRIMARY KEY,
        name VARCHAR(50),
        age INT
    );

    Create a table

*   DROP TABLE person;

    Delete a table

*   \d 

    List Tables

*   \d person 

    List schema


*    INSERT INTO person (name,age)  VALUES ('blah',223);   Insert  data 

*   SELECT * FROM person; 


*  COPY table FROM '/Users/x/Downloads/file.csv' DELIMITERS ',' CSV HEADER;
    Ensure to use the full path


*  COPY (query) TO 'Users/x/Downloads/file.csv' CSV HEADER;  Export query to csv





