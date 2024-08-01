# Olympics Data Engineering Project
## Overview
This project involves an end-to-end data engineering pipeline for analyzing Olympic data. The dataset includes information about athletes, medals, coaches, teams, and entries by gender. The project demonstrates the use of various Azure services to extract, transform, and load (ETL) data, culminating in analytics with Azure Synapse Analytics.

## Project Components
### Dataset

- Source: Kaggle
- Tables: Athletes, Medals, Coaches, Teams, Entries by Gender

### Data Storage
- The dataset is hosted on GitHub for easy access.

### Data Extraction
- Using Azure Data Factory to extract data from GitHub via HTTP links.
- Data is loaded into Azure Blob Storage.

### Data Transformation
- The extracted data is processed and transformed in Azure Databricks.

### Transformed Data Storage
- Transformed data is loaded into a separate folder in Azure Blob Storage.

### Analytics
Data is linked with Azure Synapse Analytics for comprehensive analytics.
Data Pipeline
Copy Data Activity
The Copy Data activity in Azure Data Factory is used to transfer data from a source to a destination. In this project, it plays a crucial role in extracting data from GitHub links and loading it into Azure Blob Storage.

![Workflow]('https://github.com/fahadrafiqueee/End-End-DataEngineering/blob/master/ScreenShots/DATA%20GATHERING.png')
