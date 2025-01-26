# Automatic_Timetable_Generator

1. Open the Project in Visual Studio
Download the repo from GitHub and open the .sln file in Visual Studio.
2. Create a New Database in SQL Server
Open SQL Server Management Studio (SSMS).
Right-click Databases and select New Database.
Name your database (e.g., YourDatabaseName), then click OK.
3. Run SQL Scripts to Set Up the Database
Find the SQL scripts in the repo (usually .sql files).
Open these scripts in SSMS and execute them to create the tables and schema in your new database.
4. Update the Connection String in the Project
Open appsettings.json (or web.config).
Update the connection string to point to your new database:
json
Copy
"ConnectionStrings": {
  "DefaultConnection": "Server=localhost;Database=YourDatabaseName;Integrated Security=True;"
}
5. Run the Project
Build and run the project in Visual Studio.
It should now connect to the database and work correctly.
