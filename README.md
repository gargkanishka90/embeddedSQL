embeddedSQL
===========

This is a course project for CS 480: Database Systems class. Task was to write a java program and interface it with MySQL database using JDBC.


The usename and password to connect to the MYSQL should be
username: root
Password: root

Please use this command to create the schema in the MYSQL Commandline:
create database homework4;

Put the homework4.java and mysql-connector-java-5.1.12-bin.jar in the same directory.

For compiling and running your Java program in the LINUX, you can use this command.

You need to add MySQL JDBC driver to your classpath while compiling and running.

Compile:
javac -cp mysql-connector-java-5.1.12-bin.jar homework4.java 

Run:
java -cp mysql-connector-java-5.1.12-bin.jar:. homework4
