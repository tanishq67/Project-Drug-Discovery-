# Project-Drug-Discovery-
`This project is inspired from the knowledge I gain through bioinformatics Machine learning & Data science course given by FreeCodeCamp.`

Breast cancer tissues have been shown to express aromatase and produce higher levels of estrogens than non-cancerous cells. This is one of the main reasons that aromatase has generated a high level of interest for treatment of breast cancer. Aromatase inhibitors (AIs) can eliminate the production of estrogen.

In this project I gathered the data, preprocessed, performed exploratary data analysis on them and then build machine learning models and compared them. Then selected the most suitable model which will help in making predicition and obtain data driven insights that will be useful for the discovery of a drug that may inhibit Aromatase.


`I am currently working on to deloy the Selected model as a web-app using streamlit. After that anyone can upload their data for target protein being Aromatase and it will give a score in terms of pIC50 value.`


Basic, overview on how I did it.
- I first collected the Data from the ChEMBL Database and then Pre-Processed it.

- Performed Exploratory Data Analysis (Chemical Space Analysis) via Lipinski descriptors which was calculated from the previous dataset.

- I calculated molecular descriptors that are essentially quantitative description of the compounds in the dataset. And then I prepared this into a dataset for machine learning models.

- I then compared ML algorithms for build regression models of Aromatase inhibitors using lazypredict library. The best one came out to be the Decision TreeRegression Model

- I will use the Decision TreeRegression Model to deploy the web-app which will be made in Streamlit







