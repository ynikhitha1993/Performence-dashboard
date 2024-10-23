# Performance Dashboard

## Overview
This project is an **AWS Cloud-Based Data-Driven Performance and Efficiency Dashboard** for 2024, focused on analyzing performance metrics such as **fuel consumption**, **energy consumption**, and **CO2 emissions** across different categories of vehicles, including **SUVs** and **Electric Vehicles**. The dashboard provides various visualizations to compare key metrics.

## Features
- **Category Filtering**: Compare metrics across categories like **SUVs** and **Electric Vehicles**.
- **Metric Comparison**: Visualize metrics such as:
  - Fuel Consumption (l/100km)
  - Energy Consumption (kWh/100km)
  - CO2 Emissions (g/km)
- **Graphical Visualizations**: Line graphs, box plots, histograms, and correlation heatmaps to gain insights into vehicle performance and environmental impact.

## Technologies Used
- **Python**: For data manipulation and analysis.
- **Dash**: For building the interactive web dashboard.
- **Plotly**: For creating visualizations such as line graphs, box plots, and heatmaps.
- **Pandas**: For handling and processing the dataset.
- **GitHub**: Version control and collaboration.

## Dataset
The dataset consists of performance metrics for various **BMW** vehicle models, including SUVs and Electric Vehicles. Key metrics include fuel consumption, energy consumption, and CO2 emissions.

## How to Run the Project
1. Clone the repository:
    ```bash
    git clone https://github.com/ynikhitha1993/Performance-dashboard.git
    ```
2. Navigate to the project directory:
    ```bash
    cd Performance-dashboard
    ```
3. Install the required dependencies (e.g., Dash, Plotly, Pandas):
    ```bash
    pip install -r requirements.txt
    ```
4. Run the dashboard locally:
    ```bash
    python app.py
    ```
5. Open your browser and go to `http://127.0.0.1:8050/` to view the dashboard.

## Visualizations
The dashboard includes the following visualizations:
- **Comparison Line Charts**: Compare metrics like **Fuel Consumption** and **CO2 Emissions** across vehicle models.
- **Box Plots**: Visualize the distribution of performance metrics for different vehicle categories.
- **Histograms**: Analyze the frequency distribution of key metrics.
- **Correlation Heatmaps**: Understand the relationships between different performance metrics.

## Future Improvements
- Integration with real-time data for live updates.
- Add more vehicle categories and expand the dataset.
- Implement predictive analytics to forecast vehicle performance based on historical data.

## Contribution
Feel free to fork this project and submit pull requests. For major changes, please open an issue first to discuss what you would like to change.
