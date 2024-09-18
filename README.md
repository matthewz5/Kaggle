
# Brazil Real Estate Price Prediction

This project uses the Brazil Real Estate dataset to build machine learning models that predict property prices (`price_brl`) based on various features such as property type, location, and area. The goal is to provide insights into the factors influencing real estate prices in Brazil and to develop predictive models for pricing.

## Dataset

The dataset is sourced from [Kaggle - Brazil Real Estate](https://www.kaggle.com/datasets/ashishkumarjayswal/brasil-real-estate) and includes the following key features:
- **Property Type**: e.g., apartment, house.
- **Location**: Includes state, region, latitude, and longitude.
- **Area**: Size of the property in square meters (`area_m2`).
- **Price (BRL)**: Target variable representing the property price in Brazilian Reais.

## Project Structure

- **Data Preprocessing**: Handling missing values, encoding categorical variables, and feature scaling.
- **Exploratory Data Analysis**: Visualizations to understand data distribution and relationships between features.
- **Modeling**: Implementing Linear Regression and Random Forest models to predict property prices.
- **Evaluation**: Comparing model performances using metrics like Mean Squared Error (MSE) and R² score.

## Results

- **Linear Regression**: Basic model with limited predictive power (low R² score).
- **Random Forest**: Improved performance with a higher R² score, indicating better handling of complex relationships.

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/matthewz5/Kaggle-Brasil-real-estate-Data.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter notebook or Python scripts to explore data and train models.

## Future Improvements

- **Feature Engineering**: Adding more relevant features to improve model accuracy.
- **Hyperparameter Tuning**: Optimizing Random Forest parameters for better performance.
- **Advanced Models**: Experimenting with other algorithms like Gradient Boosting or Neural Networks.

## Contributing

Feel free to open issues or submit pull requests to enhance the project!

## License

This project is licensed under the MIT License.
