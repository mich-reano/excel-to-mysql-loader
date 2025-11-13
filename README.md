# FROM EXCEL CHAOS TO MYSQL CLARITY.
**Automating data migration with Python, Pandas, and MySQL**

--
## PROJECT OVERVIEW
This project automates the process of transforming multiple csv and excel files into clean, structured **MySQL database tables**.

Using Python, I built a script that:
- Reads each file (whether `.csv`, or `.xlsx`).
- Cleans and standardizes column names.
- Automatically infers MySQL-compatible data types.
- Creates corresponding tables dynamically.
- Inserts all records efficiently and safely.

What began as a simple task of importing files became a full **ETL (Extract, Transform, Load)** Learning experience - one that challenged my understanding of **data consistency, type inference, and database integration.**

--

## KEY FEATURES
1. Automatic detection and creation of MySQL tables
2. Data cleaning: renames columns and removes extra spaces
3. Smart type imference for MySQL fields
4. Error handling for missing data, and connection drops
5. Works for both `.csv` and `.xlsx` files
6. Commits data in a file-by-file sequence

--

## TECH STACK
| Component | Technology|
|-----------|-----------|
| Languages | Python,SQL|
| Libraries | Pandas, Numpy, mysql-connector-python |
| Database | MySQL |
| IDE | VS Code |
| Visualization | Process Diagram |

--

## PROCESS FLOW DIAGRAM
![ETL diagram]([images\csv_to_mysql.png](https://github.com/mich-reano/excel-to-mysql-loader/blob/b64e3b2189cb049abddf0844f4d14362d9af5703/images/csv_to_mysql.png))

--

## REFLECTIONS
What started as an import script became a hands-on data engineering milestone.
From cleaning raw spreadsheets to uatomating structured database creation, this project embodies the process of turning **data chaos into clarity.**
`Every dataset has potential. The goal is to make it useful.`

## LICENSE
This project is open source under the **MIT License**

## CONTACT
**Michael Reagan.**
Data Science Enthusiast | Data Engineer | Python Developer.

Founder: Lumetra Analytics.
![logo](images\lumetra-logo.png)

LinkedIn : www.linkedin.com/in/magollo-michael-reagan-a61222230.
michaelreaga94@gmail.com
