# helm-charts

# temporal
`./charts/temporal` contains the latest Helm chart for Temporal copied from [official Temporal repo](https://github.com/temporalio/helm-charts). 
To upgrade it remove everything in `./charts/temporal` folder and copy it again from the **latest tag** (do not copy from unstable `main` branch❗).

We do not use official temporal Helm template because Temporal team decided not to host it. They [discourage using Helm in production for Temporal](https://temporal.io/blog/temporal-and-kubernetes).