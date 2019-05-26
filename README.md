# blockchain-lottery

- solc compiler 0.4.25
- web3.js to interact with the ABI
- ganache testsuite
- mocha for testing

# set up

- `npm install`
- `node compile.js`

# To deploy

- `node deploy.js`

# To test

- `npm run test`

## If error: cannot find module ../utils,

- remove package-lock.json
- `npm cache clean --force`
- `npm install`

### If error persists, reinstall `node 10.15 LTS` and retry the above commands
