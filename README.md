# Real Estate Price Predictor 🏠

This project predicts residential real estate prices in the USA using public datasets from Redfin and the U.S. Census Bureau. The app is built using Streamlit and trained with machine learning models such as Random Forest and XGBoost.

## 💡 Features
- Predicts property price based on ZIP code, size, bedrooms, bathrooms
- Uses real housing trend data from Redfin
- Enriches model with demographic data from the U.S. Census (ACS)
- Visualizes predictions and historical trends

## 📁 Project Structure
```
real-estate-price-predictor/
├── app/
│   └── app.py                 # Streamlit web app
├── data/
│   ├── raw/                   # Original datasets
│   └── processed/             # Cleaned/merged data
├── models/
│   └── price_model.pkl        # Trained ML model
├── notebooks/
│   └── eda_modeling.ipynb     # EDA and modeling steps
├── scripts/
│   └── fetch_census_data.py   # Script to get Census data
├── requirements.txt
├── .gitignore
└── README.md
```

## 🚀 How to Run Locally
```bash
git clone https://github.com/yourusername/real-estate-price-predictor.git
cd real-estate-price-predictor
pip install -r requirements.txt
streamlit run app/app.py
