# Santander Bank Account

A JavaScript OOP exercise developed during the **Santander Coders bootcamp**. It models a bank account hierarchy using class inheritance, demonstrating encapsulation and polymorphism in vanilla JavaScript.

## Tech stack

- JavaScript (ES6 classes, no runtime dependencies)
- Node.js (to run the script)

## Getting started

No installation required.

```bash
node test.js
```

The script runs immediately and prints account operation results to the console.

## Project structure

```
test.js   # All class definitions and usage examples in a single file
```

## What it covers

- `BankAccount` — base class with `deposit` and `withdraw` methods
- `SavingsBankAccount` — extends `BankAccount`; enforces a minimum balance on withdrawals
- `ProfitableBankAccount` — extends `BankAccount`; applies a 1% deposit bonus and a R$3 fee on deposits, plus a R$0.50 fee on withdrawals
- `Client` — associates a customer name with one or more accounts (only savings or profitable accounts are accepted)
