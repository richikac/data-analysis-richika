**My AWS Data Analytics Platform Projects Portfolio**
</br></br> Welcome to my GitHub portfolio! This Portfolio is to showcase the projects that demonstrate my skills and expertise in creating Data Analytics Platform (DAP) using Amazon Web Services (AWS) cloud services. My project work focuses on two procedures - Council Voting records for the City of Vancouver and Academic Integrity Procedure for University Canada West (UCW). DAP created for both the procedures leverages a range of AWS services such as Amazon S3, Amazon Glue, Amazon Athena, KMS etc. for data storing, querying, data cleaning, transforming data, and quality control. By working on these projects, I have covered various aspects of analysis like exploratory data analysis , descriptive analysis, implementing ETL Pipelines, and data quality control. </br>
</br></br>**Section 1: Council Voting Records for the City of Vancouver**
</br></br>**Project 1: Exploratory Data Analysis Using Amazon Athena**
</br>This project involves exploratory data analysis of council voting records for the City of Vancouver to generate insights on the number of votes based for Year 2023 and 2024 to generate insights on the curated zone.
</br>**Project Title:** "Exploring Council Voting Patterns with Amazon Athena"
</br>**Objective:** To perform an exploratory data analysis on council voting records using Amazon Athena, identifying trends and participation rates.
</br>**Dataset:** Council Voting Records for Year 2023 and 2024 which are stored in the Raw Zone of Amazon S3.
</br>Dataset has these fields : Meeting Type, Vote Date, Vote Number, Agenda Description, Vote Start Date Time, Council Member Names, Vote (whether in Favour, Abstain or in opposition), Decision (Lost, carried or Carried Unanimously), Vote Detail Id
</br>**Methodology:**
</br>Methodolgy involves using Amazon Athena to run SQL query on the curated data stored in the Amazon S3 for the council voting memebers to generate statistical insights on the percentage votes in the favour for two years 2023 and 2024. Then, using Chart function in the excel to explore the patterns of votes in favour.
</br>**Tools and Technologies:**
</br>Amazon Athena for querying the council voting database.
</br>Amazon S3 for storing the dataset for council voting records.
</br>**Deliverables:** To generate a report showing bar graph of percentage number of council votes in favour for the years 2023 and 2024.
</br></br>**Project 2: Descriptive Analysis of Council Voting Outcomes with Amazon Athena**
</br>**Project Description:** Conducting a comprehensive descriptive analysis of council voting outcomes using Amazon Athena.
</br>**Project Title:** "Descriptive Analysis of Council Voting Outcomes with Amazon Athena"
</br>**Objective:** To leverage Amazon Athena for performing descriptive analysis on council voting outcomes and participation rates, providing valuable insights into voting trends.
</br>**Dataset:** Council Voting Records from Amazon S3, including vote details and participation information.
</br>**Methodology**
</br>Data Extraction: Use Amazon Athena to query data directly from Amazon S3.
</br>Data Analysis
</br>Query Execution: Write and execute SQL queries in Athena to extract key metrics.
</br>Insight Generation: Analyze voting outcomes and participation rates.
</br>Data Aggregation:
</br>Metric Calculation: Aggregate data to calculate total votes and participation rates.
</br>Statistical Summaries: Generate statistical summaries and visualizations.
</br>**Tools and Technologies:**
</br>Amazon Athena for executing SQL queries and analysis.
</br>Amazon S3 for storing the council voting datasets.
</br>**Deliverables:**
</br>Analysis Report: Aggregated data and statistical insights of voting patterns.
</br>Visualizations: Charts and graphs illustrating key findings.
</br>Query Documentation: SQL queries and process overview.
</br></br>**Project 3: ETL Pipeline for Council Voting Records of the City of Vancouver with AWS Glue**
</br>**Project Description**: Developing a robust ETL pipeline to process council voting records using AWS Glue.
</br>**Project Title:** "Data Wrangling for Council Voting Records Using AWS Glue"
</br>**Objective:** To design and implement an ETL pipeline using AWS Glue that efficiently cleans, transforms, and prepares council voting records.
</br>**Background:** Ensuring data consistency and removing inaccuracies from council voting records for meaningful analysis.
</br>**Dataset:** Council Voting Records stored in Amazon S3.
</br>**Methodology:**
</br>Data Extraction: Use AWS Glue Crawlers to catalog the source data in Amazon S3.
</br>Data Cleaning:
</br>Duplicate Removal: Identify and remove duplicates.
</br>Handling Missing Values: Implement strategies to manage incomplete data.
</br>Standardization: Ensure data formats are consistent.
</br>Data Transformation:
</br>Field Derivation: Create new fields for analysis.
</br>Normalization: Standardize data values and structures.
</br>Data Loading: Store the cleaned and transformed data back into Amazon S3.
</br>**Tools and Technologies:**
 </br>AWS Glue for data cleaning and transformation.
 </br>Amazon S3 for storing the structured dataset.
</br>**Deliverables:**
 </br>Cleaned and structured dataset in Amazon S3.
 </br>ETL Pipeline Documentation: Process flow, scripts, and data quality report.
</br></br>** **Project 4: Ensuring Data Quality and Privacy Control with AWS Glue and Amazon S3****
</br>**Project Description:** Implementing data quality control measures on council voting records using AWS Glue.
</br>**Project Title:** "Ensuring Data Quality in Council Voting Records Using AWS Glue"
</br>**Objective:** To establish and enforce data quality control measures using AWS Glue to ensure data accuracy.
</br>**Background:** The necessity of highquality data in council voting records for accurate analysis and reporting.
</br>**Scope:** Data Profiling, Cleansing, and Validation for council voting records.
</br>**Methodology:**
</br>Data Cleansing and Validation: Use AWS Glue to apply data quality rules.
</br>Data Quality Checks: Validate data against predefined quality metrics.
</br>**Tools and Technologies:**
</br>AWS Glue for data cleansing and validation.
</br>Amazon S3 for storing validated datasets.
</br>**Deliverables:**
</br>Validated dataset in the Trusted Zone.
</br>Data Quality Report: Summary of quality improvements.
</br></br>**Section 2: UCW Academic Integrity Procedure**
</br></br>**Project 1: Exploratory Data Analysis for UCW Academic Integrity Using Amazon Athena**
</br>**Project Description:** Analyzing academic integrity records to uncover patterns using Amazon Athena for querying data stored in Amazon S3.
</br>**Project Title:** "Exploring Academic Integrity Patterns with Amazon Athena"
</br>**Objective:** To perform an exploratory data analysis on academic integrity cases using Amazon Athena, identifying trends and patterns.
</br>**Dataset:** UCW Academic Integrity Records stored in Amazon S3.
</br>**Methodology:**
</br>Data Querying: Use Amazon Athena to run SQL queries for summarizing data and generating descriptive statistics.
</br>Data Exploration: Explore the dataset to understand academic integrity trends.
</br>**Tools and Technologies:**
</br>Amazon Athena for data querying and analysis.
</br>Amazon S3 for storing academic integrity records.
</br>**Deliverables:**
</br>A report generated from Athena queries summarizing insights into academic integrity patterns.
</br></br>**Project 2: Descriptive Analysis of Academic Integrity Outcomes with Amazon Athena**
</br>**Project Description:** Conducting a comprehensive descriptive analysis of academic integrity outcomes using Amazon Athena.
</br>**Project Title:** "Descriptive Analysis of Academic Integrity Outcomes with Amazon Athena"
</br>**Objective:** To leverage Amazon Athena for performing descriptive analysis on academic integrity cases, providing insights into patterns and outcomes.
</br>**Dataset:** UCW Academic Integrity Records from Amazon S3.
</br>**Methodology:**
</br>Data Extraction: Use Amazon Athena to query data directly from Amazon S3.
</br>Data Analysis:
</br>Query Execution: Write and execute SQL queries to extract metrics.
</br>Insight Generation: Analyze outcomes and trends.
</br>Data Aggregation:
</br>Metric Calculation: Aggregate data to calculate key metrics.
</br>Statistical Summaries: Generate summaries and visualizations.
</br>**Tools and Technologies:**
</br>Amazon Athena for querying and analysis.
</br>Amazon S3 for storing academic integrity datasets.
</br>**Deliverables:**
</br>Analysis Report: Aggregated data and statistical insights.
</br>Visualizations: Charts and graphs illustrating findings.
</br>Query Documentation: SQL queries and process overview.
</br></br>**Project 3: ETL Pipeline for UCW Academic Integrity Records with AWS Glue**
</br>**Project Description:** Developing an ETL pipeline to process academic integrity records using AWS Glue.
</br>**Project Title:** "Data Wrangling for Academic Integrity Records Using AWS Glue"
</br>**Objective:** To design and implement an ETL pipeline using AWS Glue to clean, transform, and prepare academic integrity records.
</br>**Background:** Ensuring data consistency and accuracy in academic integrity records for meaningful analysis.
</br>**Dataset:** UCW Academic Integrity Records stored in Amazon S3.
</br>**Methodology:**
</br>Data Extraction: Use AWS Glue Crawlers to catalog data in Amazon S3.
</br>Data Cleaning:
</br>Duplicate Removal: Identify and remove duplicates.
</br>Handling Missing Values: Implement strategies for incomplete data.
</br>Standardization: Ensure consistent data formats.
</br>Data Transformation:
</br>Field Derivation: Create metrics for analysis.
</br>Normalization: Standardize values and structures.
</br>Data Loading: Store the processed data back into Amazon S3.
</br>**Tools and Technologies:**
</br>AWS Glue for data cleaning and transformation.
</br>Amazon S3 for storing structured datasets.
</br>**Deliverables:**
</br>Cleaned dataset in Amazon S3.
</br>ETL Pipeline Documentation: Process details and scripts.
</br>Data Quality Report: Summary of quality improvements.
</br></br>**Project 4: Ensuring Data Quality Control for UCW Academic Integrity with AWS Glue and Amazon S3**
</br>**Project Description:** Implementing data quality control measures on academic integrity records using AWS Glue.
</br>**Project Title:** "Ensuring Data Quality in Academic Integrity Records Using AWS Glue"
</br>**Objective:** To establish and enforce data quality control measures using AWS
</br>Glue for academic integrity records.
</br>Background: Ensuring highquality data in academic integrity records for accurate analysis.
</br>Scope: Data Profiling, Cleansing, and Validation for academic integrity records.
</br>**Methodology:**
</br>Data Cleansing and Validation: Apply data quality rules using AWS Glue.
</br>Data Quality Checks: Validate data against predefined metrics.
</br>**Tools and Technologies:**
</br>AWS Glue for data cleansing and validation.
</br>Amazon S3 for storing validated datasets.
</br>**Deliverables:**
</br>Validated dataset in the Trusted Zone.
</br>Data Quality Report: Summary of quality improvements.
