# TXON Task 01 – Data Cleaning & Basic Visualization

## Project overview
This project completes Week 01 of the TXON Data Science Internship roadmap using the UCI Student Performance (Mathematics) dataset.

## Folder structure
```text
TXON_Task_01/
├── data/
│   └── student-mat.csv                 # Add the original CSV here
├── outputs/                            # Charts are saved here when notebook runs
├── TXON_01_Data_Cleaning_Visualization.ipynb
├── requirements.txt
└── README.md
```

## Setup
1. Install Python 3.10+ and Jupyter Notebook.
2. Download `student.zip` from https://archive.ics.uci.edu/dataset/320/student+performance
3. Extract `student-mat.csv` into the `data` folder.
4. Open a terminal in this project folder and run:
   `pip install -r requirements.txt`
5. Start Jupyter:
   `jupyter notebook`
6. Open `TXON_01_Data_Cleaning_Visualization.ipynb` and run all cells from top to bottom.

## Task requirements covered
- Load and inspect CSV using `head()`, `info()` and `describe()`.
- Check and handle missing values.
- Detect and remove duplicate rows.
- Calculate mean, median, mode and standard deviation.
- Create a bar chart, histogram and pie chart.
- Save the cleaned CSV and chart images.

## Dataset credit
Cortez, P. (2008). Student Performance [Dataset]. UCI Machine Learning Repository.
https://doi.org/10.24432/C5TG7T
