My process began by defining clear objectives: to identify the most and least trafficked routes, analyze trends and geographical patterns, and build short-term forecasts of passenger traffic. After installing and importing the necessary libraries, I loaded the dataset and performed an initial inspection to check for duplicates, missing values, and data types. I then carried out data cleaning and feature engineering by standardizing text fields, reorganizing the DataFrame, and creating a new route column to simplify analysis. With the cleaned dataset, I conducted exploratory analysis to uncover traffic patterns, seasonal trends, and geographical insights, using visualizations to highlight the highest and lowest performing routes over time. Building on this, I applied Prophet to model passenger traffic on selected routes, formatting the data into Prophet’s required structure and leveraging yearly seasonality to capture demand cycles. I validated the models with cross-validation and performance metrics such as MAE, RMSE, and MAPE, and experimented with tuning parameters like `changepoint_prior_scale` to refine results. Alongside modeling, I focused on improving the interpretability of visualizations by adjusting axes and considering static route maps for clearer storytelling. Overall, my process moved from data inspection and cleaning to exploration, forecasting, evaluation, and refinement—demonstrating a full data science workflow from raw data to actionable insights.


<p align="center">
  <strong><a href="https://drive.google.com/file/d/1jWBBT2BAr68uIwOmSPTRaMDJSoqHwCCd/view?usp=sharing">Cleaned Data Set</a></strong> |
  <strong><a href = "https://docs.google.com/document/d/1UjLSU7bZSHWQEx6QbIdl2f1SNRqDdI6D1Of_C4wz7Oc/edit?usp=sharing">Report</a></strong>
</p>



