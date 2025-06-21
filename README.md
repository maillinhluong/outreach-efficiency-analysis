# Outreach Efficiency Optimization

This project analyzes historical outreach data to identify key factors driving successful communication, using regression models.

## 📂 Project Structure
- `outreach_model.ipynb` – Jupyter Notebook with full analysis
- `data/outreach_data.csv` – Cleaned outreach dataset
- `visuals/feature_importance.png` – Feature importance from Random Forest

## 🧠 Tools Used
- Python
- Pandas, Scikit-learn, Matplotlib
- MySQL (for data extraction)
- Linear & Random Forest Regression

## 🧪 Key Steps
1. Cleaned and structured outreach data (1,300+ records)
2. Extracted features: communication channel, demographic info, timing
3. Built and tuned regression models to predict success rates
4. Achieved 82% R² score with Random Forest

## 📊 Business Impact
- Identified top-performing outreach methods and timings
- Helped increase outreach success by 20%

## 🚀 Future Improvements
- Deploy the model for live recommendation
- Automate data updates with Airflow or a cron job
