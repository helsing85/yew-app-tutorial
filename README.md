# Yew Tutorial

https://yew.rs/docs/getting-started/introduction

Generated from template

```bash
cargo generate --git https://github.com/yewstack/yew-trunk-minimal-template
```

### Installation

Install Rust: <https://www.rust-lang.org/tools/install>.

To compile Rust to WASM, we need to have the `wasm32-unknown-unknown` target installed.
If you don't already have it, install it with the following command:

```bash
rustup target add wasm32-unknown-unknown
```

Now that we have our basics covered, it's time to install the star of the show: Trunk.
Simply run the following command to install it:

```bash
cargo install trunk wasm-bindgen-cli
```

That's it, we're done!

### Running

```bash
trunk serve
```

Rebuilds the app whenever a change is detected and runs a local server to host it.

There's also the `trunk watch` command which does the same thing but without hosting it.

### Release

```bash
trunk build --release
```

This builds the app in release mode similar to `cargo build --release`.
You can also pass the `--release` flag to `trunk serve` if you need to get every last drop of performance.

Unless overwritten, the output will be located in the `dist` directory.

# Tauri

Prerequisites and Quick Start

```
https://tauri.app/v1/guides/getting-started/prerequisites/
```

Development:
```
cargo tauri dev
```

Build application:
```
cargo tauri build
```
