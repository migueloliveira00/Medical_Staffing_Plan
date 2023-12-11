# Medical Staffing Plan - Influenza Season Staffing Project

## Project Overview:
This project aimed to assist a medical staffing agency in preparing for the influenza season, addressing high-demand periods for temporary staff in clinics and hospitals across the United States. The objective was to determine the optimal timing and quantity of staff allocation to each state during the influenza season. Stakeholders include frontline medical agency staff, healthcare facilities, influenza patients, and agency administrators. Success factors involved creating a staffing plan that efficiently utilizes available resources, minimizing instances of understaffing or overstaffing. Assumptions consider vulnerable populations and the effectiveness of flu shots, while constraints include limited staffing and budgetary constraints. Requirements include data-informed staffing plans, seasonal influenza analysis, prioritization based on vulnerable populations, and addressing data limitations.

## Tools & Skills:

### Excel:
+ Ensure data quality and consistency by cleansing, transforming, and integrating diverse datasets.
+ Translate intricate business objectives into actionable, data-driven strategies and solutions.
+ Employ statistical hypothesis testing to extract meaningful insights, validate assumptions, and facilitate evidence-based decision-making.

### Tableau:
+ Manipulate and transform data.
+ Apply spatial analysis methods.
+ Utilize visual analysis to reveal patterns, trends, and crucial information.
+ Employ statistical methods for forecasting to enhance proactive planning and resource allocation.
+ Engage in data storytelling by communicating findings through data-driven insights.

## Data Cleaning, Integration & Transformation:
+ Removed duplicate records in the U.S. Census dataset, retaining unique County-Year-Population combinations.
+ Imputed missing state values in the "Influenza Death" dataset using other identifying variables for data completeness.
+ Systematically removed irrelevant or missing data.
+ Converted values like population counts to whole numbers and transformed state abbreviations into full names.
+ Corrected all instances of mispelling in the datasets.
+ Restructured age groups for consistent formatting, facilitating seamless dataset integration.
+ Integrated datasets to create a new variable normalizing mortality rates for each age group.

## Visualizations:
https://public.tableau.com/app/profile/miguel.oliveira8698/viz/CFDataImmersion2_9_2-MiguelOliveira/MedicalStaffAllocationforInfluenzaSeason2018

## Recommendations & Findings:
+ Highest influenza mortality rate is seen among people 65 years or older, confirming the initial hypothesis.
+ Influenza season typically happens in the coldest months of the year, between November and March.
+ States with the highest need for medical staff are the ones with the biggest vulnerable populations and these are also the states that have the largest number of influenza related deaths between 2009 and 2017.
+ The majority of medical staff should be sent to the states with the largest vulnerable populations between the months of November and March 

## Learning Experience:
Creating intuitive and interactive visualizations in Tableau emerged as a notable challenge. I researched tutorials and troubleshooting strategies to align outcomes with my initial objectives. During this process, I uncovered unexpected findings that catalyzed new techniques to incorporate into my project. The procedural walkthrough of each step enabled me to develop a coherent narrative for my final presentation, fostering a deeper understanding of potential impacts on outcomes.

## Data Sources:
+ Underlying Cause of Death, 1999-2020 [Data set]. CDC. https://wonder.cdc.gov/ucd-icd10.html
+ Population data by geography [Data set]. US Census Bureau, CSV file. https://coach-courses-us.s3.amazonaws.com/public/courses/data-immersion/A1-A2_Influenza_Project/Census_Population_transformed_202101.csv
+ Counts of influenza laboratory test results by state [Data set]. CDC Fluview, Excel file. https://images.careerfoundry.com/public/courses/data-immersion/A1-A2_Influenza_Project/CDC_Influenza_Visits.xlsx
