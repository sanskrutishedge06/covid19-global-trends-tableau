# 🦠 COVID-19 Global Trends Dashboard — Tableau

![Dashboard Preview](screenshots/dashboard_preview.png)

## 📌 Project Overview

This project explores global COVID-19 trends using an interactive Tableau dashboard. It analyzes confirmed cases, fatalities, and daily trends across countries and continents to uncover patterns in the spread of the pandemic.

---

## 🎯 Objective

To identify and visualize:
- Global spread of COVID-19 across countries
- Daily trend of confirmed cases over time
- Top 10 countries by confirmed cases
- Top 10 countries by total fatalities

---

## 📂 Dataset

- **Source:** [Kaggle — COVID-19 Global Dataset](https://www.kaggle.com/datasets/josephassaker/covid19-global-dataset)
- **File used:** `covid-19.csv`
- **Records:** 27,231 rows × 6 columns
- **Columns:** `Id`, `Province State`, `Country Region`, `Date`, `Confirmed Cases`, `Fatalities`

---

## 📊 Dashboard Visualizations

| Sheet | Chart Type | Description |
|---|---|---|
| World Map | Filled Map | COVID-19 confirmed cases by country — darker = more cases |
| Daily Trend | Line Chart | Daily confirmed cases over time (Jan–Apr 2020) |
| Top 10 Countries | Bar Chart | Top 10 countries by total confirmed cases |
| Top 10 by Deaths | Bar Chart | Top 10 countries by total fatalities |

---

## 🛠️ Tools Used

- **Tableau Public Desktop** — Dashboard building & visualization
- **Microsoft Excel / CSV** — Raw data format
- **GitHub** — Project hosting and version control

---

## 🚀 How to Open the Dashboard

1. Download and install [Tableau Public](https://public.tableau.com/en-us/s/download) (free)
2. Clone this repository:
   ```
   git clone https://github.com/SanskrutiShedge/covid19-global-trends-tableau.git
   ```
3. Open the file `dashboard/covid19_dashboard.twbx` in Tableau Public Desktop
4. The dashboard will load with all 4 interactive sheets

---

## 📁 Repository Structure

```
covid19-global-trends-tableau/
├── data/
│   └── covid-19.csv
├── dashboard/
│   └── covid19_dashboard.twbx
├── screenshots/
│   └── dashboard_preview.png
└── README.md
```

---

## 💡 Key Insights

- The **United States** recorded the highest number of confirmed cases in the early months of 2020
- **Italy** had the highest fatality count among the top 10 countries
- Daily cases grew **exponentially** from February to April 2020
- The world map reveals that **Europe and North America** were the most heavily impacted regions

---

## 👩‍💻 Author

**Sanskruti Shedge**  
Data Science Student  
[GitHub Profile](https://github.com/SanskrutiShedge)

---

## 📄 License

This project is licensed under the MIT License.
