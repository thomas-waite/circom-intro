This follows the tutorial outlined here: https://github.com/iden3/circom/blob/master/TUTORIAL.md

## Summary
1) Clone the repo
2) Run `yarn install`
3) Run `yarn compile` to compile the circuit
4) Run `yarn setup` to run the trusted setup, generating proving and verification keys
5) Run `yarn witness` to generate the witness
6) Run `yarn proof` to create a proof
7) Run `yarn verify` to verify the proof
8) Run `yarn generateVerifier` to generate a Solidity contract to verify the proof
9) Run `yarn generateTx` to generate the transaction data that should be sent to the contract, in order toverify the proof

