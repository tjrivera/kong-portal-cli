# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [3.3.0] - 2021-11-08
### Added
- Add new command `init` to initialize a local workspace with a default cli.conf.yaml configuration file
- Add new option `-S/--skip-path` to skip files and directories that match the given path

## [3.2.1] - 2021-11-05
### Fixed
- Bump glob-parent from 5.0.0 to 5.1.2
- Bump axios from 0.19.2 to 0.21.2
- Bump lodash from 4.17.15 to 4.17.21

## [3.2.0] - 2021-07-14
### Changed
- File size limit for uploaded files set to 10MB

### Fixed
- Deploy script terminates with exit code 1 when an error occurs

## [3.1.0] - 2020-06-15
### Added
- View version with `-v`
- Self-signed SSL cert support with `--disable-ssl-verification`
- Ignore specs directory for better CI/CD use with `--ignore-specs`

### Changed
- Improved help text with help on each command

## [3.0.1] - 2020-04-24
### Changed
- Improve error for workspace folder not found

### Fixed
- Non-default workspace not working correctly in 3.0.0

## [3.0.0] - 2020-04-16
### Changed
- Code refactor
- CLI copy updates

### Fixed
- Better support for large file count
- Config command shows all config files

## [2.0.0] - 2020-01-21
### Added
- Binary assets now converted to base64 strings on deploy.

### Changed
- By default base64 converted assets are converted to binary on fetch (keep previous behavior with `--keep-encode`).

- By default deploy wipes all upstream files first (preserve upstream files not found locally with `--preserve`)

### Fixed
- Support for large file count

## [1.0.0] - 2019-06-20
- Initial release

[1.0.0]: https://github.com/kong/kong-portal-cli/releases/tag/v0.0.1
[3.1.0]: https://github.com/kong/kong-portal-cli/releases/tag/v0.0.1
