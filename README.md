# Pharmaceutical-Data-Insights-Analysis-of-Medicine-Usage-Side-Effects-and-User-Reviews

Table of Contents
Project Overview
Data Description
Setup and Installation
Data Processing and Cleaning
Exploratory Data Analysis
Visualizations
Review Analysis
Key Findings
Conclusion
Future Work
 
Project Overview
This project aims to analyze a comprehensive dataset of medicines, examining aspects such as composition, uses, side effects, manufacturers, and user reviews. The primary goals are to identify patterns in medication use, assess the frequency and severity of side effects, and evaluate user satisfaction across different pharmaceutical brands. This analysis can aid in understanding medication trends and informing better healthcare decisions.

# Data Description
The dataset includes the following columns:

Medicine Name: The name of the medicine.
Composition: The active pharmaceutical ingredients.
Uses: The medical conditions treated by the medicine.
Side Effects: Reported adverse effects from using the medicine.
Manufacturer: The pharmaceutical company that produces the medicine.
Excellent Review %: The percentage of reviews rating the medicine as excellent.
Average Review %: The percentage of reviews rating the medicine as average.
Poor Review %: The percentage of reviews rating the medicine as poor.
The dataset comprises 11,498 unique medicine entries, covering a wide range of therapeutic areas and manufacturers.

# Setup and Installation
Prerequisites
Python 3.7 or later
Jupyter Notebook or Google Colab
Required Python libraries: numpy, pandas, matplotlib, seaborn, plotly, re

# Data Processing and Cleaning
 Data Loading: The dataset is loaded into a Pandas DataFrame.
 Handling Missing Values: Missing data is identified and handled through imputation or removal, depending on the context.
 Data Transformation: Necessary transformations, such as converting text to lowercase or splitting multi-valued fields, are applied to standardize the data.
 Basic statistics and visualizations are generated to understand the distribution and relationships within the data.
# Exploratory Data Analysis
Unique Medicines and Uses
Unique Medicine Groups: The dataset contains 11,498 unique medicine groups.
## Top 10 Medicines: The most frequently occurring medicines include:
## Lulifin Cream
## Benadryl Syrup
## Livoluk Oral Solution
## Nebistar 5 Tablet
## Amrolstar Cream
## Lulibet Cream
## Lulilok Cream
## Monoguard Cream
## Tcris Cream
## Hexidine Mouth Wash

# Most Common Uses
The dataset reveals the top medical conditions treated by the medicines, with the leading uses being:

## Treatment of Type 2 diabetes mellitus
## Treatment of bacterial infections
## Hypertension management
## Pain relief
## Treatment of fungal skin infections

# Visualizations
Several visualizations were created to illustrate the data insights:

### Top 10 Most Frequent Medicines: A bar chart showing the most common medicines in the dataset. ![Alt text](https://github.com/nakul-cloud/Pharmaceutical-Data-Insights-Analysis-of-Medicine-Usage-Side-Effects-and-User-Reviews/blob/main/top%2010%20medicine.png)

### Top 10 Most Frequent Uses: A bar chart depicting the most common medical uses for the medicines. ![Alt text](https://github.com/nakul-cloud/Pharmaceutical-Data-Insights-Analysis-of-Medicine-Usage-Side-Effects-and-User-Reviews/blob/main/top%2010%20freq%20use.png)

### Top Manufacturer The dataset analysis revealed that [Pfizer & Merck] is the leading producer, with the highest number of unique medicines in the dataset.:![Alt text](https://github.com/nakul-cloud/Pharmaceutical-Data-Insights-Analysis-of-Medicine-Usage-Side-Effects-and-User-Reviews/blob/main/manufacturere.png)

### Side Effects Analysis: A horizontal bar chart highlighting the most reported side effects, such as pain, nausea, and headaches.
![Alt text](https://github.com/nakul-cloud/Pharmaceutical-Data-Insights-Analysis-of-Medicine-Usage-Side-Effects-and-User-Reviews/blob/main/most%20common%20side%20effects.png)

### Review analysis focused on understanding user satisfaction through the distribution of reviews categorized as Excellent, Average, and Poor. The data was aggregated to identify trends in user feedback across different manufacturers. ![Alt text](https://github.com/nakul-cloud/Pharmaceutical-Data-Insights-Analysis-of-Medicine-Usage-Side-Effects-and-User-Reviews/blob/main/revirew.png)
![Alt text](https://github.com/nakul-cloud/Pharmaceutical-Data-Insights-Analysis-of-Medicine-Usage-Side-Effects-and-User-Reviews/blob/main/manufacturer%20review%20score.png)

# Findings
Distribution by Manufacturers: Analysis of the distribution of medicine production by various manufacturers.
Review Score Statistics: Descriptive statistics on review scores were calculated, showing variability in satisfaction levels.
# Key Findings
The dataset covers a broad range of medicines with diverse compositions and uses.
There is significant variation in the frequency of certain side effects, with pain and nausea being the most common.
User reviews provide a mixed perspective, with some medicines receiving predominantly excellent reviews, while others have higher proportions of average or poor reviews.
# Conclusion
The analysis provides valuable insights into the landscape of pharmaceutical products, highlighting key areas of interest such as the prevalence of specific medicines, common uses, and side effects. The findings can inform healthcare professionals, patients, and pharmaceutical companies about medication trends and user experiences, potentially guiding better healthcare decisions and product improvements.

# Future Work
Future analyses could explore the following:
Longitudinal analysis to track changes in medication use and reviews over time.
In-depth studies on the correlation between specific compositions and reported side effects.
Machine learning models to predict potential side effects based on composition and user demographics.
