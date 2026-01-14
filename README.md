# Google-Play-Store-Case-Study
## Problem Statement

The team at **Google Play Store** aims to develop a feature that enhances the visibility of the most promising applications on the platform. To achieve this, a preliminary analysis is required to understand the key factors that define a **well-performing app**.

This analysis seeks to explore relationships between various app attributes and performance metrics by addressing the following questions:

- Does a higher **app size** or **price** necessarily indicate better app performance?
- Does a higher number of **installs** provide a clear indication of better **user ratings** compared to other apps?

Understanding these relationships will help identify the attributes that contribute most significantly to app success and support data-driven feature development.
## Data Cleaning

- Removed duplicates, handled missing values, and filtered invalid ratings or zero installs.
- Converted **Reviews, Installs, Price, and Size** into numeric formats.
- Standardized categorical fields and created derived features for analysis.

## Technologies Used

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**


  ## Key Insights

- **App Size & Price**
  - App size and price have minimal impact on ratings; user experience matters more.

- **Installs & Ratings**
  - Higher installs improve visibility but do not always guarantee higher ratings.

- **Reviews Impact**
  - Apps with more reviews tend to have more stable and trustworthy ratings.

- **Content Rating**
  - Apps rated **“Everyone”** achieve broader reach and higher installs.

- **Free vs Paid**
  - Free apps dominate installs; ads and in-app purchases outperform upfront pricing.
- **Seasonal insights**
This trend aligns with **USA school and college holidays**, during which teens have more free time, resulting in higher app engagement, increased installs, and more frequent ratings; once the holiday period ends and usage declines, overall app ratings stabilize at normal levels.
## Business Recommendations

- Prioritize app visibility based on **user engagement metrics** such as installs and number of reviews rather than app size or price.
- Promote **high-rated apps with moderate-to-high install counts**, as they indicate both quality and user trust.
- Encourage developers to focus on **lightweight app design**, since smaller apps perform just as well and improve user adoption.
- Promote apps with **“Everyone” content ratings** to maximize reach and audience size.
- Introduce recommendation algorithms that balance **install count, ratings, and review volume** instead of relying on a single performance metric.

