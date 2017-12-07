
# BigQuery Deployment Manager Example

Google Cloud Deployment Manager is an infrastructure management service that makes it simple to create, deploy, and manage Google Cloud Platform resources. With Deployment Manager, you can create a static or dynamic template that describes the configuration of your Google Cloud environment and then use Deployment Manager to create these resources as a single deployment.

This repository contains a BigQuery example template for use with Deployment Manager. The example creates a dummy sales dataset along with a transaction table. The table is partitioned by day and provides an example of nested/repeated fields within the schema.

See https://cloud.google.com/deployment-manager/overview for more information.

## License

Apache 2.0 - See [LICENSE](LICENSE) for more information.