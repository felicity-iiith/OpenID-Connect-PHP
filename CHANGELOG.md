# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/)
and this project adheres to [Semantic Versioning](http://semver.org/).

## [Unreleased]
### Added
* Timeout is configurable via setTimeout method. This addresses issue #94.
* Add the ability to authenticate using the Resource Owner flow (with or without the Client ID and ClientSecret). This addresses issue #98
* Add support for HS256, HS512 and HS384 signatures
* Removed unused calls to $this->getProviderConfigValue("token_endpoint_…
* Store id_token and access_token in session for access later (no need to keep reauthenticating)

### Changed

### Removed
