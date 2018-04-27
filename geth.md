# geth

geth is an abbreviation of go-ethereum. It is client api to interact with the
Ethereum Network. You can mine/transfer the ether with it.

## options

There is no man page for this script, and you have to grep through the go-ethereum
code what these are, but:

```
--mine:                     mine ethereum
--minerthreads:             the amount of miners simultaneously work
--rpc:                      remote process call
--rpcaddr:                  remote process call address (for localhost, would be 127.0.0.1)
--rpcapi:                   usually eth,net,web3,personal
--unlock [account address]: this is necessary to launch the network
--datadir:                  the specific directory to refer to the Ethereum keydata etc..
                            sometimes this option cause the error on testnet (kind of
                            conflict + duplication among the global datadir so omitting
                            this option can solve the bug sometimes.
--password [password]:      if the error asks for the account's password, just put it.
```
