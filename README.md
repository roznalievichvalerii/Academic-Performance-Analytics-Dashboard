# Academic Performance & Analytics Dashboard

An interactive, dark-themed Power BI dashboard designed for educational institutions to monitor student performance, track test metrics, analyze historical trends, and forecast future academic outcomes.

## 📊 Visuals & Pages
![Academic Performance Overview](Academic%20Performance%20Overview.png)
![Analytics & Time Intelligence](Analytics%20&%20Time%20Intelligence.png)
![Class Performance](Class%20Performance.png)
![Class Details](Class%20Details.png)

## 🎯 Key Features
1. **Academic Performance Overview:** High-level executive summary of grades distributed by class sections and subjects using spectral conditional formatting.
2. **Analytics & Time Intelligence:** Advanced time-series analysis comparing Year-to-Date (YTD) metrics, Month-over-Month (MoM) performance shifts, and automated future grade forecasting.
3. **Class Performance:** Deep-dive into class statistics, breakdown of grade categories (Homework, Exams, Quizzes, Projects), and tracking of negative grade ratios.
4. **Class Details:** Granular row-level view showcasing individual student progress across all assessment types.

## 🛠️ Tech Stack & Architecture
* **BI Tool:** Power BI Desktop (Project format `.pbip`)
* **Data Modeling:** Star Schema (Fact table linked with Dim_Students, Dim_Calendar, Dim_Classes, Dim_Subjects)
* **UX/UI:** Premium Dark Theme, custom horizontal tab navigation, and responsive tooltips.
* **Advanced DAX Formulas:** Custom Time Intelligence measures built manually to handle specific school periods, bypassing standard calendar constraints.

## 🚀 How to Run
1. Clone this repository.
2. Open the `academic performance.pbip` file using Power BI Desktop.
