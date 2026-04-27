# ShubhEntry Trading Tool

ShubhEntry is a desktop trading application for fast options, futures, and equity order entry across supported Indian broker APIs. The app provides a compact trading panel, broker login helpers, order and position management screens, configurable trading defaults, and optional VPS/router-based request routing.

> This application can place live market orders. Review broker credentials, route settings, order values, and confirmation settings before using it with a real trading account.

## Supported Brokers

- Kotak Neo
- Flattrade


## Main Functionality

- Order entry for calls, puts, futures, and equity symbols, commodity .
- Quick trade buttons for Buy Call, Sell Call, Buy Put, and Sell Put.
- LTP fetch controls that can populate the order price field.
- Blank or zero price handling with optional LTP-based offset pricing.
- Stop loss, auto stop loss, target profit, and trailing stop loss options.
- Order splitting using freeze quantity limits where configured.
- Bulk order placement from `terminal.xlsx`.
- Order book screen for viewing, modifying, and canceling open orders.
- Open positions screen with selected or full square-off workflows.
- Cancel All and Square Off All actions.
- Protected position support so selected positions can be skipped during square-off.
- Symbol, expiry, lot size, strike, and freeze quantity data management.
- Download and conversion of broker scrip master data into local JSON indexes.
- App settings editor for runtime behavior such as shortcuts, confirmations, logging, and order-splitting limits.
- Direct broker API mode and optional VPS/router mode for supported broker routes.



## Requirements


- Windows desktop environment
- Broker API credentials 
- A valid app license file required


## Packaged Build

Use the packaged executable (exe file) when you want to run the bundled desktop app. Runtime credentials and generated data files are still treated as local machine data.


## Common Workflows

1. Select or configure the broker Static IP settings in settings.
2. Initiate login and save broker session credentials.
3. Download scrip master data if symbols, expiries, strikes, or lot sizes need updating.
4. Choose exchange segment, symbol, expiry, strike, product, quantity, and price settings.
5. Place single orders with the quick trade buttons or bulk orders from Excel.
6. Monitor open orders and positions from the Manage menu.
7. Use Cancel All or Square Off All when needed, checking protected positions first.

## Keyboard Shortcuts

Default shortcuts are configurable settings.

- Buy Call: `Alt+UP`
- Buy Put: `Alt+DOWN`
- Sell Call: `Alt+RIGHT`
- Sell Put: `Alt+LEFT`
- Fetch Call LTP: `Ctrl+1`
- Fetch Put LTP: `Ctrl+2`
- Cancel All Orders: `Ctrl+Shift+Q`
- Square Off All: `Ctrl+Shift+X`
- Save/Open Excel: `Ctrl+S`