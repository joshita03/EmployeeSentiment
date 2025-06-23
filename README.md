# Employee Sentiment Analysis

## Project Overview
This project analyzes employee messages to assess engagement and identify potential retention risks through sentiment analysis.

## Key Findings
### Top Performers (Positive Sentiment)
1. eric.bass@enron.com
2. patti.thompson@enron.com  
3. don.baughman@enron.com

### Employees Needing Support (Negative Sentiment)
1. bobette.riner@ipgdirect.com
2. john.arnold@enron.com  
3. lydia.delgado@enron.com

### Flight Risk Employees
- bobette.riner@ipgdirect.com (3 negative messages in 30 days)
- john.arnold@enron.com (3 negative messages)
- lydia.delgado@enron.com (3 instances)
- patti.thompson@enron.com (2 instances)

## Files Structure
- `data/`: Contains all processed CSV files
- `notebooks/`: Jupyter notebook with complete analysis
- `reports/`: Detailed findings report
- `results/`: Flight risk identification
- `visualizations/`: All generated charts

## How to Reproduce
1. Install dependencies: `pip install -r requirements.txt`
2. Run the notebook: `jupyter notebook notebooks/employee_sentiment_analysis.ipynb`

## Dependencies
Python 3.8+ with packages listed in requirements.txt
