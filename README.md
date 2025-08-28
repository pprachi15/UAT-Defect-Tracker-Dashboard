# UAT Defect Tracker Dashboard (Tableau)

An interactive **User Acceptance Testing (UAT) Defect Tracker Dashboard** built in Tableau.  
This dashboard simulates how QA managers and business analysts monitor **system readiness, defect resolution, and testing progress** during UAT cycles.  

It provides visibility into **defect severity, backlog trends, resolution speed, and test pass/fail rates**, enabling faster decision-making before go-live.  
<img width="1512" height="916" alt="image" src="https://github.com/user-attachments/assets/e435be80-bfc4-48c7-a7c6-f2e84b295b79" />


---

## 🚀 Dashboard Overview

The dashboard consolidates UAT testing data (5,000+ synthetic test cases) into an interactive view that supports:  
- Tracking **defect workflow health** (Open → In Progress → Resolved → Closed).  
- Monitoring **backlog trends** and identifying bottlenecks.  
- Comparing **severity vs priority** to focus on high-risk items.  
- Measuring **testing progress** with pass vs fail rates.  

Filters allow drill-down by:  
- Execution Month  
- Status (Open, Resolved, Closed, etc.)  
- Module (Billing, Claims, Policy Admin, Reporting, etc.)  
- Severity (Critical, Major, Minor)  
- Priority (High, Medium, Low)  
- Test Result (Pass/Fail)  

---

## 📌 Key KPIs

- **Total Test Cases Executed** – number of UAT cases run.  
- **Pass Rate %** – % of test cases that passed.  
- **Defect Density %** – ratio of defects found per test case.  
- **Defects by Severity** – count of Critical, Major, and Minor issues.  
- **Average Defect Resolution Days** – average time to close defects.  
- **Defect Status Distribution** – Open vs Resolved vs Closed defects.  

---

## 📊 Visualizations

1. **Defects by Severity (Bar Chart)**  
   Highlights distribution of defects across Critical, Major, and Minor.  

2. **Average Resolution Time Trend (Line Chart)**  
   Tracks how long it takes to resolve defects month by month.  

3. **Pass vs Fail by Module (Stacked Bar)**  
   Shows readiness of different modules (Billing, Claims, Policy Admin, etc.).  

4. **Defects Open vs Closed Over Time (Stacked Area Chart)**  
   Visualizes backlog build-up vs closure, helping managers see if UAT is under control.  

5. **Defects by Priority vs Severity (Heatmap)**  
   Cross-tab view showing how many defects fall into “Critical + High” or “Minor + Low” buckets.  

---

## 🎯 Why This Dashboard is Valuable

- **For QA Managers** → Provides real-time defect tracking and team performance insights.  
- **For Business Analysts** → Demonstrates system readiness and supports go/no-go decisions.  
- **For Executives** → Clear at-a-glance view of project health with KPIs and trends.  

---

## 🛠️ Tools & Tech

- **Tableau** → Dashboarding & interactivity  
- **Python / Excel** → Synthetic dataset creation (test cases + defects)  
- **GitHub** → Documentation and project portfolio  

---

## 📝 Insights & Takeaways

- Majority of defects are **Major/Minor**, but **Critical defects** must be prioritized before release.  
- Average resolution time is stable (~10 days), but spikes highlight resource bottlenecks.  
- Pass rate varies by module — Billing and Claims need more attention compared to Policy Admin.  
- Open vs Closed trend shows backlog stability → key metric for UAT exit criteria.  

---

## 🔮 Future Enhancements

- Add **Tester Productivity** (defects reported vs resolved per tester/team).  
- Build predictive alerts for modules with consistently high defect density.  
- Integrate with JIRA/Xray APIs for real UAT defect imports.  

---

## 📢 About

This project was built to demonstrate **business solutions analyst skills** in UAT defect tracking, defect resolution analytics, and executive dashboarding.  
It aligns with how companies like **Capital Insurance Group (CIG)** monitor UAT readiness before deploying new systems.  
