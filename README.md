# ETHBT Wallet — Network Selector

Adds Ethereum, BNB Chain, and Polygon network selection to the ETHBT wallet UI.

Safety behavior:
- A clear warning is shown before every network switch.
- Switching uses the wallet's standard `wallet_switchEthereumChain` request.
- The site does not request seed phrases or private keys.
- The site does not initiate transactions or token approvals.
- If a wallet does not have the selected network configured, the user is told to add it through official wallet settings.
