# Hospital Management System
Hospital Management System in java.
This system has a home page from where the administrator can login. On logging in the user can add details of patients and doctors.

## Installation
1. Clone or download zip from github repository
2. Install [MySQL Connector/J](https://dev.mysql.com/downloads/connector/j/3.1.html), on Ubuntu/linux MySQL connector can be installed by `apt-get install libmysql-java` and then add the path of `.jar` file to `CLASSPATH`. On Ubuntu/linux the location of `.jar` file can be added to `CLASSPATH` by adding the following line `export CLASSPATH=".:/usr/share/java/mysql.jar"` to `~/.bashrc` file followed by `source ~/.bashrc`
3. Create database named `hms` and table `users` with columns `username`, `password`, table `doctors` with columns `DocName`, `Specialisation`, `Address`, `Pnumber`, table `Patients` with columns `Pname`, `Address`, `Pnumber`, `Age`, `Sex`, `Illness` and table `contactus` with columns `email`, `comments`
4. Navigate to the project folder and run `javac HomePage.java` to compile and `java HomePage` to run the program

