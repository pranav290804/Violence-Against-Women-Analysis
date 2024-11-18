# Analysis on Violence Against Women

This project leverages data from the Demographic and Health Surveys (DHS) Program to analyze attitudes and perceived justifications for violence against women across African, Asian, and South American countries. The aim is to uncover patterns and key factors influencing these attitudes to support efforts to eliminate violence against women globally.

---

## Table of Contents
1. [Project Overview](#project-overview)
2. [Dataset Description](#dataset-description)
3. [Key Insights](#key-insights)
4. [Technologies Used](#technologies-used)
5. [Installation and Setup](#installation-and-setup)
6. [Usage](#usage)

---

## Project Overview

### Purpose
This analysis highlights how sociodemographic factors like education, employment, and marital status influence perceptions of violence against women. Insights gained aim to inform policies and awareness campaigns for reducing gender-based violence.

### Objectives
- Identify demographic factors that justify violence against women.
- Emphasize the importance of education in shaping attitudes.
- Create visualizations and summaries for global and regional insights.

---

## Dataset Description

The dataset, sourced from DHS, includes the following features:
- **RecordID**: Unique identifier for each survey entry.
- **Country**: Country where the survey was conducted.
- **Gender**: Gender of the respondent (Male/Female).
- **Demographics Question**: Type of demographic grouping (e.g., marital status, education).
- **Demographics Response**: Respondent's demographic category.
- **Question**: Survey question exploring attitudes toward violence.
- **Survey Year**: Year of the survey.
- **Value**: Percentage of respondents agreeing with the statement.

---

## Key Insights
- **Education**: Respondents with higher education levels are less likely to justify violence against women.
- **Public Awareness**: Campaigns targeting awareness and education can significantly reduce harmful attitudes.
- **Global Trends**: There are regional differences in attitudes, requiring localized interventions.

---

## Technologies Used
- **Python Libraries**: 
  - `pandas` and `numpy` for data manipulation.
  - `matplotlib` and `seaborn` for visualization.
  - `folium` and `geopandas` for geospatial analysis.
- **Jupyter Notebook**: For interactive data exploration and analysis.

---

## Installation and Setup

### Prerequisites
- Python 3.8 or later
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `folium`, `geopandas`

### Steps
1. Clone this repository:
   ```bash
   git clone https://github.com/pranav290804/Violence-Against-Women-Analysis
   cd violence-against-women-analysis

2. Install the required libraries:
   ```bash
   pip install -r requirements.txt

3. Download the dataset:
   - Locate the dataset file in the data folder of the repository (data/Violence Against Women and Girls.csv).
   - Copy the file path of the dataset.

4. Update the dataset file path in the notebook:
   - Open the Jupyter Notebook:
     ```bash
     jupyter notebook Notebook.ipynb

    - In the notebook, locate the line where the dataset is loaded:
      ```bash
      file_path = "C:/Users/prana/Downloads/Violence Against Women Girls Data.csv"

    - Replace the file path with the path to the dataset in the repository, for example:  
      ```bash
      file_path = "./data/Violence Against Women Girls Data.csv"

5. Run the notebook cells to execute the analysis.

---

## Acknowledgments
- **Data source:** https://www.kaggle.com/datasets/andrewmvd/violence-against-women-and-girls
- **Inspired by efforts to end violence against women globally.**

