# ModelFirstMVCEF
MODEL FIRST APPROACH OF ENTITY FRAMEWORK IN ASP.NET MVC
Model First is great for when you're starting a new project where the database doesn't even exist yet.
The model is stored in an EDMX file and can be viewed and edited in the Entity Framework Designer.
In Model First, you define your model in an Entity Framework designer then generate SQL,
 which will create database schema to match your model and then you execute the SQL to create the schema in your database.
The classes that you interact with in your application are automatically generated from the EDMX file.

    DDL (Data Definition Language)
Data Definition Language (DDL) is a standard for commands that define the different structures in a database. DDL statements create, modify,
 and remove database objects such as tables, indexes, and users. Common DDL statements are CREATE, ALTER, and DROP
