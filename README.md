# 🚗 US Traffic Accidents Analysis - Python EDA

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) ![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white) ![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=plotly&logoColor=white) ![Seaborn](https://img.shields.io/badge/Seaborn-4C8CBF?style=for-the-badge&logo=seaborn&logoColor=white) ![EDA](https://img.shields.io/badge/EDA-FF9800?style=for-the-badge&logo=googleanalytics&logoColor=white) ![Jupyter Notebook](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white) ![CSV](https://img.shields.io/badge/CSV-1572B6?style=for-the-badge&logo=files&logoColor=white) 

Exploratory data analysis of US traffic accidents from 2016-2023, analyzing patterns by time, location, weather, and severity using Python data science libraries.

## 🎯 What This Project Shows

This analysis explores US traffic accident patterns to understand:

- When accidents happen most (time, day, season)
- Where accidents occur most frequently (states)
- Weather conditions during accidents
- Accident severity patterns
- Rush hour and weekend vs weekday trends


## 📊 Dataset Information

**Source**: [US Accidents Dataset (Kaggle)](https://www.kaggle.com/datasets/sobhanmoosavi/us-accidents)

- **Time Period**: 2016-2023 (7 years of data)
- **Total Records**: 1 million accident records
- **Coverage**: 49 US states
- **Data Points**: Location, time, weather, severity, and more


## 📈 Key Analysis Results

### 1. **Day vs Night Accidents**

- **Day Accidents**: 538,199 (69%) - Much higher
- **Night Accidents**: 242,235 (31%) - Lower
- **Insight**: More accidents happen during daylight hours due to higher traffic volume


### 2. **Weekly Accident Patterns**

- **Highest**: Friday (172,961 accidents)
- **Weekdays**: 154k-173k accidents each day
- **Weekend**: Much lower (Sunday: 70,340)
- **Insight**: Work commute days have significantly more accidents


### 3. **Hourly Accident Distribution**

- **Morning Rush**: 7-9 AM peak (70k+ accidents)
- **Evening Rush**: 4-6 PM peak (73k+ accidents)
- **Lowest**: Late night/early morning (2-5 AM)
- **Insight**: Clear correlation with commuting patterns


### 4. **Geographic Distribution**

- **California**: 220,429 accidents (highest)
- **Florida**: 112,111 accidents
- **Texas**: 74,404 accidents
- **Other top states**: SC, NY, NC, PA, VA, MN, OR
- **Insight**: High-population states dominate accident statistics


### 5. **Temperature Analysis**

- **Peak Temperature**: 50°F-80°F (normal driving weather)
- **Highest**: Around 70°F (202,254 accidents)
- **Pattern**: Most accidents in moderate temperatures
- **Insight**: Accidents occur mainly in normal weather, not extreme conditions


## 🔍 Key Insights from Analysis

### Traffic Patterns

- **Weekday Dominance**: 85% of accidents happen Monday-Friday
- **Rush Hour Impact**: Clear spikes during 7-9 AM and 4-6 PM
- **Commuter Correlation**: Accidents align with work travel patterns


### Geographic Trends

- **Population Factor**: States with more people have more accidents
- **California Leading**: Nearly 2x more accidents than second-place Florida
- **Regional Distribution**: Concentrated in highly populated areas


### Weather Conditions

- **Normal Weather**: Most accidents happen in 50°F-80°F range
- **Moderate Conditions**: Extreme weather doesn't cause most accidents
- **Daily Activity**: Regular driving conditions see highest accident rates


### Severity Analysis

- **Severity 2**: Most common accident type (538k)
- **Day vs Night**: Day accidents show higher severity patterns
- **Traffic Volume**: More accidents when more cars are on road


### Time-Based Patterns

- **Daily Cycle**: Accidents follow work/commute schedules
- **Weekend Drop**: 60% fewer accidents on weekends
- **Seasonal Consistency**: Temperature data shows year-round patterns


## 🛠️ Python Libraries Used

- **pandas**: Data manipulation and cleaning
- **matplotlib**: Creating visualizations
- **seaborn**: Statistical plotting
- **numpy**: Numerical analysis
- **plotly**: Interactive charts


## 📁 Project Files

```
📦 us-accidents-eda/
├── 📄 README.md                           (This file)
├── 📓 EDA_US_accidents.html               (Jupyter notebook)
├── 📊 Accidents_by_Day_of_Week.png        (Weekly patterns)
├── 📊 Accidents_by_Daylight_vs_Night.png  (Day/night analysis)
├── 📊 Accidents_by_state.png              (Geographic distribution)
├── 📊 Accidents_vary_by_time_of_day.png   (Hourly patterns)
└── 📊 Temperature_Distribution_During_Accidents.png (Weather analysis)
```


## 🚀 How to Run This Analysis

### Prerequisites

- Python 3.7+
- Jupyter Notebook
- Libraries: pandas, matplotlib, seaborn, numpy


### Steps

1. **Download dataset** from [Kaggle](https://www.kaggle.com/datasets/sobhanmoosavi/us-accidents)
2. **Install packages**: `pip install pandas matplotlib seaborn numpy`
3. **Open notebook**: `jupyter notebook EDA_US_accidents.html`
4. **Run analysis** to see all visualizations and insights

## 💡 Data Science Skills Demonstrated

- ✅ **Large Dataset Handling**: Processing 3+ million records
- ✅ **Time Series Analysis**: Hourly, daily, weekly patterns
- ✅ **Geographic Analysis**: State-wise distribution
- ✅ **Data Visualization**: Multiple chart types and insights
- ✅ **Statistical Analysis**: Pattern recognition and correlation
- ✅ **Business Intelligence**: Actionable traffic safety insights


## 🔮 Real-World Applications

### Traffic Safety Planning

- **Rush Hour Management**: Focus safety measures during peak times
- **Weekend vs Weekday**: Different safety strategies needed
- **State-Level Insights**: Resource allocation based on accident volume


### Policy Development

- **Work Schedule Impact**: Understanding commute-related accidents
- **Geographic Targeting**: Focus on high-accident states
- **Weather Preparedness**: Most accidents in normal weather conditions


### Urban Planning

- **Infrastructure Design**: Account for rush hour accident patterns
- **Traffic Flow**: Reduce congestion during peak accident times
- **Public Transportation**: Alternative options during high-risk periods


## 📝 Key Findings Summary

1. **69% of accidents happen during day** due to higher traffic
2. **Weekdays have 2.5x more accidents** than weekends
3. **Rush hours (7-9 AM, 4-6 PM) show clear peaks** in accidents
4. **California leads with 220k+ accidents** - population correlation
5. **Most accidents occur in 50°F-80°F weather** - normal conditions
6. **Friday is the highest accident day** of the week
7. **Commuting patterns directly correlate** with accident timing

***

**Created by**: [sankaran-s2001](https://github.com/sankaran-s2001)
**Tools Used**: Python, Jupyter Notebook, pandas, matplotlib, seaborn
**Project Type**: Exploratory Data Analysis
**Domain**: Traffic Safety \& Transportation Analytics
**Dataset**: 1 million US accident records (2016-2023)

## ✉️ Contact

**Sankaran S**  
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/sankaran-s2001) [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sankaran-s21/) [![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:sankaran121101@gmail.com)

*Complete analysis of US traffic accidents revealing critical patterns for traffic safety and urban planning*
