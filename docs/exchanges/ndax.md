---
tags:
- spot exchange connector
---

# `ndax`

## 📁 [Connector folder](https://github.com/hummingbot/hummingbot/tree/master/hummingbot/connector/exchange/ndax)

## ℹ️ Exchange Info

**NDAX**
[Website](https://ndax.io/) | [CoinMarketCap](https://coinmarketcap.com/exchanges/ndax/)

* API docs: <https://ndaxlo.github.io/API/#introduction>
* Transaction fees: <https://ndax.io/fees>
* Minimum order size:
* Creating API keys: <https://help.ndax.io/hc/en-us/articles/8749975550989-Where-can-I-find-credentials-to-access-NDAX-s-trading-API>-

## 👷 Maintenance

* Release added: [0.42.0](/release-notes/0.42.0/) by CoinAlpha
* Maintainer:

## 🔑 Connection

Run `connect ndax` in order to enter your API keys:

```
Enter your NDAX user ID (uid) >>>
Enter the name of the account you want to use >>>
Enter your NDAX API key >>>
Enter your NDAX secret key >>>
```

If connection is successful:

```
You are now connected to ndax.
```

## 🪙 Fees

Hummingbot assumes 0.2% maker fees and 0.2% taker fees ([source](https://github.com/hummingbot/hummingbot/blob/master/hummingbot/connector/exchange/ndax/ndax_utils.py#L14)).

Users can override these assumptions with [Override Fees](/global-configs/override-fees/).
