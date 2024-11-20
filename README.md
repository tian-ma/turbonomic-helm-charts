## Usage

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

  helm repo add turbo-charts https://tian-ma.github.io/turbonomic-helm-charts/

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.  You can then run `helm search repo
turbo-charts` to see the charts.

To install the kubeturbo chart:

    helm install my-<chart-name> turbo-charts/kubeturbo

To uninstall the chart:

    helm delete my-<chart-name>