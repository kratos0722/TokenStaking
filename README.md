# Token Staking

A token-staking program on Solana (internally named `food_gathering`), built with Anchor.

Built with the [Anchor](https://www.anchor-lang.com/) framework for [Solana](https://solana.com/).

## Tech Stack
- **Language:** Rust
- **Framework:** Anchor
- **Chain:** Solana

## Workspace
This is an Anchor workspace. The on-chain program lives under `programs/food_gathering`.

## Prerequisites
- [Rust & Cargo](https://rustup.rs/)
- [Solana CLI](https://docs.solana.com/cli/install-solana-cli-tools)
- [Anchor](https://www.anchor-lang.com/docs/installation) (via `avm`)

## Build & Test
```sh
anchor build
anchor test
```

## Deploy
```sh
anchor deploy
```