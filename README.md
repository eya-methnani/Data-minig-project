# Data Mining In-Class Assessment - Scrum Master Report

## Overview

This repository contains the deliverables and project documentation for an in-class assessment in the Data Mining course, under the supervision of Dr. Fadoua Ouamani. The assessment involved the analysis of three unique datasets by three separate teams. I, Eya Methnani, served as the Scrum Master, overseeing the project workflow, team collaboration, and the quality of deliverables.

## Table of Contents
1. [Introduction](#introduction)
2. [Preparation and Workflow Design](#preparation-and-workflow-design)
3. [Team Meetings](#team-meetings)
4. [In-Class Assessment Day Support](#in-class-assessment-day-support)
5. [Final Deliverables](#final-deliverables)
6. [Conclusion](#conclusion)

---

## 1. Introduction

As Scrum Master, I facilitated a structured workflow to ensure teams remained focused, collaborated effectively, and followed best practices in data mining. Each team was assigned a dataset, and I guided them through the various stages of data analysis, from initial understanding to model evaluation and interpretation of results. This repository contains the datasets, Jupyter notebooks, and documentation summarizing the processes and insights gained.

## 2. Preparation and Workflow Design

To ensure consistency and thoroughness across all teams, I developed a **Workflow Template** that each team followed. This template covered five critical steps of the data mining process:

### 2.1 Data Understanding
- **Objective:** Guide teams in identifying dataset-specific challenges and categorizing each problem (classification, clustering, or regression).
- **Process:** Teams explored data attributes, examined initial patterns, and noted significant features and any anomalies.

### 2.2 Data Exploration
- **Objective:** Detect data quality issues such as missing values, noise, outliers, and redundancies.
- **Process:** Teams used summary statistics, visualizations, and correlation matrices to explore data structure and distribution, identifying necessary preprocessing tasks.

### 2.3 Data Preprocessing
- **Objective:** Ensure data consistency and reliability.
- **Process:** I shared guidelines on handling missing data, reducing noise, and removing redundancies. Techniques like imputation, normalization, and feature engineering were discussed.

### 2.4 Modeling
- **Objective:** Select appropriate models based on problem type and dataset characteristics.
- **Process:** We discussed criteria for model selection, providing examples such as logistic regression for classification, clustering algorithms for behavior analysis, and regression models for continuous data prediction.

### 2.5 Evaluation and Visualization
- **Objective:** Evaluate model performance and interpret results effectively.
- **Process:** We covered metrics like accuracy, precision, and recall, and suggested visualizations (confusion matrices, ROC curves, etc.) to facilitate interpretation.

This **Workflow Template** provided a structured approach, while the **Jira Board** helped track progress and ensure alignment with project goals.

## 3. Team Meetings

### 3.1 Initial Meeting - November 10, 2024
- **Participants:** 
  - Scrum Master: Eya Methnani
  - Team Members: Hala Dhaouadi, Menyar Benameur, Zayneb Samaali, Mohamed Amine Staali, Imen Lakhal, Majd Bougares, May Selmi, Mohamed Amine Kacem, Echrak Bouafif
- **Objectives:**
  - Establish a structured workflow for all teams.
  - Assign datasets and define tasks and objectives for each team.
  - Discuss data-specific challenges and initial strategies.
- **Key Discussion Points:**
  - **Workflow Steps:** Each team received guidance on understanding, exploring, and preprocessing their datasets.
  - **Dataset Assignments:**
    - Team 1: Telecom Churn Dataset
    - Team 2: Non-Verbal Tourist Data
    - Team 3: Hepatitis C Virus (HCV) Data
  - **Challenges and Strategies:** Discussed common challenges like missing data and feature selection techniques.
  - **Action Items:** Teams began initial data analysis, documented quality issues, and started basic exploration.

### 3.2 Follow-Up Meeting - November 13, 2024
- **Objective:** Review team progress and address any workflow gaps.
- **Summary:** Each team shared their progress on data exploration and preprocessing. They were guided on refining classification and clustering approaches.
- **Feedback and Adjustments:** I provided insights on handling missing values, optimizing feature selection, and documenting preprocessing steps.

## 4. In-Class Assessment Day Support

On the day of the assessment, I provided hands-on support to ensure each team adhered to the workflow and addressed last-minute issues. My key responsibilities included:

- **Workflow Adherence:** Ensuring each team followed the structured workflow and didn’t miss any critical steps.
- **Code Quality Review:** Reviewing code for common errors or misinterpretations and suggesting improvements.
- **Clarifying Misinterpretations:** Providing real-time adjustments to address misunderstandings related to data preprocessing or model selection.
- **Optimizations:** Recommending ways to improve model performance and accuracy.

## 5. Final Deliverables

Each team successfully produced a notebook summarizing their analyses and findings. Below is a summary of each team’s project:

### 5.1 Team 1: Telecom Churn Analysis
- **Team Members:** Majd Bougares, Mohammedamine Kacem, Hale Dhaouadi, Fatma Zahra Smaali
- **Objective:** Analyze customer churn in a telecom dataset to identify patterns for retention strategies.
- **Data Cleaning:** Applied median imputation for missing values, capped outliers using the IQR method.
- **Modeling:** Implemented Logistic Regression with an accuracy of 81%.
- **Highlights:**
  - Clustered customers into three segments (low usage, high data usage, high call usage).
  - Confusion Matrix indicated strong performance for non-churned customers.

### 5.2 Team 2: Non-Verbal Tourist Data Analysis
- **Team Members:** May Selmi, Sahar Heni, Imen Lakhal
- **Objective:** Classify tourists based on non-verbal feedback and demographic factors.
- **Data Exploration and Cleaning:** Addressed missing values using mode and median imputation; applied PCA for dimensionality reduction.
- **Modeling:** Achieved 98% accuracy with Random Forest, excelling in classifying multiple tourist categories.
- **Highlights:**
  - Used PCA to reduce dataset dimensions.
  - Model effectively classified various tourist engagement levels.

### 5.3 Team 3: Hepatitis C Virus (HCV) Data Analysis
- **Team Members:** Echrak Bouafif, Minyar Benameur, Mohamed Amine Staali
- **Objective:** Analyze clinical data to classify patients based on disease progression (normal, hepatitis, fibrosis, cirrhosis).
- **Data Cleaning:** Handled missing values using KNN imputer; capped outliers using IQR.
- **Modeling:** Random Forest with 87% accuracy, CNN with 86%.
- **Highlights:**
  - PCA revealed significant patterns within the data.
  - Random Forest provided strong accuracy for healthy class classification but had room for improvement in disease-specific classifications.

## 6. Conclusion

Through this project, each team demonstrated significant progress, effectively applying data mining principles to real-world datasets. The structured workflow and collaborative checkpoints facilitated consistency and quality in our analysis. This experience underscored the importance of clear guidance, proactive feedback, and adaptable problem-solving in data mining projects.

Each deliverable reflects our collective effort and adherence to the structured approach, resulting in insightful analyses and valuable learnings. 

---

Thank you for visiting this repository. Feel free to explore the notebooks and datasets to gain a better understanding of the methodologies and insights gained during this assessment.
