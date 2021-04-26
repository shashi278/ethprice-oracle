# ethprice-oracle

** Simple oracle example that allows only one user, its owner, to fetch data from Binance's public API. **

### How to run?

* Clone this repo: `git clone https://github.com/shashi278/ethprice-oracle.git`
* `cd ethprice-oracle`
* `npm install`
* Create private keys for caller and oracle:
    * `npm run generate-key:oracle`
    * `npm run generate-key:caller`
* Deploy both caller and oracle contracts: `npm run deploy:all`

* Finally, start oracle: `npm run oracle`
* Open another terminal and start caller: `npm run caller`

* It'll keep printing the current Ether value in the caller terminal