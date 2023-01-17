![Kuma](https://kuma-public-assets.s3.amazonaws.com/kuma-logo-v2.png)

# Kuma Helm Charts

## Add the Kuma Helm repository

```sh
helm repo add kuma https://kumahq.github.io/charts
```

## Install Kuma with Helm

```sh
helm upgrade -i kuma kuma/kuma
```
## Source Code

The code of the Helm Charts is maintained in the main Kuma repo under [deployment/charts](https://github.com/kumahq/kuma/tree/master/deployments/charts)

The charts are published in this repo's [gh-pages branch](https://github.com/kumahq/charts/tree/gh-pages)

Artifact Hub references to these charts at https://artifacthub.io/packages/helm/kuma/kuma

### License

[Apache 2.0 License](https://www.apache.org/licenses/LICENSE-2.0)
