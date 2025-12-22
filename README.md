# Macroeconomic Dynamics of Japan: Consumption Behaviour, Phillips Curve Breakdown, Monetary Policy, and GDP Forecasting

## Introduction
This project provides an econometric and theoretical analysis of Japan’s macroeconomic environment. Using real datasets on GDP, CPI, unemployment, and policy rates, the study investigates Japan’s growth trends, inflation dynamics, consumption behaviour, and the breakdown of the Phillips Curve. Visual models such as IS–LM and AD–AS are incorporated to interpret structural issues in Japan’s economy.

## 🧭 Motivation
Japan is a unique macroeconomic case where:
- Inflation remains near zero for decades, despite massive monetary stimulus.
- GDP growth is stagnant, showing little cyclical fluctuation.
- The Phillips Curve has collapsed, showing no inflation–unemployment trade-off.
- Consumption behaviour remains stable, driven strongly by income.
  
This project attempts to empirically diagnose these anomalies using data-driven evidence.

## 🎯 Objectives
- To forecast Japan’s GDP using ARIMA/SARIMAX models.
- To estimate Japan’s consumption function using regression analysis.
- To test the validity of the Phillips Curve for Japan.
- To evaluate the effectiveness of monetary policy in a low-interest, near-deflation environment.
- To illustrate macroeconomic relationships using IS–LM and AD–AS curve plots.

---

## 📂 Repository Structure

```
├── datasets/
│   ├── 1. Unemployment Data.csv
│   ├── 2. CPI Data.csv
│   ├── 3. GDP Data.csv
│   ├── 4. Policy Data.csv
│   ├── 5. Consumption Data .csv
│   ├── Merged Data.csv
├── SQL File/
│   ├── 1. Data Pre-processing.sql 
├── Python File/
│   ├── 1. Scrapping data.ipynb
│   ├── 2. Philips Curve.ipynb
│   ├── 3. Consumption Function.ipynb
│   ├── 4. Japan's GDP Forecasting.ipynb
├── Report on Project Japan.pdf   [ A detailed report on the project ]
├── 1. Summary.pdf                [ A short summary of the full project ]
└── README.md
```

## 📊 Modeling Framework

- Consumption Function (Log–Log OLS)

  [lnC=α+βlnY+γr+ϵ]
  
  <img width="692" height="475" alt="Screenshot 2025-12-22 223128" src="https://github.com/user-attachments/assets/7bfe7586-3286-4398-8a0e-3f1e2d0d04af" />

- Phillips Curve Estimation

  [πt​=α+βut−1​+γrt−1​+ϵ]
  
<img width="700" height="245" alt="Screenshot 2025-12-22 223107" src="https://github.com/user-attachments/assets/82e58425-2f7a-4545-a4cf-712568e03236" />

  
- GDP Forecasting using ARIMA

  [ARIMA(0,1,0)]
  ​
<img width="706" height="436" alt="Screenshot 2025-12-22 223151" src="https://github.com/user-attachments/assets/f42e273c-afa1-4612-b6a0-0b535ae23e55" />


## 📌 Report 
Please see the attach file "Report on Project Japan.pdf" for the full details of the project and detailed analysis.

## 📊 Key Findings
### GDP Trends
- GDP growth remains modest with signs of stagnation.
- Forecast shows slow recovery with wide uncertainty bands.

### Consumption Behaviour
- Consumption strongly correlates with income (R² ≈ 0.77).
- MPC is positive and economically meaningful.

### Phillips Curve Breakdown
- No statistically significant negative relationship between unemployment and inflation.
- Confirms decades of Japan’s flat Phillips Curve.

### Monetary Policy Ineffectiveness
- ZIRP and deflation expectations weaken transmission.
- LM curve appears vertical, consistent with liquidity trap conditions.

### Structural Challenges
- Aging population
- High savings–investment gap
- Weak domestic demand
- Global competition and import pricing
- AD and AS curves are flat → explains low inflation equilibrium.

## 🏛️ Policy Recommendations

✔ Strengthen Fiscal Policy
1. Increase Govt. Spending, 2. Lower consumption tax, 3. Direct cash transfer or 
vouchers, basically, encouraging spending, 4.  Force companies to pay higher wages.

✔ Use Unconventional Monetary Tools
- Yield Curve Control
- Forward guidance
- Large-scale QE

✔ Structural Reforms
- Increase female & elderly labour participation
- Immigration reform
- Productivity-enhancing investment

✔ Decrease investments in Abroad
- Only households holding excess money do not 
cause Japan’s liquidity trap. A major factor is that Japanese corporations invest 
heavily overseas rather than domestically. This reduces domestic investment and 
weakens aggregate demand. As a result, domestic output and wages grow very slowly, 
preventing inflation from rising.

✔ Improve Inflation Expectations
- Coordinated fiscal–monetary communication
- Persistent policy commitment
  
## Conclusion
The project demonstrates that Japan’s macroeconomic performance is shaped by deep structural factors rather than short-term shocks. The Phillips Curve does not hold, monetary policy has limited influence, and aggregate demand remains persistently weak. IS–LM and AD–AS analyses support the view that Japan is in a liquidity-trap-like condition with limited policy effectiveness.
