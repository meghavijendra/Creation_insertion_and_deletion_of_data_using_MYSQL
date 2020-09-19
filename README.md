# Creation_insertion_and_deletion_of_data_using_MYSQL
A basic project to demonstrate loading of data using java program and querying the DB

Database design using MYSQL Workbench. 

Database program : Java with JDBC(Using Eclipse IDE). <br />
	           - The Java program imports the necessary classes for the execution of the JAVA file which is connecting to the MYSQL.<br />
             - I have also imported the csv files(country, players, player_assists_goals, players_cards, match_results) in the Eclipse IDE and placed in a seperate folder for easier access then executed.<br />


1. Since we are using Eclipse IDE to insert the values into the created tables, we have to add the JDBC connection dependency in the pom.xml 

2. As we are loading the data into the tables using JAVA program, we need to change the value of the variable "table" to the table name to which we are going to load the table data into.

3. To make the connection using JDBC, we have used the grant permission commands.
   
4. While running the java code remember to change the pathname of the csv file.

5. Edit the insert query by changing the insert tablename for all 5 tables.
