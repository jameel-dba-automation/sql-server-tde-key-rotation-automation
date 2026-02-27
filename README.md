# SQL Server TDE Key Rotation Automation

This project automates Transparent Data Encryption (TDE) certificate rotation 
for SQL Server environments including:

- Standalone instances
- Always On Availability Groups

## Features

- Automated certificate creation
- Secure certificate backup
- Audit logging into Backupdb
- Cross-node deployment for AG
- SQL Agent job compatible
- Error handling and logging

## Use Case

Helps DBAs maintain encryption compliance by rotating TDE certificates 
when older than specific months.

## Technologies Used

- Microsoft SQL Server
- T-SQL
- SQL Agent Jobs
- Always On Availability Groups

## Author

Jameel Ahmed Qureshi  
SQL Server DBA 
Mumbai, India
