<!-- markdownlint-disable MD024 -->
# Changelog

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased] (OpenSSH middleware API version 7) - xxxx-xx-xx

## [2.0.0] (OpenSSH middleware API version 7) - 2020-10-06

### Added

- You can now create and use keys created with `no-touch-required` option.
- Support for `verify-required` option is added(with a little limitation).
- New attestation data will be returned if available(a bit different but correct).

### Changed

- Bumped API version to 0x00070000 (requires OpenSSH v8.4p1).

## [v1] (OpenSSH middleware API version 5)

- [Branch v1 changelog](https://github.com/tavrez/openssh-sk-winhello/blob/v1/CHANGELOG.md).

[Unreleased]: https://github.com/tavrez/openssh-sk-winhello/compare/v2.0.0...HEAD
[2.0.0]: https://github.com/tavrez/openssh-sk-winhello/compare/v1.0.2...v2.0.0
[v1]: https://github.com/tavrez/openssh-sk-winhello/tree/v1
