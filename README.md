# Oracle-Database-Development

### Project Overview
This project involves the development of an Oracle Database designed to manage and analyze operational data for a nonprofit organization. The database tracks essential information such as supplies, project costs, locations, donors and their contributions, and volunteer details. I pulled the data from Mockaroo (test data generator) to simulate real-world scenarios.

### Key Features
- **Data Modeling:**
  - Designed and created relational tables for entities such as `Volunteers`, `Donors`, `Supplies`, `Projects`, `Plants`, and `Locations`.
  - Integrated relationships to maintain data consistency and enable comprehensive queries.

- **Data Ingestion:**
  - Inserted comprehensive datasets into the database to populate tables with detailed information:
    - Supplies and their costs.
    - Donors and their donations.
    - Volunteer details, including skills and assigned projects.

- **SQL Queries for Reporting:**
  - Developed advanced SQL queries for analyzing the data, providing insights into:
    - Total donations and supplies costs per project.
    - Volunteer participation counts for individual projects.
    - Status updates and progress tracking for active and pending projects.

- **Stored Procedures:**
  - Automated repetitive operations to enhance database usability:
    - **Financial Summaries:** Calculate total donations and supply costs per project.
    - **Volunteer Reporting:** List volunteers per project along with participation counts.
    - **Data Corrections:** Fix errors in project names dynamically.
    - **Transaction Management:** Ensure data integrity during insertions and updates with `COMMIT` and `ROLLBACK`.

- **Database Views:**
  - Simplified reporting by creating pre-aggregated views:
    - **Project Overview View:** Displays project details, linked locations, plants, and their current status.
    - **Financial Overview View:** Summarizes total donations and supply costs for each project.

### Purpose of the Project
This Oracle Database serves as a centralized solution for nonprofits to efficiently track and manage their operations. From recording donations and volunteer skills to analyzing project progress and financial data, this system integrates all aspects of organizational management into a single database.

### Technologies Used
- **Oracle SQL** for database design and data management.
- **PL/SQL** for building dynamic and reusable stored procedures.
- **Mockaroo** for sourcing simulated data to mimic real-world operational needs.
- **Entity-Relationship Diagram (ERD)** for visualizing the database schema and its relationships.
