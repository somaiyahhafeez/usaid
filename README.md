# USAID Foreign Assistance Analysis

## 📊 Project Overview

This project aims to analyze the distribution of foreign assistance provided by the United States Agency for International Development (USAID) across different countries, looking at ten year's of data. The analysis utilizes data sourced from [ForeignAssistance.gov](https://www.foreignassistance.gov/).
With USAID facing aid cuts and employee lay offs, my aim was to look at how the agency has provided aid worldwide, particularly which countries have recieved highest aid.
## 🔍 Key Findings

- **Top 10 Countries Receiving USAID**: 
   - The analysis highlights which countries have consistently been the largest recipients of USAID over the years, shedding light on U.S. foreign aid priorities.
  
- **Ukraine’s Aid Trends**: 
   - An in-depth look at Ukraine’s aid distribution demonstrates how the country's foreign assistance has fluctuated, especially following major geopolitical events such as Russian invasion of Ukraine.


## 💾 Data Collection Process

The raw data was sourced from [ForeignAssistance.gov](https://www.foreignassistance.gov/), which provides detailed records of U.S. foreign assistance. CSV files (e.g., `results.csv`, `results(1).csv`) were downloaded and processed for this analysis.

The data was cleaned and prepared for analysis using Python, leveraging the `pandas` library to filter, group, and aggregate key information.

## 🧑‍💻 Data Analysis Process

The analysis is detailed in the `USAID.ipynb` Jupyter notebook. Here’s a summary of the steps taken:

1. **Data Import & Cleaning**: 
   - The raw CSV data was imported and 
  
2. **Top 10 Countries Analysis**: 
   - The countries receiving the highest amounts of aid were identified and visualized, providing insights into the global priorities of USAID.
  
3. **Ukraine Aid Trend Analysis**: 
   - A specific focus on Ukraine’s yearly aid was explored to visualize how the U.S. has adjusted its assistance over time.
  
4. **Data Visualization**: 
   - Several visualizations (using `matplotlib` and `seaborn`) were created to highlight trends in aid distribution and to make the findings more accessible.

## 🧠 Skills & Approaches

In this project, I utilized the following skills:

- **Data Manipulation**: 
   - Cleaned and prepared large datasets using the `pandas` library for analysis.
  
- **Data Visualization**: 
   - Created meaningful visualizations using `matplotlib` and `seaborn` to tell a story with the data.
  
- **Time-Series Analysis**: 
   - Analyzed trends in USAID’s funding, particularly focusing on year-by-year changes in aid distribution.
  
- **Jupyter Notebooks**: 
   - Documented the entire process in an interactive, shareable format to make the analysis reproducible.

This project helped me strengthen my skills in handling large datasets, cleaning messy data, and visualizing complex patterns effectively.

## 🚀 Future Improvements

Here are some aspects I wanted to explore further, but due to time constraints, were not included in this analysis:

- **Expansion to More Countries**: 
   - Analyzing additional countries or regions to provide a more comprehensive overview of U.S. foreign assistance globally.
  
- **Specific Program Analysis**: 
   - Investigating which specific programs or projects were funded by USAID, and how those projects have evolved.
  
- **Advanced Predictive Modeling**: 
   - Utilizing machine learning to predict future aid trends based on historical data.

## 📥 Data Used for Analysis

The data used for this analysis was sourced from [ForeignAssistance.gov](https://www.foreignassistance.gov/). Due to the size of the dataset (over 100MB), the raw CSV files are excluded from the repository but are still referenced for clarity.

The `.gitignore` file ensures that large files like raw CSVs are not tracked by version control.

## 📖 Notebooks

The analysis is conducted in the `USAID.ipynb` Jupyter notebook, where you can find detailed explanations of each step, from data import to final visualizations. Throughout the notebook, I’ve included commentary and questions to clarify the decisions and processes involved.

## 🛑 .gitignore

A `.gitignore` file is included in the repository to prevent large or unnecessary files (like raw data) from being committed to the GitHub repository.

---

Feel free to explore the project and explore how the USAID data changes over time!
