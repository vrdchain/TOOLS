balance
===



The balance utility iterates through the dag, determining the VRD coin balance of a given address.
```bash
$ balance -h
Usage of balance:
  -address string
    	Address to check balance of
  -json
    	Output in JSON format
  -mainnet
    	Use mainnet params for rpc calls
  -rpccert string
    	VRDd RPC server cert chain
  -rpcpass string
    	VRDd RPC server password to use
  -rpcserver string
    	VRDd RPC server to scan for transactions
  -rpcuser string
    	VRDd RPC server username to use
  -simnet
    	Use simnet params for rpc calls
  -testnet
    	Use testnet params for rpc calls
```

### Example usage
```
balance -simnet -rpccert /home/cedric/.VRDd/rpc.cert -rpcserver 127.0.0.1:5071 -rpcuser USER -rpcpass PASS -address SQoJvhmt6QkK7itCgy4S12JN2CkVMoqNf5
```