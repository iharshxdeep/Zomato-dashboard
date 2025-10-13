# 🍴 Zomato Insights — Restaurant Analytics Dashboard

A powerful, data-driven dashboard that provides insights into Zomato’s restaurant listings, ratings, customer preferences, and city-wise performance.  
It enables data analysts, marketers, and restaurant owners to make smarter, insight-backed decisions for growth and customer satisfaction.

---

## 📝 1. Short Description / Purpose
**Zomato Insights Dashboard** is an analytical tool designed to visualize and explore restaurant data — including cuisines, delivery trends, customer ratings, and pricing.  
The dashboard helps identify high-performing restaurants, analyze customer satisfaction patterns, and optimize business strategies across multiple cities.

---

## 🚀 2. Key Features
- 🍽️ **Restaurant Overview:** Total restaurants, cuisines, and city coverage.  
- ⭐ **Rating Analytics:** Average ratings, top-rated restaurants, and customer feedback trends.  
- 💰 **Price Range Insights:** Comparison of restaurant pricing across cities and cuisines.  
- 📊 **Order & Delivery Trends:** Peak order hours, delivery time averages, and demand analysis.  
- 🌆 **City Performance Dashboard:** Compare restaurant density, ratings, and cost-of-living factors city-wise.  
- 🧭 **Interactive Filters:** City, cuisine type, cost bracket, delivery/ dine-in options, and more.

---

## 🧠 3. Tech Stack
The dashboard was built using the following tools and technologies:

- **Power BI / Tableau / Dash (Plotly):** Main visualization platform for analytics and reporting.  
- **SQL / Pandas:** Data transformation, cleaning, and preprocessing for visualization.  
- **Excel / CSV / API:** Source data containing restaurant, user, and review details.  

---

## 🗂️ 4. Data Sources & Modeling
The data follows a **star-schema model** with `Restaurants` as the central fact table and supporting dimension tables.

- **Restaurants:** `restaurant_id`, `name`, `city`, `cuisine`, `price_range`, `average_cost`, `rating`.  
- **Orders:** `order_id`, `restaurant_id`, `order_value`, `delivery_time`, `date`.  
- **Customers:** `customer_id`, `location`, `age_group`, `order_frequency`.  
- **Reviews:** `review_id`, `restaurant_id`, `rating`, `sentiment_score`, `review_text`.  

---


## Screenshot / Demos
Example: ![Dashboard preview](https://github.com/iharshxdeep/Zomato-dashboard/blob/main/Screenshot%202025-10-13%20160140.png)
