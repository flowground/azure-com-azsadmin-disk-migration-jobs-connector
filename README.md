# ![LOGO](logo.png) ComputeDiskAdminManagementClient **flow**ground Connector

## Description

A generated **flow**ground connector for the ComputeDiskAdminManagementClient API (version 2018-07-30-preview).

Generated from: https://api.apis.guru/v2/specs/azure.com/azsadmin-DiskMigrationJobs/2018-07-30-preview/swagger.json<br/>
Generated at: 2019-05-07T17:37:27+03:00

## API Description

The Admin Compute Disk Management Client.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Returns a list of disk migration jobs.

*Tags:* `DiskMigrationJobs`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `location` - _required_ - Location of the resource.
* `status` - _optional_ - The parameters of disk migration job status.
* `api-version` - _required_ - Client API Version.

### Returns the requested disk migration job.

*Tags:* `DiskMigrationJobs`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `location` - _required_ - Location of the resource.
* `migrationId` - _required_ - The migration job guid name.
* `api-version` - _required_ - Client API Version.

### Create a disk migration job.

*Tags:* `DiskMigrationJobs`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `location` - _required_ - Location of the resource.
* `migrationId` - _required_ - The migration job guid name.
* `targetShare` - _required_ - The target share name.
* `api-version` - _required_ - Client API Version.

### Cancel a disk migration job.

*Tags:* `DiskMigrationJobs`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `location` - _required_ - Location of the resource.
* `migrationId` - _required_ - The migration job guid name.
* `api-version` - _required_ - Client API Version.

## License

**flow**ground :- Telekom iPaaS / azure-com-azsadmin-disk-migration-jobs-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
