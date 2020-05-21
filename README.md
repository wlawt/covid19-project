## Kaggle COVID-19 Challenge:

Data Science for COVID-19 [(DS4C)](https://www.kaggle.com/kimjihoo/coronavirusdataset)

### What it does
This repo explores the impact/spread of COVID-19 in Canada. Intentions were to provide some visualizations of time-series data, 
forecast the total number of cases/recoveries/deaths in Canada, and to predict the number of days a patient will spend recovering 
in the hospital (using the DS4C dataset).

### Acknowledgements
- [DS4C Kaggle Korea Dataset](https://www.kaggle.com/kimjihoo/coronavirusdataset)
- [John Hopkins University Dataset](https://github.com/CSSEGISandData/COVID-19)
- [CalTech CS156b Dataset Collection](https://github.com/quantummind/caltech_covid_19_modeling)
- [therealcyberlord's Kaggle Notebook](https://www.kaggle.com/therealcyberlord/coronavirus-covid-19-visualization-prediction)

### Directory Structure
```
/datasets
    /caltech_covid_19_modeling
    /korea_dataset
    /COVID19
/img
/main
    COVID-19 Notebook.ipynb
.gitignore
README.md
```

### Running the repo
#### Downloading the source code & datasets
```
git clone https://github.com/wlawt/covid19-project.git
cd covid19-project/main
```

#### Running the model 
We suggest to consider additional factors for the linear regression models. 
```
COVID-19 Notebook.ipynb
```

### Forecasting graphs
#### Total cases/recoveries/deaths - 2 week forecast (without poly preprocessing)
![case_recovery_death](https://github.com/wlawt/covid19-project/blob/master/img/nopoly.png)

#### Total cases/recoveries/deaths - 2 week forecast (with poly preprocessing)
![case_recovery_death2](https://github.com/wlawt/covid19-project/blob/master/img/poly.png)

#### Newly Infected vs. Newly Recovered in Canada & Recovery rate vs Death rate
![comparison](https://github.com/wlawt/covid19-project/blob/master/img/comparison.png)
