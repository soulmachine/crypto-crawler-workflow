# crypto-crawler-workflow

Crawl websocket data from cryptocurrency exchanges using Sogou workflow

## URLs

| Websocket URL                                   | command                                                                                          |
| ----------------------------------------------- | ------------------------------------------------------------------------------------------------ |
| <wss://stream.binance.com:9443/stream>          | {"id":9527,"method":"SUBSCRIBE","params":["btcusdt@depth"]}                                      |
| <wss://fstream.binance.com/stream>              | {"id":9527,"method":"SUBSCRIBE","params":["btcusdt@depth"]}                                      |
| <wss://dstream.binance.com/stream>              | {"id":9527,"method":"SUBSCRIBE","params":["btcusd_perp@depth"]}                                  |
| <wss://api-pub.bitfinex.com/ws/2>               | {"event": "subscribe","channel": "book","symbol": "tBTCUST","prec": "P0","frec": "F0","len": 25} |
| <wss://csocketapi.bitget.com/ws/v1>             | {"op":"subscribe","args":["swap/depth:btcusd"]}                                                  |
| <wss://global-api.bithumb.pro/message/realtime> | {"cmd":"subscribe","args":["ORDERBOOK:BTC-USDT","ORDERBOOK:ETH-USDT"]}                           |
| <wss://www.bitmex.com/realtime>                 | {"op":"subscribe","args":["orderBookL2_25:XBTUSD"]}                                              |
| <wss://ws.bitstamp.net>                         | {"event":"bts:subscribe","data":{"channel":"diff_order_book_btcusd"}}                            |
| <wss://stream.bybit.com/realtime>               | {"op":"subscribe","args":["orderBookL2_25.BTCUSD"]}                                              |
| <wss://ws-feed.pro.coinbase.com>                | {"type":"subscribe","channels": [{"name":"level2","product_ids":["BTC-USD"]}]}                   |
| <wss://www.deribit.com/ws/api/v2/>              | {"method": "public/subscribe", "params": {"channels": ["book.BTC-31DEC21.100ms"]}}               |
| <wss://api.dydx.exchange/v3/ws>                 | {"type": "subscribe", "channel": "v3_orderbook", "id": "BTC-USD"}                                |
| <wss://ftx.com/ws/>                             | {"op":"subscribe","channel":"orderbook","market":"BTC/USD"}                                      |
