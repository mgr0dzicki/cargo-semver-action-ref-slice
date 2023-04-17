# ref\_slice (test branch including a patch change)

This fork is used in CI workflows of the following repositories:
 - [`cargo-semver-checks`](https://github.com/obi1kenobi/cargo-semver-checks)
 - [`cargo-semver-checks-action`](https://github.com/obi1kenobi/cargo-semver-checks-action)

**When making changes here, please make sure that the corresponding jobs in the above repositories still work!**

## Original README

[![Documentation](https://docs.rs/ref_slice/badge.svg)](https://docs.rs/ref_slice)
[![Crates.io](https://img.shields.io/crates/v/ref_slice.svg)](https://crates.io/crates/ref_slice)

Small utility functions for getting slices of length one.

This [used to be in the standard library][ref], but was removed. So here you go!

There are also versions that work on `Option<T>` as well.

[ref]: https://github.com/rust-lang/rust/issues/27774#issuecomment-150058618
