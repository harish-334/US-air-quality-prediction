# 🌍 US Air Quality Prediction

## 🚀 Project Overview

This project uses machine learning to predict ground-level ozone (O₃) concentrations across various US cities. Leveraging a large-scale pollution dataset spanning 2000–2022 from Kaggle, we built, tuned, and evaluated Random Forest and XGBoost models to forecast air quality levels accurately.

## 📊 Dataset

- Source: [US Pollution Data (2000–2023)](https://www.kaggle.com/datasets/guslovesmath/us-pollution-data-200-to-2022)
- Size: ~530,000 rows with 200+ features
- Target: `O3 Mean` (Average ozone concentration)
- Features: Various pollutant measurements (CO, NO₂, SO₂, AQI values), timestamps, city/state one-hot encoded data

## 🧠 Models and Performance

| Model                 | R² Score | MAE    | RMSE   | Median Absolute Error |
|-----------------------|----------|--------|--------|----------------------|
| Random Forest (Tuned) | 0.9199   | 0.0030 | 0.0039 | 0.0023               |
| XGBoost (Tuned)       | **0.9263** | **0.0028** | **0.0037** | **0.0021**             |

Both models demonstrate excellent predictive power, with XGBoost slightly outperforming Random Forest. 🎉

## 📈 Visualizations

- Predicted vs Actual ozone levels scatter plots
- Feature importance ranking
- Monthly ozone trends over time
- Correlation heatmaps of pollutants
- Top 10 cities with the highest average ozone concentrations

## 🛠 Tools & Libraries

- Python (Pandas, NumPy, Scikit-learn)
- XGBoost
- Matplotlib, Seaborn
- Google Colab

## 🏃‍♂️ How to Run

1. Clone or download the repository.
2. Open `US_Air_Quality_Prediction_RF_XGBoost_Tuned.ipynb` in Google Colab or Jupyter Notebook.
3. Upload the Kaggle dataset or mount your Google Drive.
4. Run all cells sequentially.

## 🔮 Future Work

- Deploy the model with Streamlit or Flask for interactive use
- Incorporate SHAP for model explainability
- Add external data like weather and traffic to improve accuracy

## 👨‍💻 Author

**Harish Sondagar**  
📧 harishsondagar3@gmail.com  
📧 harishha@buffalo.edu  
🔗 [GitHub Profile](https://github.com/harish-334)

---

⭐️ If you find this project useful, please give it a star!

---

Feel free to ask if you want me to generate the `.ipynb` too or help with GitHub setup! 🚀
