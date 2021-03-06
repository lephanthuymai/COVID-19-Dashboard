# COVID-19 Data Portal

## About

This repository aims to create a dashboard visualizing COVID-19 statistics using [Plotly Dash](https://github.com/plotly/dash) and [Python](https://github.com/python).

The COVID-19 Data Portal live dashboard can be accessed [here](https://covid-data-portal.herokuapp.com).

## Description

The COVID-19 Data Portal automatically retrieves the latest data from [Johns Hopkins University CSSE COVID-19 Data Repository](https://github.com/CSSEGISandData/COVID-19) and provides the user with an interactive interface to check the number of cases in the world in a straightforward way. The global impact is visualized using a world map highlighting country and regions affected the most by this pandemic. The user can select a time frame to see the trends of new cases and deaths, the default setting is to show the recent 6-month period. Statistics of a country of interest is also displayed with overal numbers as well as recent trends.


## Dashboard

![](docs/images/dash-demo.gif)

### Build the dashboard locally

**Step 1: Clone this repository**

**Step 2:**

Create and activate a conda environment using the env.yaml at the root of this project by running the following command at the root directory of the project. (Alternatively, you can manually install the dependencies listed in the env.yaml file)

``` {.bash}
conda env create --file env.yaml
conda activate covid_dash
```

Go to the root folder of the repo and execute `python src/python/app.py`

## License

-   The COVID-19 Data Portal materials here are licensed under the Creative Commons Attribution 2.5 Canada License (CC BY 2.5 CA). If re-using/re-mixing please provide attribution and link to this web page.

## References

-   COVID-19 Data Repository by the Center for Systems Science and Engineering (CSSE) at Johns Hopkins University, contributors: Johns Hopkins University. <https://github.com/CSSEGISandData/COVID-19>
