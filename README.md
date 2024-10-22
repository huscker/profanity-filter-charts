# Profanity filter Helm charts
[![MIT license](https://img.shields.io/github/license/huscker/profanity-filter-docker)](https://github.com/huscker/profanity-filter-docker/blob/main/LICENSE)

This repo collects a set of [Helm](https://helm.sh) charts for deploying [Profanity filter service](https://github.com/huscker/profanity-filter-docker). 

## Usage

[Helm](https://helm.sh) must be installed and initialized to use the charts.
Please refer to Helm's [documentation](https://helm.sh/docs/) to get started.

Once Helm is set up properly, add the repo as follows:

1. Add charts repo
```console
helm repo add profanity-filter-charts https://huscker.github.io/profanity-filter-charts/
```

2. Install chart
```bash
helm install profanity-filter profanity-filter-charts/profanity-filter --version 1.0.0
```
## Contributing

We welcome contributions.
Please refer to our [contribution guidelines](CONTRIBUTING.md) for details.
