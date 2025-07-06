# stevgarcia-azure-data-factory-databricks
Azure Data Engineering End-To-End Project with  Data Factory , Databricks ,Pyspark  and Azure Synapse Analytics


![image]([https://github.com/user-attachments/assets/a549d9d7-3b1d-4169-a037-07eff6139d06](https://github.com/stevgarcia/Azure-data-factory-databricks/blob/main/docs/architecture.png))

## 📖 Project Overview

# Azure data Factory
It has a lookup activity that is connected to an Azure datalake Gen2, it gets a Json file with the url's, names and folders
It creates a for each loop to get different data from GitHub
A copy activity copies the data to the bronze layer supported on Azure datalake Gen2
