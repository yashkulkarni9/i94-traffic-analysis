# 📊 Finding Heavy Traffic Indicators on I-94

## 🧠 Project Overview:
- This project explores the I-94 Interstate Highway traffic data to identify indicators of heavy traffic using exploratory data visualization techniques.

- The goal is to discover patterns such as:
1. What time of day traffic peaks?

2. How weather conditions influence volume?

3. Whether weekends, holidays, or months show any specific trends?

- By analyzing and visualizing this dataset, we uncover key insights that can help traffic planners, city engineers, or logistics companies make data-driven decisions.

## ✅ Key Objectives
- Identify peak traffic hours and days

- Examine weather's impact on traffic volume

- Understand traffic patterns by month and holiday

- Visualize all insights using Python’s plotting libraries

## 🧰 Technologies & Libraries Used

- Python 3

- Pandas – Data handling and preprocessing

- Matplotlib – Basic plotting

- Seaborn – Advanced visualization and styling

- Google Colab / Jupyter Notebook – Running and displaying visualizations

## 📁 Dataset Used
- Name: [Metro Interstate Traffic Volume]([url](https://archive.ics.uci.edu/dataset/492/metro+interstate+traffic+volume))

- Source: UCI Machine Learning Repository

- File Name: Metro_Interstate_Traffic_Volume.csv

## 💻 How to Set Up and Run Locally
### 🔧 Prerequisites
Make sure you have the following installed:

- Python 3.7+

- pip (Python package manager)

- Jupyter Notebook (optional if not using Google Colab)

### 📥 Step-by-Step Setup Instructions
- Clone the Repository
```
git clone https://github.com/yashkulkarni9/i94-traffic-analysis.git
cd i94-traffic-analysis
```
- Create a Virtual Environment (Optional but Recommended)
```
python -m venv env
source env/bin/activate  # macOS/Linux
env\Scripts\activate     # Windows
```

- Install Required Packages
```
pip install pandas matplotlib seaborn
```
- Download the Dataset You can download it manually from the UCI Repository
Save it as:
Metro_Interstate_Traffic_Volume.csv

- Place it in the same folder as the notebook.

- Run the Notebook
```
jupyter notebook
```
- Then open the .ipynb file and run all cells
### 📈 Output Visualizations You’ll See
- Line plot of traffic by hour
- Box plots by day of week, weather, month, and holiday
- Correlation heatmap for weather-related variables

### 🎯 Real-World Use Cases
- Urban Planning: Schedule road repairs during off-peak hours

- Logistics Optimization: Improve delivery schedules based on traffic patterns

- Weather Insights: Understand how rain/snow affects traffic
