# Multi-Sig Wallet Lite

This repository features a robust and easy-to-understand Multi-Signature Wallet. It is an essential tool for DAO treasuries or shared crypto accounts where no single person should have total control over funds.

### Features
* **M-of-N Confirmation:** Set a required number of owners and a threshold for execution.
* **Transaction Queueing:** Any owner can propose a transaction; others must confirm it.
* **Security First:** Prevents unauthorized transfers and protects against single-point-of-failure attacks.
* **Events Driven:** Comprehensive logging for all proposals, confirmations, and executions.

### Core Logic
1. **Submit:** An owner proposes a destination address, value, and data.
2. **Confirm:** Other owners call the confirm function for the transaction ID.
3. **Execute:** Once the threshold is met, anyone can trigger the execution.

### License
MIT
