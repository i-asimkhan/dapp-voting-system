# dapp-voting-system


## Configuration

1. Configure metamask in the browser with truffle using this https://trufflesuite.com/docs/truffle/how-to/truffle-with-metamask/ 
2. Run Ganache UI,and import the acounts to Metamask localhost channel using this https://ethereum.stackexchange.com/questions/30593/how-can-i-import-the-accounts-from-truffle-develop-into-metamask. 
3. Deploy smart contract to the (local) blockchain network using VS Code extension. 
   Use this https://consensys.net/docs/qbs/en/latest/tutorials/deploy-smart-contract/vscode/ or https://coinsbench.com/compile-and-deploy-smart-contracts-inside-vscode-8226ec001806

   or use terminal

   ```shell
   # on the dVoting directory
   truffle migrate
   ```
   > Note: Use `truffle migrate --reset` for re-deployments
4. Launch the the frontend application.

   ```shell
   cd client
   npm install
   npm start
   ```