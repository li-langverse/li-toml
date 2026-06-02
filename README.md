# li-toml

Li-native TOML 1.0 subset parser for ecosystem configuration.

**Scope:** generic `TomlDoc` / `TomlValue` tree — no httpd-specific logic. Httpd desugar lives in **li-httpd**.

## Status

Phase 0 scaffold — parser implementation follows in phase A0.

## Build

```bash
export LIC_ROOT=../lic
lic check src/lib.li
```

## Import

```li
import toml
```
