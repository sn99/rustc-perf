# Rust Compiler Performance Monitoring & Benchmarking

This repository contains two primary crates:

* [`collector`](./collector): gathers data for each bors commit
* [`site`](./site): [displays](https://perf.rust-lang.org) the data and provides a GitHub bot for on-demand benchmarking

Additional documentation on running and setting up the frontend and backend can
be found in the `README` files in the `collector` and `site` directories.

Additional documentation on the benchmark programs can be found in the `README`
file in the `collector/benchmarks` directory.
