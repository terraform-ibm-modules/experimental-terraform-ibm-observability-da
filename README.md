# EXPERIMENTAL - IBM Cloud Observability solution


> ⚠️ **Warning**
> Go to https://github.com/terraform-ibm-modules/terraform-ibm-observability-da for the released graduated version of this module.
> This repository is used for experimental features.



[![Implemented (No quality checks)](https://img.shields.io/badge/Status-Implemented%20(No%20quality%20checks)-yellowgreen)](https://terraform-ibm-modules.github.io/documentation/#/badge-status)
[![latest release](https://img.shields.io/github/v/release/terraform-ibm-modules/terraform-ibm-observability-da?logo=GitHub&sort=semver)](https://github.com/terraform-ibm-modules/terraform-ibm-observability-da/releases/latest)
[![pre-commit](https://img.shields.io/badge/pre--commit-enabled-brightgreen?logo=pre-commit&logoColor=white)](https://github.com/pre-commit/pre-commit)
[![Renovate enabled](https://img.shields.io/badge/renovate-enabled-brightgreen.svg)](https://renovatebot.com/)
[![semantic-release](https://img.shields.io/badge/%20%20%F0%9F%93%A6%F0%9F%9A%80-semantic--release-e10079.svg)](https://github.com/semantic-release/semantic-release)

> [!IMPORTANT]
> The IBM Log Analysis and IBM Cloud Activity Tracker services are deprecated. IBM Cloud Logs is the replacement service. This module will be updated to provision the new services before the end of support in March 2025.

This repository contains the following infrastructure as code solutions:
- [IBM Cloud Observability instances solution](./solutions/instances)
- [IBM Cloud Observability agents solution](./solutions/agents)

> [!NOTE]
> These solutions are not intended to be called by one or more other modules because they contain a provider configurations. They are not compatible with the `for_each`, `count`, and `depends_on` arguments. For more information see [Providers Within Modules](https://developer.hashicorp.com/terraform/language/modules/develop/providers).

<!-- Leave this section as is so that your module has a link to local development environment set up steps for contributors to follow -->
## Contributing

You can report issues and request features for this module in GitHub issues in the module repo. See [Report an issue or request a feature](https://github.com/terraform-ibm-modules/.github/blob/main/.github/SUPPORT.md).

To set up your local development environment, see [Local development setup](https://terraform-ibm-modules.github.io/documentation/#/local-dev-setup) in the project documentation.
