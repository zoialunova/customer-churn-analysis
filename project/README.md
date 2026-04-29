## Customer Churn Analysis
Fit.ly Tech Comany has seen an increase in customer churn over the past two quarters. At the same time, the cost of acquiring new users is rising, so retaining existing customers has become very important.
My aim is to clearly identify the main reasons for churn and suggest practical actions that can help the company retain more customers and support future growth.

### Description
Customer churn analysis using Python and SQL. The project includes data cleaning, exploratory data analysis, and actionable insights to identify key drivers of churn. Initially developed for a DataCamp certification and further enhanced with additional analysis.

### Dataset
The dataset consists of three main tables:

- accounts — customer information, subscription plans, and churn status
- support — customer support interactions and ticket details
- activity — user activity and engagement events

### Steps Performed
- Data cleaning and preprocessing
- Handling missing values and inconsistent formats
- Exploratory Data Analysis (EDA)
- Identifying churn patterns and correlations

### Key Insights
- Overall churn rate is 27.2%, significantly above the expected 10–20% range
- Churn among paying users is nearly 2x higher than in the free segment
- Most churned users contacted support at least once, indicating high user friction
- Average support response time is a key driver: ~18 hours for churned users vs ~6 hours for retained users
- Churned users show lower early engagement and often do not reach core actions (e.g., workouts)

**Conclusion:** churn is primarily driven by poor early user experience and slow support response

### Recommendations
- Improve onboarding and first user experience (especially initial actions)
- Reduce support response time
- Focus on inactive users who have not taken any actions
- Enhance data tracking (first action time, first support contact, issue type)
- Success Metrics
- Reduce average support resolution time from ~18h to ~6h
- Decrease the share of inactive users
