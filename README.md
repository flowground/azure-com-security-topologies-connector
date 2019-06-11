# ![LOGO](logo.png) Security Center **flow**ground Connector

## Description

A generated **flow**ground connector for the Security Center API (version 2015-06-01-preview).

Generated from: https://api.apis.guru/v2/specs/azure.com/security-topologies/2015-06-01-preview/swagger.json<br/>
Generated at: 2019-06-11T18:14:16+03:00

## API Description

API spec for Microsoft.Security (Azure Security Center) resource provider

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Gets a list that allows to build a topology view of a subscription and location.

*Tags:* `Topology`

#### Input Parameters
* `subscriptionId` - _required_ - Azure subscription ID
* `ascLocation` - _required_ - The location where ASC stores the data of the subscription. can be retrieved from Get locations
* `api-version` - _required_ - API version for the operation

### Gets a list that allows to build a topology view of a subscription.

*Tags:* `Topology`

#### Input Parameters
* `subscriptionId` - _required_ - Azure subscription ID
* `api-version` - _required_ - API version for the operation

### Gets a specific topology component.

*Tags:* `Topology`

#### Input Parameters
* `subscriptionId` - _required_ - Azure subscription ID
* `resourceGroupName` - _required_ - The name of the resource group within the user's subscription. The name is case insensitive.
* `ascLocation` - _required_ - The location where ASC stores the data of the subscription. can be retrieved from Get locations
* `topologyResourceName` - _required_ - Name of a topology resources collection.
* `api-version` - _required_ - API version for the operation

## License

**flow**ground :- Telekom iPaaS / azure-com-security-topologies-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
