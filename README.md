# ELO Merchant Category Recommendation

Live Demo: [![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://share.streamlit.io/shekhartz/elo-app)

Elo, one of the largest payment brands in Brazil, has built partnerships with merchants to offer promotions or discounts to cardholders. Elo has built machine learning models to understand the most important aspects and preferences in their customers' lifecycle, from food to shopping. But so far none of them is specifically tailored for an individual or profile. Elo thus has a new objective to build a model to provide personalized recommendations. The model aims to improve customers' lives and help Elo reduce unwanted campaigns, to create the right experience for customers.

This project aims to build a machine learning model to identify and serve the most relevant opportunities to individuals, by exposing indicators in customer loyalty by predicting a loyalty score for each payment card id.

1. Exploratory Data Analysis
2. Preprocessing
3. Feature Correlation
4. Feature Engineering
5. Feature Visualization
6. First Cut Solution
    - 6.1. Splitting Features and Labels
    - 6.2. Train Validation Split
    - 6.3. Base Line Model
    - 6.4. Model Building
          - 6.4.1. Linear regression
          - 6.4.2. SVR Model
          - 6.4.3. Random Forest Regressor
          - 6.4.4. LGBM Regressor
          - 6.4.5. AutoEncoder Model
  - 6.5. Summary
  - 6.6. Final Submission
7. Advance Feature Engineering
8. Improved Solution
  - 8.1. Splitting Features and Labels
  - 8.2. LGB Model with KFold
          - 8.2.1. Hyperparameter Tuning
          - 8.2.2. Model Building
  - 8.3. LGB Model with Repeated KFold
          - 8.3.1. Hyperparameter Tuning
          - 8.3.2. Model Building
  - 8.4. Summary
  - 8.5. Final Submission

