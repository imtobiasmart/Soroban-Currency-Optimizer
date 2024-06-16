# Soroban-Currency-Optimizer
The Soroban Currency Converter is a decentralized service designed to facilitate seamless currency conversions using blockchain technology. It leverages the Soroban platform to provide a secure, transparent, and efficient way to convert currencies, supporting various DeFi applications and financial services.

This repository contains a simple Soroban smart contract for converting currencies using a simulated exchange rate. The contract is designed to demonstrate basic functionality and can be extended to fetch real-time exchange rates from an oracle like Reflector.Network.

## Overview

The contract provides two main functions:
1. `get_exchange_rate`: Simulates fetching the current exchange rate from an oracle.
2. `convert_currency`: Converts an amount from one currency to another using the fetched exchange rate.

## Contract Details

### `get_exchange_rate`

- **Description**: This function simulates fetching the exchange rate from an oracle. In this example, it returns a placeholder exchange rate.
- **Parameters**:
  - `env`: The environment in which the contract is running.
  - `from_currency`: The symbol of the currency to convert from.
  - `to_currency`: The symbol of the currency to convert to.
- **Returns**: A placeholder exchange rate represented as an `i128` value.

### `convert_currency`

- **Description**: This function converts an amount from one currency to another using the exchange rate fetched from `get_exchange_rate`.
- **Parameters**:
  - `env`: The environment in which the contract is running.
  - `amount`: The amount of currency to convert.
  - `from_currency`: The symbol of the currency to convert from.
  - `to_currency`: The symbol of the currency to convert to.
- **Returns**: The converted amount as an `i128` value.

## Usage

To use this contract, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/soroban-currency-converter.git
   cd soroban-currency-converter
