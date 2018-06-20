Tronscan API
============

# Running

```bash
./start.sh
```

# Environment Variables

`NODE_FULL_IP` IP Address of the Full Node  
`NODE_FULL_PORT` GRPC Port of the Full Node, default: 50051  
`NODE_SOLIDITY_IP` IP Address of the Solidity Node  
`NODE_SOLIDITY_PORT` GRPC Port of the Solidity Node, default: 50051  
`ENABLE_SYNC` If the synchronisation should be enabled. Values: "true" or "false"
`ENABLE_NETWORK_SCANNER` If the network scanner should be enabled. Values: "true" or "false"
`SECRET_KEY` Random string used to encrypt cookie data. Only requires to be changed if the API is gonna be publicly available
