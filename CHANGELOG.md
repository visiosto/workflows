# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to
[Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.3.2] - 2025-04-21

### Fixed

- GitHub CLI as the Git credentials helper for the `lint-terraform-module`
  workflow.

## [0.3.1] - 2025-04-21

### Fixed

- GitHub CLI as the Git credentials helper for the `lint-terraform-module`
  workflow.

## [0.3.0] - 2025-04-21

### Changed

- Input secret `token` to `lint-terraform-module` to `access-token`.

### Fixed

- Input secrets being used in the `if` condition of the `lint-terraform-module`
  workflow.

## [0.2.0] - 2025-04-21

### Added

- Input secret `token` to `lint-terraform-module` workflow for setting up
  authentication with GitHub.

## [0.1.0] - 2025-04-20

### Added

- `lint-terraform-module` workflow for linting standalone Terraform modules.

[0.3.2]: https://github.com/visiosto/workflows/compare/v0.3.1...v0.3.2
[0.3.1]: https://github.com/visiosto/workflows/compare/v0.3.0...v0.3.1
[0.3.0]: https://github.com/visiosto/workflows/compare/v0.2.0...v0.3.0
[0.2.0]: https://github.com/visiosto/workflows/compare/v0.1.0...v0.2.0
[0.1.0]: https://github.com/visiosto/workflows/releases/tag/v0.1.0
