# SwiftSC-Lang Standard Library

Core standard library for SwiftSC-Lang smart contracts.

> **Note:** v1.0 includes basic modules. Full collections (Vec, HashMap) coming in v2.0.

## Modules

- `math.stc` - Safe arithmetic
- `crypto.stc` - Cryptographic functions
- `blockchain.stc` - Blockchain utilities
- `token.stc` - ERC-20 token standard
- `test.stc` - Testing framework

## Installation

```bash
# Included by default with SwiftSC-Lang compiler
swiftsc build  # Automatically includes stdlib
```

## Usage

```rust
use std::math::checked_add;
use std::blockchain::caller;

contract MyContract {
    fn example() {
        let result = checked_add(10, 20);
    }
}
```

## Documentation

See [stdlib documentation](https://docs.swiftsc-lang.dev/stdlib)

## Contributing

See [CONTRIBUTING.md](../CONTRIBUTING.md)

## License

MIT
