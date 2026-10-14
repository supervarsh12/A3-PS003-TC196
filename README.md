# Federated Traffic-Flow Prediction with Communication-Cost Evaluation

## 📌 Project Overview

Traffic-flow prediction is an important part of Intelligent Transportation Systems (ITS). It helps predict future traffic conditions, reduce road congestion, improve route planning, and optimize traffic signals.

This project proposes a **Federated Learning (FL)** approach to traffic-flow prediction that enables multiple road intersections to collaboratively train a machine-learning model without sharing their raw traffic data. The system uses **Federated Averaging (FedAvg)** to aggregate local model updates and generate a global prediction model.

The project focuses on evaluating prediction accuracy and communication overhead to identify an effective balance between model performance, data privacy, and communication efficiency.

## 🎥 Project Video

Watch the project demonstration on YouTube:

👉 https://youtu.be/raxStNY_IlE

## 🎯 Objectives

- Predict future traffic flow using historical traffic data.
- Apply Federated Learning to train models across multiple traffic intersections.
- Keep raw traffic data locally stored instead of transferring it to a central server.
- Use FedAvg to combine local model updates into a global model.
- Evaluate prediction accuracy using MAE and RMSE.
- Measure communication cost using transmitted data, communication rounds, and training time.
- Compare federated learning with centralized and local learning approaches.

## ⚙️ Proposed Methodology

1. **Data Collection:** Collect historical traffic data from road intersections or traffic sensors.
2. **Client Distribution:** Divide the dataset among multiple clients representing different intersections.
3. **Local Training:** Train a machine-learning model locally at each client.
4. **Model Aggregation:** Send model updates to the central server and aggregate them using FedAvg.
5. **Global Model Update:** Distribute the aggregated model back to participating clients.
6. **Traffic Prediction:** Use the trained model to predict future traffic flow.
7. **Performance Evaluation:** Measure prediction accuracy and communication overhead.
8. **Comparison:** Compare results across centralized, local, and federated learning approaches.
## 🛠️ Technologies

The implementation can use the following technologies:

- **Python** — Primary programming language
- **Pandas and NumPy** — Data processing and numerical operations
- **Scikit-learn** — Machine-learning models and evaluation metrics
- **TensorFlow or PyTorch** — Model development and training
- **Flower** — Federated Learning framework
- **Matplotlib** — Performance visualization

*The final technology list should be updated to reflect the libraries actually used in the implementation.*

## 🚀 Expected Outcomes

- Collaborative traffic-flow prediction across multiple clients.
- Reduced need to share raw traffic data.
- Quantitative evaluation of prediction accuracy.
- Measurement of communication overhead during federated training.
- Comparison of accuracy and communication efficiency across learning approaches.

Actual improvements will be determined through experimental evaluation.

## 🔬 Research Gap

Existing traffic-prediction approaches face challenges related to data privacy, non-IID traffic distributions, model convergence, and communication overhead. This project evaluates these challenges together by analyzing prediction accuracy and communication cost within a federated learning framework.

## 👨‍💻 Applications

- Intelligent Transportation Systems
- Smart-city traffic management
- Traffic congestion monitoring
- Route planning and optimization
- Adaptive traffic signal management

## 📺 Project Demonstration

**YouTube:** https://youtu.be/raxStNY_IlE

## 📄 License

This project can be distributed under the MIT License after adding an appropriate `LICENSE` file to the repository.



