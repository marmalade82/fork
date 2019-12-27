# Changelog
All notable changes to this project will be documented in this file.

## [0.1.1]
### Added
- Dynamic array input and more built-in inputs

## [1.0.0]
### Added
- Support for any side effect free validation
- `:external-errors` key to differenciate from input `:errors`
- `:form-id` to let fork know about the inputs

### Changed
- `:initial-values` not required
- Safe calls to `(values "input")` or `(touched "input")` when no value is set

### Removed
- Built-in validation
- Array input support

## [1.0.2]
### Added
- `set-touched` handler

### Changed
- Bulma dropdowns take a list of maps as options rather than a map