# solar_investment_model_py
Financial model for assessing solar project viability
This is an interactive financial model built to assess the investment viability of a 100 MW utility-scale solar project in India. The tool is designed to replicate the kind of analysis performed by top-tier consulting firms and investment funds when evaluating major infrastructure projects.

The primary goal is to move beyond a static Excel sheet and create a dynamic, web-based dashboard that allows for real-time sensitivity analysis and robust risk assessment.

## ✨ Key Features

* **Interactive Dashboard:** Easily modify key project assumptions like CAPEX, Plant Load Factor (PLF), tariff, and financing structures to see their immediate impact.
* **25-Year DCF Model:** A complete Discounted Cash Flow model is calculated in the background, projecting revenues, costs, taxes, and cash flow to equity.
* **Core Financial Metrics:** Instantly calculates and displays the project's **Net Present Value (NPV)**, **Equity IRR**, **Payback Period**, and **Levelized Cost of Energy (LCOE)**.
* **Monte Carlo Risk Simulation:** The standout feature—runs 1,000 randomized scenarios to simulate real-world uncertainty in costs and performance, providing a probabilistic view of the investment's potential returns.

## 🛠️ Technology Stack

* **Frontend:** HTML
* **Styling:** Tailwind CSS
* **Logic & Calculations:** JavaScript (ES6)
* **Data Visualization:** Chart.js

## 🚀 How to Use

1.  Adjust any of the input parameters in the "Project Assumptions" panel on the left.
2.  Click **"Calculate Financials"** to update the key metrics and the 25-year cash flow table.
3.  Click **"Run Simulation"** to perform the Monte Carlo risk analysis and view the distribution of potential IRR outcomes.
