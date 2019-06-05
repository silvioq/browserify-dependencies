# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Fixed
- Failure on successive runs due to attempting to delete a file using directory methods. Scenario now addressed in unit tests.

### Security
- Updated dev dependency `ava` to address vulnerabilities in indirect dependencies `tar` and `js-yaml`.

## [1.0.0] - 2019-03-12

First stable release.

## [1.0.0-rc.1] - 2019-03-12

### Fixed
- Possible failure in directory tree creation.

## [1.0.0-beta.1] - 2019-01-09

Inital release
