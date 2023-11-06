# Customer Reviews Analysis and Predictive Booking Modeling
# Customer Reviews Analysis and Predictive Booking Modeling

This repository contains code for analyzing customer reviews sentiment and performing predictive modeling for customer bookings.

## Table of Contents

- [Description](#description)
- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Description

This project focuses on two main tasks:

1. **Customer Reviews Sentiment Analysis:** It analyzes customer reviews to determine their sentiment (positive, negative, or neutral). The sentiment analysis is based on the NLTK library and includes visualizations like word clouds and bar charts.

2. **Predictive Modeling of Customer Bookings:** It uses a Random Forest Classifier to predict whether a customer's booking will be completed or not. The model is trained on booking-related data, and its performance is evaluated.
![image](https://github.com/unspecifiedcoder/-The-Role-of-Data-Science-in-British-Airways-Success/assets/130489622/51af2e6b-3002-4b91-9722-5c02b62eee8d)

## Features

Key features of this project include:

- Sentiment analysis of customer reviews
- Predictive modeling of customer bookings
- Data visualization with word clouds and bar charts

## Getting Started

To get started with this project, follow the instructions below.

### Prerequisites

Before you begin, ensure you have the following installed:

- Python (version X.X.X)
- Required Python libraries listed in `requirements.txt`

## __Setup⚙__

1. Clone the repository:

   ```bash
   $ git clone https://github.com/yourusername/yourproject.git
   $ cd yourproject
## Model Evaluation

After training and evaluating the predictive model, the following insights were obtained:

- The most important variable in the model was `purchase_lead`, which represents the time between purchase and departure.
- Information about the flight, such as `flight_hour` and `flight_duration`, was also found to be significant in predicting booking completion.
- Surprisingly, the `booking_origin` of the customer was not an important predictor.
- The accuracy of the model was approximately 0.7 (Precision), which suggests that the model performs well in identifying completed bookings. However, the low recall of approximately 0.003 indicates that the model has a challenge in correctly identifying incomplete bookings. This implies that the model requires further improvement.

To enhance the model's performance, consider adding more customer-centric features to capture additional factors influencing booking completion.

