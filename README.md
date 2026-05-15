# @encoding/toml — TOML Parsing/Encoding for Zeta

Auto-converted from [toml](https://crates.io/crates/toml) v1.1.2 via [Dark Factory](https://github.com/murphsicles/dark-factory).

## Features
- **Deserialize** — `toml::from_str` for parsing TOML into typed structs
- **Serialize** — `toml::to_string` for encoding structs as TOML
- **Value API** — dynamic `Value` enum for exploring TOML documents
- **Pretty print** — `toml::to_string_pretty` for human-readable output
- **Spanned values** — preserve span information for error reporting

## Usage
```zeta
use @encoding/toml;

let config: Config = toml::from_str(r#"
[server]
host = "localhost"
port = 8080
"#).unwrap();
```

## Stats: ~5,113 lines, 0 unsupported items

## License: MIT