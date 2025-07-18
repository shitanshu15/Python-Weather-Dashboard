# 🌦️ Python-Weather-Dashboard

A Python-based real-time Weather Dashboard that fetches 5-day weather forecast data using the OpenWeatherMap API and creates clean, visually appealing graphs using Matplotlib and Seaborn. Designed for students, interns, data learners, and those looking to practice API integration, data handling, and visualization using Python.

---

## 🧠 Project Objective

The main goal of this project is to demonstrate the ability to:

Connect and retrieve real-time data from an external API.

Analyze and clean the data using Pandas.

Create understandable graphs using Matplotlib and Seaborn.

Organize the output clearly and professionally.

Present a local weather forecasting system (like a mini weather app).

---

## 📌 Key Features

✔️ Real-time city input

✔️ 30-hour weather forecast using OpenWeatherMap API

✔️ Clean timestamp formatting: "Thu 07 Jul, 05:00 PM"

✔️ Graphs generated:

🌡️ Temperature (°C)

💧 Humidity (%)

🍃 Wind Speed (m/s)

✔️ Graphs saved as .png inside a graphs/ folder

✔️ Beginner-friendly and well-commented code

✔️ Ready to run inside VS Code or any Python IDE

---

## ⚙️ How It Works

1.The user is prompted to enter a city name (e.g., Mumbai, London).

2.The script sends a request to the OpenWeatherMap API.

3.Data for the next ~30 hours is parsed and processed.

4.Using Pandas, the data is structured and cleaned.

5.Three visual graphs are generated and saved:

   > Temperature vs. Time
   
   > Humidity vs. Time

   > Wind Speed vs. Time

---

## 🔑 Get an API Key

 Visit: https://openweathermap.org/api

 Sign up for free

 Copy your API key

Open weatherdashboard.py and replace:

    API_KEY = "your_openweathermap_api_key"

---

## ▶️ Usage

Run the script using Python:

     python weather_dashboard.py
     
When prompted:

    Enter city name: mumbai
    Enter date: Today
 
📊 After execution:

Graphs will directly open infront of you on your screen.

---

## 💬 Sample Questions / Inputs

Enter city: Pune, Mumbai, London

Get hourly forecasts for 5 days

Visual graph of temperature over time

Output weather conditions like "clear sky", "scattered clouds"

## 📄 Sample Output

<img width="1918" height="1018" alt="467183010-67a2a523-e5cc-464d-88e7-f68b1fee03c0" src="https://github.com/user-attachments/assets/e9b98100-9721-4793-93e3-ed65ce3e40e1" />

---

## 📜 License

This project is licensed under the MIT License — you are free to use, modify, and distribute it with proper credit.
