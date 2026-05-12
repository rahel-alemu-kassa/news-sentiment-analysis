# Financial News Sentiment & Stock Price Correlation

## Project Overview
This project analyzes the relationship between daily financial news sentiment and stock price movements. Using Python, I processed a large dataset of analyst headlines and historical stock prices to determine if news mood predicts market changes.

## My Original Work & Contributions
- **Data Engineering:** Developed a modular pipeline to clean and standardize disparate datasets (Headlines and Stock CSVs).
- **Sentiment Analysis:** Implemented NLP using `TextBlob` to score over 50,000 headlines for emotional polarity.
- **Quantitative Analysis:** Calculated technical indicators like Simple Moving Averages (SMA) using `Pandas`.
- **Statistical Correlation:** Performed a merge of 55,000+ rows to calculate the Pearson correlation coefficient between sentiment and price.

## Tech Stack
- **Language:** Python
- **Libraries:** Pandas, NumPy, TextBlob, Matplotlib, Seaborn
- **Tools:** Git/GitHub, VS Code, Virtual Environments

## How to Run
1. Activate the virtual environment: `source venv/Scripts/activate`
2. Install dependencies: `pip install pandas textblob matplotlib seaborn`
3. Run the notebooks in the `notebooks/` folder in order.