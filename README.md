# k8spacket Helm Charts

The code is provided as-is with no warranties.

## Usage

[Helm](https://helm.sh) must be installed to use the charts.
Please refer to Helm's [documentation](https://helm.sh/docs/) to get started.

Once Helm is set up properly, add the repo as follows:

```bash
  helm repo add k8spacket https://k8spacket.github.io/k8spacket-helm-chart
```

Cortex can now be installed with the following command:

```bash
  helm install k8spacket --namespace k8spacket k8spacket/k8spacket
```

If you have custom options or values you want to override:

```bash
  helm install k8spacket --namespace k8spacket -f my-k8spacket-values.yaml k8spacket/k8spacket
```