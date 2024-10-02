# Air Quality Analysis and Forecasting

## 🌟 Objective
The goal of this project is to investigate the **seasonal patterns** and **meteorological factors** contributing to air pollution in Delhi. In addition, we explore the use of several **machine learning models** to predict future trends in the Air Quality Index (AQI). The findings offer valuable insights into air quality trends and the ability to forecast potential fluctuations.

## 📊 Dataset
The dataset includes comprehensive air quality measurements and AQI values recorded at **hourly and daily intervals** from various monitoring stations across multiple cities in India. This data is publicly available from the [Central Pollution Control Board (CPCB)](https://cpcb.nic.in/), the official pollution control body of the Government of India.

🔗 **Dataset**: You can access the compiled dataset [here](https://www.kaggle.com/rohanrao/air-quality-data-in-india).

After downloading, extract the dataset into the `air-quality-dataset` folder for analysis.

## 🧠 Machine Learning Models
We applied several advanced models to forecast AQI based on past trends, leveraging machine learning techniques:

- **[FB Prophet Model](notebooks/fb-prophet-air-quality-forecasting.ipynb)**: Time series forecasting using Facebook’s Prophet model.
- **[SARIMA Model](notebooks/sarima-model-AQI-forecasting.ipynb)**: Seasonal AutoRegressive Integrated Moving Average (SARIMA) model to capture the seasonal patterns in AQI data.
- **[RNN-LSTM Model](notebooks/rnn-lstm-model-AQI-forecasting.ipynb)**: Recurrent Neural Network (RNN) with Long Short-Term Memory (LSTM) layers for deep learning-based forecasting of AQI.

Each model explores different aspects of AQI trends and produces forecasts that can help policymakers and environmentalists act proactively.

## 📈 Data Visualization & Analysis
The project includes in-depth data visualization to uncover hidden patterns and trends in air pollution levels:

- **[Air Quality Analysis](notebooks/air-quality-analysis.ipynb)**: Visualizes data across various dimensions such as city-wise pollution levels, temporal trends, and correlation with meteorological factors.

## 🔧 How to Run the Project
1. Download and extract the dataset from [here](https://www.kaggle.com/rohanrao/air-quality-data-in-india) into the `air-quality-dataset` folder.
2. Open the Jupyter notebooks mentioned above for detailed analysis and forecasting models.
3. Install the required dependencies from `requirements.txt`.

```bash
pip install -r requirements.txt
```

## 💡 Insights
- **Seasonality**: Air pollution in Delhi peaks during winter months due to weather conditions like lower temperatures and stagnant winds.
- **Meteorological Factors**: Elements such as humidity, wind speed, and temperature significantly impact AQI levels.
- **Forecasting**: Machine learning models like **SARIMA** and **LSTM** show strong potential in predicting air quality, enabling early intervention strategies.

## 📚 Notebooks
- `air-quality-analysis.ipynb`: Visualize and analyze air quality trends.
- `fb-prophet-air-quality-forecasting.ipynb`: Forecast AQI using the FB Prophet model.
- `sarima-model-AQI-forecasting.ipynb`: Forecast AQI using the SARIMA model.
- `rnn-lstm-model-AQI-forecasting.ipynb`: Deep learning approach with RNN-LSTM for AQI prediction.

## 👥 Author
Developed by [Gourav Pandey](https://www.linkedin.com/in/gouravpandey09/) 
