# DatabaseManipulationApp

This is a simple Java App in which I used JDBC to conncect to existing SQLite Database.
Database is made from 3 tables Music, Albums and Artists.
In app I made simple queries, created views and inserts.

To run the app you need to:

1. In Datasource class change path of field named CONNECTION_STRING to the database which is provided inside main folder.
   So it says: public static final String CONNECTION_STRING =
                "jdbc:sqlite:C:\\Path to the database\\" + DB_NAME;
                
2. You need to add the JDBC driver (sqlite-jdbc-3.34.0.jar) to project. Driver is provided inside main folder.
3. Inside Main comment out queries you dont wish to perform.
4. Run Main
