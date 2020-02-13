# Welcome to Pledra helm charts

This contains a collection of standard helm charts ready for use in any given kubernetes cluster.

The main star of our show is the awesome [Doodba](https://github.com/Tecnativa/doodba) docker image which we consider the golden standard for deploying [Odoo](https://www.odoo.com/).

Odoo-doodba chart also supports cluster-deployed psql database as well as external CloudSQL instances from Google Cloud.

### How do I deploy odoo-doodba in Kubernetes?

1. Download the latest 2.X version of [helm](https://helm.sh/).
2. Run `helm repo add https://charts.pledra.com`
3. Create a local copy of [values.yaml](https://github.com/pledra/helm-charts/blob/master/charts/odoo-doodba/values.yaml).
4. Discard any default values and keep only ones you need.
5. Run `helm install [your-release-name] pledra/odoo-doodba -f values.yaml`.

This is indeed a oversimplification of the process but not much time has been invested into the UX of this project for now..


###### * Future updates will make this chart helm 3.X compatible
