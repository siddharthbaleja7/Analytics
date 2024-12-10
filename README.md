# App Performance Dashboard

## Setup Instructions
1. Install Python 3.8+.
2. Install required libraries using:
   ```bash
   pip install pandas matplotlib
3. Run the script:
   ```bash
   python app_analysis.py
## Approach
* **Metrics**: Calculated average, P95 response times, error rates, and peak usage.
* **Visualizations**: Used matplotlib for trends, error patterns, and comparisons.
* **Anomalies**: Detected unusual spikes using statistical methods.

## Insights
* Found peak hours of usage.
* Observed endpoints with high latency.
* Detected anomaly in error rates at specific times.

## Future Improvements
* Use interactive dashboards like Plotly.
* Add detailed anomaly reporting.
* Include real-time monitoring.
