# Data Lake
Data lake is a set of projects, which will cover data sync up, ETL, Cube system, monitoring/alert system, data mining/machine learing and AI system. Pharse I is comming soon, which focus on real time data sync up from RMDB to Hive.

## Why data lake?
Establish a reliable data transfer pipeline between RMDB and hive by wed based UI. We customize an OGG adapter which could guarantee the data consistency during data transfer with selectable encrypt method. Using OGG is not only for sync up data in real time but also for those databases with physical delete and update, traditional incremental dump with sqoop can't deal with these scenario except fully dump all the tables. Currently we support Oracle, DB2, MySQL, MSSQL. And it sync up data to a single hbase table to reduce overhead of hbase region server.  **KERBEROS SUPPORTED!** **CARBONDATA SUPPORTED!**

## Features

| Feature        | Community Version | Enterprise Version  |
| ------------- |:-------------:| :-----:|
| Auto deployment tool|√|√|
| Web based managment tool|√|√|
| Real time data sync up|√|√|
| Data encryption|√|√|
| Data transfer encryption|√|√|
| Dynamic encryption key|√|√|
| Database level snapshot|√|√|
| Row/Column level access control|√|√|
| Configurable data desensitization|√|√|
| Data consistency guarantee|√|√|
| ***Carbondata supported***|***√***|***√***|
| ***Kerberos supported***|***√***|***√***|
| Pipeline monitoring by machine learning|×|√|
| Selectable encrypt method|×|√|
| Data quality audit|×|√|
| Data access monitoring/audit|×|√|
| Diagnosis report|×|√|
| E-mail support|√|√|
| Tel support|×|√|

## Contact us
