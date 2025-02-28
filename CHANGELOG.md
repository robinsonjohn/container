# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

- `Added` for new features.
- `Changed` for changes in existing functionality.
- `Deprecated` for soon-to-be removed features.
- `Removed` for now removed features.
- `Fixed` for any bug fixes.
- `Security` in case of vulnerabilities

## [3.0.1] - 2024.12.23

### Added

- Tested up to PHP v8.4.
- Updated GitHub issue templates.

## [3.0.0] - 2023.01.21

## Changed

- Refactored code to only support PHP 8.

## [2.0.1] - 2023.01.21

## Fixed

- Fixed `getAliases` bug

## [2.0.0] - 2023.01.21

## Added

- Complete rewrite, now supporting PHP 8.0 and above.

## [1.1.3] - 2020.09.08

### Changed

- Changed return type declaration from `object` to `mixed` from `get`, `set`, and `create` methods,
as this does not allow specific class name type hinting/return type declarations
where these methods are used.

## [1.1.2] - 2020.08.29

### Fixed

- Fixed a bug where some thrown exceptions were not properly chained.

## [1.1.1] - 2020.08.18

### Changed

- Updated `README.md` documentation

## [1.1.0] - 2020.08.04

### Added

- Added `put()` method

## [1.0.0] - 2020.08.01

### Added

- Initial release.