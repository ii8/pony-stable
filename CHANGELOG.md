# Change Log

All notable changes to the Pony compiler and standard library will be documented in this file. This project adheres to [Semantic Versioning](http://semver.org/) and [Keep a CHANGELOG](http://keepachangelog.com/).

## [unreleased] - unreleased

### Fixed


### Added


### Changed


## [0.1.3] - 2018-06-02

## [0.1.2] - 2018-05-25

### Fixed

- Update usage of Env.exitcode to be compatible with ponyc 0.22.x ([PR #56](https://github.com/ponylang/pony-stable/pull/56))
- Fixed issue with the way the `.deps` directory is updated to avoid problems with non-master versions

## [0.1.1] - 2017-10-16

### Fixed

- Fix possible illegal instruction core dump when using prebuilt ponyc binaries ([PR #45](https://github.com/ponylang/pony-stable/pull/45))

### Added

- Add `version` command line option ([PR #44](https://github.com/ponylang/pony-stable/pull/44))

## [0.1.0] - 2017-09-17

### Fixed

- Fix invalid separator in PONYPATH for Windows. ([PR #32](https://github.com/ponylang/pony-stable/pull/32))

### Added

- Display an error message when add subcommand cannot be found ([PR #39](https://github.com/ponylang/pony-stable/pull/39))

