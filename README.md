# Financial-Analysis-Correlation


### Project Overview

In the dynamic world of finance, the ability to identify undervalued companies offers a significant competitive edge for investors. This financial analysis delves into the intricate relationship between key economic variables and the valuation of companies, leveraging financial data to uncover investment opportunities.
The core objective of this analysis is to seeks to establish a correlation between critical economic indicators such as GDP growth rates, inflation, interest rates, and unemployment rates and company performance metrics. Understanding these correlations provides insights into how macroeconomic trends influence the financial health and valuation of individual companies. I am to conduct a financial analysis involving the correlation between the key economic variables and to identify undervalued company.

### Data Sources

The data used in this report were secondary data collected from both NBS ,World bank and other secondary data.At first, I collected NIGERIAN STOCK EXCAHNGE DATA, HISTORICAL DATA, INFLATION AND DATA FOR MONEY SUPPLY FROM 2014-2023.At first, I analysed the data ,worked on the time series.i made sure the whole data had one time zone (2014-2024),then unified them to a workbook but different worksheet.

### Tools Used

Microsoft Excel - Data cleaning,Data Analysis

Power BI - Creating charts 

### Methodology

#### Data preparation

- Unified all datasets to cover the same time period (2014-2023).

- Used Excel for data cleaning and time-series alignment.

- Combined data into a single workbook with separate worksheets for different variables.

#### Correction Analysis

computed correlation co-efficients to measure relationships

![Inflation vs. NSE Data](https://github.com/user-attachments/assets/2eb6e844-520a-4db7-aac0-132c91eb9388)


I observed a weak correlation of (-0.14),indicating that there is little or slight tendency for higher inflation to be associated with lower NSEDATA values. 

![Money vs. inflation](https://github.com/user-attachments/assets/8d6b1e8f-3c5f-49f0-901f-156fff1b0031)


I observed a Strong positive correlation (0.91).This strong relationship indicates that as the money supply increases, inflation tend to rise or increase. This aligns to the economic theory that says when a that an increase in money supply can lead to higher inflation due to more money chasing the same amount of goods and services.

![Black market vs. Inflation](https://github.com/user-attachments/assets/0a296960-ca58-42fd-b3ba-9dbd3d075122)


I observed a moderate positive correlation (0.44).This means that the higher inflation is associated with increased black market activity. High inflation might drive consumers and businesses to the black market in other to avoid the higher price in the official market.


![Money vs. black market](https://github.com/user-attachments/assets/d346ee55-3def-44e8-83e8-c3e62f49a0db)

This shows a moderate positve correlation (0.48).This moderate positive relationship indicates that an increase in money supply is associated with an increase in black market activity. More money in circulation might lead to higher liquidity, making it easier for transaction to occur in the black market

![NSE Data vs. Money](https://github.com/user-attachments/assets/85573b6d-afd5-4325-a1f7-11a7c583ff6b)

This shows a weak negative correlation(-0.18).This weak negative relationship indicates that an increase in the money supply is slightly associated with a decrease in the NSEDATA values, but the relationship is not strong.

#### Regression Analysis

Developed a regression model to predict productivity based on:

- Money supply (M1)

- Inflation rate

- Black market exchange rates
  
 Analyzed the regression output to assess significance and model fit.

 #### visualisation

 Scatter plots and regression outputs were generated to illustrate relationships and model results.

 ![image](https://github.com/user-attachments/assets/e37c194d-071e-40b6-ac9e-24bec2ff62df)


### Results/Findings

Correlation Analysis

- Inflation vs. NSE Data: Minimal impact of inflation on stock market performance.

- Money Supply vs. Inflation: As money supply increases, inflation tends to rise, aligning with economic theory.

- Black Market Activity vs. Inflation: High inflation may drive increased black market activity.

Regression Analysis

The regression model showed weak relationships, indicating the need for additional variables or alternative models for better insights.

### Implications

- Policymakers should monitor money supply to manage inflation and its ripple effects.

- Investors should consider broader economic factors beyond inflation when evaluating stock market performance.

- Addressing black market activity could improve economic transparency and government revenues.



