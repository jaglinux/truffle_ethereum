# truffle_ethereum

1. Install truffle: npm install -g truffle
2. Install webpack: npm install -g webpack
                    truffle unbox webpack
3. Download this source code.
4. Run Rinkeby test network node in seperate terminal
5. Install geth and connect to Rinkeby
   https://gist.github.com/cryptogoth/10a98e8078cfd69f7ca892ddbdcf26bc
6. truffle console
      web3.personal.newAccount()
      web3.eth.getBalance()
      web3.personal.unlockAccount()
7. truffle migrate
   This will compile and push the contract to Rinkeby network.
8. Start the server 
    npm run dev
9. Install metamask plugin and connect to Rinkeby network.
