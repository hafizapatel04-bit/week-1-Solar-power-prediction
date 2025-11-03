# week-1-Solar-power-prediction
Solar Plant Data Merge Project  This project cleans and merges solar power generation data with weather sensor data. The datasets were joined using DATE_TIME and SOURCE_KEY to create one final dataset for analysis or future machine learning work.  
Final Output: Merged_Plant_Data.csv 
Tools Used: Python, Pandas
# ☀️ Solar Plant Data Merge Project

This project focuses on cleaning and merging solar power generation data with weather sensor data to create a single unified dataset suitable for analysis and modeling.

## 📄 Objective

* Clean power generation dataset
* Clean weather sensor dataset
* Merge both datasets using `DATE_TIME` and `SOURCE_KEY`
* Produce a final ready-to-use dataset

## 🔗 Datasets Used

| File Name                           | Description                          |
| ----------------------------------- | ------------------------------------ |
| `Cleaned_Plant_Generation_Data.csv` | Cleaned solar power generation data  |
| `Plant_1_Weather_Sensor_Data.csv`   | Weather and irradiation measurements |
| `Merged_Plant_Data.csv` ✅           | Final merged dataset                 |

## 🧰 Tools & Libraries

* Python
* Pandas
* NumPy

## ⚙️ Key Steps

1. Loaded both datasets
2. Checked and handled missing values
3. Standardized timestamp formats
4. Merged datasets on:

   ```
   DATE_TIME
   SOURCE_KEY
   ```
5. Saved final merged dataset

## 🚀 How to Use

```python
import pandas as pd

merged = pd.read_csv("Merged_Plant_Data.csv")
merged.head()
```

## 🌱 Future Improvements

* Feature Engineering (hour, month, temperature-based effects)
* Visualizations of solar output trends
* ML Model to predict AC Power output

---

✨ *Made as part of a daily data analysis learning project*
