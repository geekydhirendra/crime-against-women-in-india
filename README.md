<div align="center">

<!-- Header Banner -->
<img src="assets/banner.png" alt="Project Banner" width="100%"/>

# 🔍 Crime Against Women in India
### A Comprehensive Data Analytics Project

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.9+-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Power_BI-Dashboard-F2C811?style=for-the-badge&logo=powerbi&logoColor=black"/>
  <img src="https://img.shields.io/badge/Pandas-Data_Analysis-150458?style=for-the-badge&logo=pandas&logoColor=white"/>
  <img src="https://img.shields.io/badge/Matplotlib-Visualization-11557c?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Status-Complete-2ea44f?style=for-the-badge"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Data_Years-2001--2023-orange?style=flat-square"/>
  <img src="https://img.shields.io/badge/Datasets-15_Files-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/Charts-18_Visualizations-green?style=flat-square"/>
  <img src="https://img.shields.io/badge/Dashboard_Pages-4-red?style=flat-square"/>
  <img src="https://img.shields.io/badge/States_&_UTs-36-purple?style=flat-square"/>
</p>

> **Analyzing 22+ years of NCRB crime data to uncover patterns, trends, and insights about crimes against women across all Indian States & Union Territories.**

[📊 View Dashboard](#-dashboard-preview) • [📈 Key Findings](#-key-findings) • [🚀 Getting Started](#-getting-started) • [📁 Project Structure](#-project-structure)

</div>

---

## 📋 Table of Contents

- [About the Project](#-about-the-project)
- [Dashboard Preview](#-dashboard-preview)
- [Key Findings](#-key-findings)
- [Dataset Information](#-dataset-information)
- [Project Structure](#-project-structure)
- [Tech Stack](#-tech-stack)
- [Getting Started](#-getting-started)
- [Analysis Sections](#-analysis-sections)
- [Charts & Visualizations](#-charts--visualizations)
- [Insights](#-insights)
- [Limitations](#️-limitations)
- [Author](#-author)
- [License](#-license)
- [References](#-references)

---

## 🎯 About the Project

This project presents a **comprehensive data analytics study** of crimes committed against women in India, spanning **22+ years (2001–2023)**. Using data from the **National Crime Records Bureau (NCRB)** — the official government body under the Ministry of Home Affairs — this project analyzes crime patterns across:

- 📅 **22+ years** of historical data (2001–2023)
- 🗺️ **All 36 States & Union Territories** of India
- 🏘️ **1,140+ districts** across the country
- 📊 **8 major crime categories** + cyber crimes
- 👮 **Arrest & justice rate** analysis

### 🎯 Objectives

```
1. Identify long-term trends in crimes against women (2001–2021)
2. Compare state-wise and district-wise crime distribution
3. Analyze the impact of key events (Nirbhaya Case, COVID-19)
4. Evaluate law enforcement effectiveness through arrest rates
5. Study emerging cyber crimes against women (2023)
```

---

## 🖥️ Dashboard Preview

> **Interactive Power BI Dashboard — 4 Pages**

| Page | Description |
|------|-------------|
| ![Page 1](https://github.com/geekydhirendra/crime-against-women-in-india/blob/398012a7db9a6fda14d94e8211963a44985be289/page1_main_analysis.png) | **Main Analysis** — Year-wise trends, state comparison, crime distribution |
| ![Page 2](https://github.com/geekydhirendra/crime-against-women-in-india/blob/59a7b114713ac987ca2ddab14f767bd962abe0b1/page2_district_analysis.png) | **District Analysis** — Top 20 dangerous districts, drill-down |
| ![Page 3](https://github.com/geekydhirendra/crime-against-women-in-india/blob/bb4da7577327cf261ec7a918904278b4b592874a/page3_arrests_justice.png) | **Arrests & Justice** — Arrest rates, crime vs arrest comparison |
| ![Page 4](https://github.com/geekydhirendra/crime-against-women-in-india/blob/98d379c863b2cdbeaa8fb043a901d36577e61bc3/page4_cyber_crime.png) | **Cyber Crime 2023** — State-wise cyber crimes, type distribution |

---

## 📊 Key Findings

<div align="center">

| # | 🔍 Finding | 📈 Value |
|---|-----------|---------|
| 1 | Total crimes growth (2001–2021) | **+170.8%** |
| 2 | Total crimes reported (2001–2021) | **48,67,722** |
| 3 | Highest crime state (cumulative) | **Uttar Pradesh — 5,29,734** |
| 4 | Most common crime type | **Domestic Violence — 39.2%** |
| 5 | Post-Nirbhaya reporting surge | **+46.8% (2013–2021 vs 2001–2012)** |
| 6 | Rape cases growth in 20 years | **+101.8% (15,694 → 31,677)** |
| 7 | Average arrest rate (2001–2012) | **183.1%** |
| 8 | Most dangerous district | **Murshidabad, WB — 37,010 crimes** |
| 9 | Worst cyber crime state (2023) | **Karnataka — 7,002 cases** |
| 10 | Total cyber crimes (2023) | **19,510** |

</div>

### 🔑 Headline Statistics

```
📈 CRIME GROWTH          🗺️ WORST STATE           ⚖️ MOST COMMON CRIME
   170.8% in 20 years       Uttar Pradesh            Domestic Violence
   1.28L → 3.48L crimes     5,29,734 total           39.2% of all crimes

👮 ARREST RATE           💻 CYBER CRIMES           🏘️ WORST DISTRICT
   183.1% average           19,510 in 2023           Murshidabad, WB
   (Multiple accused)       Karnataka leads          37,010 cumulative
```

---

## 📁 Dataset Information

### Source Files (15 CSV files)

| # | File | Years | Records | Key Columns |
|---|------|-------|---------|-------------|
| 1 | CrimesOnWomenData.csv | 2001–2021 | 736 | State, Year, 8 crime types |
| 2 | Crime Against Women 2001-2012.csv | 2001–2012 | 324 | State, Crime Head, Year-wise |
| 3 | Crime Against Women 2013.csv | 2013 | ~40 | State, Crime Head |
| 4 | Crime Against Women 2014.csv | 2014 | ~40 | State, Crime Head |
| 5 | Crime against Women 2001-2022.csv | 2001–2022 | 11 | Crime Head, Year-wise |
| 6 | District-wise 2001-2012.csv | 2001–2012 | 8,000+ | State, District, Year |
| 7 | District-wise 2013.csv | 2013 | ~800 | State, District |
| 8 | District-wise 2014.csv | 2014 | ~800 | State, District |
| 9 | District Area-wise 2015.csv | 2015 | ~800 | State, District |
| 10 | NCRB District Wise 2022.csv | 2022 | ~800 | State, District, 55 columns |
| 11 | Persons Arrested 2001-2012.csv | 2001–2012 | ~400 | State, Crime Head, Arrested |
| 12 | Cyber Crimes 2023.csv | 2023 | 36 | State, 6 cyber crime types |
| 13 | State & UT-wise 2015.csv | 2015 | 39 | State, 123 columns |
| 14 | Crime Head-wise 2023.csv | 2023 | 39 | State, 164 columns |
| 15 | data 2019-2021.csv | 2019–2021 | ~120 | State, Category, Year |

### Cleaned Datasets (7 CSV files)

```
data/cleaned/
├── CLEAN_main_data.csv        → Primary dataset (2001–2021, state-wise)
├── CLEAN_district_data.csv    → District-level data (2001–2022)
├── CLEAN_arrested_data.csv    → Arrests data (2001–2012)
├── CLEAN_cyber_data.csv       → Cyber crimes (2023)
├── CLEAN_national_trend.csv   → National crime head trends
├── CLEAN_2015_crime_rate.csv  → Crime rate per lakh women (2015)
└── CLEAN_2023_detail.csv      → Detailed 2023 state-wise data
```

### Data Sources

```
📌 Primary Source   : NCRB (National Crime Records Bureau)
📌 Portal           : data.gov.in (Open Government Data Platform)
📌 Compiled Dataset : Mendeley Data (2001-2022)
📌 Ministry         : Ministry of Home Affairs, Government of India
```

---

## 📂 Project Structure

```
📁 crime-against-women-india/
│
├── 📁 data/
│   ├── 📁 raw/                    ← Original 15 CSV files from NCRB
│   └── 📁 cleaned/                ← 7 processed & cleaned datasets
│
├── 📁 notebooks/
│   └── crime_analysis.ipynb       ← Complete Python analysis notebook
│
├── 📁 charts/                     ← 18 high-resolution visualizations
│   ├── 01_yearly_trend.png
│   ├── 02_top10_states.png
│   ├── 03_crime_type_pie.png
│   ├── 04_heatmap.png
│   ├── 05_category_trend.png
│   ├── 06_before_after_nirbhaya.png
│   ├── 07_top20_districts.png
│   ├── 08_district_heatmap.png
│   ├── 09_district_trend.png
│   ├── 10_arrests_trend.png
│   ├── 11_crime_arrests.png
│   ├── 12_justice_rate.png
│   ├── 13_cyber_top10.png
│   ├── 14_cyber_types.png
│   ├── 15_cyber_heatmap.png
│   ├── 16_national_trend.png
│   ├── 17_crime_rate_2015.png
│   └── 18_top10_2023.png
│
├── 📁 dashboard/
│   ├── crime_dashboard.pbix       ← Power BI Dashboard file
│   ├── crime_dashboard.pdf        ← Exported PDF version
│   └── 📁 screenshots/            ← 4 page screenshots
│       ├── page1_main_analysis.png
│       ├── page2_district_analysis.png
│       ├── page3_arrests_justice.png
│       └── page4_cyber_crime.png
│
├── 📁 report/
│   └── final_report.pdf           ← Complete project report
│
├── README.md                      ← You are here
├── requirements.txt               ← Python dependencies
└── .gitignore
```

---

## 🛠️ Tech Stack

<div align="center">

| Category | Technology | Purpose |
|----------|-----------|---------|
| **Language** | Python 3.9+ | Data processing & analysis |
| **Data Manipulation** | Pandas, NumPy | Cleaning, merging, transforming |
| **Visualization** | Matplotlib, Seaborn | 18 statistical charts |
| **Dashboard** | Microsoft Power BI | Interactive 4-page dashboard |
| **Notebook** | Google Colab | Cloud-based Python environment |
| **Report Design** | Canva | Final presentation design |
| **Version Control** | GitHub | Code & file management |

</div>

---

## 🚀 Getting Started

### Prerequisites

```bash
Python 3.9+
Jupyter Notebook or Google Colab
Microsoft Power BI Desktop (for dashboard)
```

### Installation

```bash
# 1. Clone the repository
git clone https://github.com/[your-username]/crime-against-women-india.git

# 2. Navigate to project directory
cd crime-against-women-india

# 3. Install required packages
pip install -r requirements.txt

# 4. Open the notebook
jupyter notebook notebooks/crime_analysis.ipynb
```

### Requirements

```
pandas==2.0.0
numpy==1.24.0
matplotlib==3.7.0
seaborn==0.12.0
plotly==5.14.0
jupyter==1.0.0
```

### Running the Analysis

```python
# The notebook is divided into sections:

# Section 1 — Data Loading & Exploration
# Section 2 — Data Cleaning
# Section 3 — Main Analysis (Charts 1-6)
# Section 4 — District Analysis (Charts 7-9)
# Section 5 — Arrests Analysis (Charts 10-12)
# Section 6 — Cyber Crime Analysis (Charts 13-15)
# Section 7 — Additional Analysis (Charts 16-18)
```

---

## 📈 Analysis Sections

### 1️⃣ Main Analysis (2001–2021)

```
Data: CrimesOnWomenData.csv + additional files
Coverage: All 36 States & UTs
Charts: 6 visualizations

Key Questions Answered:
→ How have crimes grown over 20 years?
→ Which states are the worst?
→ What is the most common crime type?
→ Did the Nirbhaya case change anything?
```

### 2️⃣ District Level Analysis (2001–2022)

```
Data: 5 district-wise CSV files merged
Coverage: 1,140+ districts
Charts: 3 visualizations

Key Questions Answered:
→ Which are India's most dangerous districts?
→ How do districts within a state compare?
→ Which districts show fastest growth?
```

### 3️⃣ Arrests & Justice Analysis (2001–2012)

```
Data: Persons Arrested file
Coverage: All states, 12 years
Charts: 3 visualizations

Key Questions Answered:
→ What is the arrest rate for each crime type?
→ Is the justice system becoming more effective?
→ Which crime sees highest/lowest arrests?
```

### 4️⃣ Cyber Crime Analysis (2023)

```
Data: Cyber Crimes 2023 + Crime Head 2023
Coverage: All states, year 2023
Charts: 3 visualizations

Key Questions Answered:
→ Which states have the most cyber crimes?
→ What type of cyber crime is most common?
→ How do 2023 total crimes compare by state?
```

---

## 📊 Charts & Visualizations

### Main Analysis Charts

| Chart | Title | Key Insight |
|-------|-------|-------------|
| 01 | Year-wise Crime Trend | 170.8% growth in 20 years |
| 02 | Top 10 States | UP leads with 5.29L crimes |
| 03 | Crime Type Distribution | Domestic Violence = 39.2% |
| 04 | State vs Crime Heatmap | WB highest in Domestic Violence |
| 05 | Category-wise Trend | Cruelty (498A) fastest growing |
| 06 | Before vs After Nirbhaya | 46.8% surge post-2012 |

### District Analysis Charts

| Chart | Title | Key Insight |
|-------|-------|-------------|
| 07 | Top 20 Dangerous Districts | Murshidabad #1 (37,010) |
| 08 | District Crime Heatmap | WB dominates top districts |
| 09 | District Year-wise Trend | Mumbai Commr. fastest growing |

### Arrests & Justice Charts

| Chart | Title | Key Insight |
|-------|-------|-------------|
| 10 | Year-wise Arrests Trend | Arrests grew 61.9% (2001-2012) |
| 11 | Crime-type wise Arrests | Marital Cruelty = most arrested |
| 12 | Justice Rate Analysis | 183.1% average arrest rate |

### Cyber Crime Charts

| Chart | Title | Key Insight |
|-------|-------|-------------|
| 13 | Top 10 Cyber Crime States | Karnataka = 7,002 cases |
| 14 | Cyber Type Distribution | Other Cyber = 74.2% |
| 15 | Cyber Crime Heatmap | State × Type matrix |

### Additional Analysis Charts

| Chart | Title | Key Insight |
|-------|-------|-------------|
| 16 | National Crime Head Trend | Cruelty surged post-2012 |
| 17 | Crime Rate per Lakh Women | Delhi = 184.3 per lakh |
| 18 | Top 10 States 2023 | UP leads with 66,381 crimes |

---

## 💡 Insights

### 📌 Insight 1 — The 20-Year Growth Story
```
2001: 1,28,537 crimes  →  2021: 3,48,092 crimes
Growth: +170.8% in 20 years

The numbers reflect both actual increase in crimes
AND increased reporting awareness post-Nirbhaya (2012).
```

### 📌 Insight 2 — The Nirbhaya Effect
```
Before Nirbhaya (2001–2012): 1,972,456 total crimes
After Nirbhaya (2013–2021):  2,895,266 total crimes
Increase: +46.8%

The 2012 Delhi gang rape case triggered massive
legal reforms and encouraged more women to report.
```

### 📌 Insight 3 — Domestic Violence Dominates
```
Domestic Violence: 19,09,978 cases (39.2%)
Assault on Women:  11,62,229 cases (23.9%)
Kidnapping:         8,35,023 cases (17.2%)

The home remains the most dangerous place for women.
Protection of Women from Domestic Violence Act (2005)
improved reporting but not prevention.
```

### 📌 Insight 4 — The COVID-19 Dip
```
2019: 3,33,717 crimes
2020: 3,02,166 crimes  ← -9.5% dip
2021: 3,48,092 crimes  ← Bounce back

The 2020 dip is attributed to lockdown restricting
access to police stations, NOT actual crime reduction.
Studies suggest domestic violence INCREASED during
COVID but went largely unreported.
```

### 📌 Insight 5 — Murshidabad — India's Most Dangerous District
```
District: Murshidabad, West Bengal
Cumulative crimes (2001–2022): 37,010

4 of the top 5 most dangerous districts
are from West Bengal alone — indicating
a systemic issue requiring state-level intervention.
```

### 📌 Insight 6 — The Arrest Rate Paradox
```
Average arrest rate: 183.1%
(> 100% because multiple accused per crime)

2011 had highest rate: 203.8%
Despite lower crimes (1,78,529),
more arrests (3,63,802) → better policing.

2012 had lowest rate: 167.8%
Crimes surged post-Nirbhaya but
police capacity couldn't keep up.
```

### 📌 Insight 7 — Delhi's Crime Rate Reality
```
Crime rate per lakh women (2015):
Delhi:  184.3  ← Highest in India
Assam:  148.2  ← 2nd highest
National Average: 50.5

While UP has highest absolute numbers,
Delhi has highest RATE relative to population.
Small area + high density + better reporting = high rate.
```

### 📌 Insight 8 — Cyber Crime: The New Frontier
```
Total cyber crimes against women (2023): 19,510

Most common type: Other Cyber Crimes (74.2%)
Includes: Blackmailing, Defamation, Morphing,
          Fake Profiles, Harassment

Karnataka leads: 7,002 cases (35.9% of national total)
High IT sector presence = higher digital crime exposure.
```

---

## ⚠️ Limitations

```
1. UNDERREPORTING
   Data reflects only REPORTED crimes.
   Actual crimes are significantly higher
   due to social stigma and fear.

2. DATA GAPS
   Arrest data only available till 2012.
   District-level data missing for some years.
   Cyber crime detailed data only from 2023.

3. BOUNDARY CHANGES
   District boundaries changed over 22 years.
   New states formed (Telangana 2014,
   Ladakh 2019) affect comparisons.

4. DEFINITIONAL CHANGES
   IPC sections and crime definitions
   changed over years, affecting comparability.

5. REPORTING BIAS
   Post-Nirbhaya surge may reflect
   increased reporting, not actual
   increase in crimes.
```

---

## 📜 References

```
[1] National Crime Records Bureau (NCRB)
    Annual Report on Crime in India
    https://ncrb.gov.in

[2] Open Government Data Platform India
    Crime Against Women Datasets
    https://data.gov.in

[3] Mendeley Data — Compiled NCRB Dataset
    Crime Against Women 2001-2022
    https://data.mendeley.com

[4] Ministry of Home Affairs, Government of India
    https://mha.gov.in

[5] Protection of Women from Domestic Violence Act, 2005
    Ministry of Women & Child Development

[6] Criminal Law (Amendment) Act, 2013
    Post-Nirbhaya legal reforms
```

---

## 👤 Author

<div align="center">

**DHIRENDRA SINGH**

*Data Analytics Portfolio Project*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/dhirendra-singh-621371309/)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/geekydhirendra)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:your-dhirendraa4141@gmail.com)

</div>

---

## 📜 License

```
This project is created for academic and research purposes only.

Data © National Crime Records Bureau (NCRB),
Ministry of Home Affairs, Government of India.

All visualizations and analysis are original work.
Please cite this project if you use it for research.
```

---

<div align="center">

**⭐ If this project helped you, please give it a star! ⭐**

*Made with ❤️ for data-driven social awareness*

![Visitor Count](https://visitor-badge.laobi.icu/badge?page_id=your-username.crime-against-women-india)

</div>
