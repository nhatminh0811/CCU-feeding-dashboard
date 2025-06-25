# 🏥 CCU Feeding Dashboard

A web-based dashboard designed to support Critical Care Unit (CCU) staff in identifying patients who may require dietitian referrals, by analyzing and visualizing physiological data.

## 📌 Overview

This project helps ICU/CCU staff make timely nutrition-related decisions. It allows uploading of patient data via CSV, visualizes clinical metrics, and uses machine learning to flag patients at nutritional risk.

## 🚀 Features

- Upload and process patient data from CSV files
- Visualize key physiological indicators with charts
- Flag patients needing dietitian referral
- Filter patients based on customizable criteria
- Admin panel for managing data and alerts

## 🧠 Tech Stack

- **Frontend**: React, Bootstrap, Chart.js  
- **Backend**: Node.js, Express.js  
- **Database**: MongoDB  
- **ML/Analytics**: Python (pandas, scikit-learn), via microservice or precomputed logic

## 🗃️ Dataset

Patient data is uploaded via CSV and includes:
- Demographics
- Ventilation parameters (FiO2, Tidal Volume, PEEP, etc.)
- Feeding metrics (volume, rate)
- Calculated BMI and clinical flags



