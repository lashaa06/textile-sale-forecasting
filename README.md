#  Textile Sales Forecasting using SARIMA (1964–1975)

> A time-series forecasting project using a simulated dataset to model monthly garment sales and predict future demand trends in the textile industry.

---

##  Overview:

This project involves the development of a **Seasonal ARIMA (SARIMA)** model to forecast **monthly sales of garments** from **January 1973 to December 1975** based on simulated historical sales data from **1964 to 1972**.

Due to data confidentiality during internship, a synthetic dataset was generated to closely reflect real-world seasonal trends, upward growth, and volatility seen in garment manufacturing sales cycles.

---

##  Objective:

- Simulate monthly garment sales data to mimic industry behavior  
- Perform basic exploratory data analysis (EDA)  
- Apply SARIMA model for seasonal forecasting  
- Visualize historical vs. predicted future sales  
- Provide business inferences for inventory and production planning  

---

##  Project Structure:

```bash
├── garment_monthly_sales_1964_1972.csv   # Simulated dataset
├── sales_forecasting_textile.ipynb       # Colabk with code, EDA, SARIMA model
├── plot.png                               # Forecast plot image 
├── README.md                              # Project documentation
```

---

##  Tools & Technologies:

| Tool        | Purpose                          |
|-------------|----------------------------------|
| Python      | Programming Language             |
| pandas      | Data manipulation and analysis   |
| matplotlib  | Plotting and visualization       |
| seaborn     | Statistical visualization        |
| statsmodels | Time series modeling (SARIMA)    |

---

##  Dataset Description:

- **Type**: Simulated monthly sales data  
- **Range**: Jan 1964 – Dec 1972  
- **Frequency**: Monthly  
- **Features**:
  - Realistic seasonality (higher sales in festive months)
  - Gradual upward trend
  

⚠️ *Note: The dataset was artificially generated due to confidentiality of real business data.*

---

##  Exploratory Data Analysis (EDA)

- Checked for null values  
- Visualized overall sales trend (line plot)   
- Identified seasonal spikes around year-end months  

---

##  Modeling Approach:

Used **SARIMA (Seasonal Auto-Regressive Integrated Moving Average)**:
- Accounts for seasonality, trends, and lagged dependencies  
- Trained on 9 years of monthly sales data  
- Forecasted for 2 future years (1973–1975)  

---

##  Results:

- Seasonal sales peaks were accurately captured  
- Demand remained stable with slight upward trend  
- Forecast followed realistic textile industry patterns  

---

##  Business Inference:

- Helps in **inventory planning** by identifying high-demand months  
- Supports **production optimization** aligned with seasonal demand  
- Reduces risks of **overproduction or stockouts**  
- Can be extended to include **category-level forecasts** or **region-wise segmentation**

---

##  How to Use This Project:

1. Clone or download this repository  
2. Run `sales_forecasting_textile.ipynb` in Google Colab 
3. Review the EDA, model fitting, and forecast sections  
4. Modify the dataset or model parameters to explore further  

---

##  Author:

**MAGHEILASHAA SELVAKUMAR**  
B.Tech – Artificial Intelligence & Data Science  

LinkedIn: [https://www.linkedin.com/in/magheilashaa-s-74b53a274/]
GitHub: [https://github.com/lashaa06]

---

## Acknowledgments;

- Project guided by concepts learned during academic and internship training  
- Dataset generated using OpenAI's ChatGPT for educational purposes  

---

##  Tags:

`Time Series` `SARIMA` `Sales Forecasting` `Textile Industry` `AI & DS` `Internship Project` `Python`
