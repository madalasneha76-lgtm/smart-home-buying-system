# 🏡 Smart Home Buying System

## 📌 Project Overview

The **Smart Home Buying System** is a Python-based application that helps users evaluate whether a house is suitable for purchase based on multiple factors.

The system considers financial, location, safety, infrastructure, and property-related conditions and provides a final recommendation:

* ✅ **BUY THIS HOUSE**
* ❌ **DON'T BUY THIS HOUSE**

The application provides an interactive user interface using **Gradio**.

## 🚀 Features

* 💰 Budget affordability check
* 💵 Monthly salary evaluation
* 🏦 Loan eligibility check
* 🚗 Distance to office evaluation
* 🏫 Nearby school availability
* 🏥 Nearby hospital availability
* 🛡️ Crime-rate evaluation
* 💧 Water-supply evaluation
* ⚡ Power-supply evaluation
* 🌐 Internet availability check
* 🚘 Parking availability check
* 🏠 House-age evaluation
* 📄 Legal-document verification
* 🏡 Final home-buying recommendation

## 🛠️ Technologies Used

* Python
* Gradio
* Google Colab / Jupyter Notebook

## ⚙️ How It Works

The application collects information from the user through an interactive Gradio interface.

The entered values are evaluated using predefined decision rules. Each condition produces an individual assessment, followed by a final decision based on the overall criteria.

For example, the system checks whether the house price is within the user's budget and whether the user meets the required salary and loan conditions.

## 📥 Input Parameters

The system accepts the following inputs:

| Input              | Description                             |
| ------------------ | --------------------------------------- |
| City               | Location of the property                |
| Budget             | Maximum affordable house budget         |
| House Price        | Price of the house                      |
| Monthly Salary     | User's monthly salary                   |
| Loan Eligible      | Whether the user is eligible for a loan |
| Distance to Office | Distance from house to workplace        |
| Nearby School      | Availability of a nearby school         |
| Nearby Hospital    | Availability of a nearby hospital       |
| Crime Rate         | Crime level of the area                 |
| Water Supply       | Quality of water availability           |
| Power Supply       | Power-supply condition                  |
| Internet           | Internet connectivity                   |
| Parking            | Parking availability                    |
| House Age          | Age of the property                     |
| Legal Documents    | Whether documents are verified          |

## 🧠 Decision Criteria

The system recommends buying the house when the required conditions are satisfied, including:

* House price is within the budget
* Monthly salary is at least ₹60,000
* Loan eligibility is available
* Office distance is within 20 km
* School and hospital are nearby
* Crime rate is not high
* Water supply is not poor
* Power supply is good
* Internet is available
* Parking is available
* House age is not more than 15 years
* Legal documents are verified

Otherwise, the system recommends **DON'T BUY THIS HOUSE**.

## ▶️ How to Run

### 1. Install Gradio

```bash
pip install gradio
```

### 2. Open the Notebook

Open:

```text
project_on_function.ipynb
```

using Jupyter Notebook or Google Colab.

### 3. Run the Code

Execute the notebook cell containing the Gradio application.

The application will launch an interactive interface where users can enter their house and personal details.

## 📂 Project Structure

```text
smart-home-buying-system/
│
├── project_on_function.ipynb
└── README.md
```

## 🎯 Purpose

This project demonstrates how Python conditional logic and an interactive Gradio interface can be combined to build a simple decision-support application for home buyers.

## 👨‍💻 Author

**Sneha**

---

⭐ If you find this project useful, consider giving the repository a star.
