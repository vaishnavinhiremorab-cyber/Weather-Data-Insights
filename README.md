# Weather-Data-Insights
Project Description 🌍
An end-to-end Power BI solution that tracks live weather and air quality using WeatherAPI.com. It features a dynamic dashboard with real-time health alerts, atmospheric trends, and multi-city monitoring. 📡☁️

Project Overview 🚀
This project turns live environmental data into an easy-to-read dashboard. By connecting Power BI to a weather API, I created a tool that tracks temperature, wind speed, and air quality in real-time. 🌡️ It is designed to help users understand local conditions and health risks at a glance, using cities like Ajmer and Bengaluru as examples. 🏙️

Prerequisites 🔑
To run this project, you need a free account on WeatherAPI.com to get your own API key.
💻 You also need Power BI Desktop installed to open the project file. 
✅ Basic knowledge of how data models work will help you navigate the charts and filters used in the final report. 

Connecting the Data 🔗
The process starts by linking Power BI to the web using an API URL. This link acts as a bridge, allowing Power BI to "talk" to the weather servers. 
🌐 By setting this up as a web source, the dashboard stays dynamic, meaning it can refresh and show the latest weather every time you open it. 

Cleaning and Shaping 🧹
Raw API data usually arrives in a messy format called JSON. I used the Power Query Editor to "flatten" this data, turning nested code into a clean table with columns for temperature, humidity, and pollution. 🧱 This step is crucial for making the data readable so it can be used in charts and gauges. 

Smart Health Alerts 🧠
I used DAX formulas to add "smart" features to the report.
For example, the dashboard uses the US-EPA standard to judge air quality. 🚦 A custom formula checks the pollution score and automatically updates the color—turning green for "Good" or red for "Unhealthy"—while providing health advice like "Air is clean" or "Wear a mask." 😷 

Dashboard Features 🎨
The final dashboard uses a dark theme to make the visuals "pop." It includes KPI cards for humidity and UV index, a 7-day temperature trend line, and a "Chance of Rain" bar chart. 📊 A central gauge shows the Air Quality Index (AQI), making it easy to monitor specific pollutants like PM2.5 and Carbon Monoxide. 📉 

Project Outcome ✨
This dashboard provides a powerful, live view of our environment. It demonstrates how to handle real-time APIs, transform complex data, and use professional design principles to create a tool that is both useful and easy for anyone to understand. 🏆

### 🌦️ Weather Analysis Dashboard
![Real-time Weather Insights](https://github.com/vaishnavinhiremorab-cyber/Weather-Data-Insights/blob/main/SnapShot_of_the_Dashboard.png)

 
