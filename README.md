HAI Surveillance Dashboard - Power BI
This repository contains a Power BI project called HAI Surveillance Dashboard that focuses on the surveillance of Health-Associated Infections (HAI), the correlation of medical conditions and bacterial infections with Procalcitonin (PCT) levels, and providing insights through a live antibiogram. The dashboard visualizes this critical data to help monitor infection trends and inform treatment decisions.

Project Overview
The HAI Surveillance Dashboard aims to provide healthcare professionals with a real-time, data-driven tool to monitor the dynamics of hospital-acquired infections (HAI). By analyzing the correlation between HAI cases and biomarkers such as PCT, as well as bacterial resistance patterns through antibiograms, the dashboard helps in:

Identifying and tracking rising rates of HAI.
Analyzing the relationship between Procalcitonin (PCT) levels and infection severity.
Visualizing the most common bacterial infections and their resistance patterns via live antibiograms.
Providing a dynamic tool for healthcare professionals to quickly adapt to changing infection patterns and make informed clinical decisions.

File Structure
The project repository contains the following files:

bash
HAI_Surveillance/
├── HAI_Surveillance.pbix                   # Power BI report (dashboard)
├── data/
│   ├── culture_results_data.csv            # Synthetic data - culture results (CSV)
│   └── main_patient_data.csv               # Synthetic data - patient details (CSV)
└── README.md                               # Project overview and setup instructions

Data Sources
The data used in the dashboard includes:

Culture Results Data: Tracks bacterial cultures, infection types, and antimicrobial resistance patterns.
Main Patient Data: Contains details about patient demographics, medical conditions, and Procalcitonin (PCT) levels.
CSV Files
The repository includes two synthetic data files:

culture_results_data.csv: Contains the results of bacterial culture tests, including infection types and resistance patterns.
main_patient_data.csv: Contains patient details, including PCT levels and associated medical conditions.

These files are synthetic data examples. If you are working with your own data, you can replace these CSVs with your own data in the same format.

How to Use the Dashboard
Open the Power BI Report:

Download and install Power BI Desktop (if you haven't already).
Open the HAI_Surveillance.pbix file in Power BI Desktop.

Load the Data:

If you are replacing the provided data files, ensure your CSV files are updated and reflect the necessary columns: Patient ID, Condition, PCT Levels, Bacterial Infection, Antibiogram Results, etc.

Exploring the Dashboard:

The dashboard includes several visualizations:
HAI Trends: A time-based visualization showing the rise or fall of hospital-acquired infections.
PCT Levels Analysis: A correlation between PCT levels and infection types.
Live Antibiogram: A dynamic display of bacterial resistance patterns based on the latest available data.
Interacting with the Data:

You can filter by different conditions, infection types, and PCT thresholds using slicers on the dashboard.
Hover over charts for more detailed insights and data points.
Customizing the Dashboard
If you'd like to customize the dashboard:

Open the HAI_Surveillance.pbix file in Power BI Desktop.
Modify the queries or visualizations to reflect your organization's specific data or requirements.
Save your changes and publish to Power BI Service for collaboration or sharing.
Dependencies
This project relies on:

Power BI Desktop
CSV Files: The data is stored in two CSV files: culture_results_data.csv and main_patient_data.csv. Ensure the file format aligns with your data source.
Future Improvements
Integration with real-time data via APIs for live updates of infection trends and antibiogram results.
Enhanced predictive analytics for forecasting HAI trends using machine learning models.
Collaboration with healthcare systems to incorporate data from multiple hospitals for broader surveillance.

License
This project is licensed under the MIT License - see the LICENSE file for details.