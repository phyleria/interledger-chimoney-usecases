# Chimoney-Interledger Use Cases

This repository contains starter code and examples for various use cases that integrate Chimoney's API with Interledger. These use cases demonstrate how businesses, microfinance platforms, remittance services, and charitable organizations can leverage Chimoney-Interledger endpoints to handle global payouts, payments, and donations.

## Use Cases

- **Seamless International E-commerce**: Enables merchants and customers to process global transactions using Interledger.
- **Microfinance and Lending**: Facilitates the distribution of loans using Interledger payment pointers for both lenders and borrowers.
- **Global Remittances**: Allows users to send money internationally with low transaction fees using Interledger Wallet Addresses.
- **Charitable Donations**: Allows users to donate to charities globally by sending funds to their Interledger Wallet Address.

## Setup & Installation
Before setting up any individual use cases, make sure you have the following installed:

- Node.js (version 14 or higher)
- MongoDB (if using local DB)
- Docker (optional, but recommended for running the project in containers)
- Chimoney API Keys: You'll need API credentials to access Chimoney's endpoints. You can sign up at Chimoney API.

Clone the repository:

```
git clone https://github.com/yourusername/chimoney-interledger-usecases.git
cd chimoney-interledger-usecases
```

Navigate to a specific use case:

```
cd ecommerce-usecase
```

Install dependencies:

```bash
npm install
```

Set up environment variables: Copy the .env.example file in each use case folder and rename it to .env. Then, fill in the required variables.

Example .env file for E-commerce use case:

```makefile
CHIMONEY_API_KEY=your-chimoney-api-key
INTERLEDGER_WALLET_ADDRESS=your-interledger-wallet-address
MONGO_URI=mongodb://localhost:27017/ecommerce
```

Run the application:

```bash
npm start
```

