# 🐾 Animal Shelter Analysis

_Understanding animal intake, risk, length-of-stay, and outcomes to improve shelter operations and live-release performance._

---

## Quick Look

- **Total Intakes (2020–2025):** ~32,000 animals (+23% YoY)  
- **Primary Intake Type:** Strays and special-case animals (highest volume & risk)  
- **Average Length of Stay:** 21–26 days; cats & small animals longest  
- **Live Release Rate (LRR):** ~78%; adoption & rescue programs are key  
- **High-Risk Bottlenecks:** Repeat intakes, seasonal surges, special-case subtypes
-  **Dataset:** [View the Raw Dataset]()
- **Interactive Dashboard:** [View Power BI Report](https://app.powerbi.com/view?r=eyJrIjoiZTViYTg2MmMtZjcxNy00OTA2LTk3MDAtMmZmM2YwMTBkZjI1IiwidCI6IjdlMGI1ZmNmLTEyYzQtNGVmZi05NmI2LTQ2NjRmMjVkYzdkYSIsImMiOjEwfQ%3D%3D)  
- **Full Story & Deep Dive:** [Read Full Analysis on Medium](https://medium.com/@odzainab1/animal-shelter-analysis-c8fa4e627c0e)


---

## Introduction

Every day, animals arrive at the shelter with unique stories. Some are lost, surrendered, or injured; others face long-term care challenges. Each record represents a life moving through the system, where outcomes depend on **timely care, available capacity, and targeted interventions**.

This project analyzes **shelter intake, risk, and outcome data from 2020–2025** to uncover operational pressures, high-risk populations, and factors that affect live-release rates. The goal is to turn **raw intake records into actionable insights**, guiding staffing, foster programs, adoption campaigns, and preventive initiatives.

---

## Business Questions

The analysis focuses on:

- How do intake and outcome patterns evolve over time?  
- Which animals face longer stays or higher risk of non-live outcomes?  
- What drives successful outcomes (adoptions, transfers, reunifications)?  
- How do intake sources and conditions influence operational workload?  
- Where are opportunities to optimize shelter performance and animal welfare?

---


**Key Tables:**  
- Animal characteristics: species, age, sex, breed  
- Intake details: type, condition, source, date  
- Outcome details: type, date, live vs non-live  

**Tools Used:**  
- Power Query – Data cleaning and transformation  
- Power BI – Data modeling, DAX measures, and visualization  

---

## Data Preparation & Validation

- Standardized intake and outcome labels for consistency  
- Created intake status indicators and calculated up-to-date **length-of-stay (LOS)**  
- Derived **risk severity** (mild, moderate, severe) and intake subtype categories  
- Built **Date dimension tables** for trend and seasonality analysis  
- Validated relationships between intake, outcome, and analytical tables  
- Tested key metrics: total intake, adoptions, repeat intakes, LRR%, return-to-intake ratio, average LOS  

**Outcome:** a clean, analysis-ready dataset enabling **cross-dimensional insights** into intake trends, risk exposure, and adoption performance.

---
## Data Visualization

<img width="1036" height="591" alt="Screenshot 2026-01-08 213412" src="https://github.com/user-attachments/assets/f621de90-c625-4073-bb0c-b0365dcb1881" />


<img width="1023" height="581" alt="Screenshot 2026-01-08 213425" src="https://github.com/user-attachments/assets/aee6a8b9-2de7-4ea0-9682-be5d63d70b04" />



<img width="1036" height="592" alt="Screenshot 2026-01-08 213449" src="https://github.com/user-attachments/assets/49349301-010f-47ac-97de-3404f470c539" />




<img width="1030" height="601" alt="Screenshot 2026-01-08 213503" src="https://github.com/user-attachments/assets/3d584310-2703-4b91-a158-4a790e53dbf5" />

## Key Insights

### 1. Intake pressure drives operational risk
Strays and special-case intakes dominate (~22,000 animals), particularly in **spring and summer**, causing predictable capacity and staffing pressure. Weekends and midweek peaks intensify the load.

### 2. Length-of-stay is the primary bottleneck
High-risk animals, cats, and small mammals (rabbits, guinea pigs) remain longest in the shelter, consuming resources and increasing non-live outcome risk. LOS improvements for these groups could materially enhance throughput.

### 3. Repeat intakes compound inefficiency
~2,130 animals returned more than once, predominantly dogs and cats. Repeat admissions increase cost per animal and occupy shelter space without adding net placement outcomes.

### 4. Live-release performance is strong but sensitive
Overall **LRR ~78%**, supported by adoptions (~8,670) and rescues (~7,970). However, complexity in intake mix and prolonged stays are starting to reduce efficiency.

### 5. Species-level differences highlight targeted opportunities
- Cats: longer LOS, high adoption demand  
- Small mammals: very long LOS, lower adoption volume  
- Wildlife & amphibians: low live-release rates, regulatory or placement constraints  

---

## Recommendations

1. **Optimize Resource Allocation**  
   Adjust staffing and medical coverage for seasonal peaks and high-risk intake days.

2. **Targeted Community Outreach & Preventive Programs**  
   Focus on high “special case” and stray intake areas. Promote education and community engagement.

3. **Improve Adoption & Placement Programs**  
   Expand foster-to-adopt and rescue partnerships for species with longer LOS.

4. **Manage Repeat Intakes**  
   Implement post-adoption support to reduce avoidable returns.

5. **Monitor & Reduce LOS**  
   Prioritize rapid medical and behavioral interventions for high-risk animals.

---

## Next Steps

- Implement operational and preventive recommendations  
- Track KPIs: LRR%, repeat intake rate, LOS by species/intake type  
- Leverage the Power BI dashboard for decision support and resource allocation  
- Conduct quarterly reviews of intake patterns, outcomes, and program effectiveness  

---

## Conclusion

The shelter maintains strong throughput and adoption success, but **structural risks remain**. By addressing high-risk intakes, seasonal surges, repeat admissions, and prolonged LOS, the shelter can improve **live-release rates**, reduce **capacity strain**, and enhance **animal welfare**.

