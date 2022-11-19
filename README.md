# Solana Prettier config

Let's share this Prettier config across all of our projects, to keep things consistent.

## Installation

1. Install this package in the target project, along with the required peer dependencies
   ```bash
   pnpx install-peerdeps@2 --pnpm --dev @solana/prettier-config-solana
   ```
2. Add a reference to this module in your `package.json`
   ```json
   "prettier": "@solana/prettier-config-solana"
   ```
