# Zomato-Bangalore-Restaurant-Trends-Hackathon
# Zomato Bangalore Restaurant Analysis
- Made By: Kanishka Sejwal
📌 Overview

- This project presents a complete data-driven analysis of Zomato restaurant data for Bangalore.
- It includes data cleaning, preprocessing, EDA, visualizations, geospatial mapping, dashboards, and insights to understand customer behavior, pricing trends, cuisine preferences, and locality performance.

* The analysis aims to provide value for:

~ Food delivery platforms (Zomato, Swiggy)

~ Restaurant owners & consultants

~ Business analysts & data scientists

* Marketing strategists

Students participating in analytics hackathons

📂 Project Contents

This project contains the following essentials:

📁 Dataset  
   ├── zomato_data.csv  
   ├── Geographical Coordinates.csv  
   ├── merged_cleaned.csv  

📁 Visualizations  
   ├── colored_rating_distribution.png  
   ├── colored_cost_distribution.png  
   ├── colored_top10_cuisines.png  
   ├── colored_top10_localities.png  
   ├── colored_votes_vs_rating.png  

📁 Maps  
   ├── restaurant_density_map.html  
   ├── italian_restaurants_map_fixed.html  
   ├── italian_restaurants_filtered_map.html  

📁 Dashboards  
   ├── interactive_dashboard.html  
   ├── streamlit_zomato_app.py  

📁 Reports  
   ├── Zomato_Full_Report_With_Visuals.pdf  
   ├── EDA_Presentation.pptx  

🧹 Data Cleaning Steps

* The dataset was cleaned using:

~ Converted rating from “X/5” to float

~ Removed special characters and commas from cost column

~ Filled missing ratings, costs, and votes with median values

~ Converted binary columns (online_order, book_table) to 0/1

~ Categorical values filled with appropriate defaults

~ Merged restaurant data with coordinates on listed_incity

* Ensured final types:

~ rate → float

~ votes → int

~ approx_costfor_two_people → int

📊 Key Visualizations

* The project includes:

~ Ratings Distribution

~ Cost for Two Distribution

~ Top Cuisines

~ Top Localities

~ Votes vs Rating Scatter Plot

~ Italian Restaurant Geospatial Map

* Interactive Plotly Dashboard

- All visualizations are color-coded and saved as PNG files.

🌍 Geospatial Analysis

* Using Folium, the project generates:

✔ Restaurant Density Map

- Shows clusters of food hotspots across Bangalore.

✔ Italian Restaurant Map

- Highlights restaurants serving Italian cuisine.

✔ Italian Filtered Map

With dynamic filters:

- Rating

- Cost

- Locality

- Votes

📈 Dashboard

Two dashboards are included:

✔ Plotly Interactive Dashboard (HTML)

:Hover interaction

:Region insights

:Cuisine frequency

:Rating & cost analysis

✔ Streamlit App

:Sidebar filters (cuisine, locality, rating, votes)

:Interactive charts

:Restaurant maps

:Data table preview

Run locally:

streamlit run streamlit_zomato_app.py

📝 EDA Answers (Summary)

- Minimum cost for two: ₹40

- Most low-rated + high-voted locality: Brookefield

- Highest restaurant-type diversity: BTM

- Most profitable locality: MG Road

- Worst rated category: Dessert Parlor, Kiosk

- Best quality-demand locality: Koramangala 7th Block

- These insights come from detailed statistical calculations included in the notebook.

🧠 Findings

1. system is dense, competitive, and dominated by mid-priced restaurants.

2. North Indian, South Indian, Chinese, and Desserts are most popular cuisines.

3. Koramangala, Indiranagar, Whitefield, and HSR are top hotspots.

4. MG Road and Church Street offer high revenue potential.

5. Online orders correlate strongly with high ratings and high votes.

6. Improvement is needed in Dessert Parlors and Kiosks.

🏁 Conclusion

This project provides a deep understanding of the food landscape in Bangalore.
The insights can guide Zomato and other food platforms to:

Improve service quality

Optimize recommendations

Target marketing campaigns

Expand strategically

Improve customer satisfaction

The report, dashboards, and visualizations together form a complete analytical case study.

✒ Made By

KANISHKA SEJWAL
Business Analyst | Data Enthusiast
