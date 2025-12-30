# 📈 Stock Market Analytics Dashboard (Power BI)

## 📌 Project Overview
This project is a Power BI–based Stock Market Analytics Dashboard that analyzes and visualizes stock market data using live API integration. Stock price data is fetched directly from the Twelve Data API and transformed using Power Query to generate interactive and meaningful insights.

---

## 🎯 Objectives
- Analyze historical stock price trends  
- Compare performance of multiple companies  
- Provide interactive visual insights for investment analysis  

---

## 📊 Stocks Covered
- Apple (AAPL)  
- Tesla (TSLA)  
- Amazon (AMZN)  

---

## 🛠️ Tools & Technologies
- Power BI Desktop  
- Power Query (M Language)  
- Twelve Data REST API  
- Time-Series Data Analysis  

---

## 📈 Dashboard Features
- Time-series line charts for stock prices  
- Company-wise comparison visuals  
- Key performance indicators (KPIs)  
- Interactive slicers and filters  

---

## 🔗 Data Source
- Twelve Data API – provides real-time and historical stock market data through REST API endpoints.

---

## 📂 Project Structure
Stock-Market-Analytics-PowerBI/
│
├── Stock_Market_Analytics.pbix
├── README.md
├── assets/
│ ├── dashboard_overview.png
│ └── stock_comparison.png


---

## 🚀 How to Use the Project
1. Clone or download this repository  
2. Open `Stock_Market_Analytics.pbix` in Power BI Desktop  
3. Set your Twelve Data API key using Power BI parameters  
4. Click **Refresh** to load the latest data  

---

## 🔐 API Key Setup (Secure Method)

To keep the API key safe, Power BI parameters are used instead of hardcoding the key.

### Steps to Configure API Key:
1. Open Power BI Desktop  
2. Go to **Transform Data → Manage Parameters → New Parameter**  
3. Create a parameter with the following details:
   - Name: `TwelveData_API_Key`
   - Type: Text  
   - Value: Paste your API key here  
4. Use this parameter inside the Power Query API URL  
5. Click **Close & Apply**, then **Refresh**

---

## 🧩 How to Get Twelve Data API Key
1. Visit https://twelvedata.com  
2. Sign up for a free account  
3. Generate your API key from the dashboard  
4. Paste the key into Power BI parameter  

---

## 📌 Important Notes
- API key is NOT included in this repository for security reasons  
- Users must use their own API key  
- Free API plan has request limitations  

---

## 📚 Key Learnings
- Power BI API integration using Power Query  
- Secure handling of API credentials  
- Time-series stock data analysis  
- Financial dashboard design and storytelling  

---

## 🏁 Conclusion
This project demonstrates how Power BI can be effectively used to build a real-time stock market analytics dashboard using API-based data sources, without relying on external programming languages.

---





