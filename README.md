# Final-Grade-Prediction-Project

## Project Overview
This project uses **multiple linear regression** to predict student final grades (G3) based on various academic and personal factors. The model leverages multiple features — including prior grades, study habits, attendance, demographic information, and family background — to estimate GPA.  

Categorical features such as `sex`, `address`, and others are **encoded**, and the dataset is split into training and testing sets to evaluate model performance.

## Key Features
- Uses multiple features to predict student GPA (G3).
- Encodes categorical variables for model compatibility.
- Splits data into training and testing sets for performance evaluation.
- Trains a **multiple linear regression model** using scikit-learn.
- Visualizes predicted vs actual GPA for insights.

## Dataset Details
- **Source:** [UCI Student Performance Dataset](https://archive.ics.uci.edu/ml/datasets/Student+Performance)
- Features used:
  - Academic: `G1`, `G2`, `studytime`, `failures`
  - Attendance: `absences`
  - Demographics: `age`, `sex`, `address`
  - Family background: `Medu`, `Fedu`, `famrel`
  - Lifestyle: `freetime`, `goout`, `health`
- Target variable: `G3` (final grade)

## How It Works
1. **Importing Data**
   - Reads CSV with `;` separator.
2. **Feature Selection & Encoding**
   - Selects relevant numeric and categorical features.
   - Encodes categorical variables into numeric values.
3. **Train-Test Split**
   - Splits data into training and testing sets.
4. **Model Training**
   - Trains a multiple linear regression model.
5. **Evaluation**
   - Evaluates performance using metrics like R² and visual comparison of predicted vs actual grades.

## Tech Stack
- Python
- pandas, NumPy
- scikit-learn (`LinearRegression`, `train_test_split`, `OneHotEncoder`)
- Matplotlib / Seaborn for visualization

## 🚀 How to Run
1. Clone the repository:
```bash
git clone https://github.com/yourusername/gpa-prediction-ml.git
