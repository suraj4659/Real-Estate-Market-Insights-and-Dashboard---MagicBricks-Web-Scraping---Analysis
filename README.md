# 🏠  MagicBricks Web Scraping And Analysis-PYTHON-POWER BI 

## 📌 Project Overview
Ever wondered which Indian city secretly beats Mumbai in property rates?  
This project dives deep into **India’s real estate market** using data **scraped directly from MagicBricks**, one of India’s leading property platforms.  

The goal was to **collect, clean, analyze, and visualize** property listings to uncover patterns, anomalies, and insights that can help:
- Home buyers understand fair pricing
- Investors identify undervalued cities
- Businesses make data-driven real estate decisions

---

## 🕸️ Web Scraping
I scraped **real property listings from MagicBricks** using Python libraries like `BeautifulSoup` and `requests`.  
The scraped data included:
- City name  
- Price  
- Carpet area (sqft)  
- Room type (BHK)  
- Facing direction (North, East, etc.)  
- Property type  

The raw data was then transformed into a structured dataset for deeper analysis.

---

## 🧹 Data Cleaning & Feature Engineering
Using **Pandas**, I performed:
- Removal of missing and duplicate values  
- Standardization of prices (converted to ₹)  
- Conversion of area metrics into sqft  
- Created **new insights** such as:
  - `price_per_sqft_calc` → price per square foot  
  - `price_per_bhk` → average price per BHK  
  - Categorical segmentation (city, facing, room type)

---

## 🔍 Exploratory Data Analysis (EDA)
Through **Python (Matplotlib, Seaborn)**, I explored:
- **City-wise average price**  
- **Price variation by facing direction**  
- **Relationship between carpet area & price**  
- **Most common room types (BHKs)**  
- **Cities offering best value per sqft**

Key insights included:
- 🏙️ **Gandhinagar** surprisingly showed one of the highest price-per-sqft averages.  
- 🧭 **East-facing** and **North-East-facing** homes commanded higher prices.  
- 💰 Strong correlation between carpet area and price — but with city-specific anomalies.  

---

## 📊 Power BI Dashboard
After cleaning and analyzing the data, I built a **Power BI Dashboard** for interactive visualization.  

### 🧩 Key Dashboard Features:
- **KPIs** → Average Price, Price per Sqft, Total Listings  
- **Interactive Filters** → City, Room Type (BHK), Facing  
- **Visuals Used:**
  - Bar charts (city-wise average price)
  - Scatter plot (Price vs Carpet Area)
  - Geo-map (property distribution)
  - Pie chart (room type share)

This dashboard enables **real-time data exploration** and quick insights for decision-making.

---

## ⚙️ Tech Stack
| Category | Tools Used |
|-----------|-------------|
| Web Scraping | Python, BeautifulSoup, Requests |
| Data Cleaning & Analysis | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn, Power BI |
| Data Source | MagicBricks (Web Scraping) |

---

## 📈 Key Learnings
- End-to-end data pipeline: from web scraping → data cleaning → visualization  
- Data storytelling and dashboard design for business insights  
- Handling real-world messy data and uncovering market trends  
- Creating KPIs that help users make actionable decisions  

---

## 🌟 Future Enhancements
- 🧠 **Add Machine Learning:** Predict property prices based on features (city, facing, area, etc.)  
- 🌐 **Automate Web Scraping:** Schedule daily/weekly data refresh  
- 🗺️ **Add Location Intelligence:** Use Geo-coded coordinates for deeper spatial insights  

---

## 📬 About
**Author:** [Your Name]  
**Role:** Aspiring Data Analyst / Data Scientist  
**Connect with me on:** [LinkedIn](https://linkedin.com/in/yourprofile)  

> “Turning raw data into powerful business insights — one dashboard at a time.”
