# ![LOGO](logo.png) Provider API Client **flow**ground Connector

## Description

A generated **flow**ground connector for the Provider API Client API (version 2018-02-01).

Generated from: https://api.apis.guru/v2/specs/azure.com/web-Provider/2018-02-01/swagger.json<br/>
Generated at: 2019-05-07T17:39:24+03:00

## API Description



## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Get available application frameworks and their versions

*Tags:* `Provider`

#### Input Parameters
* `osTypeSelected` - _optional_
    Possible values: Windows, Linux, WindowsFunctions, LinuxFunctions.
* `api-version` - _required_ - API Version

### Gets all available operations for the Microsoft.Web resource provider. Also exposes resource metric definitions

*Tags:* `Provider`

#### Input Parameters
* `api-version` - _required_ - API Version

### Get available application frameworks and their versions

*Tags:* `Provider`

#### Input Parameters
* `osTypeSelected` - _optional_
    Possible values: Windows, Linux, WindowsFunctions, LinuxFunctions.
* `subscriptionId` - _required_ - Your Azure subscription ID. This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000).
* `api-version` - _required_ - API Version

## License

**flow**ground :- Telekom iPaaS / azure-com-web-provider-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
