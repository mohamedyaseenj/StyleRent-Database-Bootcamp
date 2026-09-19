👗 StyleRent – Database Bootcamp
Smart Clothing Rental & Inventory Management System

StyleRent is a two-week SQL database development and implementation project focused on designing a structured database for a smart clothing rental system.

The project covers ER diagram design, SQL, database creation, table design, data insertion, queries, joins, aggregate functions, grouping, and window functions.

🎯 Project Objective

To design and implement a structured database that makes clothing rental data simple, organized, and easy to manage.

🗂️ Database Modules
Module	Description
👤 Users	Customer and user details
👗 Clothing	Clothing/product details
📂 Category	Clothing categories
📝 Rental	Rental details and dates
🔗 Rental Item	Connects rentals with clothing
💳 Payment	Payment information
⭐ Review	Ratings and comments
🧩 Database Concepts
ER Diagram
Primary Key
Foreign Key
Unique Key
Composite Key
Table Relationships
Data Integrity
Composite Key Example
PRIMARY KEY (rental_id, clothing_id)
🛠️ Technologies
SQL
PostgreSQL
MySQL
Draw.io
pgAdmin
Git
GitHub
📚 SQL Topics
DDL
CREATE • ALTER • DROP
DML
INSERT • UPDATE • DELETE
DCL
GRANT • REVOKE
DQL
SELECT
🔗 SQL Joins
INNER JOIN
LEFT JOIN
RIGHT JOIN
FULL OUTER JOIN
CROSS JOIN
SELF JOIN

Example:

SELECT u.name, r.rental_id, r.total_amount
FROM users u
INNER JOIN rental r
ON u.user_id = r.user_id;
📊 Aggregate & Advanced Queries
SUM()
AVG()
COUNT()
MAX()
MIN()

GROUP BY
HAVING
LIMIT
Window Functions
RANK() OVER (ORDER BY total_amount DESC)
📁 Repository Structure
StyleRent-Database-Bootcamp/
│
├── README.md
├── database/
├── er-diagram/
├── documentation/
└── screenshots/
📄 Documentation

The repository includes the StyleRent Capstone Bootcamp – SQL Database Development Report, containing the ER diagram, SQL concepts, database operations, joins, aggregate functions, window functions, and project conclusion.

🎓 Learning Outcomes
Database Design
ER Modeling
SQL & PostgreSQL
Keys & Relationships
SQL Joins
Aggregate Functions
Grouping
Window Functions
Database Querying
👨‍💻 Project Information

Project: StyleRent
Type: Capstone Bootcamp
Domain: Clothing Rental & Inventory Management
Focus: SQL Database Development
Duration: Two Weeks

📌 Status

Completed – Capstone Database Development Project
