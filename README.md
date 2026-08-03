# N100-FINANCIAL-INTELLIGENCE-PLATFORM
📈 Nifty100 Financial Intelligence Platform

A comprehensive Financial Intelligence Dashboard for analyzing Nifty100 companies using Python, SQLite, Pandas, Plotly, and Streamlit.

🔗 Live Demo
https://n100-financial-intelligence-platform-gxelmw4o3zvqdhfcwptznn.streamlit.app/

📌 Project Overview

The Nifty100 Financial Intelligence Platform transforms raw financial datasets into an interactive analytics dashboard. It enables investors, analysts, and finance enthusiasts to explore company fundamentals, compare peers, screen stocks, analyze financial trends, and generate business insights from multiple financial datasets.

The platform integrates several structured datasets into a centralized SQLite database and provides a fast, user-friendly interface through Streamlit.

✨ Features
🏢 Company Profile
Company overview
Business description
Website
ROE
ROCE
Book Value
Face Value
🔍 Stock Screener

Filter companies using

Minimum ROE
Minimum ROCE

Export screened companies as CSV.

📊 Peer Comparison

Compare companies within the same peer group.

Includes:

ROE Comparison
ROCE Comparison
Book Value Comparison
Interactive charts
📈 Financial Trends

Visualize company financial performance across years.

Metrics include:

Sales
Net Profit
EPS
Operating Profit
🏭 Sector Analysis

Explore companies sector-wise.

Includes

Company Count
Sector Distribution
Interactive Charts
💰 Capital Structure

Analyze

Book Value
Face Value
Financial Strength
📑 Reports

Generate downloadable reports and view important financial information.

🛠 Tech Stack
Frontend
Streamlit
Backend
Python
Database
SQLite
Data Processing
Pandas
NumPy
Visualization
Plotly
Deployment
Streamlit Community Cloud
📂 Project Structure
nifty100-financial-intelligence-platform/
│
├── app.py
├── nifty100.db
├── requirements.txt
│
├── pages/
│   ├── 02_Profile.py
│   ├── 03_Screener.py
│   ├── 04_Peers.py
│   ├── 05_Trends.py
│   ├── 06_Sectors.py
│   ├── 07_Capital.py
│   └── 08_Reports.py
│
├── utils/
│   └── db.py
│
└── supporting datasets/
📊 Datasets Used
Companies
Profit & Loss
Balance Sheet
Cash Flow
Financial Ratios
Market Capitalization
Stock Prices
Peer Groups
Sectors
Analysis
Documents
Pros & Cons
🚀 Installation

Clone the repository

git clone https://github.com/your-username/nifty100-financial-intelligence-platform.git

Move into the project

cd nifty100-financial-intelligence-platform

Install dependencies

pip install -r requirements.txt

Run the application

streamlit run app.py
📈 Dashboard Modules
Module	Description
Company Profile	Explore company fundamentals
Stock Screener	Filter companies by financial metrics
Peer Comparison	Compare companies within the same industry
Financial Trends	Analyze historical financial performance
Sector Analysis	Visualize sector-wise insights
Capital Structure	Study capital and valuation metrics
Reports	Download and review financial reports
🎯 Key Highlights
Interactive financial dashboard
SQLite-powered backend
Fast data loading with Streamlit caching
Clean and responsive interface
Peer group analytics
Financial screening engine
Interactive visualizations
Downloadable reports
Cloud deployed with Streamlit
