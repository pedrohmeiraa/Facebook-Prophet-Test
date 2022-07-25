<img src="https://storage.googleapis.com/kaggle-datasets-images/122/260/46fddab9a36e911c711f85624ac0081f/dataset-cover.jpeg">

# Facebook Prophet Test
## - Pedro Henrique Meira de Andrade¶
## - Github: pedrohmeiraa

**Prophet** is a forecasting technique developed by the Facebook Core Data Science team. According to their website, it's fast and can be automated to make predictions. Prophet is well suited to time series with seasonal characteristics. Also, according to , the technique is robust to outliers and changes in the trend.

The dataset for testing the technique was downloaded from [Kaggle](https://www.kaggle.com/datasets/uciml/electric-power-consumption-data-set). The dataset represents measurements of **electric power consumption in one household with a one-minute sampling** rate over a period of almost 4 years. Different electrical quantities and some sub-metering values are available.

The complete archive contains 2075259 measurements gathered between December 2006 and November 2010 (47 months). For the Prophet test, I used only 1 week (*10080 samples*).

The variable used for forecasting was the **global active power**, given in kW.
