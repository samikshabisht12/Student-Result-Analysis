# Student Result Analysis

A comprehensive data analysis project examining the factors that influence student academic performance across Math, Reading, and Writing subjects.

## 📊 Project Overview

This project analyzes student performance data to identify patterns and relationships between various demographic and socioeconomic factors and academic achievement. The analysis provides insights into how factors like parental education, gender, ethnicity, and marital status correlate with student scores.

## 📁 Project Structure

```
student-result-analysis/
├── project 2.ipynb          # Main Jupyter notebook with analysis
├── student_scores.csv       # Dataset containing student information and scores
├── plots/                   # Generated visualizations
│   ├── gender_distribution.png
│   ├── ethnic_group_distribution.png
│   ├── ethnic_group_count.png
│   ├── parent_education_vs_student_score.png
│   ├── marital_status_vs_student_score.png
│   ├── math_score_distribution.png
│   ├── reading_score_distribution.png
│   └── writing_score_distribution.png
└── README.md               # Project documentation
```

## 📋 Dataset Description

The dataset contains information about students including:

- **Demographics**: Gender, Ethnic Group
- **Family Background**: Parent Education Level, Parent Marital Status
- **Academic Performance**: Math Score, Reading Score, Writing Score
- **Other Factors**: Lunch Type, Test Preparation, Study Hours, Sports Practice, etc.

## 🔍 Key Analyses Performed

### 1. Gender Distribution Analysis
- Examined the distribution of male and female students in the dataset
- **Finding**: More females than males in the dataset

### 2. Parental Education Impact
- Analyzed the relationship between parent education levels and student performance
- **Finding**: Higher parental education correlates with better student scores across all subjects

### 3. Marital Status Impact
- Investigated how parental marital status affects student performance
- **Finding**: Minimal to no impact of parental marital status on student scores

### 4. Score Distribution Analysis
- Created box plots for Math, Reading, and Writing scores to identify:
  - Central tendencies
  - Outliers
  - Score ranges and quartiles

### 5. Ethnic Group Analysis
- Examined the distribution of different ethnic groups
- Analyzed representation across all groups (A through E)

## 📈 Key Findings

1. **Parental Education is Crucial**: Students with parents having higher education levels (master's degree, bachelor's degree) consistently perform better across all subjects.

2. **Gender Balance**: The dataset shows a slight female majority, providing balanced gender representation for analysis.

3. **Marital Status Negligible Impact**: Parental marital status shows no significant correlation with student academic performance.

4. **Ethnic Diversity**: The dataset includes students from 5 different ethnic groups with varying representation levels.

## 🛠️ Technologies Used

- **Python 3.x**
- **Pandas** - Data manipulation and analysis
- **NumPy** - Numerical computations
- **Matplotlib** - Data visualization
- **Seaborn** - Statistical data visualization

## 🚀 Getting Started

### Prerequisites

Make sure you have Python installed with the following packages:

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### Running the Analysis

1. Clone or download this repository
2. Navigate to the project directory
3. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
4. Open `project 2.ipynb`
5. Run all cells to reproduce the analysis

## 📊 Visualizations

The project generates several insightful visualizations:

- **Gender Distribution**: Bar chart showing male/female student counts
- **Ethnic Group Analysis**: Both pie chart and bar chart representations
- **Parental Education Heatmap**: Shows correlation between parent education and student scores
- **Marital Status Heatmap**: Analyzes impact of parental marital status
- **Score Distributions**: Box plots for Math, Reading, and Writing scores

## 🎯 Future Enhancements

Potential areas for further analysis:

- Correlation analysis between different score types
- Impact of study hours on performance
- Effect of test preparation on scores
- Transportation method influence on academic performance
- Lunch type (standard vs. free/reduced) impact analysis
- Sports participation correlation with academic performance

## 📝 Data Preprocessing

The analysis includes data cleaning steps:
- Removal of unnecessary columns (`Unnamed: 0`)
- Standardization of weekly study hours format
- Handling of missing values

## 🤝 Contributing

Feel free to fork this project and submit pull requests for any improvements or additional analyses.

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 📧 Contact

For questions or suggestions regarding this analysis, please feel free to reach out.

---

*This analysis provides valuable insights into factors affecting student performance and can be used by educators and policymakers to make data-driven decisions.*