A Multiwii Serial Protocol (MSP) implementation for Rust
===========================================

[![Build Status](https://travis-ci.org/hashmismatch/multiwii_serial_protocol.rs.svg?branch=master)](https://travis-ci.org/hashmismatch/multiwii_serial_protocol.rs)

[![Documentation](https://docs.rs/multiwii_serial_protocol/badge.svg)](https://docs.rs/multiwii_serial_protocol)

## Introduction

An incomplete implementation of the MSP protocol, with some Cleanflight and Betaflight extensions. Allows one to implement a flight controller that can connect to the Cleanflight or Baseflight configurator.

# Installation

MSP is available on crates.io and can be included in your Cargo enabled project like this:

```toml
[dependencies]
multiwii_serial_protocol = "0.1.0"
```

Then include it in your code like this:

```rust
extern crate multiwii_serial_protocol;
```

License: MIT OR Apache-2.0
