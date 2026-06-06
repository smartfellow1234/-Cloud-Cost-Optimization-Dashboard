# Cloud Cost Optimization Dashboard

## 📌 Project Overview

The **Cloud Cost Optimization Dashboard** is an AWS-based project that helps monitor cloud spending, visualize cost trends, and identify optimization opportunities. The project uses AWS Cost Explorer data, AWS Budgets, and Microsoft Power BI to provide insights into AWS resource costs and improve cost efficiency.

---

## 🎯 Objective

- Monitor AWS cloud usage and costs.
- Visualize spending trends using Power BI.
- Configure budget alerts to prevent overspending.
- Provide actionable cost optimization recommendations.

---

## 🛠️ Technologies Used

### AWS Services
- AWS Cost Explorer
- AWS Budgets
- Email Notifications

### Visualization Tool
- Microsoft Power BI

---

## 🏗️ Architecture

<img width="2816" height="1536" alt="Architecture Flow" src="https://github.com/user-attachments/assets/84b84c8d-189a-4d12-ab94-40e1d8cc188c" />

## ✨ Features

### 1. Cost Monitoring
- Monitor AWS billing and usage data.
- Track monthly cloud spending.
- Analyze service-wise costs.

### 2. Cost Visualization
- Monthly Cost Trend Analysis
- Service-wise Cost Distribution
- Total Cost Summary
- Interactive Dashboard Reports

### 3. Budget Alerts
- Configure monthly budget thresholds.
- Receive email notifications when spending exceeds predefined limits.
- Alert thresholds:
  - 80% Budget Utilization
  - 100% Budget Utilization

### 4. Cost Optimization Insights
Based on the cost analysis, the following recommendations are provided:

- Review Amazon Redshift cluster usage to reduce unnecessary costs.
- Optimize AWS Glue jobs and schedule them only when required.
- Remove unused VPC resources.
- Stop idle EC2 instances.
- Monitor spending continuously using AWS Budgets and Cost Explorer.

---

## 📊 Dashboard Visualizations

The Power BI dashboard includes:

1. Monthly Cost Trend Chart
2. Service-wise Cost Distribution Chart
3. Total AWS Cost Summary Card
4. Cost Optimization Insights Section

---

## 🚀 Implementation Steps

### Step 1: Enable AWS Cost Explorer
- Navigate to AWS Billing & Cost Management.
- Enable Cost Explorer.

### Step 2: Download Cost Data
- Open AWS Cost Explorer.
- Select the desired date range.
- Export the cost report as a CSV file.

### Step 3: Configure AWS Budgets
- Create a monthly cost budget.
- Set alert thresholds at 80% and 100%.
- Configure email notifications.

### Step 4: Create Power BI Dashboard
- Import the AWS Cost Explorer CSV file.
- Create charts and visualizations.
- Add cost optimization recommendations.

---

## 📈 Benefits

- Improved visibility into AWS spending.
- Early detection of cost overruns.
- Better cloud resource utilization.
- Enhanced cost management and optimization.

---

## 📷 Sample Outputs

- AWS Cost Explorer Cost Report
<img width="1919" height="903" alt="Screenshot 2026-06-06 123701" src="https://github.com/user-attachments/assets/a76c66cf-da7e-4231-b7ca-54bde7e41415" />
- AWS Budget Alert Configuration
<img width="1919" height="900" alt="Screenshot 2026-06-06 124106" src="https://github.com/user-attachments/assets/59d61e3e-6547-48ce-a88b-8667777b301b" />
<img width="1919" height="907" alt="Screenshot 2026-06-06 124258" src="https://github.com/user-attachments/assets/2a5ea994-776f-402e-9a8e-5610d0784e00" />
<img width="1919" height="902" alt="Screenshot 2026-06-06 124501" src="https://github.com/user-attachments/assets/a1d95d19-eb7f-46a6-92c7-56255f7d5194" />
<img width="1919" height="902" alt="Screenshot 2026-06-06 124746" src="https://github.com/user-attachments/assets/d9b4e526-e672-45d4-a7c6-4eec8676110d" />
- Power BI Cost Dashboard
<img width="1919" height="974" alt="Screenshot 2026-06-06 140734" src="https://github.com/user-attachments/assets/9268a903-936d-4a91-9ba8-7a5c1bc5c289" />

---
## 📚 Future Enhancements

- Automate data collection using AWS Cost Explorer API.
- Integrate Grafana dashboards.
- Add real-time cost monitoring.
- Implement predictive cost forecasting.

---

## 👨‍💻 Author

**K V Manoj Kumar**

Cloud Cost Optimization Dashboard Project
