# Key Features & Insights
- Patients who **did not receive SMS reminders** are significantly more likely to miss appointments.
- **Longer waiting days** between scheduling and appointment increases no-show risk.
- Certain **neighborhoods and age groups** show disproportionately high no-show patterns.
- Predictive model trained with **Decision Tree Classifier** (accuracy ~74%).

---

# Dashboard Features
Developed in Power BI:
- **Filters**: Gender, Weekday, SMS, Scholarship, Neighborhood
- **Charts**:
  - No-show rate by weekday
  - Age group vs no-show distribution
  - SMS reminder impact
  - Neighborhood heatmap
- **KPIs**: Total Appointments, No-show Rate, Avg Waiting Time

---

# Model Details
- **Model**: Decision Tree Classifier
- **Features Used**:
  - Age
  - Waiting Days
  - SMS_received
  - Hypertension, Diabetes, Scholarship
- **Target**: `No-show` (binary: 1 = missed, 0 = attended)

---

# Deliverables
- 📁 Cleaned and modeled dataset
- 📈 Power BI interactive dashboard
- 📘 Final project report in PDF
- 💻 Source notebook for training ML model


