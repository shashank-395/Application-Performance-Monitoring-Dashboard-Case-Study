# 🚦 Application Performance Monitoring Dashboard

**Tools Used:** Power BI Service | SQL Server | DAX

---

## 🔍 Overview

This case study presents a BI solution developed to monitor and optimize application/API performance in a production environment. The dashboard provided engineering and DevOps teams with real-time visibility into API usage patterns, performance metrics, and error trends, enabling proactive issue resolution and long-term reliability improvements.

---

## 🧩 Business Objective

- Monitor API call performance in real-time  
- Identify high-failure endpoints and performance bottlenecks  
- Track and improve system reliability via measurable KPIs  
- Support data-driven decisions to enhance customer experience  

---

## 🏗️ Solution Architecture

### 1. Data Sources
- Data ingested from SQL Server, capturing API logs (response time, status codes, payload metadata)

### 2. Data Modeling & Preparation
- Created fact tables for API calls and status logs  
- Optimized Power BI data model using calculated columns and relationships for trend analysis  

### 3. Key Metrics Tracked
- **API Success Rate:** % of successful responses (e.g., HTTP 200)  
- **Average Response Time:** Monitored across endpoints and time windows  
- **Failure Rate & Retry Analysis:** Identified frequent timeouts and 4xx/5xx errors  
- **Request Volume Trends:** Detected usage spikes and anomalies  

### 4. Visualizations & Features
- Dynamic dashboards with time filters and endpoint-level drill-downs  
- Rolling averages and cumulative DAX measures for trend analysis  
- Heatmaps to identify performance issues by time of day or client type  
- KPI cards and threshold indicators for real-time alerts  

### 5. DAX and Automation
- Custom DAX Measures:
  - Rolling error rates  
  - Monthly cumulative success trends  
  - Endpoint health scores based on latency  
- Scheduled refreshes enabled via Power BI Service for continuous data delivery  

---

## 📈 Impact & Results

- Identified underperforming endpoints, leading to targeted code optimizations  
- Improved API reliability by **32.53%** within 2 months  
- Enabled real-time visibility for DevOps, reducing MTTD and MTTR  
- Transitioned from static performance reports to an interactive, automated dashboard  

---

## 🔐 Note

This case study is based on a real production implementation. All datasets and business identifiers have been anonymized for confidentiality. The objective is to highlight the technical execution, performance monitoring strategy, and Power BI implementation patterns.
