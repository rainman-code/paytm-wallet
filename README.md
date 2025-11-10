🚀 Paytm-Style Wallet System (MongoDB + Node.js)

A lightweight digital wallet system inspired by Paytm, supporting:

✅ Deposit

✅ Withdraw

✅ Peer-to-peer money transfer

✅ Atomic transactions using MongoDB sessions

✅ Idempotency to prevent duplicate payments

Designed to demonstrate secure financial transaction handling with backend focus.


🧠 Features

🧍‍♂️ User Wallet System

Each user has a dedicated wallet record linked to their account

💰 Deposit & Withdraw

Secure balance updates with validation and checks

🔄 Peer-to-Peer Transfers

Wallet-to-wallet transfers using MongoDB session-based atomic transactions

🛑 Idempotency Protection

Ensures duplicate requests don’t trigger duplicate payments

(Same request twice ≠ double debit)

🧾 Transaction Ledger

Every transaction logged for audit & traceability

🔐 JWT-Based Authentication

Secure access to wallet APIs with token validation

⚡ Robust Error Handling

Automatic rollback on failure to maintain data integrity


🛠 Tech Stack

🧾 Backend

Node.js

Express.js

🗄️ Database

MongoDB

Mongoose ORM

🔐 Security

JWT Authentication

Encrypted credentials & secure token flow

⚙️ Core System Logic

MongoDB Transactions (session-based, atomic)
