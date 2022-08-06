# azure-policy
Azure policy files used for managing deployments at scale

## Stamp RG with Date
Adds a tag to every newly deployed resource group called `deployment-date` which is the datetime the resource group was created.

## Inherit Tags from RG
Assigns specified tags from the parent resource group to all resources within the group
