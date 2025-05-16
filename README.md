# sql-etl-monitoring-
This project is simulating an automated ETL pipeline in SQL server which includes job status tracking, failure alerting and logging along with optional python based email alerts. this reflects a real world production readiness for enterprise database jobs

# SQL ETL Monitoring & Alerting Framework

This project demonstrates a production-style ETL monitoring system using SQL Server and Python-based alerting.

## 🔧 Features
- Logs job status and errors
- Tracks ETL start and end times
- Detects job failures and triggers alerts
- Email alerts via Python

## 🛠 Tech Stack
- SQL Server
- T-SQL (Try/Catch, logging)
- Python 3.x (pyodbc + SMTP)
- Windows Task Scheduler / SQL Agent

## 🚨 Alert System
- Daily check for failed jobs
- Email notifications with error details

## 📁 Folder Structure
- `SQL/`: T-SQL job logic and monitoring
- `Python/`: Email alert script
- `Logs/`: Sample log output
- `screenshots/`: Visuals of output/monitoring

## 🖼 Dashboard Screenshot
![Monitoring](screenshots/monitoring_ui.png)
