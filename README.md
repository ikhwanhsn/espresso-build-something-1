# Espresso Rollup Integration

## Build & Brew Hackathon Submission | Track 1: Caffeinate & Code

![Espresso Network](https://cdn.dorahacks.io/static/files/195461b26b9dc69f277e97948ecac51a.jpg)

## Overview

This project demonstrates a fully functional rollup deployment integrated with Espresso's Decaf testnet and Arbitrum Sepolia. Our implementation leverages Espresso's fast confirmations to create a specialized L2 solution that [briefly describe your rollup's unique value proposition].

### Key Features

- 🚀 Fully functional rollup deployed on Espresso's Decaf testnet
- ⚡ Integrated with Espresso confirmations for enhanced security and speed
- 🔄 Seamless compatibility with Arbitrum Sepolia

## Deployment Information

**CreateRollup Transaction Hash**: `0xf33d16d9449ab9624d3727726afe9f37414381cabf00fe3836101b3f3de6f176`

**Cloud Server IP Address**: `3.27.107.202`

**Chain ID / Namespace**: `898989`

## Technical Architecture

Our rollup implementation consists of the following components:

1. **Sequencer Node**: Responsible for transaction ordering and batch creation
2. **Prover Service**: Generates validity proofs for transaction batches
3. **Espresso Integration Layer**: Connects to Decaf testnet for fast confirmations
4. **Arbitrum Bridge**: Enables cross-chain communication with Arbitrum Sepolia

## Demo

A complete demonstration of our rollup's functionality can be found in our [video demo](https://youtu.be/PGIDwCzqDxs).

The demo showcases:
- Rollup initialization and connection to Espresso Decaf
- Transaction processing
- Integration with Espresso confirmations
- Proof verification
- Docker logs showing the rollup in action

## Setup & Installation

### Prerequisites

- Docker & Docker Compose
- Node.js v16+
- Golang 1.19+

### Local Development Setup

```bash
# Clone the repository
git clone https://github.com/ikhwanhsn/espresso-build-something-1.git
cd espresso-build-something-1

# Install dependencies
npm install

# Configure environment
cp .env.example .env
# Edit .env file with your configuration

# Start the rollup
docker-compose up
```

### Deployment Steps

1. Configure AWS/cloud environment
2. Set up necessary security groups
3. Deploy using our automated script:

```bash
./scripts/deploy.sh
```

## Testing

```bash
# Run unit tests
npm test

# Run integration tests
npm run test:integration
```

## Acknowledgements

- Espresso Network team for their technical support

---

*This project was created for the Espresso Build & Brew Hackathon (March 2025).*
