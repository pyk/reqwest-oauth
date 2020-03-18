<p align="center">
  <h3  align="center">reqwest-oauth</h3>
  <p align="center">
    <i>
        OAuth support for Rust reqwest library
    </i>
  </p>
</p>

<p align="center">
  <a href="https://crates.io/crates/reqwest-oauth"><img alt="reqwest-oauth crates" src="https://img.shields.io/crates/v/reqwest-oauth.svg?color=%23fdc452"></a>
  <a href="https://docs.rs/reqwest-oauth"><img alt="reqwest-oauth docs" src="https://docs.rs/reqwest-oauth/badge.svg?color=%233b6837"></a>
  <a href="https://github.com/pyk/reqwest-oauth/actions"><img alt="reqwest-oauth" src="https://github.com/pyk/reqwest-oauth/workflows/reqwest-oauth/badge.svg?branch=master"></a>
</p>

## Documentation
- [Quickstart Tutorial][quickstart tutorial]
- [API Reference]

[API Reference]: https://docs.rs/reqwest-oauth

## Usage
Add this to your `Cargo.toml`:

```toml
[dependencies]
reqwest-oauth = "*"
```

and this to your crate root:

```rust
use reqwest_oauth::prelude::*;
```

To get started using reqwest-oauth, read the [quickstart tutorial].

[quickstart tutorial]:  https://docs.rs/reqwest-oauth#quickstart-tutorial

## Development
Clone the repository using the following command:

```sh
git clone https://github.com/pyk/reqwest-oauth.git --depth=1
cd reqwest-oauth/
```

To build the project, use the following command:

```sh
cargo build
```

To run the tests, use the following command:

```sh
cargo test
```

## Getting help
Feel free to start discussion at [GitHub issues].

[Github issues]: https://github.com/pyk/reqwest-oauth/issues/new/choose

## License
reqwest-oauth is licensed under the [Apache-2.0](./LICENSE) license.

## Contribution

Unless you explicitly state otherwise, any contribution intentionally
submitted for inclusion in reqwest-oauth by you, as defined in the Apache-2.0
license, shall be licensed as above, without
any additional terms or conditions.
