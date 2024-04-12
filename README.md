# Trading Bot for Oanda

This is a trading bot that interacts with the Oanda API to execute trades automatically. It is written in Python and designed to be customizable and extensible.

## Prerequisites

Before running the trading bot, make sure you have the following:

- Python 3.x installed
- Oanda API access token
- Oanda account ID

## Installation

1. Clone this repository:

    ```shell
    git clone https://github.com/your-username/trading-bot.git
    ```

2. Navigate to the project directory:

    ```shell
    cd trading-bot
    ```

3. **Set up a virtual environment (optional but recommended):**

    If you prefer to work within a virtual environment (which is highly recommended), follow these steps:

    - Install `virtualenv` (if not already installed):

        ```shell
        pip install virtualenv
        ```

    - Create a new virtual environment inside the project directory:

        ```shell
        virtualenv venv
        ```

    - Activate the virtual environment:

        **For Windows:**

        ```shell
        venv\Scripts\activate
        ```

        **For macOS and Linux:**

        ```shell
        source venv/bin/activate
        ```

4. Install the required dependencies:

    ```shell
    pip install -r requirements.txt
    ```

5. Create a `config.py` file in the root directory of the project and add your Oanda API access token and account ID:

    ```python
    # config.py

    ACCESS_TOKEN = 'your-access-token'
    ACCOUNT_ID = 'your-account-id'
    ```

## Usage

To run the trading bot, execute the following command:

```shell
python trading_bot.py
