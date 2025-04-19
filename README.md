#  Housing Index Analysis

*Exploratory data analysis of the U.S. housing market using the Case-Shiller index to identify high-return investment areas in 2016.*

---

##  Dataset Overview

- **Source:** [DataHub - House Prices US Dataset](https://datahub.io/core/house-prices-us#readme)
- **Variables:**
  - `date`: Date of housing index collection
  - `state`: U.S. state abbreviation
  - `city`: City name
  - `housing_index`: Numeric value representing housing price level

**Key Index Insights:**
- `100`: No change in housing prices  
- `<100`: Price decrease  
- `>100`: Price increase

> Note: Missing values may appear in early records for some cities due to incomplete data collection.

---

##  Project Context

 **Year:** 2016  
 **Client:** Central Bank Economic Studies Department  
 **Objective:**  
Support economists in identifying high-return housing markets in the U.S., with a special focus on West Coast states and cities.

---

##  Analysis Plan

- Calculate the national average housing index for recent years
- Determine recent average indexes for:
  - West Coast states
  - West Coast cities
- Highlight top-performing cities across the U.S. based on recent data

---

##  Tools & Technologies

- Python
- Pandas
- Google Sheets
- Jupyter Notebook

---

##  Project Structure

```
housing-index-analysis/
│
├── housing_index_analysis.ipynb
├── requirements.txt
└── README.md
```
---

##  Status

✔️ Project completed as part of the **TripleTen Bootcamp** – Sprint: *Spreadsheets for Data Analysis*

---

##  Author

David Villanueva  
[LinkedIn](https://www.linkedin.com/in/david-villanueva-59659727)  
[GitHub](https://github.com/lolapaul)
