# webasm-runtime
Course Project for CS 263: Runtime Systems at UC Santa Barbara

## Final Presentation
Uploaded as `CS 263 - WebAssembly.pdf` in this repo.
Google drive Read only link - https://docs.google.com/presentation/d/1oc4ynTOwDnZeJlmJqLB0oggZRxxQ7RxIIhwIAto2I28/edit?usp=sharing


## Setup

* Install rustup (also installs Rust compiler) `curl https://sh.rustup.rs -sSf | sh`
* Install Rust nightly for wasm compilation tools:
  * `rustup default nightly`
  * `rustup target add wasm32-unknown-unknown --toolchain nightly`
* Install a webserver for local development
  * `cargo install https`
* Start the webserver
  * `${HOME}.cargo/bin/http`

[Rust and WebAssembly Tutorial](https://rust-lang-nursery.github.io/rust-wasm/introduction.html)
