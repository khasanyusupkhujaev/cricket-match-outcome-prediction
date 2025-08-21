# Cricket Match Outcome Prediction

This project is a dissertation research effort aimed at developing an accurate predictive model for forecasting outcomes in The Hundred cricket format. Using machine learning techniques, we analyze match data to identify influential factors like team composition, playing strategies, and performance metrics. The research explores whether match results can be reliably predicted and how insights can optimize team strategies.

## Project Overview
- **Research Aim**: Build a model to predict cricket match outcomes in The Hundred format, introduced in 2021.
- **Key Questions**:
  - What are the most influential factors for victory?
  - How do team composition and game situations impact winning likelihood?
  - Which ML algorithms perform best for predictions?
  - How can insights improve decision-making in cricket?
- **Data Source**: Cricsheet (official cricket match statistics).
- **Methodology**: Data extraction, preprocessing, feature engineering, and models like Poisson regression, logistic regression, decision trees, random forests.
- **Comparisons**: Insights vs. other formats like T20 and ODIs.
- **Applications**: Sports betting, fan engagement, economic/social impacts of cricket.

For full details, see the attached project plan document.

## Installation
1. Clone the repository:
https://github.com/khasanyusupkhujaev/cricket-match-outcome-prediction.git
2. Install dependencies:
pip install -r requirements.txt
## Usage
- Open the Jupyter notebook `Research_project.ipynb` in Google Colab or locally with Jupyter.
- Mount your Google Drive (if using Colab) and update paths to your data files.
- Run cells sequentially for data extraction, model training, and predictions.
- Example prediction:
```python
score = score_predict('Northern Superchargers', 'male', 'Manchester Originals', 0, 0, 0, 0, 0, forest)
print(f'Predicted Score: {score}')
