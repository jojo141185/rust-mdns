# Branch "spotty" 
Modifications by jr01 to support linux kernels <3.9 and windows
(for more information see https://github.com/plietar/rust-mdns/pull/11#pullrequestreview-66336314).

# rust-mdns - Rust mDNS responder

rust-mdns is a pure rust implementation of the mDNS ([RFC 6762]) and DNS-SD ([RFC 6763]) protocols.

## Usage

To use it, first add this to your `Cargo.toml`:

```toml
[dependencies.mdns]
git = "https://github.com/jojo141185/rust-mdns", branch = "spotty"
```

Then, add this to your crate root:

```rust
extern crate mdns;
```

[RFC 6762]: https://tools.ietf.org/html/rfc6762
[RFC 6763]: https://tools.ietf.org/html/rfc6763
