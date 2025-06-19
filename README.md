# Water Quality Prediction - RMS

This project aims to predict multiple water quality parameters using machine learning techniques, specifically `MultiOutputRegressor` wrapped around a `RandomForestRegressor`. It was developed as part of a one-month AICTE Virtual Internship sponsored by Shell in June 2025.

---

## Overview

Ensuring the safety of water resources is vital for environmental and public health. Traditional water testing can be time-consuming and resource-intensive. This project utilizes machine learning to efficiently predict various water quality parameters, enabling timely and informed decision-making.

In this project, we:

- Collected and preprocessed real-world water quality datasets  
- Used supervised machine learning for multi-target regression  
- Built a pipeline using `MultiOutputRegressor` with `RandomForestRegressor`  
- Evaluated the model using appropriate regression metrics  

---

## Technologies Used

- **Python 3.12**  
- **Pandas, NumPy** – Data handling  
- **Scikit-learn** – Machine learning model and evaluation  
- **Matplotlib, Seaborn** – Data visualization  
- **Jupyter Notebook** – Interactive experimentation  

---

## Predicted Water Quality Parameters

The model predicts multiple water quality parameters such as:

- NH₄  
- BOD₅ (BSK₅)  
- Colloids  
- O₂, NO₃, NO₂, SO₄, PO₄  
- Cl  

---

## Model Performance

The model was evaluated using:

- **R² Score**  
- **Mean Squared Error (MSE)**  

Performance was acceptable across all parameters.

---

## Internship Details

- **Internship Type:** AICTE Virtual Internship - Edunet Foundation  
- **Sponsor:** Shell  
- **Duration:** June 2025 (1 month)  
- **Focus Area:** Machine Learning in Environmental Monitoring  
