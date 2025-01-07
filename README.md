# Final Project for HINF 5531 - Health Data Analytics and Data Science

This repository contains the final project for the **Health Data Analytics and Data Science (HINF 5531) course at the University of Minnesota**. The project explores a healthcare dataset through data importation, summarization, analysis, and visualization.

# Dataset
The dataset used in this project is private and cannot be shared publicly due to confidentiality and privacy concerns.

While the data files themselves are not included, they typically consist of the following:
* patients.csv: Contains patient demographic information.
* diseases.csv: Contains medical diagnoses linked to patients.
* medications.csv: Contains medication prescriptions for patients.
* encounters.csv: Contains details about patient encounters with healthcare providers.
* departments.csv: Contains information about the various hospital departments.
* disease_types.csv: Contains categorization of diseases by type. 
* medication_types.csv: Contains categorization of medications by type. 
* providers.csv: Contains information about healthcare providers and their specialties.

# Repository Structure

* Data_Validation_and_Anonymization_Report.pdf: A detailed report on the validation and anonymization of data.
* Hospital_Data_Analysis_Final_Report.pdf: The final report summarizing the analysis of hospital data.
* Hospital_Data_Analysis_code.qmd: Quarto Markdown file that includes the analysis code and workflows.
* README.md: This file, which provides an overview of the repository and project.

# Project Breakdown 
1. Data Import: Import the CSV files and handle missing data encoded as "NULL". Ensure correct date/time formats.
2. Data Summary: Summarize key data points, including patient counts, medication types, disease types, and more. You’ll generate a table stratifying patients by sex/gender, race/ethnicity, and marital status.
3. Data Manipulation: Calculate BMI, perform LOS (length of stay) analysis, and handle missing or skewed data.
4. Data Visualization: Create histograms, scatterplots, and facet plots to visualize patient demographics, encounters, and BMIs.
5. Missing Values: Analyze the rate of missing data and its potential impact on analysis.
6. Data Validation: Investigate unreasonable values and duplicate data, making recommendations for cleaning.
