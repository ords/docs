# Infrastructure

## Naming Convention

#### Projects:
`project-name--environment`

#### Global scope
Some resources requires gloabal scope access. Can be named:
`environment.project-name`

#### Service / App prefix
Resources dedicated to a specific app is prefixed with the service or app name. Examples:

`product-cool-app.environment.project-name`
`team-services.environment.project-name`

Sometimes a service name matches that the cloud name is included as a prefix:

`bucket.team-services.environment.project-name`