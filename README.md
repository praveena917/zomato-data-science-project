# 🍽️ Zomato Bangalore Restaurant EDA

## 📌 Project Overview
This project performs **Exploratory Data Analysis (EDA)** on the **Zomato Bangalore restaurant dataset** to uncover insights related to restaurant locations, cuisines, ratings, pricing, and customer preferences.  
The goal is to understand food trends in Bangalore and support **data-driven decision making** in the restaurant industry.

The analysis is implemented in a Jupyter Notebook using Python and popular data analysis libraries.

---

## 🎯 Objectives
- Identify locations with the highest number of restaurants  
- Analyze the **Top 10 most popular cuisines** in Bangalore  
- Compare **Online Orders vs Table Booking** trends  
- Study **rating distribution across different cost categories**  
- Detect restaurants with **high votes but low ratings**  
- Locate **top low-cost, high-rated restaurants** using map-based analysis  

---

## 📂 Dataset Information
- **Source:** Zomato Bangalore Restaurants Dataset  
- **Records:** Restaurants listed in Bangalore  

### Key Columns
- `name` – Restaurant name  
- `location` – Area in Bangalore  
- `cuisines` – Types of cuisines served  
- `rate` – Restaurant rating  
- `votes` – Number of user votes  
- `approx_cost(for two people)` – Average cost for two  
- `online_order` – Online ordering availability  
- `book_table` – Table booking availability  
- `rest_type` – Type of restaurant  

---

## 🛠️ Tools & Technologies Used
- **Python**
- **Jupyter Notebook**

### Libraries
- **Pandas** – Data manipulation  
- **NumPy** – Numerical operations  
- **Matplotlib** – Data visualization  
- **Folium** – Map-based visualization  

---

## 🔄 Project Workflow

### 1️⃣ Data Loading
- Import dataset
- Inspect structure and data types

### 2️⃣ Data Cleaning
- Handle missing values  
- Convert rating and cost columns to numeric format  
- Remove duplicates and irrelevant columns  

### 3️⃣ Exploratory Data Analysis (EDA)
- Location-wise restaurant distribution  
- Top 10 cuisines analysis  
- Online orders vs table booking comparison  
- Rating distribution by cost category  
- High votes but low ratings analysis  
- Low-cost, high-rated restaurants identification  

### 4️⃣ Data Visualization
- Bar charts for location and cuisine distribution  
- Pie chart for online orders vs table bookings  
- Box plots for rating vs cost categories  
- Scatter plot for votes vs ratings  
- **Geographical map visualization using Folium**

---

## 📊 Key Insights

### 1️⃣ Which Location Has the Most Restaurants

<img width="2967" height="1466" alt="Location with most restaurants" src="https://github.com/user-attachments/assets/11ec49bc-55b8-48ae-9f33-403a0e735371" />


**Insight:**  
BTM has the highest number of restaurants, followed by Koramangala 5th Block and HSR, indicating these areas are major food hubs driven by high demand and commercial activity.

---

### 2️⃣ Top 10 Most Popular Cuisines
<img width="960" height="498" alt="top cuisines" src="https://github.com/user-attachments/assets/94a6111a-58f4-4e1b-9342-cfe89f034d88" />





**Insight:**  
North Indian cuisine dominates Bangalore’s restaurant landscape, followed by Chinese and South Indian cuisines, reflecting strong customer preference for familiar and comfort food options.

---

### 3️⃣ Online Orders vs Table Booking
<img width="508" height="406" alt="online vs offline orders " src="https://github.com/user-attachments/assets/0a9121eb-c5c2-4aab-91f2-40d237d20eec" />

**Insight:**  
More than **80% of restaurants support online orders**, highlighting a strong shift toward convenience-based dining and digital food delivery platforms.

---

### 4️⃣ Rating Distribution by Cost Category

<img width="1750" height="1332" alt="rating distribution by cost category" src="https://github.com/user-attachments/assets/d534640b-c77e-410f-89d3-4f469b47b7f8" />


**Insight:**  
Mid-range and premium restaurants generally receive higher and more consistent ratings, while budget restaurants show wider variation in customer satisfaction.

---

### 5️⃣ Restaurants with High Votes but Low Ratings

<img width="710" height="469" alt="restaurants with high votes but low ratings " src="https://github.com/user-attachments/assets/8ba802ca-b2a6-4c3a-9e6f-15ea3ddcaeb6" />


**Insight:**  
Some restaurants attract large customer volumes despite lower ratings, suggesting popularity driven by factors such as location, pricing, or brand visibility rather than food quality alone.

---

### 6️⃣ Top 10 Low-Cost, High-Rated Restaurants & Map Analysis

![map](https://github.com/user-attachments/assets/c853d055-3112-45e3-a09d-0ee909f6c50f)


**Insight:**  
Several affordable yet highly rated restaurants are concentrated in high-demand areas, proving that quality dining in Bangalore is not limited to expensive restaurants.

---

## ✅ Conclusion
This analysis highlights how **location, cuisine preference, pricing, and convenience** strongly influence restaurant success in Bangalore.  
The insights can help restaurant owners, food delivery platforms, and customers make informed decisions.
