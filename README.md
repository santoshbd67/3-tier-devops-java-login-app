### Deploy Java Application on AWS 3-Tier Architecture

![f](https://github.com/santoshbd67/3-tier-devops-java-login-app/assets/150413783/21c01ada-277a-4904-8db5-0f7d7b360db1)




![Untitled](https://github.com/santoshbd67/3-tier-devops-java-login-app/assets/150413783/114507f4-62bb-4598-9f5a-8bb1d491cdde)





## Java Login App ##
Testing 

## Sample Java Login application uses "UserDB" database and Table schema to store the Employee Login details. ##

## How to see list of Databases ##
SHOW DATABASES;

## How to create Database ##

CREATE DATABASE UserDB;

## How to list Tables ##

USE UserDB;

SHOW TABLES;

## How to create Table ##
## Below Query to create require TABLE schema to store Employee records ##

CREATE TABLE Employee (
  id int unsigned auto_increment not null,
  first_name varchar(250),
  last_name varchar(250),
  email varchar(250),
  username varchar(250),
  password varchar(250),
  regdate timestamp,
  primary key (id)
);

## List Table data ##
SELECT * FROM Employee;

## Describe Table schema ##
DESCRIBE Employee;
