# tonic-disable-doctest

[![crates.io](https://img.shields.io/crates/v/tonic-disable-doctest.svg)](https://crates.io/crates/tonic-disable-doctest)
[![Released API docs](https://img.shields.io/docsrs/tonic-disable-doctest/latest)](https://docs.rs/tonic-disable-doctest)
[![MIT licensed](https://img.shields.io/badge/license-MIT-blue.svg)](./LICENSE)

Separate docstring for specific structs autogenerated by [`tonic_build`](https://docs.rs/tonic-build). This may be handy in cases where comments for autogeneration input contain code that will be incorrectly treated as rust code and you have no control over the input. This will disable doctest of these docs while retaining the docstring in a separate struct.
