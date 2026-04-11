---
name: exchange-converter-ui
description: Convert between fiat currencies AND cryptocurrencies using live exchange rates with offline cache support. Trigger when user says "convert currency", "how much is X in Y", "exchange rate", "convert BTC to USD", "how much is ETH in EUR", "help", or asks to convert an amount from one currency/crypto to another.
metadata:
  homepage: https://github.com/victoralv/exchange-converter-ui
---

# Exchange Converter

Supports **fiat currencies** (USD, EUR, GBP, JPY, MXN...) and **cryptocurrencies** (BTC, ETH, SOL, BNB, XRP, DOGE, ADA, DOT, MATIC, LTC, and hundreds more).

## Examples

- "Convert 100 USD to EUR"
- "How much is 50 euros in Japanese yen?"
- "Exchange rate from GBP to USD"
- "500 MXN to dollars"
- "Convert 0.5 BTC to USD"
- "How much is 1 ETH in EUR?"
- "1000 DOGE to GBP"


## Instructions

Extract amount (default 1), FROM code, TO code from the user message (uppercase ISO 4217 or crypto ticker). 
Call `run_js`: `{"action":"convert","amount":<n>,"from":"<FROM>","to":"<TO>"}`
