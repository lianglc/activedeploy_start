# activedeploy_start

IDS pipeline extension used to begin an active deploy for Cloud Foundry applications.

A pipeline job created from this extension must be used in the same stage with a job to deploy a single unrouted instance 
of the successor app and a job to complete the active deploy.

For more details, see [here](https://hub.jazz.net/docs/deploy_ext/).