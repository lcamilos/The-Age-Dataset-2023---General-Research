# The-Age-Dataset-2023---General-Research

This report outlines the exploratory data analysis conducted in the "The-Age-Dataset-2023---General-Research" project. The project's objective is to analyze a dataset containing information related to ages, genders, countries, causes of death, and other associated variables. Various Python libraries were employed to perform data cleaning, preprocessing, visualization, and analysis.

**Summary of Tasks Performed**

**1. Library Installation:** Essential libraries such as NumPy, Pandas, Matplotlib, Seaborn, WordCloud, Folium, and Missingno were installed to facilitate data analysis and visualization.

**2. Data Loading:** Data was loaded from a CSV file ("age_dataset.csv") into a DataFrame named df.
   
**3. Initial Exploratory Data Analysis (EDA):** An initial overview of the data was conducted, including visualization of the first few rows, column information, and descriptive statistics.

**4. Data Cleaning - Removal of Unwanted Columns:** The 'Id' column, which held no pertinent information, was removed from the dataset.

**5. Data Cleaning - Handling Null Values:** Null values were identified and visualized. Rows with null values in key columns were dropped.

**6. Correlation Analysis:** Correlations between numeric features were analyzed using a heatmap and dendrogram.

**7. Data Preprocessing:** New columns were created, and transformations were applied to existing data, including average calculations and string-to-list conversions.

**8. Data Visualization:** Visualizations were generated to explore gender distribution, age at death, most represented countries, birth year distribution, and common       causes of death.

**9. Geographical Visualization:** An interactive map was created using the Folium library to visualize geographical coordinates associated with countries.

**10. Word Clouds:** Word clouds were generated to visualize the most common first and last names in the dataset.

**11. Analysis of Top 5 Causes of Death by Gender:** A deep analysis of the top five common causes of death was conducted, including a stacked bar chart depicting gender distribution.

**Conclusions and Findings**

The "The-Age-Dataset-2023---General-Research" project has demonstrated a range of data analysis techniques. Data has been cleaned, prepared, informative visualizations have been created, and trends and relationships within the data have been analyzed. Insights garnered from this analysis can inform decision-making and enhance understanding of patterns inherent in the dataset.
