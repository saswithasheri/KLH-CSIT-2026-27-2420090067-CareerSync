# KLH-CSIT-2026-27-2420090067-careerSync
# CareerSync: AI Resume Screening & Job Recommendation
# Adaptive Software Engineering - 24CI3201

## Project Overview

CareerSync is an AI-powered resume screening and job recommendation system designed to automate the initial recruitment process and help candidates identify suitable job roles.

The system uses Machine Learning and Natural Language Processing (NLP) techniques to analyze resumes, extract relevant skills and qualifications, classify candidate profiles, and recommend suitable job roles based on their skills and qualifications.



## Abstract

CareerSync aims to provide an intelligent and efficient solution for automated resume screening and personalized job recommendation. Traditional recruitment processes often require significant time and manual effort to evaluate resumes and match candidates with appropriate job positions.

The proposed system automates this process by parsing resumes, extracting relevant information such as skills, education, experience, and qualifications, and applying Machine Learning techniques to classify candidate profiles. Based on the extracted features and predicted category, the system recommends suitable job roles to candidates.

CareerSync can assist recruiters in reducing the time required for preliminary resume screening while providing candidates with relevant career opportunities. The project combines Python, Natural Language Processing, Machine Learning, Pandas, NumPy, Scikit-learn, and optionally Streamlit for the user interface.

---

## Objectives

- Automate the initial screening of resumes.
- Extract relevant candidate information from resumes.
- Identify and classify candidate skills and qualifications.
- Recommend suitable job roles based on candidate profiles.
- Reduce the manual effort involved in preliminary recruitment screening.
- Provide an easy-to-use interface for resume analysis and recommendations.
- Demonstrate the practical application of Machine Learning and NLP in recruitment.

---

## Key Features

### 1. Resume Parsing

Extract relevant information from uploaded resumes, including:

- Skills
- Educational qualifications
- Work experience
- Certifications
- Technical competencies

### 2. Resume Classification

Uses Machine Learning techniques to classify resumes according to relevant job or career categories.

### 3. Job Recommendation

Recommends suitable job roles by comparing candidate skills and qualifications with available job categories.

### 4. Machine Learning Model

Uses supervised Machine Learning techniques for resume classification and recommendation.

### 5. User-Friendly Interface

Provides an interface through which users can upload resumes and obtain screening results and job recommendations.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Natural Language Processing (NLP)
- Streamlit
- Matplotlib
- Seaborn

---

## Mandatory Repository Structure

The project follows the required repository structure:

copy


CareerSync/
│
├── src/
│   └── Source code and application modules
│
├── docs/
│   └── Project documentation and supporting documents
│
├── data/
│   └── Datasets used for training and evaluation
│
├── results/
│   └── Model outputs, evaluation results, and visualizations
│
├── reports/
│   └── Project reports and academic documents
│
└── README.md

### Folder Description

* src/ – Contains the source code, preprocessing modules, Machine Learning models, recommendation logic, and application files.
* docs/ – Contains project documentation, diagrams, methodology, and supporting documents.
* data/ – Contains datasets used for training, testing, and evaluation. If the dataset cannot be redistributed, a documented reference to the original data source will be provided.
* results/ – Contains model predictions, evaluation metrics, graphs, visualizations, and experimental results.
* reports/ – Contains project reports, research documentation, and final academic deliverables.
* README.md – Contains the project overview, team information, setup instructions, execution instructions,
and current project status.

---

## Team Members

| Name            | ID Number   |
| --------------- | ----------- |
| Harshini S. R   | 2420030113  |
| M. Pallavi      | 2420030373  |
| G. Divija Medha | 2420030481  |
| S. Saswitha     | 2420090067  |

---

## Supervisor

Supervisor Name: Dr. Rajkumar Patil

---

## System Workflow

copy


Resume Upload
      ↓
Resume Parsing
      ↓
Text Preprocessing
      ↓
Skill & Feature Extraction
      ↓
Machine Learning Model
      ↓
Resume Classification
      ↓
Job Matching
      ↓
Job Recommendation
      ↓
Recommended Job Roles

---

## Installation and Setup

### 1. Clone the Repository

Bash


git clone https://github.com/2420030113Harshini/KLH-CSE-2026-27-2420030113-CareerSync
cd CareerSync

### 2. Create a Virtual Environment

Bash


python -m venv venv

### 3. Activate the Virtual Environment

#### Windows

Bash


venv\Scripts\activate

#### Linux / macOS

Bash


source venv/bin/activate

### 4. Install Dependencies

Bash


pip install -r requirements.txt

---

## Execution

### Using Python

If the application is implemented as a standard Python application:

Bash


python src/app.py

### Using Streamlit

If Streamlit is used for the user interface:

Bash


streamlit run src/app.py

After launching the application, upload a resume to analyze the candidate profile and generate suitable job recommendations.

---

## Machine Learning Pipeline

The system follows the following Machine Learning pipeline:

1. Data Collection
2. Data Cleaning
3. Resume Text Preprocessing
4. Feature Extraction
5. Feature Engineering
6. Model Training
7. Resume Classification
8. Job Matching
9. Job Recommendation
10. Model Evaluation

---

## Model Evaluation

The Machine Learning model will be evaluated using appropriate classification metrics, including:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

Additional evaluation metrics may be included depending on the final model and dataset.

---

## Dataset

The data/ directory contains the datasets used for training and evaluation.

If the dataset is obtained from an external source and cannot be included directly in the repository, the following information will be documented:

* Dataset Name
* Original Source
* Dataset URL / Reference
* Dataset Format
* Relevant Features
* Intended Use

---

## Current Phase Status

Current Phase: Development / Implementation

### Project Progress

* [x] Project topic finalized
* [x] Project title finalized
* [x] Initial project architecture defined
* [x] Mandatory repository structure created
* [ ] Dataset collection and preparation
* [ ] Resume preprocessing pipeline
* [ ] Feature extraction
* [ ] Machine Learning model development
* [ ] Resume classification
* [ ] Job recommendation module
* [ ] User interface implementation
* [ ] Model evaluation
* [ ] Testing
* [ ] Final documentation
* [ ] Final deployment and demonstration

---

## Future Enhancements

* Deep Learning-based resume classification.
* Advanced NLP-based skill extraction.
* Semantic similarity-based job matching.
* Integration with live job databases.
* Personalized career-path recommendations.
* Resume improvement suggestions.
* Explainable AI for recommendation results.
* Multi-language resume support.
* Cloud-based deployment.

---

## Disclaimer

CareerSync is developed as an academic and educational project to demonstrate the application of Artificial Intelligence, Natural Language Processing, and Machine Learning in resume screening and job recommendation.

The recommendations generated by the system should be considered supportive suggestions and not definitive employment decisions.

---

## License

This project is developed for academic and educational purposes.
