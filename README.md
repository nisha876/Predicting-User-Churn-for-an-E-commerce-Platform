# Predicting-User-Churn-for-an-E-commerce-Platform

**Churn Prediction Model Summary**

The churn prediction model for the e-commerce platform identifies users likely to stop engaging or purchasing, using events(activity data such as views, charts, and purchases). Key components include-

**Data cleaning:**
involved handling missing values, removing duplicates, converting event_time to datetime, standardizing data types, and filtering invalid or inconsistent entries.

**Feature Engineering:**
Derived meaningful features such as RFM metrics (Recency, Frequency, Monetary), session behaviors (session count, view-to-cart ratio, cart-to-purchase ratio), and user preferences (top categories or brands viewed/purchased).

**Model Training:**
Built and evaluated Random Forest and XGBoost models for churn prediction. Both models achieved high-performance metrics (e.g., AUC = 1.0), showcasing their strong predictive power.

**Insights:**
Key features influencing churn include recency of visits, frequency of purchases, and behavioral patterns (e.g., users with high views but low purchases are more likely to churn).
Model interpretability tools like feature importance plots and SHAP values explain how specific features drive predictions.

**Recommendations:**
Personalized offers: Use discounts, loyalty rewards, or re-engagement emails to target users with low engagement or high churn risk.
Behavior-based strategies: Address users with high view-to-cart or cart-to-purchase ratios by offering tailored promotions or reminders.

