# sha2-const

[![Build status](https://github.com/thebox-labs/sha2/workflows/CI/badge.svg)](https://github.com/thebox-labs/sha2/actions)
[![Documentation](https://docs.rs/sha2-const/badge.svg)](https://docs.rs/sha2-const)

`const fn` implementation of the SHA-2 family of hash functions.

This crate allows you to use the SHA-2 hash functions as constant expressions
in Rust. For all other usages, the [`sha2`] crate includes more optimized
implementations of these hash functions.

[`sha2`]: https://crates.io/crates/sha2
