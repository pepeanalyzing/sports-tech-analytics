███████╗██████╗  ██████╗ ██████╗ ███████╗████████╗
██╔════╝██╔══██╗██╔════╝ ██╔══██╗██╔════╝╚══██╔══╝
█████╗  ██████╔╝██║  ███╗██████╔╝█████╗     ██║   
██╔══╝  ██╔══██╗██║   ██║██╔══██╗██╔══╝     ██║   
███████╗██║  ██║╚██████╔╝██║  ██║███████╗   ██║   
╚══════╝╚═╝  ╚═╝ ╚═════╝ ╚═╝  ╚═╝╚══════╝   ╚═╝   

# 🏟️ SPORTS TECH ANALYTICS

Synthetic Data • Python • Pandas • EDA • KPIs • Power BI


This project simulates a real sports‑tech analytics environment by generating synthetic platform logs, match events, and user activity data.  
It demonstrates a full analytics workflow — from data generation and processing to KPI development and dashboard reporting.

The goal is to showcase practical skills across **Python, Pandas, SQL‑style logic, data modelling, and Power BI** while telling a clear business story.

---

# 📁 **Project Structure**

```
sports-tech-analytics/
│
├── data/
│   ├── platform_logs.csv
│   ├── sports_events.csv
│   └── user_activity.csv
│
├── notebooks/
│   ├── data_generation.ipynb
│   └── eda_kpis.ipynb
│
├── dashboard/
│   └── sports_tech_analytics.pbix
│
└── README.md
```

---

# 🧪 **1. Data Generation (Python)**

All datasets are created programmatically using Python to simulate realistic behaviour:

### **platform_logs.csv**
Simulates system performance:
- timestamps  
- latency (ms)  
- API endpoints  
- success/error status  
- error types  

### **sports_events.csv**
Simulates match activity:
- passes  
- shots  
- tackles  
- sprints  
- match IDs  
- player IDs  
- event timestamps  

### **user_activity.csv**
Simulates platform usage:
- user roles (coach, player, analyst)  
- actions (login, upload, review, annotate)  
- timestamps  

This approach demonstrates the ability to **design datasets**, **control distributions**, and **model real‑world behaviour**.

---

# 📊 **2. Exploratory Data Analysis (EDA)**

The EDA notebook calculates key performance indicators across three domains:

### **Platform KPIs**
- Uptime %  
- Average latency  
- Error rate  
- Errors by endpoint  

### **Match & Player KPIs**
- Events per match  
- Events by type  
- Events per player  

### **User Engagement KPIs**
- Daily active users  
- Actions by role  
- Actions by type  

The notebook includes sanity‑check charts to validate data quality and behaviour patterns.

---

# 🧠 **3. Data Modelling & Measures (Power BI)**

Power BI is used to build a clean, three‑page analytics dashboard.  
Custom DAX measures include:

- **Uptime %**  
- **Average Latency (ms)**  
- **Error Rate %**  
- **Daily Active Users**  
- **Events per Match**  

The model is intentionally simple and domain‑separated to reflect real monitoring dashboards.

---

# 📈 **4. Dashboard Pages**

## 🟦 **Platform Health**
Monitors system reliability and performance.

**Includes:**
- Uptime %  
- Average Latency  
- Error Rate %  
- Latency Over Time  
- Errors by Endpoint  

**Business value:** mirrors real DevOps/SRE monitoring.

---

## 🟦 **Match & Player Analytics**
Analyses match intensity and player workload.

**Includes:**
- Events by Type  
- Events per Match  
- Events per Player  
- Match & Player slicers  

**Business value:** supports coaching and performance analysis.

---

## 🟦 **User Activity**
Tracks platform engagement and behaviour.

**Includes:**
- Daily Active Users  
- Actions by Role  
- Actions by Type  
- Role slicer  

**Business value:** mirrors SaaS user‑engagement dashboards.

---

# 🧩 **5. Skills Demonstrated**

### **Technical**
- Python (Pandas, NumPy, datetime)
- Data generation & simulation
- Exploratory data analysis
- KPI development
- Power BI modelling & DAX
- Dashboard design
- Data storytelling

### **Business**
- Platform performance monitoring  
- Sports analytics  
- User engagement analysis  
- Operational insights  
- Stakeholder‑friendly reporting  

---

# ▶️ **6. How to Run This Project**

### **1. Clone the repository**
```
git clone <your-repo-url>
```

### **2. Run the data generation notebook**
Generates all CSVs into `/data`.

### **3. Run the EDA notebook**
Calculates KPIs and validates data.

### **4. Open the Power BI file**
```
dashboard/sports_tech_analytics.pbix
```

Refresh the data source if needed.

## 📸 **7. Dashboard Previews

### Platform Health
![Platform Health](screenshots/platform_health.png)

### Match & Player Analytics
![Match & Player Analytics](screenshots/match_player_analytics.png)

### User Activity
![User Activity](screenshots/user_activity.png)

---

# 🎯 **8. Project Summary**

This project demonstrates the ability to:

- Build a complete analytics pipeline from scratch  
- Simulate realistic datasets for testing and portfolio work  
- Develop KPIs that reflect real operational and sports‑tech environments  
- Design clean, professional dashboards  
- Communicate insights clearly and visually  

It reflects the type of work done in **data analytics, BI, product analytics, and sports performance roles**.
