# Starknet contract

The Starknet contracts are uploaded on Etherscan here: [0xd8cd77206fcb239bddaaddda8c87cbfe7d67ca2b](https://etherscan.io/address/0xd8cd77206fcb239bddaaddda8c87cbfe7d67ca2b/advanced#code)

And live behind the starkgate proxy (IIUC) here: [0xc662c410C0ECf747543f5bA90660f6ABeBD9C8c4](https://etherscan.io/address/0xc662c410C0ECf747543f5bA90660f6ABeBD9C8c4#writeProxyContract)

The main updatable smart contract's code is on Github: [starknet-io/starkgate-contracts](https://github.com/starknet-io/starkgate-contracts)

but not the implementation behind it. So I just copy/pasted all the implementation files from [Etherscan](https://etherscan.io/address/0xd8cd77206fcb239bddaaddda8c87cbfe7d67ca2b/advanced#code) in this repo for easier reading.

> Note: these might not be up-to-date as the starknet contracts are upgradable.

The most important file is [`Starknet.sol`](./contracts/Starknet.sol).
