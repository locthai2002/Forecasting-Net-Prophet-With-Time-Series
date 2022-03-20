# Forecasting-Net-Prophet-With-Time-Series
Use time series data to find out the ability to predict search traffic can translate into the ability to successfully trade the stock. We will leverage Google Colab and Facebook Prophet to predict search traffic. 

The steps for this project are divided into the following sections:

1. Find unusual patterns in hourly Google search traffic 
2. Mine the search traffic data for seasonality 
3. Relate the search traffic to stock price patterns
4. Create a time series model with Prophet
5. Forecast revenue by using time series models


---

## Technologies

Instead of running Facebook Prophet on your local machine, using Google Colab would be ideal to run Facebook Prophet. You can 'Upload' the Jupyter notebook after launching https://colab.research.google.com

Need to install and import the following libraries and dependencies in Google Colab:

```
!pip install pystan
!pip install fbprophet
!pip install hvplot
!pip install holoviews

import pandas as pd
import holoviews as hv
from fbprophet import Prophet
import hvplot.pandas
import datetime as dt
%matplotlib inline

```


## Usage

You will need to clone the repo so that you can run the application:

```
 git clone https://github.com/locthai2002/Forecasting-Net-Prophet-With-Time-Series.git
```
You also need to upload the three .csv files in the Resources folder to run the application:

```
google_hourly_search_trends.csv
mercado_daily_revenue.csv
mercado_stock_price.csv
```

Here are some screenshots from running the application:

## Find unusual patterns in hourly Google search traffic

![Find unusual patterns in hourly Google search traffic](images/1.png)
![Find unusual patterns in hourly Google search traffic](images/2.png)
![Find unusual patterns in hourly Google search traffic](images/3.png)

## Mine the search traffic data for seasonality

![Mine the search traffic data for seasonality](images/4.png)
![Mine the search traffic data for seasonality](images/5.png)
![Mine the search traffic data for seasonality](images/6.png)

## Relate the search traffic to stock price patterns

![Relate the search traffic to stock price patterns](images/7.png)
![Relate the search traffic to stock price patterns](images/8.png)
![Relate the search traffic to stock price patterns](images/9.png)
![Relate the search traffic to stock price patterns](images/10.png)
![Relate the search traffic to stock price patterns](images/11.png)
![Relate the search traffic to stock price patterns](images/12.png)
![Relate the search traffic to stock price patterns](images/13.png)
![Relate the search traffic to stock price patterns](images/14.png)

## Create a time series model with Prophet

![Create a time series model with Prophet](images/15.png)
![Create a time series model with Prophet](images/16.png)
![Create a time series model with Prophet](images/17.png)
![Create a time series model with Prophet](images/18.png)
![Create a time series model with Prophet](images/19.png)
![Create a time series model with Prophet](images/20.png)
![Create a time series model with Prophet](images/21.png)
![Create a time series model with Prophet](images/22.png)

## Forecast revenue by using time series models

![Forecast revenue by using time series models](images/23.png)
![Forecast revenue by using time series models](images/24.png)
![Forecast revenue by using time series models](images/25.png)
![Forecast revenue by using time series models](images/26.png)
![Forecast revenue by using time series models](images/27.png)
![Forecast revenue by using time series models](images/28.png)
![Forecast revenue by using time series models](images/29.png)

---

## Contributors

Loc Thai -- www.linkedin.com/in/loc-thai-69b8a2141
Phone: 415.400.9998

---

## License

MIT
