# 🚗 Machine Learning on Sports Car Spec & Prices

## 📌 Project Overview

This project aims to explore and analyze the characteristics, performance metrics, and pricing of various **sports cars** to provide valuable insights into the automotive market. By leveraging data analysis and machine learning techniques, we examine how different specifications such as **engine size**, **horsepower**, and **acceleration** influence the pricing and popularity of sports cars.

## ❓ Problem Statement

This analysis focuses on answering key business and performance-related questions:

- What is the relationship between **engine size (L)** and the **price** of sports cars?
- How does **horsepower** influence **0–97 km/h acceleration** times?
- Is there a significant difference in sports car prices across **different manufacturing years**?
- How do **torque** and **horsepower** together affect car prices?
- Which **car brands** have the highest and lowest **average prices**, and how do their specs compare?

## 📊 Dataset Description

The dataset contains specifications and pricing details of various high-end sports cars. Key columns include:

- **Car Make**: Manufacturer or brand (e.g., Ferrari, McLaren, Porsche)
- **Car Model**: Specific model (e.g., 911 Turbo, C_Two)
- **Year**: Manufacturing year of the car
- **Price (RM)**: Price in Malaysian Ringgit
- **Engine Size (L)**: Engine capacity in liters
- **Horsepower**: Power output of the car
- **0–97 km/h Time (s)**: Time to accelerate from 0 to 97 km/h (0–60 mph)

## 🎯 Objectives

We aim to perform exploratory data analysis to:

- Calculate average price by **car make**
- Analyze average price across **different years**
- Identify top 10 **fastest cars** (by 0–97 km/h time)
- Identify top 10 **most powerful cars** (by horsepower)
- Visualize relationships:
  - Price vs Horsepower
  - Engine Size vs Horsepower
  - Torque vs Horsepower
  - 0–97 km/h Time vs Horsepower
- Assess **brand popularity**
- Understand **price trends over time**

## 🧠 Technologies Used

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib / Seaborn**
- **Jupyter Notebook**

## 🚀 How to Run

1. Clone the repository
2. Open the `.ipynb` file in Jupyter Notebook
3. Run all cells to view the analysis
