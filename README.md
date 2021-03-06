This is a collection of libraries and utilities for [Ethereum](https://ethereum.org).

## Use cases

### Creating an online wallet?

Check out [keythereum](https://github.com/ethereumjs/keythereum) for managing keys and [ethereumjs-tx](https://github.com/ethereumjs/ethereumjs-tx) for creating transactions with them.

### Creating a Dapp?

You will need to interface with the Ethereum network. [web3.js](https://github.com/ethereumjs/web3.js) provides a complete RPC interface from Javascript. If looking for a more lightweight option, [ethereumjs-abi](https://github.com/axic/ethereumjs-abi) or [solidity.js](https://github.com/ethereumjs/solidity.js) can handle the ABI encoding.

### Interested in running a node?

See [node-blockchain-server](https://github.com/ethereumjs/node-blockchain-server). It is in a pretty rough state at the moment, but at least can download the blockchain.

## Full list of repos

* [common](https://github.com/ethereumjs/common): the genesis data for the blockchain
* [ethashjs](https://github.com/ethereumjs/ethashjs): [Ethash](https://github.com/ethereum/wiki/wiki/Ethash) in Javascript
* [ethereumjs-abi](https://github.com/axic/ethereumjs-abi):  ABI encoding and decoding
* [ethereumjs-account](https://github.com/ethereumjs/ethereumjs-account): account schema encoding, decoding and validation
* [ethereumjs-block](https://github.com/ethereumjs/ethereumjs-block): block schema encoding, decoding and validation
* [ethereumjs-blockchain](https://github.com/ethereumjs/ethereumjs-blockchain): manage a blockchain
* [ethereumjs-codesim](https://github.com/axic/ethereumjs-codesim): run EVM or Solidity code and examine the output
* [ethereumjs-lib](https://github.com/ethereumjs/ethereumjs-lib): meta package for loading the other ethereumjs- modules
* [ethereumjs-testing](https://github.com/ethereumjs/ethereumjs-testing): transforms the [official test vectors](https://github.com/ethereum/tests) to a format suitable for ethereumjs
* [ethereumjs-tx](https://github.com/ethereumjs/ethereumjs-tx): transaction creation, manipulation, signing and verification
* [ethereumjs-util](https://github.com/ethereumjs/ethereumjs-util): a collection of frequently used methods by the other libraries
* [ethereumjs-vm](https://github.com/ethereumjs/ethereumjs-vm): a complete EVM (Ethereum Virtual Machine) and state processing implementation
* [geth.js](https://github.com/ethereumjs/geth.js): start and stop geth from Node.js
* [keythereum](https://github.com/ethereumjs/keythereum): create, import and export Ethereum keys
* [merkle-patricia-tree](https://github.com/ethereumjs/merkle-patricia-tree): This is an implementation of the modified merkle patricia tree as specified in the [Ethereum yellow paper](http://gavwood.com/Paper.pdf)
* [node-blockchain-server](https://github.com/ethereumjs/node-blockchain-server): aims to provide a full Ethereum node implementation
* [node-devp2p](https://github.com/ethereumjs/node-devp2p): implementation of the [RLPx](https://github.com/ethereum/devp2p/blob/master/rlpx.md) transport protocol for Ethereum (used between nodes)
* [node-devp2p-dpt](https://github.com/ethereumjs/node-devp2p-dpt): implementation of the [RLPx](https://github.com/ethereum/devp2p/blob/master/rlpx.md) DPT (peer table) protocol for Ethereum
* [organization](https://github.com/ethereumjs/organization) and [ideas](https://github.com/ethereumjs/ideas): plans and discussions
* [rlp](https://github.com/ethereumjs/rlp): [RLP (Recursive Length Prefix)](https://github.com/ethereum/wiki/wiki/RLP) encoding and decoding


## Ethereum JS projects not tracked here
* [web3.js](https://github.com/ethereum/web3.js): the complete API as seen in the [wiki](https://github.com/ethereum/wiki/blob/master/JSON-RPC.md)
* [solidity.js](https://github.com/ethereum/solidity.js): ABI encoding and decoding (the relevant code split out from web3.js)

## Contributing and contact

Please check out [organization](https://github.com/ethereumjs/organization) and [ideas](https://github.com/ethereumjs/ideas) repos first.  Contributing to each of the projects is preferably done via pull requests.

You can also reach out on:
* [Gitter](https://gitter.im/ethereum/ethereumjs-lib)
* [#ethereumjs](https://webchat.freenode.net/?channels=ethereumjs) on freenode
