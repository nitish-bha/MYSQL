# SQL
 This repository includes all the SQL Operations.

CREATE TABLE Employee(
firstname varchar(20),
middlename varchar(20),
lastname varchar(20),
age int,
salary int,
location varchar(20)
);                                                                                             # creating table

desc Employee;                                                                                 #describing table

select * from employee                                                                         #showing or selecting values

INSERT INTO Employee(firstname, middlename,lastname,age,salary,location) VALUES ('kapil','kumar','sharma',28,10000,'banglore');  #inserting values into the table Employee

INSERT INTO Employee(firstname, lastname,age,salary,location) VALUES ('charan','sharma',28,10000,'banglore');

INSERT INTO Employee(firstname, middlename,lastname,age,salary,location) VALUES ('kapil','kumar','sharma',28,10000,'banglore'),('charan','Kumar','sharma',28,10000,'banglore');

CREATE TABLE Employee(
firstname varchar(20) NOT NULL,
middlename varchar(20),
lastname varchar(20) NOT NULL,
age intNOT NULL,
salary int NOT NULL,
location varchar(20) NOT NULL
);


