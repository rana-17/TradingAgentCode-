# TradingAgentCode-

# AI Stock Trading Assistant 📈🤖

An AI-powered stock trading assistant built with **LangChain**, **Google Gemini**, and several financial APIs. The assistant analyzes stocks using technical indicators, recent market data, and news before generating a BUY, SELL, or HOLD recommendation. It can also place simulated paper trades using Alpaca.

## Features

* AI-powered stock analysis using Google Gemini
* Current stock price retrieval
* Historical price analysis
* RSI (Relative Strength Index)
* Simple Moving Average (50-day & 200-day)
* Latest company news
* BUY / SELL / HOLD recommendation
* Paper trading using Alpaca API
* Portfolio balance and holdings lookup

## Technologies Used

* Python
* Google Colab
* LangChain
* Google Gemini
* Twelve Data API
* Finnhub API
* Alpaca Paper Trading API

## Project Workflow

1. User asks the AI to analyze a stock.
2. The AI retrieves:

   * Current stock price
   * Recent price history
   * RSI
   * SMA
   * Recent company news
3. The AI combines all signals.
4. A BUY, SELL, or HOLD recommendation is generated.
5. If the recommendation meets the configured rules, a paper trade is placed automatically.

## Installation

Install the required packages:

```bash
pip install langchain
pip install langchain-google-genai
pip install langchain-groq
pip install finnhub-python
```

## API Keys

This project uses Google Colab Secrets to securely store API keys. The following secrets are required:

* Google Gemini API Key
* Twelve Data API Key
* Finnhub API Key
* Alpaca API Key
* Alpaca Secret Key

No API keys are stored directly in the notebook.

## Disclaimer

This project is for educational purposes only. It is not financial advice. All trading actions are performed using Alpaca Paper Trading unless modified by the user.

## Future Improvements

* Add MACD as an integrated LangChain tool.
* Improve error handling for API failures.
* Add chart visualizations.
* Support multiple stock exchanges.
* Add portfolio performance analytics.
* Build a Streamlit web interface.

## Author

Developed as a personal project to explore AI agents, financial APIs, and automated stock analysis using LangChain.
