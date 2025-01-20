# AgriPrice-Analysis
Analyzing Consumption, Production, and Pricing of Food Commodities in Yogyakarta (2018–2023)

---

## Overview
This project aims to analyze the consumption, production, and pricing of various food commodities in Yogyakarta from 2018 to 2023. It involves data preprocessing, merging, visualization, and the application of multiple linear regression to predict food prices and identify key influencing factors.

---

## Project Structure
### **Datasets**
The project uses the following datasets:
- **HargaBahan18-23.csv**: Contains the prices of various food commodities from 2018 to 2023.
- **JumlahKonsumsi18-23.csv**: Contains the consumption data of various food commodities from 2018 to 2023.
- **JumlahProduksi18-23.csv**: Contains the production data of various food commodities from 2018 to 2023.
- **PenghasilanMin18-23.csv**: Contains the minimum income data in Yogyakarta from 2018 to 2023.

---

## Workflow
### **Data Preprocessing**
1. Convert relevant columns to the appropriate data types (e.g., float).
2. Filter datasets to include only relevant commodities.
3. Transform datasets into long format using the `melt` method.
4. Merge datasets based on shared columns (e.g., year, commodity).

### **Visualization**
- **Scatter Plots and Line Plots**:
  - Visualize trends in consumption, production, and pricing over time.
- **Histograms**:
  - Analyze the distribution of residuals to assess model fit.

### **Modeling**
- Apply **multiple linear regression** using:
  - **scikit-learn**: For splitting data into training and testing sets and evaluating model performance.
  - **statsmodels**: For detailed statistical analysis, including coefficient estimation and significance testing.
- Evaluate the model by:
  - Assessing R-squared values.
  - Analyzing residuals.

---

## Results
- The regression model outputs include:
  - **Coefficients**: Indicating the impact of each independent variable.
  - **R-squared values**: Measuring the model's fit to the data.
  - **Residual Analysis**: Verifying assumptions of linear regression.
- Key Findings:
  - The production of staple foods significantly influences price trends compared to other factors.

---

## Tools & Libraries
- **Programming Language**: Python
- **Development Environment**: Visual Studio Code
- **Libraries**:
  - **Pandas**: Data manipulation and preprocessing.
  - **Matplotlib**: Data visualization.
  - **scikit-learn**: Machine learning and model evaluation.
  - **statsmodels**: Statistical analysis and model diagnostics.

---

