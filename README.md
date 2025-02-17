# IMC Trading Algorithm

This project implements two trading strategies: a Mean Reversion strategy and a Linear Regression strategy. These strategies are designed for the IMC Trading Challenge 2024 and are implemented in Python. We were able to complete 2 out of the 5 rounds in the challenge, before getting swarmed by university work.

## Table of Contents
- [Description](#description)
- [Achievements](#achievements)
- [Strategies](#strategies)
  - [Mean Reversion Strategy](#mean-reversion-strategy)
  - [Linear Regression Strategy](#linear-regression-strategy)
- [Installation](#installation)
- [Usage](#usage)
- [Configuration](#configuration)
- [Contributing](#contributing)
- [License](#license)
- [Contact Information](#contact-information)

## Description

The IMC Trading Algorithm project showcases two well-known trading strategies: Mean Reversion and Linear Regression. These strategies are implemented to demonstrate coding skills in the context of the IMC Trading Challenge 2024.

## Achievements

In the IMC Trading Challenge 2024, this project achieved notable rankings (at the conclusion of round 2):
- **70th in Australia**
- **800th in the World**

## Strategies

### Mean Reversion Strategy

The Mean Reversion strategy operates based on the assumption that the price of a security will tend to move to the average price over time. The implementation includes:
- Position limits for each product.
- Price history tracking.
- Calculation of short-term and long-term simple moving averages (SMA).
- Buy/Sell logic based on SMA comparisons.

### Linear Regression Strategy

The Linear Regression strategy predicts the future price of a security based on past prices using linear regression. The implementation includes:
- Calculation of linear regression parameters (slope and intercept).
- Prediction of future prices based on the linear regression model.

## Installation

This project is specific to the IMC Trading Challenge 2024 and is not intended for general use. The code is not functional outside of the IMC Trading simulator environment.

## Usage

As mentioned, this project is specific to the IMC Trading Challenge 2024 and is not usable outside the IMC Trading simulator.

## Configuration

This project comes pre-configured for the IMC Trading Challenge 2024. However, there are several parameters and settings you might want to adjust to tailor the algorithm to different conditions or preferences:

1. **Simple Moving Average (SMA) Windows**
    - Customize the short-term and long-term SMA windows to suit different trading strategies.
    ```python
    SHORT_WINDOW = 10  # Short-term SMA window
    LONG_WINDOW = 25   # Long-term SMA window
    ```

2. **Linear Regression Scope**
    - Modify the scope (number of data points) used for the linear regression calculation.
    ```python
    # Example usage in the calculate_linear_regression function
    scope = 25  # Number of data points to consider
    ```

3. **Product-Specific Settings**
    - If needed, adjust settings specific to each product being traded. For example, you might want different SMA windows for different products.
    ```python
    # Example for setting different SMA windows for different products
    PRODUCT_SMA_WINDOWS = {
        'AMETHYSTS': {'SHORT_WINDOW': 10, 'LONG_WINDOW': 25},
        'STARFRUIT': {'SHORT_WINDOW': 15, 'LONG_WINDOW': 30}
    }
    ```

## Contributing

There are no specific guidelines for contributing to this project.

## License

The license for this project is currently unspecified.

## Contact Information

**Contributors:**

Zackariya Taylor - zackariya.taylor@gmail.com

Owen Harding

Project Link: https://github.com/mngv7/IMC-algorithmic-trader
