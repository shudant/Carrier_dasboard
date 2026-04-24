# 🚀 Carrier Dashboard – Logistics & Billing Analytics
## 📌 Overview

The Carrier Dashboard is an end-to-end data analytics project built to monitor and analyze logistics operations, billing status, and vendor performance.
It provides actionable insights into:

📦 Bill processing <br/>
⏳ Pending workflows <br/>
🚚 Vendor performance <br/>
📊 Branch-level operations <br/>

This project demonstrates real-world data engineering + analytics skills using Power BI, SQL, and data transformation techniques.

## 🎯 Key Business Problems Solved

- Identify pending bills and bottlenecks
- Track APMS uploads vs completed payments
- Monitor vendor-wise performance & delays
- Analyze branch-level billing distribution
- Provide real-time operational visibility

📂 Project Structure


## 📊 Dashboard Features

🔹 1. Billing Overview <br/>
- Total Bills <br/>
- Payment Completed <br/>
- APMS Uploaded <br/>
- Total POD (Proof of Delivery) <br/>

🔹 2. Pending Analysis <br/>
- Pending with Vendor
- Pending with DSC
- Pending with CARL
- Today’s Pending

🔹 3. Vendor Insights <br/>
- Vendor-wise bill distribution <br/>
- Validation status by vendors <br/>
- Top vendors by workload <br/>

🔹 4. User Performance Tracking <br/>
- APMS uploads by user <br/>
- Bill count by user <br/>
- POD handled by users <br/>

🔹 5. Branch-Level Analysis <br/>
- Bill count by branch <br/>
- Regional workload distribution <br/>

## 🛠️ Tech Stack <br/>
🔹 Data Processing <br/>
- SQL (Data extraction & aggregation) <br/>
- Power Query (Data cleaning & transformation) <br/>

🔹 Visualization
- Power BI (Interactive dashboards) <br/>

🔹 Tools
- Git & GitHub <br/>
- Excel (Data source) <br/>

## ⚙️ Data Pipeline

```mermaid
flowchart LR
A[Raw Data: Excel / SQL] --> B[Data Cleaning: Power Query]
B --> C[Transformation & Aggregation]
C --> D[Power BI Data Model]
D --> E[Dashboard Visualization]
```

## 📸 Dashboard Preview

🔹 Billing Overview <br/>
- Total Bills: 4803 <br/>
- Payment Done: 4503 <br/>
- Total POD: 108487 <br/>

🔹 Pending Breakdown <br/>
- Vendor Pending: 177 <br/>
- DSC Pending: 112 <br/>
- CARL Pending: 191 <br/>

🔹 Vendor Distribution <br/>
- Major vendors include: <br/>
- BLT Logistics Pvt Ltd <br/>
- Century Cargo Carrier Pvt Ltd <br/>
- Agarwal Packers & Movers <br/>

<img width="1374" height="779" alt="image" src="https://github.com/user-attachments/assets/ce93296e-955b-46dc-8c69-ae102e9191e9" /> <br/>

<img width="1376" height="781" alt="image" src="https://github.com/user-attachments/assets/94eaa1fd-dc01-4b54-814c-39d65283c22c" /> <br/>

<img width="1374" height="778" alt="image" src="https://github.com/user-attachments/assets/4a0cdba7-b0e2-46e4-a43c-7b01026ca892" /> <br/>

<img width="1373" height="775" alt="image" src="https://github.com/user-attachments/assets/0f31b4f6-f534-4ab6-a4ff-25f8eefca1af" /> <br/>


## 📈 Key Insights

📊 Majority of bills are successfully processed (~94%) <br/>
⚠️ Significant delays observed in vendor and DSC stages <br/>
🏢 Certain branches contribute disproportionately to workload <br/>
👨‍💻 User-level performance varies significantly <br/>

## 🚀 How to Use

### Clone the repository
git clone https://github.com/shudant/Carrier_dasboard.git

## 💡 Future Enhancements

☁️ Migrate pipeline to Azure Data Factory (ADF) <br/>
🧊 Store data in Azure Data Lake / SQL Database <br/>
⚡ Build real-time streaming dashboard <br/>
🤖 Add ML model for delay prediction <br/>
🌐 Deploy dashboard via Power BI Service <br/>

## 🧠 Skills Demonstrated

- Data Cleaning & Transformation <br/>
- ETL Pipeline Design <br/>
- Data Modeling <br/>
- Dashboard Design (Power BI) <br/>
- Business Insight Generation <br/>
- SQL Query Optimization <br/>

## 👨‍💻 Author


Suddhant Gautam
