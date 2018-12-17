# CS230
1. Before running please install the following libraries:
  - Auquan Toolbox to download the data
    Auquan Toolbox: https://bitbucket.org/auquan/auquantoolbox/wiki/Home
  - Technical Analysis Library to genereate technical indicators
    TA: https://technical-analysis-library-in-python.readthedocs.io/en/latest/
  - PyWavelets Library to perform wavelet de-noising
    PyWavelets: https://pywavelets.readthedocs.io/en/latest/
  - PyKalman Library to run Kalman Filter model
    PyKalman: https://pykalman.github.io/
  - StatsModels Library to run the statistical models
    StatsModels: https://www.statsmodels.org/stable/index.html
  - Facebook Prophet Library to run the facebook prophet prediction model
    FbProphet: https://facebook.github.io/prophet/docs/quick_start.html#python-api
  - Keras Library to implement LSTM model
    Keras: https://keras.io/

2. Run the Jupyter Notebook on AWS Machine, given the large historical data required. 
The data is downloaded on the fly. 

The code was run on AWS EC2 Machine with instance type p2.xlarge in python 2.7 environment for tensorflow (tensorflow_p27).
