
# Grocery Management System

This repository contains the source code and documentation for the Grocery Management System, a project developed to modernize and automate the management processes of a grocery store. The system focuses on efficient data storage, retrieval, and management using a database, enhancing the overall operational efficiency of the store.


## Table of Contents

1. Problem Definition

2. Learning Objectives

3. Learning Outcomes

4. Abstract

5. Modules

6. MySQL Tables Description

7. Installation

8. Conclusion


## Problem Definition

Managing a grocery store efficiently involves complex tasks such as inventory management, order processing, sales tracking, and customer management. The Grocery Management System aims to address these challenges by developing a comprehensive database management system that enhances the overall operations of the grocery store.
## Learning Objectives

1. Create a robust database schema for managing grocery store data.

2. Establish a connection between the database and a Java application using JDBC, enabling data interaction.

3. Implement CRUD (Create, Read, Update, Delete) operations for products, customers, orders, and suppliers within the database.

4. Record and manage essential information about products, customers, orders, and suppliers for efficient inventory and customer relationship management.

5. Design a user-friendly web interface using HTML and CSS that integrates CRUD operations, allowing store staff to interact with the database in real-time.
## Learning Outcomes

1. Successful design and implementation of a comprehensive database schema tailored to grocery store management.

2. Proficiency in establishing a secure and efficient connection between a MySQL database and a Java application using JDBC.

3. Proficient execution of CRUD operations, enabling effective data management for products, customers, orders, and suppliers.

4. Effective recording and management of crucial information, enhancing inventory control and customer service.

5. The ability to design a user-friendly web interface that incorporates CRUD operations, providing a visual representation of data interactions and changes within the grocery store's management system.
## Abstract

The Grocery Management System project aims to computerize and modernize the management of a grocery store by developing user-friendly, efficient, and cost-effective software. The system facilitates the collection of customer information, management of product inventory, order processing, and supplier information, eliminating the need for traditional manual methods. It ensures data security and significantly enhances data processing speed.
## Modules

 • Product

Contains information about the products available in the grocery store, including product ID, name, price, and quantity in stock.

 • Customer

Stores information about the customers who purchase products from the grocery store, including customer ID, name, contact information, and purchase history.

 • Supplier

Keeps a record of the suppliers who provide products to the grocery store, including supplier ID, name, contact details, and products supplied.

 • Inventory

Tracks the stock levels of all products in the store, including product ID, quantity in stock, and reorder level.

 • Sales
 
Records information about each sale transaction, including transaction ID, customer ID, products purchased, quantity, and total cost.
## MySQL Tables Description

Products Table:  
  
    create table customer (      id int 
    not null auto_increment,       fname 
    varchar45),       lname varchar45),       
    email varchar45),       address 
    varchar45),       destination varchar45),      
    primary key(id));  
  
  
Orders Table:   
  
    CREATE TABLE AGENCY (  
    Pname varchar (30) NOT NULL,  
    Pphone int NOT NULL,  
    Pmail varchar (30),      
    Reg_id int,      days int NOT 
    NULL,      dest varchar (30),  
    cost float);  


Order_details Table:  

    CREATE TABLE SITE (  
    Place varchar (30),  
    BestTime varchar (40),  
    Time varchar (30) NOT NULL,  
    Charge int NOT NULL,  
    Spot_id int,   
    PRIMARY KEY(Spot_id));  

Uom Table:  

    CREATE TABLE HOTEL (  
    NOR int,  
    Address varchar (40),  
    FoodCost int,  
    Tariff int,  
    Cid int NOT NULL,  
    FOREIGN KEY(Cid) REFERENCES CUSTOMER (Cust_id));
## Installation

1. Clone the repository: 

        git clone https://github.com/omkar3905/Grocery-Management-System-using-MySQL.git

2. Navigate to the project directory: 

        cd Grocery-Management-System-using-MySQL

3. Set up the database using the provided schema.

4. Configure the database connection in the Java application.

5. Deploy the web interface on a local server.
## Conclusion

The Grocery Management System successfully implements JDBC with HTML and CSS to create a simple web page with basic CRUD operations, using MySQL as the backend database management system. This project modernizes grocery store management, improving efficiency and productivity.