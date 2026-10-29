# KX-9 Developers

Open-source software for wallet-controlled trading protocols on Robinhood mainnet.

[Website](https://kx9.tech) · [Command app](https://app.kx9.tech) · [Documentation](https://github.com/kx9-dev/kx9-docs) · [dev@kx9.tech](mailto:dev@kx9.tech)

## What we build
KX-9 combines a wallet-connected Command interface, deterministic strategy
rules, a risk-checking Core and operator-controlled Shield contracts.
The design separates a trading intent, permission to submit, submission and
actual on-chain confirmation.

## Open-source repositories
| Repository | Responsibility |
| --- | --- |
| [kx9-web](https://github.com/kx9-dev/kx9-web) | KX-9 landing page and wallet-connected Command app for Robinhood mainnet. |
| [kx9-core](https://github.com/kx9-dev/kx9-core) | Wallet-authenticated Core API, deterministic trading rules, risk checks and mainnet execution controls. |
| [kx9-contracts](https://github.com/kx9-dev/kx9-contracts) | Solidity Shield vaults and factory with operator limits, supervised approvals and local-chain tests. |
| [kx9-docs](https://github.com/kx9-dev/kx9-docs) | Architecture, operating flows, OpenAPI specification, security boundaries and mainnet configuration. |

## Engineering principles
- Private keys and provider credentials stay outside public source and browser code.
- The operator controls permissions, limits, modes and supervised approvals.
- Missing data stays unavailable; no invented market history or trade fills.
- Rule facts and risk decisions stay verifiable, even with optional text narration.
- Real tests, documented boundaries and truthful release notes—not artificial contribution activity.

## Current boundaries
Chain ID: **4663**. A connected RPC is not proof of trading readiness.
Contract deployment, liquidity, feeds and execution authorization are separate
requirements. Local tests are not an audit. Physical AI · NVDA is an asset
allocation strategy, not an NVIDIA AI integration or partnership.

## Contribute
Start with a repository's README, CONTRIBUTING.md and SECURITY.md.
Report reproducible non-sensitive bugs in issues. For private security reports
and maintainer contact, email **dev@kx9.tech**.

KX-9 is not affiliated with NVIDIA Corporation or Robinhood Markets.
No investment advice or promise of returns.
