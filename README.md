# Earthquake Magnitude Prediction Using Attention Mechanism and LSTM

![Earthquake Prediction Banner](https://img.shields.io/badge/Deep_Learning-LSTM_attention-blue)
A deep learning project that leverages **Attention Mechanism** and **Long Short-Term Memory (LSTM)** networks to predict the **magnitude of recent earthquakes** using real seismic data.

## 🌍 Overview

Predicting earthquake magnitude is a crucial component of disaster preparedness. In this project, we utilize temporal patterns in seismic activity to build a robust LSTM-based model enhanced with an attention mechanism, enabling the model to focus on the most relevant time-steps for more accurate magnitude prediction.


---

## 📁 Dataset

The dataset includes details of recent earthquakes such as:

* **Time**
* **Latitude & Longitude**
* **Depth**
* **Magnitude**
* **Place**
* **Type**
* **ID**
* And other metadata fields

Dataset file used: (https://www.kaggle.com/datasets/shreyasur965/recent-earthquakes)


## 🧠 Model Architecture

The model uses:

* **Preprocessing**: Normalization, feature engineering, handling missing values.
* **LSTM Layers**: To capture temporal dependencies in seismic sequences.
* **Attention Layer**: To assign importance to relevant time steps.
* **Dense Layers**: For final magnitude prediction.

---

## ⚙️ Technologies Used

* Python
* NumPy / Pandas
* Scikit-learn
* PyTorch
* Matplotlib / Seaborn
* Jupyter Notebook


## 📊 Evaluation Metrics

* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)
* R² Score

## 📌 Project Goals

1 Explore seismic data patterns for prediction.
2 Evaluate LSTM vs. LSTM+Attention performance.
3 Contribute towards intelligent disaster prediction systems.

## 🤝 Contributions

Contributions, suggestions, and improvements are welcome. Feel free to fork and raise a pull request.

## 📜 License

This project is open-source and available under the MIT License.

## 🌐 Author

**Ibrahim Lodhi**

