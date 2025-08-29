# 🚀 Food Delivery Operations — SQL Case Study Project

**Author:** Sonal Anand  
**Duration:** 4 min read | Completed Aug 2025  

---

## 📌 Project Overview
This project simulates **real-world challenges** faced by food delivery platforms such as **Just Eat, Uber Eats, and Deliveroo**.  
Using a mock dataset of `orders` and `couriers`, I analysed delivery performance, customer experience, and courier efficiency using **advanced SQL**.

The aim was to replicate **real business reporting workflows**, where raw data is transformed into **actionable insights** for stakeholders.

---

## 🔍 Why This Project?
In business environments, stakeholders don’t need raw data dumps — they need **fast, targeted insights** that drive decisions.  
Each SQL question here mirrors how reporting works inside an analytics team:  

- Translate **business problem statements** into SQL logic  
- Extract **metrics** like delivery delay %, courier efficiency, complaint ratios  
- Deliver **actionable inferences** as if presenting in a dashboard or executive deck  

---

## ✅ Core SQL Skills Practiced
- 📊 **Aggregations & Ratios** — delay %, cancellation %, courier-to-order ratio  
- 📅 **Date & Time Analysis** — monthly trends, delivery durations, tenure-based grouping  
- 🧠 **Business Logic Simulation** — flags (`frequently_late`), route density analysis  
- 🧮 **Conditional Logic** — `CASE WHEN`, NULL handling, outlier detection  
- 📈 **Performance Monitoring** — ranking couriers, KPI thresholds, heatmaps  
- 🤝 **Join Logic & Groupings** — combining city, region, and courier-level metrics  

---

## 🗂️ Dataset Structure

**Orders Table**  
- order_id  
- courier_id  
- order_date  
- delivery_time  
- status (Completed / Cancelled / Delayed)  
- customer_complaint  

**Couriers Table**  
- courier_id  
- courier_name  
- city  
- vehicle_type (Bike / Car / Scooter)  
- avg_rating  
- join_date  

---

## 📊 Key Business Questions Answered

### Q1. Average delivery time across all orders  
**Goal:** Benchmark operational efficiency & SLA baselines  
➡️ Avg delivery time = **30.3 minutes**

---

### Q2. Which vehicle type is fastest?  
**Goal:** Optimise fleet allocation by city  
➡️ **Bikes** are fastest (28.4 mins), outperforming Cars & Scooters  

---

### Q3. What % of orders are delayed?  
**Goal:** Monitor SLA compliance  
➡️ **40% of orders delayed**, well above acceptable benchmarks  

---

### Q4. Top 5 cities with highest delay %  
**Goal:** Identify high-risk zones  
➡️ **Bristol (53.3%)**, Leeds (44.4%), London (37.5%)  

---

### Q5. Average rating of couriers delivering delayed orders  
**Goal:** Test reliability of courier ratings  
➡️ Even couriers with **4.9 rating** caused delays — ratings don’t always equal punctuality  

---

### Q6. Couriers late on >3 occasions  
**Goal:** HR / Ops performance flagging  
➡️ **Courier C203** was late **6 times**  

---

### Q7. Monthly order & delay trends  
**Goal:** Spot seasonal performance dips  
➡️ **Delays rose from 33% in June to 46% in July** due to demand surge  

---

### Q8. Cancellation-to-completion ratio by city  
**Goal:** Identify risk zones  
➡️ **Birmingham: 200%** (more cancellations than completions)  

---

### Q9. Avg delivery time by courier tenure  
**Goal:** Check if experience impacts performance  
➡️ No clear correlation; city & vehicle type influence more than tenure  

---

### Q10. Couriers marked “frequently late” but highly rated  
**Goal:** Explore misalignment in performance tracking  
➡️ **Courier C203** is frequently late but maintains **4.9 rating** → ratings don’t reflect SLA adherence  

---

## 🎯 Project Goal
To **demonstrate domain-specific problem solving with SQL**, while thinking like a **data analyst in delivery operations**.  
This project shows not just query writing, but **storytelling with data**: connecting SQL outputs to **real business actions**.

---

## 📌 Next Steps
- Build **Power BI dashboards** for visual storytelling  
- Add **predictive modelling** (e.g., delivery delay prediction using courier type, region, time of day)  
- Extend dataset with **customer satisfaction data** for full CX analysis  

---

## ⚡ How to Run
1. Clone this repo  
2. Import the SQL scripts into your preferred environment (PostgreSQL/MySQL/BigQuery)  
3. Run queries in sequence from `queries.sql`  
4. Compare your output with `inference.md` for business insights  

---

## 🏆 Takeaway
This project reflects the **real work of analysts at Just Eat, Uber Eats, or Deliveroo** — connecting SQL outputs to **commercial insights**, process improvements, and **strategic decision making**.
