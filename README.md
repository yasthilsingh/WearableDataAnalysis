# 🚴‍♂️ Uncovering Training Intensity

This project analyzes wearable fitness data to explore training intensity over time using time series methods. It showcases practical skills in **data cleaning**, **rolling window analytics**, and **Python dashboarding**.

## 🔍 Project Summary

The goal was to derive insights from activity tracker data by analyzing patterns in speed, pace, and distance. Activities were classified (e.g., Cycling vs. Running) based on average speed thresholds and further evaluated using smoothed trend lines.

> 📌 **Note**: This dataset is **not publicly available** due to privacy reasons.

---

## 🛠 Skills Demonstrated

- 🧹 **Data Cleaning**: Interpolated missing values, dropped high-null columns.
- 📈 **Time Series Analysis**: Used 7-day rolling averages to analyze training load.
- 📊 **Statistical Thinking**: Applied threshold-based logic for activity classification.
- 📉 **Data Visualization**: Created an interactive time series dashboard in Python.

---

## 🌐 Live Walkthrough and Visualisations

This section showcases **static visualizations** of the analysis results, rendered directly from the notebook. These plots highlight key patterns in training intensity across time.

📄 **Hosted on GitHub Pages:**  
👉 [View Walkthrough and Visualisations](https://yasthilsingh.github.io/WearableDataAnalysis/)

*The full notebook (with the code) can be viewed in the [`Notebook.ipynb`](Notebook.ipynb) file.*

---

## 🖼️ Dashboard Previews

**📊 Stats View**  
![Stats View](images/Stats%20View.png)

**📈 Time Series View**  
![Timeseries View](images/Timeseries%20View.png)


## 🔍 Insights & Recommendations

### Key Insights

- **Activity Differentiation**: Average speed clearly distinguishes between Running and Cycling, validating its use as a classification metric.
- **Training Intensity**: Most sessions reflect moderate-intensity training, with occasional spikes into high heart rate zones—indicating a well-balanced routine.
- **Cadence Stability**: Cadence remains consistent across sessions, although biomechanical differences between activities are evident.
- **Heart Rate Trends**: 7-day rolling averages of heart rate uncover cyclical periods of peak training and recovery.
- **Data Clusters**: Scatter plots reveal meaningful patterns between cadence, speed, and heart rate that differ across activity types.

### Recommendations

- 💡 Consider increasing session variety if training goals include performance gains—e.g., add more high-intensity intervals if currently dominated by moderate intensity.
- 📅 Use rolling heart rate trends to identify overtraining or undertraining periods and adjust the training load accordingly.
- 🔍 Further exploration could include segmenting workouts by duration or terrain to enhance insights.
