# DBISProject
Library Management System using Java and MySQL
  
# Environment and Requirement
- Programming Language: JAVA with  Swings
- MySQL Conncector: MySQL JConnector 8.3.40(JDBC Driver)
  https://dev.mysql.com/downloads/connector/j/
- IDE: NetBeans 8.1
- MySQL Version: 8.0.36
- MySQL WorkBench: 6.3.6+dfsg-0ubuntu1
- Created in Ubuntu(16.04 LTS)

# About Files
-  /SQL: Contains the Exported Database Schema+Data
- /src/mainlibrary: Contains JAVA source codes
- /MySQL Connector: Contains JDBC/MySQL JConnnector

# Instructions
1) Clone the Project using link https://github.com/EncoSier/DBISProject.git or Download the zip

2) Importing Java Project in NetBeans
- Clone & import the project in the NetBeans 8.1

3) Importing Database(Schema+Data)
- Import the Database in the MySQL database using MySQL WorkBench(Version is mentioned above)
- MySQL Workbench->Data Import/Restore->Load Folder Contents->SQL->exportdb.sql

4) Connect the JDBC driver(JConnector) by including the it's JAR File in the Project
- Expand Project->Libraries->ADD JAR File->include file: mysql-connector-java-8.0-bin.jar

5) Database setting can be changed
- Expand Project->Source Packages->mainlibrary->DB.java
- Change the Authentication Setting
