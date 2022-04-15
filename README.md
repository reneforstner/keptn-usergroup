# keptn-usergroup

## keptn demo repo
https://github.com/reneforstner/keptn
Branches & webhooks automatically created through keptn
shipyard.yml demo with 3 stages

## application demo repo (Jenkinsfiles)
https://github.com/rforstnerdemo/carts

- Jenkinsfile --> old pipeline
- Jenkinsfile.build --> builds a container images, pushes it to a local registry and triggers keptn delivery sequence
- Jenkinsfile.deploy --> deploys to a given namespace (parameterized with "stage" to select desired namespace/environment); sendFinish back to keptn
- Jenkinsfile.test --> tests the deployed service (parameterized with "stage" and "teststrategy" to define what should be tested in which stag; send Finish back to keptn

## Slidedeck of presentation
