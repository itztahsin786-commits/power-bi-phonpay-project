[![language](https://img.shields.io/badge/tool-Power%20BI-orange)](https://powerbi.microsoft.com/)
[![license](https://img.shields.io/badge/license-MIT-green)](#license)

# 📊 PhonePe Payment Analytics Dashboard

**One-line summary:**  
Interactive Power BI dashboard that analyzes PhonePe transaction data to track volumes, surface failure reasons, compare service performance, and recommend reliability improvements.

---

## 🧾 Overview
This Power BI project visualizes and analyzes PhonePe digital payment transactions across services (Loans, Insurance, Money Transfer, Recharge & Bills). It converts raw transactional exports into KPI cards, failure analysis, and trend reports designed for product and operations teams.

---

## 🎯 Objective
- Track total and successful transaction amounts and volumes.  
- Identify and analyze failed payment reasons and their service impact.  
- Compare service-wise and month-wise transaction patterns.  
- Provide actionable insights to improve payment reliability and reduce failures.

---

## 📊 Dashboard Features
1. **KPI Cards**  
   - Total Amount: **₹2,894M**  
   - Successful Amount: **₹2,774M**  
   - Failed Amount: **₹120M**  
   - Total Transactions: **249.79K**

2. **Date Range Filter**  
   - Interactive date slicer (example: 2024-03-02 → 2024-12-30) for time-window analysis.

3. **Failure Analysis**  
   - Pie chart showing percentage distribution of failure reasons (Server Error, Wrong Info, Bank Denied, Insufficient Balance, Wrong PIN).  
   - Bar chart: failure amount by service (Loans, Insurance, Money Transfer, Recharge & Bills).  
   - Line chart: month-wise failure trend to spot seasonal or load-driven spikes.

4. **Service & Category Breakdowns**  
   - Drillable views for each service (Loans, Insurance, Money Transfer, Recharge) with KPI trendlines, top failure reasons, and category contribution.

---

## 📈 Key Insights (summary)
- **Loans** has the highest failure amount among services.  
- **Server Error** and **Bank Denied** are the most common failure reasons.  
- Failures tend to spike around **July** and **September** — possible seasonal/load issues.  
- Despite failures, the overall success rate remains high (₹2,774M successful out of ₹2,894M total).

> _Replace figures and dates with your final cleaned numbers if they change — always publish real quantified results._

---

## 🧠 Tools & Techniques
- **Power BI Desktop** — data modeling, DAX measures, interactive visuals  
- **Power Query / Excel** — data cleaning, normalization, pivot checks  
- **DAX** — KPI measures, calculated columns, time-intelligence  
- **Versioning** — Git / GitHub for scripts, PBIX snapshots, and documentation

---

## 📁 Deliverables
- `pbix/` — Power BI file (if shareable) or PBIX screenshots  
- `data_samples/` — sample CSV extracts for reproduction (masked/anonymized)  
- `docs/` — 1–2 page executive brief with recommendations and action items  
- `screenshots/` — high-resolution dashboard images for portfolio

---

## ▶️ How to review / run
1. Open `PhonePe_Dashboard.pbix` in Power BI Desktop (or load `screenshots/` if PBIX is not shareable).  
2. If working from CSV samples: use Power Query to load `data_samples/*.csv`.  
3. Refresh data model → verify relationships → review KPI page and service pages.  
4. Export visuals or publish to Power BI Service for interactive sharing.

---

## 💡 Recommended Actions (examples)
- Investigate server-side logs for July & September spikes to detect capacity or deployment issues.  
- Prioritize fixes for server errors and bank rejection flows, as these drive the largest failure amounts.  
- Consider retry/queuing strategies for transient server failures and improved user messaging for payment denials.

---

## 👤 Author & Contact
**Tehsin Reza** — Data Analyst  
- GitHub: https://github.com/itztahsin786-commits  
- LinkedIn: https://www.linkedin.com/in/tahsin-analyst/
- Email: tehsin.reza010@gmail.com  
- Created: October 2025  
- Project type: Power BI / Data Analytics

---

## 📜 License (MIT)
- Anyone can use this code.  
- Anyone can modify or distribute it.  
- Please give proper credit to the original author.  
- The author is not legally responsible for issues arising from use.

---

> **Pro tip:** add 1–2 high-quality screenshots inside `screenshots/` and reference them in the README (e.g., `![Dashboard overview](screenshots/overview.png)`) — visual proof increases recruiter engagement.
