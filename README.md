# js-mxt-sdk

js-mxt-sdk is a JavaScript SDK for MixTrust(MXT), a decentralized synthetic asset issuance protocol based on Ethereum, and provides a decentralized cross-chain trading platform for synthetic assets.

## Project Introduction

This repository contains the JavaScript SDK code for MixTrust(MXT), which can be used to interact with the MixTrust(MXT) smart contracts and the trading application.

## Installation and Usage

To install the js-mxt-sdk, you can use npm or yarn:

```bash

npm install js-mxt-sdk

# or

yarn add js-mxt-sdk

```

To use the js-mxt-sdk, you need to import it and create an instance of it:

```javascript

import MXT from 'js-mxt-sdk';

// create an instance of MXT with a web3 provider

const mxt = new MXT(web3.currentProvider);

// or create an instance of MXT with a web3 instance

const mxt = new MXT(web3);

```

The js-mxt-sdk provides various methods to interact with the MixTrust(MXT) protocol, such as:

- `mxt.getSynthBalance(address)` : returns the balance of a synthetic asset for a given address.

- `mxt.getSynthPrice(symbol)` : returns the price of a synthetic asset for a given symbol.

- `mxt.getSynthList()` : returns the list of available synthetic assets on the MixTrust(MXT) protocol.

- `mxt.mintSynth(symbol, amount)` : mints a synthetic asset for a given symbol and amount.

- `mxt.burnSynth(symbol, amount)` : burns a synthetic asset for a given symbol and amount.

- `mxt.swapSynth(fromSymbol, toSymbol, amount)` : swaps one synthetic asset for another for a given amount.

For more details and examples, please refer to the [documentation](https://github.com/mixtrustexchange/js-mxt-sdk/blob/master/docs/README.md).

## Contact Us

If you have any questions or suggestions, please contact us:

- Twitter: [@MixtrustMXT](https://twitter.com/MixtrustMXT)

- Email: mxt@mixtrust.exchange

## License

This project is licensed under the [MIT License](https://github.com/mixtrustexchange/js-mxt-sdk/blob/master/LICENSE).

