# SQL-Car-Showroom-Analysis-
This is an SQL Challenge. Welcome to the SQL Car Showroom Analysis repository. This project aims to provide comprehensive insights and answers to Steve, the owner of a top-end car showroom, who is in need of crucial information after his data analyst quit unexpectedly. By utilizing SQL, we will analyse data and extract meaningful findings.

Database
This SQL schema defines a database that encompasses three tables: cars, salespersons, and sales. These three tables are interconnected using the join operator to establish relationships between the data.

Cars table:
The cars table stores information about different car types, including make and cost. It consists of the following columns:

car_id ( Primary Key)
make: Manufacturer or brand of the car
type: Type or model of the car
Style: Style of the car 
Cost: Cost of the car

Salespersons table:
The salespersons table contains details about the salespeople, including their personal information. The table includes the following columns:

salesman_id (Primary Key): Unique identified for each salesperson 
name: Name of the salesperson
age: Age of the salesperson
city: City where the salesperson is located

Sales table:
The sales table records the purchase information, associating a car sale with a specific salesperson. It includes the following columns:

sale_id (Primary Key): Unique identified for each sale
car_id (Foreign key): References the car_id from the cars table to indicate which car was sold
salesman_id(Foreign key) References the salesman_id from the salespersons table to indicate the salesperson involved in the sale
purchase_date: Date of purchase
