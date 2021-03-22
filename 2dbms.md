## What is DBMS ?
Database Management System (DBMS) is a software for storing and retrieving users' data while considering appropriate security measures. It consists of a group of programs which manipulate the database. The DBMS accepts the request for data from an application and instructs the operating system to provide the specific data. In large systems, a DBMS helps users and other third-party software to store and retrieve data.

DBMS allows users to create their own databases as per their requirement. The term “DBMS” includes the user of the database and other application programs. It provides an interface between the data and the software application.

Let us see a simple example of a university database. This database is maintaining information concerning students, courses, and grades in a university environment. The database is organized as five files:

+ The STUDENT file stores data of each student
+ The COURSE file stores contain data on each course.
+ The SECTION stores the information about sections in a particular course.
+ The GRADE file stores the grades which students receive in the various sections
+ The TUTOR file contains information about each professor.

To define a database system:

+ We need to specify the structure of the records of each file by defining the different types of data elements to be stored in each record.
+ We can also use a coding scheme to represent the values of a data item.
+ Basically, your Database will have 5 tables with a foreign key defined amongst the various tables.
