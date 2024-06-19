# Linear Regression: Testing Relationships and Predicting Outcomes

This repository contains a project that utilizes a dataset on beer consumption in a university region of São Paulo, Brazil. The objective of this project is to estimate a Machine Learning model using Linear Regression to demonstrate the impact of various variables on beer consumption. The dataset includes Date, Average Temperature (°C), Minimum Temperature (°C), Maximum Temperature (°C), Precipitation (mm), Weekend (1 = Yes; 0 = No), and Beer Consumption (liters). The final model is a function dependent on Maximum Temperature, Precipitation, and Weekend to predict beer consumption.

## Project Overview
The project aims to explore and model the beer consumption data using Linear Regression, providing insights into how different factors influence consumption.

## Course Details
This project was completed as part of a Data Science course on Alura. For more information about the course, visit [Alura](https://cursos.alura.com.br/formacao-data-science-v377549).

## Objectives Achieved
- Use visualizations to understand data distribution
- Differentiate between dependent and explanatory variables in the data
- Learn to separate training and testing data
- Model with linear regressions
- Understand errors through residuals and metrics
- Compare and save the best models

## Technologies Used
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Seaborn
- Scikit-learn

## Project Structure
The directory structure of the project is as follows:
```
regressão-linear-testando-relações-e-prevendo-resultados/
├───Bonus
│       Simulador Interativo.ipynb
├───Dados
│   │   Consumo_cerveja.csv
│   └───img
│           Box-Plot.png
│           reg_01.jpg
│           reg_02.jpg
│           var_u.jpg
├───Exercicio
│   │   .DS_Store
│   │   modelo_preco_apartamentos
│   │   modelo_preáo
│   │   Regressao Linear - Exercicio.ipynb
│   └───dados
│           HousePrices_HalfMil.csv
└───Projeto
        modelo_consumo_cerveja
        Regressão Linear.ipynb
```

## How to Run the Project
1. Clone the repository:
   ```sh
   git clone https://github.com/goosekiing/regressão-linear-testando-relações-e-prevendo-resultados.git
   ```
2. Navigate to the project directory:
   ```sh
   cd regressão-linear-testando-relações-e-prevendo-resultados
   ```
3. Open the Jupyter Notebook:
   ```sh
   jupyter notebook Projeto/Regressão Linear.ipynb
   ```

## Learn More
To learn more about Linear Regression and data science, visit the [course page on Alura](https://cursos.alura.com.br/formacao-data-science-v377549).

Feel free to explore, modify, and use this project as a foundation for your own linear regression models!
