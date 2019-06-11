# ![LOGO](logo.png) MonitorManagementClient **flow**ground Connector

## Description

A generated **flow**ground connector for the MonitorManagementClient API (version 2018-03-01).

Generated from: https://api.apis.guru/v2/specs/azure.com/monitor-metricAlert_API/2018-03-01/swagger.json<br/>
Generated at: 2019-06-11T18:14:03+03:00

## API Description

Azure Monitor client to create/update/delete metric based alerts.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Retrieve alert rule definitions in a subscription.

*Tags:* `MetricAlerts`

#### Input Parameters
* `subscriptionId` - _required_ - The Azure subscription Id.
* `api-version` - _required_ - Client Api Version.

### Retrieve alert rule definitions in a resource group.

*Tags:* `MetricAlerts`

#### Input Parameters
* `subscriptionId` - _required_ - The Azure subscription Id.
* `resourceGroupName` - _required_ - The name of the resource group.
* `api-version` - _required_ - Client Api Version.

### Delete an alert rule definition.

*Tags:* `MetricAlerts`

#### Input Parameters
* `subscriptionId` - _required_ - The Azure subscription Id.
* `resourceGroupName` - _required_ - The name of the resource group.
* `ruleName` - _required_ - The name of the rule.
* `api-version` - _required_ - Client Api Version.

### Retrieve an alert rule definition.

*Tags:* `MetricAlerts`

#### Input Parameters
* `subscriptionId` - _required_ - The Azure subscription Id.
* `resourceGroupName` - _required_ - The name of the resource group.
* `ruleName` - _required_ - The name of the rule.
* `api-version` - _required_ - Client Api Version.

### Update an metric alert definition.

*Tags:* `MetricAlerts`

#### Input Parameters
* `subscriptionId` - _required_ - The Azure subscription Id.
* `resourceGroupName` - _required_ - The name of the resource group.
* `ruleName` - _required_ - The name of the rule.
* `api-version` - _required_ - Client Api Version.

### Create or update an metric alert definition.

*Tags:* `MetricAlerts`

#### Input Parameters
* `subscriptionId` - _required_ - The Azure subscription Id.
* `resourceGroupName` - _required_ - The name of the resource group.
* `ruleName` - _required_ - The name of the rule.
* `api-version` - _required_ - Client Api Version.

### Retrieve an alert rule status.

*Tags:* `MetricAlertsStatus`

#### Input Parameters
* `subscriptionId` - _required_ - The Azure subscription Id.
* `resourceGroupName` - _required_ - The name of the resource group.
* `ruleName` - _required_ - The name of the rule.
* `api-version` - _required_ - Client Api Version.

### Retrieve an alert rule status.

*Tags:* `MetricAlertsStatus`

#### Input Parameters
* `subscriptionId` - _required_ - The Azure subscription Id.
* `resourceGroupName` - _required_ - The name of the resource group.
* `ruleName` - _required_ - The name of the rule.
* `statusName` - _required_ - The name of the status.
* `api-version` - _required_ - Client Api Version.

## License

**flow**ground :- Telekom iPaaS / azure-com-monitor-metric-alert-api-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
