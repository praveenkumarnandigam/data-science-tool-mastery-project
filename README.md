# Data Science Tool Mastery Project

**Student:** Nandigam Praveen Kumar  
**Internship:** YuvaIntern – Data Analyst  
**Task:** 4  
**Dataset:** UCI Student Performance

## Project overview
This repository demonstrates a practical Python data-science workflow using NumPy, Pandas, Matplotlib, Seaborn and Scikit-learn. It includes data acquisition, inspection, cleaning checks, exploratory analysis, visualizations and a baseline regression pipeline.

## Dataset
The project uses the UCI Student Performance dataset (dataset ID 320):  
https://archive.ics.uci.edu/dataset/320/student+performance

The dataset contains student achievement and related demographic, social and school attributes from two Portuguese secondary schools. It is observational, so relationships should not be interpreted as causal effects.

## Repository structure
```text
.
├── README.md
├── Task_4_Data_Science_Tool_Mastery_Nandigam_Praveen_Kumar.ipynb
└── Task_4_Data_Science_Tool_Mastery_Report_Nandigam_Praveen_Kumar.docx
```

## Tools used
- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook / Google Colab

## Run the notebook
1. Open Google Colab: https://colab.research.google.com/
2. Upload the `.ipynb` file from this repository.
3. Run all cells from top to bottom.
4. The notebook installs `ucimlrepo`, retrieves the dataset from UCI, generates tables and charts, trains a baseline Ridge regression model, and exports CSV summaries.
5. Review the actual metrics and outputs before describing findings.

## Modeling note
The default model excludes `G1` and `G2` to reduce the risk of target leakage for an early prediction use case. The model is a learning demonstration, not a validated high-stakes decision tool.

## Limitations
- Data come from two Portuguese secondary schools.
- The dataset is observational; correlation does not establish causation.
- A single train/test split and baseline model are not comprehensive validation.
- Findings should not automatically be generalized to other populations.

## Author
Nandigam Praveen Kumar
