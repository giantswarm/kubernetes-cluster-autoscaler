# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project's packages adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## [v0.8.0] WIP

### Changed

- Change prioty class to `giantswarm-critical`.


## [v0.7.0]

### Changed

- Updated cluster-autoscaler to version 1.14.3.


## [v0.6.0]

### Added

- Separate network policy for cluster-autoscaler.


## [v0.5.0]

### Added

- Separate pod security policy for cluster-autoscaler.
- Security context with non-root user (`giantswarm`) for running cluster-autoscaler inside container.


## [v0.4.1]

### Changed

- Extend configuration options to allow users to tune the Cluster Autoscaler in deep.

[v0.7.0]: https://github.com/giantswarm/kubernetes-cluster-autoscaler/pull/24
[v0.6.0]: https://github.com/giantswarm/kubernetes-cluster-autoscaler/pull/23
[v0.5.0]: https://github.com/giantswarm/kubernetes-cluster-autoscaler/pull/22
[v0.4.1]: https://github.com/giantswarm/kubernetes-cluster-autoscaler/pull/21
