# 🏨 Hotel Booking Analysis

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/techysuman27/EDA---Hotel_Booking_Analysis/blob/main/EDA_Hotel_Booking_Analysis_.ipynb)

## 📌 Project Type  
Exploratory Data Analysis (EDA)  
**Academic Project**: Almabetter 
**Contributor**: Suman Sadhukhan (Individual)

---

## 📊 Project Summary

This project explores booking data from city and resort hotels to uncover **guest behavior**, **seasonal trends**, and **factors affecting cancellations**. By conducting a thorough exploratory data analysis, we identified key metrics that impact hotel operations and customer satisfaction.  

The dataset includes attributes such as reservation date, length of stay, number of guests, booking method, cancellation status, and more.

---

## 🧩 Objectives

- Understand booking trends and patterns  
- Identify peak booking months  
- Analyze cancellation trends and reasons  
- Compare city vs resort hotel performance  
- Provide actionable business insights  

---

## 📂 Dataset

The dataset is publicly available and includes over **119K rows** of hotel bookings.  
**Features include**:  
- Booking date, check-in/out info  
- Customer demographics  
- Booking source/channel  
- Cancellation status  
- Number of nights, guests, parking, etc.

---

## 🔢 Key Numerical Insights

📌 **Dataset Overview**  
- **Total Records**: 119,390  
- **City Hotel Bookings**: ~79,330  
- **Resort Hotel Bookings**: ~40,060  

🚫 **Cancellations**  
- **Overall Cancellation Rate**: ~37% (44,317 bookings)  
- **City Hotel Cancellation Rate**: 41%  
- **Resort Hotel Cancellation Rate**: 28%  

📆 **Booking Seasonality**  
- **Most Booked Month**: July (~10.2% of total bookings)  
- **Least Booked Month**: January  
- **Lead Time Impact**: Cancellations increase with longer lead time  

🌐 **Guest Origin**  
- **Top 5 Countries** by Booking Count:  
  1. Portugal  
  2. United Kingdom  
  3. France  
  4. Spain  
  5. Germany  

📲 **Booking Channels**  
- **OTA (Online Travel Agent)** used for ~80% of bookings  
- **OTA** has the **highest cancellation rate** among all channels  

👪 **Guest Composition**  
- Majority: 2 adults, 0 children  
- **Average Guests per Booking**: ~2.1  
- **Children Field Nulls**: Filled with 0 or average  

🅿️ **Parking Space Requests**  
- ~87% of bookings did **not require** parking space

---

## 🛠️ Tools & Technologies

- **Python** (Pandas, NumPy, Seaborn, Matplotlib)  
- **Jupyter Notebook / Google Colab**  

---

## 📈 Visual Analysis

> All insights were visualized with Matplotlib/Seaborn and **verified using SQL queries** in a MySQL database.

- 📊 Booking trend by month and hotel type  
- ❌ Cancellations by lead time and booking channel  
- 🌍 Guest country heatmaps  
- 🏨 Hotel preference by guest type (solo, family, group)  
- 🧾 Revenue estimation and average stay length  

---


## 🎯 Strategic Recommendations

- Introduce flexible policies for OTA bookings with long lead time  
- Focus summer campaigns on resort bookings  
- Offer cancellation protection plans for high-risk bookings  
- Create loyalty benefits for family travelers  
- Increase parking availability in high-demand months

---

## 📁 Deliverables

- 📒 Jupyter Notebook with full EDA  
- 📊 Power BI Dashboard (optional enhancement)   
- 🧠 Strategic recommendations for business teams

---

## 🚀 How to Run

```bash
# Clone the repo
git clone https://github.com/yourusername/EDA-Hotel-Booking-Analysis.git
cd EDA-Hotel-Booking-Analysis

# Open the notebook
Open EDA_Hotel_Booking_Analysis_.ipynb in Jupyter/Colab
