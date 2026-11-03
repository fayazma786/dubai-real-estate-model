# Dubai Real Estate Valuation Model 🏙️

## Business Problem
The UAE real estate market is highly dynamic. Accurately pricing properties based on location, size, and type is critical for investors, developers, and brokerages. This project processes official Dubai Land Department (DLD) transaction records to predict market valuations instantly, providing data-driven decision support for stakeholders.

## Technical Stack
- **Data Engineering:** SQL (SQLite), Pandas
- **Machine Learning:** Scikit-Learn (Constrained Random Forest)
- **Deployment:** Streamlit

## Model Performance
- **Algorithm:** Constrained Random Forest (Optimized to prevent overfitting)
- **R-Squared:** 0.769 (Explains 76.9% of market variance)
- **Generalization:** Successfully constrained the training-to-testing gap to 0.07, ensuring reliable predictions on unseen transaction data.

## How to Run Locally
1. Clone this repository.
2. Install dependencies: `pip install -r requirements.txt`
3. Run the dashboard: `streamlit run app.py`