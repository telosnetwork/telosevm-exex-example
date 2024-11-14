# TelosEVM ExEx Example

## Overview
This repo is an example of how to run an ExEx on the TelosEVM 2.0 version (or many, you can add as many as you want to a single node).

For proper examples of various use cases, see the [examples repo](https://github.com/paradigmxyz/reth-exex-examples) from Paradigm who are the creators of reth.

### Updating/versioning
Notice that this main.rs is a copy of the telos-reth [main.rs](https://github.com/telosnetwork/telos-reth/blob/telos-main/crates/telos/bin/src/main.rs) file, with the addition of `.install_exex("Example", exex::exex_init)` to the builder.  As the telos-reth repo gets updated, this main.rs file may need to also be updated with those changes.
