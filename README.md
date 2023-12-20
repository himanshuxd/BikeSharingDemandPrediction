# Bike Sharing Demand Prediction

Helping BoomBikes recover post-COVID losses by designing a predictive model for shared bike demand. Our goal is to guide management in understanding demand dynamics and making informed business strategies for profit.

## Table of Contents
* [Project Overview](#project-overview)
* [Approach](#approach)
* [Conclusions](#conclusions)
* [Technologies Used](#technologies-used)
* [License](#license)
* [Acknowledgements](#acknowledgements)
* [Contact](#contact)

## Project Overview

BoomBikes, a U.S.-based bike-sharing company, is addressing revenue decline due to COVID-19 by planning a post-lockdown business strategy. Collaborating with a data analytics firm, they aim to maximize profits by analyzing factors influencing shared bike demand in the American market. The project's main goal is to develop a predictive model that identifies key variables impacting demand, helping management tailor their strategy and understand market trends for potential new markets.The project utilizes the `day.csv`` dataset encompassing data on various aspects like date, season, year, month, holiday status, day of the week, working day indicator, weather situation, temperature, apparent temperature, humidity, wind speed, as well as counts for casual and registered bike users.

## Approach

In this analysis, we utilized the 'day.csv' dataset from Boom Bikes to derive insights into the factors influencing bike rentals. The process began with an Exploratory Data Analysis (EDA), scrutinizing both categorical and numerical variables. Categorical variables like weather, season, weekday, and year revealed their impact on rental counts, providing valuable business insights. We conducted thorough data preprocessing, including the elimination of unnecessary variables and handling numerical and categorical data appropriately. The subsequent step involved building a multilinear regression model to predict bike rentals, considering temperature, weather conditions, and seasonal variations. Evaluation metrics, such as R-squared and Adjusted R-squared, were employed to gauge model performance, revealing a strong correlation and effectiveness in capturing the temporal trends. These findings serve as a foundation for Boom Bikes to refine business strategies, emphasizing optimal utilization of weather patterns, seasonal variations, and temperature influences on bike rentals.

## Conclusions

- Clear weather boosts bike rentals.
- Summer and fall witness peak rentals.
- Consistent rental counts on weekdays.
- Reduced rentals on holidays.
- 2019 sees more rentals.
- September marks peak rental month.
- Temperature crucial for rentals.

### Business Insights:
   1. Optimize rentals during clear weather.
   2. Leverage summer and fall for peak rentals.
   3. Tailor strategies for holidays.
   4. Recognize year-wise trends for planning.

## Technologies Used
- Python: The primary programming language for data manipulation, analysis, and visualization.
- NumPy: Used for numerical operations and efficient array handling.
- Pandas: Employed for data manipulation, including data cleaning and preprocessing.
- Matplotlib and Seaborn: Visualization libraries for creating insightful plots and charts.
- Scikit-Learn: Utilized for machine learning tasks, including model building, feature selection, and data scaling.
- Statsmodels: Leveraged for advanced statistical modeling and analysis, particularly for linear regression and VIF calculations.
- Jupyter Notebook: The interactive environment for executing code, documenting the analysis, and presenting results.
- Min-Max Scaler: A feature scaling technique from Scikit-Learn for normalizing numerical data.

## License

This project is licensed under the MIT License by :

[1] Himanshu S, "Bike Sharing Demand Prediction : A Multilinear Regression Approach (2023)" [@himanshuxd](https://github.com/himanshuxd)

[2] Fanaee-T, Hadi, and Gama, Joao, "Event labeling combining ensemble detectors and background knowledge", Progress in Artificial Intelligence (2013): pp. 1-15, Springer Berlin Heidelberg, doi:10.1007/s13748-013-0040-3.

```
@article{
	year={2013},
	issn={2192-6352},
	journal={Progress in Artificial Intelligence},
	doi={10.1007/s13748-013-0040-3},
	title={Event labeling combining ensemble detectors and background knowledge},
	url={http://dx.doi.org/10.1007/s13748-013-0040-3},
	publisher={Springer Berlin Heidelberg},
	keywords={Event labeling; Event detection; Ensemble learning; Background knowledge},
	author={Fanaee-T, Hadi and Gama, Joao},
	pages={1-15}
}
```

## Acknowledgments

- This project is inspired by the business challenges confronted by BoomBikes, a U.S.-based bike-sharing company, aiming to predict and cater to the demand for shared bikes in the American market post-COVID-19.
- This project was done as a part of a project for LJMU and IIIT Bangalore's Masters in Machine Learning & Artificial Intelligence program.

## Contact

- For inquiries or collaborations, feel free to reach out on GitHub: [@himanshuxd](https://github.com/himanshuxd)
