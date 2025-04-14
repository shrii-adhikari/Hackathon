<h1>Zeroed in 2050: Mapping the road to net zero?</h1>

Contributers:

Areez Muhammed,  areezmuhammedshabu2@sheffield.ac.uk

Kulisara Kittivibul,  kkittivibul1@sheffield.ac.uk

Seadon Rodrigues,  srodrigues4@sheffield.ac.uk

Shristi Adhikari,  sadhikari2@sheffield.ac.uk

Aparnaa Swaminathan,  aswaminathan1@sheffield.ac.uk

**Overview:**

The UK government has committed to achieving Net Zero carbon emissions, a goal that requires transformative changes across all sectors of society. Local Authorities (LAs) play a pivotal role in this transition, as they directly manage transport systems, housing development, waste services, and local industries—each contributing significantly to emissions.applying statistical analysis, visualization, and machine learning models, this project aims to provide data-driven insights that can inform policy, guide funding, and support regional climate action strategies.This project addresses the dual challenge of climate goals and economic development at the local level in the UK.The analysis focuses on local authorities within the Yorkshire and the Humber region.
The aims for this project consist of:

1.Net Zero Readiness: Can we predict which local authorities are on track to reach Net Zero by 2050 based on historical emissions?

2.Economic Linkages: Can we uncover patterns between carbon emissions and economic indicators like business density and Gross Value Added (GVA) by industry?


**Datasets:**

The datasets included in this study include 1 csv and 2 excel files.They are listed below:

📂 datasets/

    └── 2005-2022-local-authority-ghg-emissions-csv-dataset.csv
    
    └── business 2017-2022.xlsx
    
    └── 2017.xls
    
    └── 2018.xls
    
    └── 2019.xlsx

    └── 2020.xlsx
    
    └── 2021.xlsx

    └── 2022.xlsx

    └── revenue.xlsx

**Key features:**

1. Linear regression: Linear Regression produced moderately accurate predictions but lacked flexibility in capturing complex patterns. 
2. Prophet: The Prophet model outperformed all others in forecasting emissions, showing strong accuracy and temporal consistency across local authorities. Its ability to handle seasonality and trend shifts made 
   it particularly effective for environmental time series data
3. LSTM: LSTM offered competitive results but was outclassed by Prophet in terms of interpretability and generalisability.
4. ARIMA: ARIMA model underperformed, especially for smaller LAs where data variability affected reliability.
5. Polynomial regression: This model also failed to meet expectations and provided poor results.
6. XGBoost regression: Similar to ARIMA, XGBoost model also produced underwhelming results, especially for smaller LAs where data variability affected reliability.

**Visualisations:**

1.Bar charts for distribution of emissions across various sectors, 2050 net zero prediction across various LAs.

2.Line plots to represent actual values vs predicted values and forecasting emission values by 2050.

3.Box plot for highlighting emission outliers.

**Project files:**

The project files are listed below:

📂 notebook for various models tested/

    └── ARIMA_PR_LR.ipynb
    
   
📂 notebook for prophet/

    └── PROPHET Territorial emmission.ipynb
    └── PROPHET_CO2.ipynb


📂 notebook for LSTM/

    └── LSTM Territorial emmission.ipynb
    └── LSTM_CO2.ipynb
    


**Tools & Technologies:**

Python

Google Colab

Tableau 

**Conclusion**

Economic indicators such as GVA and business density play a significant role in emissions levels, underscoring the need for policies that balance economic growth with sustainability goals.The study highlights the importance of accurately forecasting emissions to support local authorities in achieving Net Zero targets, with Prophet emerging as the most reliable model.

**Presentation**

[This is the presentation link](https://www.canva.com/design/DAGkKKdIk90/yLwF_c4CQY_qP6OTR-_Yaw/view?utm_content=DAGkKKdIk90&utm_campaign=designshare&utm_medium=link2&utm_source=uniquelinks&utlId=h085d58f029)
