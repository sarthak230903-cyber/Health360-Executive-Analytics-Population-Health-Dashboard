# 🏥 Health360: Executive Analytics & Population Health Dashboard

Health360 is an enterprise-grade Tableau Business Intelligence solution designed to transform complex, multi-dimensional patient datasets into actionable population health insights. By integrating clinical vitals, lifestyle metrics, demographic stratifications, and symptom prevalence, Health360 equips executive healthcare leaders with real-time risk stratification tools.

---

## 📌 Project Overview
- **Domain:** Healthcare Analytics & Business Intelligence
- **Cohort Size:** 5,000 Patient Records (`smart_healthcare_dataset.csv`)
- **Architecture:** CSV ➔ Tableau Data Extract (`.hyper`) ➔ Master Dashboard & Executive Story
- **Deployment Platform:** Tableau Public Cloud Engine

---

## 🎯 Key Executive Personas & Target Scenarios

### Scenario 1: Dr. Michael Carter — Clinical Risk Assessment Officer
- **Challenge:** Struggled with manual analysis of patient records, making it difficult to detect early disease patterns for conditions like Heart disease, Diabetes, and Stroke, leading to delayed interventions and higher treatment costs.
- **Tableau Solution & Capabilities:** Evaluates clinical indicators (BMI, blood pressure, cholesterol, and glucose levels) via interactive scatter plots and KPI scorecards to quickly spot high-risk individuals, monitor disease prevalence, and support timely clinical decision-making.

### Scenario 2: Emily Rodriguez — Healthcare Data Analyst
- **Challenge:** Needed to uncover complex correlations between lifestyle behaviors (smoking habits, alcohol consumption, exercise levels) and chronic disease outcomes across large, manual datasets.
- **Tableau Solution & Capabilities:** Utilizes lifestyle heatmaps, trend analysis charts, and co-occurrence stacked bars to visualize how behavioral habits compound health risks, enabling data-backed preventive care strategies.

### Scenario 3: Dr. Priya Nair — Public Health Researcher
- **Challenge:** Required population-wide visibility into demographic variations, vulnerable patient segments, and symptom prevalence to design targeted health initiatives.
- **Tableau Solution & Capabilities:** Leverages demographic pyramids, BMI classification breakdowns, and multi-metric symptom distribution charts across life stages to identify vulnerable cohorts and inform public health policy and awareness programs.

---

## 📊 Core Features & Visualizations
- **Executive BAN Scorecards:** High-level metrics tracking Total Patients (5,000), Baseline Risk (1.57), Chronic Rate (36%), and High-Risk Count (3,798).
- **Vitals Risk Scatter Plot:** Quadrant analysis mapping Blood Pressure vs. Cholesterol color-coded by composite risk score.
- **Behavioral Risk Heatmap:** Matrix cross-tabulating lifestyle habits against average calculated risk.
- **Demographic Pyramids & BMI Breakdown:** Life-stage patient distribution and weight classification split.
- **Single-Screen Master Dashboard:** Unified canvas linking 9 worksheets with instant global cross-filtering (<0.5s latency).
- **9-Point Tableau Story:** Guided narrative walking stakeholders through baseline KPIs to acute symptom patterns.

---

## 🛠️ Technology Stack
- **Data Visualization Engine:** Tableau Desktop Professional
- **Extract Engine:** In-Memory Tableau Data Extract (`.hyper`)
- **Calculated Logic (9 Calculated Fields):** 
  - `Age Category` & `BMI Category` (Demographic binning)
  - `Exercise Level Label`, `Smoking Status`, & `Alcohol Usage` (Behavioral labeling)
  - `Calculated Risk Score` (Multi-factor composite clinical risk scoring model)
  - `High Risk Patient Count`, `Sedentary Population Rate`, & `Chronic Condition Rate` (Executive KPI aggregations)
- **Hosting:** Tableau Public Server

---

## 🔗 Live Interactive Links & Resources
- **Tableau Public Master Dashboard & Executive Story:**  
  [View Live Project on Tableau Public](https://public.tableau.com/views/Health360PatientInsightsRiskStory/Health360MasterDashboard?:language=en-US&:display_count=n&:origin=viz_share_link)
- **Project Dataset:**  
  [Download 5,000 Patient Record Dataset](https://drive.google.com/file/d/1RDbCMrWJaLQUufYcGbI6m9LgTvuJQcv2/view)
  
---

## 👤 Project Author
- **Developer:** Sarthak Siddharth Sahare
- **Project Track:** Data Analytics & Business Intelligence (Tableau Track)
