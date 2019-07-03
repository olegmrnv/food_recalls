# Food Recalls
A database ready for future analysis of food recalls and potential reasons for that. This is ETL project. Myself and other team members worked on extracting data from csv, tsv files and API responses. Then we transformed it in a way where we drop partial/invalid records, remove redundancy, create relational tables and after that load into MySQL database.  Diag1 and Diag2 visually present how data structured. 

Python used as a  primary programming language, other libraries: Pandas, JSON, Requests, SQLAlchemy, Pandas.io, mysql.connector, pprint.


# Instructions
*Clone repository (note: file en.openfoodfacts.org.products.tsv is 963 MB and it will be loaded from Git Large File Storage)

*Update db_key.py with your login and password from your local installation of MySQL (defaul user - root)

*Run pip install pymysql (if not already installed on computer)

*Open and run data_processing.ipynb

*Refer to Diag1 and Diag2 for DB schema and Final report for details. 
