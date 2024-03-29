![](https://coincost.net/uploads/temp/4c6fb6e0682ec5477550c7914638169c.png)
# GCR Faucet v1.0.0

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)


Claim tokens for development and testing purposes on the GCR network.
***
### Simply enter the recipient address, the desired amount of the selected token and claim.

***
## Requirements

**Node.js** is required to run GCR Faucet as a web application, version **12 LTS** is recommended.

## Building instructions

1. Clone the project.


```
git clone https://github.com/superhow/gcr-faucet.git
```

2. Navigate to the project folder.

```
cd gcr-faucet
```
	
3. Install the dependencies. This may take a while.

```
npm install 
```

4. Build the packages.

```
npm build run
```
    
5. Start the app.

```
npm start
```
    
6. Access the Faucet on your web browser. The default may be http://127.0.0.1:4000. If you get a "connection refused" error, check your .env file.
***
## Feature status
### Features currently working
* Real-time display of status notifications ✔️
* Claiming selected token (from 1 up to maximum  amount) to a specified recipient ✔️
* Faucet Address link to GCR Explorer ✔️

### Features currently not working
* Nothing to report so far.
***
## Main changes
* Altered UI elements (footer, colors, text, images) for a more appealing, consistent and coherent appearance.
* Changed terminology (Mosaics changed to Tokens).
* Removed some irrelevant UI elements for less intrusive appearance.
* Clicking the Faucet Address link opens up the Node Detail section in GCR Explorer.

***
## Known issues
* No major known issues so far.
***
## Customization (.env file example)

```shell
# set enviroment variables
# DEFAULT_NODE
# HOST
# PORT= (default: 3000)
# NATIVE_CURRENCY_NAME
# NATIVE_CURRENCY_ID
# NATIVE_CURRENCY_OUT_MAX
# NATIVE_CURRENCY_OUT_MIN
# FAUCET_PRIVATE_KEY
# MAX_FEE
# ENOUGH_BALANCE
# MAX_UNCONFIRMED
# BLACKLIST_MOSAIC_ID
# EXPLORER_URL
```
