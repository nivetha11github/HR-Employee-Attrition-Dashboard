# 📊 Employee Attrition & Retention Analysis

A Power BI dashboard analyzing why employees leave — exploring department trends, 
overtime impact, and compensation gaps — to help HR teams prioritize retention efforts.

![Dashboard Preview](dashboardscreenshot.png)
## 🔍 Key Insights

- **Overall attrition rate: 16.1%** — roughly 1 in 6 employees left, on the higher end for most industries.
- **Sales has the highest attrition (20.6%)**, followed by HR (19.0%), while R&D is more stable (13.8%) — suggesting retention efforts should be prioritized in Sales first.
- **Overtime is the strongest predictor of attrition** — employees working overtime leave at nearly 3x the rate of those who don't (30.5% vs 10.4%).
- **Employees who leave earn ~30% less on average** ($4.8K vs $6.8K monthly) than those who stay, suggesting compensation plays a role alongside workload.

## 💡 Recommendation

HR should prioritize reducing mandatory overtime in the Sales department and review 
compensation bands for roles with high overtime and lower pay — this combination 
represents the strongest attrition risk profile in the data.
## 🛠️ Tools & Skills Used

- **Power BI Desktop** — data modeling, DAX measures, dashboard design
- **DAX** — custom measure for Attrition Rate (`DIVIDE` + `CALCULATE` + `COUNTROWS`)
- **Data Analysis** — attrition trend analysis across department, workload, and compensation
- **HR Analytics** — translating workforce data into actionable retention recommendations

## 📁 Files in this Repository

- `HR-Attrition-Dashboard.pbix` — Power BI dashboard file
- `WA_Fn-UseC_-HR-Employee-Attrition.csv` — source dataset (IBM HR Analytics, via Kaggle)
- `dashboardscreenshot.png` — dashboard preview image

## 📌 Dataset Source

[IBM HR Analytics Employee Attrition Dataset](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset) (Kaggle)
