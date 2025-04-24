# CS3

This repo contains all of the materials needed to replicate my time series project in DS 4002 to detect anomalies in server metrics that are indicative of a DDoS attack.

## 1. Software Dependencies
### Software Used:
- VS Code
- Python

### Python Packages Used:
- pandas
- matplotlib
- numpy
- joblib
- statsmodels
- sklearn
- conda

The project was completed using macOS Sequoia 15.4.
  
## 2. Map of Documentation
```
CS3/
│
├── MATERIALS/
│   ├── DATA
│   │ ├── ec2_cpu_utilization_53ea38.csv
│   │ ├── ec2_network_in_5abac7.csv
│   │ └── elb_request_count_8c0756.csv
│   ├── EXAMPLE_CODE
│   │ ├── 01-test-stationarity.ipynb
│   │ ├── 02-arima.ipynb
│   │ └── 03-autoencoder.ipynb
│   └── EXAMPLE_PLOTS
│     ├── cpu-util-plot-arima.png
│     ├── cpu-util-plot-autoencoder.png
│     ├── net-in-plot-arima.png
│     ├── net-in-plot-autoencoder.png
│     ├── req-count-plot-arima.png
│     └── req-count-plot-autoencoder.png
│   
├── RUBRIC&HOOK/
│   ├── Hook.pdf
│   └── Rubric.pdf
│  
├── LICENSE.md
└── README.md
```
The `MATERIALS` folder is where you can find most of the code you will need to replicate this project. The `EXAMPLE_CODE` folder contains the Jupyter notebook files which are meant to be run in order of their numbering. The `DATA` folder contains the CSV files you need. The `EXAMPLE_PLOTS` folder contains example PNG files of what the plots you output might look like.

The `RUBRIC&HOOK` folder contains supporting materials to give you context on the project as well as further guidance on what a successful execution of the project looks like. 

## 3. References
[1] https://github.com/numenta/NAB/tree/master 

[2] A. Singh and B. B. Gupta, “Distributed Denial-of-Service (DDoS) Attacks and Defence Mechanisms in Various Web-enabled Computing Platforms,” International Journal on Semantic Web and Information Systems, vol. 18, no. 1, Jan. 2022, doi: https://doi.org/10.4018/ijswis.297143.

[3] Zaina Saadeddin, “ARIMA for Time Series Forecasting: A Complete Guide,” Datacamp.com, Sep. 09, 2024. https://www.datacamp.com/tutorial/arima.

[4] E. Zivot, “Augmented-Dickey-Fuller Unit Root Test,” Rdrr.io, May 27, 2024. https://rdrr.io/cran/urca/man/ur.df.html (accessed Mar. 07, 2025).

[5]S. Rajan, “Univariate Time Series Anomaly Detection Using ARIMA Model,” Analytics Vidhya, Aug. 09, 2021. https://www.analyticsvidhya.com/blog/2021/08/univariate-time-series-anomaly-detection-using-arima-model/.
‌
