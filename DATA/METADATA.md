# Tesla Stock Dataset

## Data Summary

This dataset contains Tesla stock data from the yfinance package in Python. The data captures open, close, low, and high prices from 2015-2025. It serves as the foundation for exploratory data analysis and classification tasks in the **Exploring the Behavior of Tesla Stock in the Face of Public Scrutiny: A Time Series Analysis** project.

The dataset file is stored in our GitHub repository: [elon_musk_timeline.csv](https://github.com/katrinag2004/TeslaDS).

---

## Provenance

* **Source**: Imported from Yahoo's Stock Data Database using yfinance [finance.yahoo.com](https://finance.yahoo.com/quote/TSLA/history/)
* **Repository**: [TeslaDS GitHub Repository](https://github.com/katrinag2004/TeslaDS)
* **Dataset Name**: `elon_musk_timeline.csv`
* **Collection Method**: Import of stock market data using the yfinance package, followed by initial cleaning and standardization.

---

## LICENSE

## 1. Project Code License (MIT License)

Copyright (c) 2025 Andrew Otwell, Zoe Gates, Katrina Garcia

Permission is hereby granted, free of charge, to any person obtaining a copy  
of this software and associated documentation files (the “Software”), to deal  
in the Software without restriction, including without limitation the rights  
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell  
copies of the Software, and to permit persons to whom the Software is  
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all  
copies or substantial portions of the Software.

**THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR  
IMPLIED**, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,  
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE  
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER  
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,  
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE  
SOFTWARE.

---

## 2. Data Source and Usage Disclaimer

All financial data used in this project was obtained from **[Yahoo Finance](https://finance.yahoo.com/)**.  
Yahoo Finance data is subject to their [Terms of Use](https://legal.yahoo.com/us/en/yahoo/terms/otos/index.html) and is provided **for personal, educational, and non-commercial purposes only**.

Redistribution, commercial use, or incorporation of this data into commercial tools or services is **prohibited** without a proper subscription (e.g., *Yahoo Finance Select*).

This project uses Yahoo Finance data **strictly for academic analysis** as part of a **university course requirement**.  
All users and contributors must comply with Yahoo Finance’s licensing restrictions and applicable terms of service.

---

## ETHICAL CONSIDERATIONS

This project analyzes public sentiment surrounding Elon Musk and its relationship to Tesla stock data.  
The analysis is conducted strictly for academic and educational purposes.

## Key Ethical Considerations

- **Public Data Only:**  
  All sentiment and financial data are sourced from publicly available platforms (e.g., Yahoo Finance, verified news outlets, social media APIs) and used in compliance with their Terms of Service.

- **Privacy and Respect:**  
  No private, leaked, or personally identifiable information is collected or analyzed. The focus remains on publicly available content relevant to market behavior.

- **No Financial Advice:**  
  The findings in this project do **not** constitute investment advice or recommendations. The analysis is for **educational use only** and should not guide financial decisions.

- **Avoiding Market Influence:**  
  The project does not attempt to manipulate, predict, or influence stock prices. Correlation between sentiment and stock movements does not imply causation.

---

## Data Dictionary

| **Field Name** | **Data Type** | **Description** | **Allowed Values / Range** | **Example** |
|----------------|---------------|------------------|-----------------------------|--------------|
| **Date** | Datetime | Date of the trading day | Any trading day between 2013–2023 | 2004-04-04 |
| **Open** | Float | Tesla stock price at market open | Any number | 400.44 |
| **High** | Float | Highest Tesla stock price during the trading day | Within the daily range | 400.44 |
| **Low** | Float | Lowest Tesla stock price during the trading day | Within the daily range | 400.44 |
| **Close** | Float | Tesla stock price at market close | Between \$10–\$4,000 | 400.44 |
| **Adj Close** | Float | Adjusted closing price (accounts for splits and dividends) | Between \$10–\$4,000 | 400.44 |
| **Volume** | Integer | Total number of Tesla shares traded during the day | Varies | 40,000,000 |

---
**2 EDA Plots**

<img width="905" height="547" alt="image" src="https://github.com/katrinag2004/TeslaDS/blob/main/OUTPUT/teslastock.png?raw=true" />
<img width="996" height="600" alt="image" src="https://github.com/katrinag2004/TeslaDS/blob/main/OUTPUT/teslastockelon.png?raw=true" />
<img width="996" height="600" alt="image" src="https://github.com/katrinag2004/TeslaDS/blob/main/OUTPUT/TSLAEvent.png?raw=true" />

