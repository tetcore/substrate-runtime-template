# Substrate Runtime Template

A FRAME runtime ready for hacking. Learn to build with Substrate at substrate.io

## Build

```bash
cargo build --release
```

## Install

This runtime is not a standalone executable. It needs to be housed in a Substrate node. Add the dependency to your node's manifest.

```toml
[dependencies]
runtime = { git = 'https://github.com/substrate-developer-hub/substrate-runtime-template', tag = 'v2.0.0-alpha.8'}
```
