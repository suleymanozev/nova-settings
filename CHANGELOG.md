# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [5.0.0] - 13-05-2022

### Changed

- NB! Changed namespace from OptimistDigital to Outl1ne
- Allow redirections as a result of settings updates (thanks to [@ianrobertsFF](https://github.com/ianrobertsFF))
- Fixed sidebar subpages titles (thanks to [@faab007nl](https://github.com/faab007nl))
- Updated packages

## [4.0.4] - 29-04-2022

### Changed

- Removed loadViewsFrom() call from ServiceProvider
- Fixed memory cache not clearing after settings update
- Updated packages

## [4.0.3] - 25-04-2022

### Changed

- Changed `empty` check to `isset` when loading settings to allow negative but defined values

## [4.0.2] - 08-04-2022

### Changed

- Reworked routing logic

## [4.0.1] - 08-04-2022

### Changed

- Fixed page titles

## [4.0.0] - 08-04-2022

### Added

- Nova 4 support
- Fully compatible with light and dark modes

### Changed

- Dropped Laravel 7 and 8 support
- Dropped PHP 7.X support
- Dropped Nova 3 support
