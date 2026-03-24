
# Project: Azure Data Factory Pipeline

## Overview
Built an end-to-end data pipeline using Azure Data Factory to copy and process data from source to destination within Azure Data Lake Storage Gen2.

This project demonstrates **data ingestion, pipeline orchestration, and cloud-based ETL** using Azure services.

---

## Architecture
Azure Data Lake (Source Container)
        ↓
Azure Data Factory (Pipeline - Copy Activity)
        ↓
Azure Data Lake (Destination Container)

---

## Steps Performed
1. Created Resource Group  
2. Created Storage Account (ADLS Gen2 enabled)  
3. Created containers: `source` and `destination`  
4. Uploaded sample CSV file to source container  
5. Created Azure Data Factory instance  
6. Configured Linked Service to ADLS Gen2  
7. Created pipeline (`pl_copy_data`)  
8. Added Copy Data activity  
9. Configured Source dataset (CSV format)  
10. Configured Sink dataset (destination container)  
11. Executed pipeline and validated successful run  

---

## Output
- Data successfully copied from **source container** to **destination container**
- Output file generated as `output.csv`

---

## Technologies Used
- Azure Data Factory  
- Azure Data Lake Storage Gen2  
- Azure Resource Group  
- Azure Storage Account  

---

## Key Highlights
- Implemented **ETL pipeline using Azure Data Factory**  
- Demonstrated **data movement between storage layers**  
- Used **Linked Services and Datasets configuration**  
- Built **scalable and reusable pipeline architecture**  

---

## Real-World Use Case
This pipeline can be used in:
- Data ingestion from raw to processed layer  
- Batch data processing workflows  
- Enterprise data lake architecture  

---

## Author
**Madhuridevi Muthukumar**
