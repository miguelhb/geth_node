<Folowing this manual: https://medium.com/blockchainbistro/set-up-a-private-ethereum-blockchain-and-deploy-your-first-solidity-smart-contract-on-the-caa8334c343d

Important: First time launching: 
geth --datadir /home/miguel/Documentos/geth_node/dataGeth --networkid 3232 --nodiscover --rpc --rpcport "7545" --rpcaddr "127.0.0.1" --rpccorsdomain "*" --port "30303" --rpcapi "personal,db,eth,net,web3,miner" --unlock 0 --password password.sec "--allow-insecure-unlock" wait to finish message "Generating DAG in process". Start a new terminal and start: geth attach http://127.0.0.1:7545 . 
Once here, "miner.start() and check in the first window our node is mining. 
If it is mining, we are ready to do the truffle migration "truffle migrate". 
If not, close all process related with geth node, remove geth folder which is inside data folder and start again.
