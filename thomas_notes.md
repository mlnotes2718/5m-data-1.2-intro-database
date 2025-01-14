# Thomas Notes - Introduction to RDBMS

https://www.codecademy.com/learn/ext-courses/comptia-it-fundamentals-database-concepts


### What is Database?
Database is a collection of records that allows us to record, access, analyze and manipulate individual records. Each database consist of table with rows and columns. Row belongs to each records and columns belongs to fields (type of data) such as name, address and contact number. These type of database are structured database.

### Structured and Unstructured Database
The tabular database mentioned above are structured database consist of records (row) and fields (column). Examples of structured database are address book table (contain name and address of your friend), account table (contains user id, name, mailing address, email, phone contact and payment information in e-commerce site) and spending table (contains items you bought or spend). There are also unstructured database such as a collection of photos, a collection of URL that we have bookmarked.  

### Type of Database
- Relational Databases : In am e-commerce site, we have a table of account that contains information of each customer. We also have another table that contains all transactional information. A customer may have multiple transactional record 
- NoSQL databases
- Online Transaction Processing (OLTP)
- Data Warehouses
- Distributed Databases
- Object-Oriented Databases

### Database Component
- Hardware : Storage solution such as Network Access Storage (NAS) or Storage Area Network (SAN). Such storage system also includes solution such as RAID technology that ensure redundancy and recovery when hard disk failed.  
- Software : RDBMS (MySQL, SQL)
    - Language : SQL, T-SQL
    - Rules : Dictate how database is stored and access including its relationship between tables
    - Data : The data itself.

### Challenges of Database
- Integrity
- Security
- Performance
- Integration


### Database Structured Types
- Structured
- Semi-Structured
- Unstructured

### Structured Database
- Contains table with records (row) and fields (column). Examples are Excel spreadsheet, 
    - easy to access
    - organized
    - wide range of tools
- Semi structured : lack the formal structure as above. It uses tag or markup to define the structure. Examples are XML, JSON.   
- Unstructured : Social media post, video, 

### Relational Databases
- data that can be related to each other
- Structured Query Language (SQL)
- Key considerations
    - Schema
    - Tables : Define Fields/Columns
    - Constrains
- Relationship : stored in schema, example is customer table that is related to transactional table. Customer table can have only one customer identifier but the customer can have many transaction. Schema also contain index (like content page) that allow us to access teh data faster.
- Tables : Fields/Column are limited but records are not limited.
- Keys must be unique, usually email address can be used as a primary key
    - primary key
    - foreign key
-  Constraints : Use field properties and 



