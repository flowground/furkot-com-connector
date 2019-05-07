# ![LOGO](logo.png) Furkot Trips **flow**ground Connector

## Description

A generated **flow**ground connector for the Furkot Trips API (version 1.0.0).

Generated from: https://api.apis.guru/v2/specs/furkot.com/1.0.0/swagger.json<br/>
Generated at: 2019-05-07T17:40:48+03:00

## API Description

Furkot provides Rest API to access user trip data.
Using Furkot API an application can list user trips and display stops for a specific trip.
Furkot API uses OAuth2 protocol to authorize applications to access data on behalf of users.


## Authorization

Supported authorization schemes:
- OAuth2
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### list user's trips

### list stops for a trip identified by {trip_id}

#### Input Parameters
* `trip_id` - _required_ - id of the trip

## License

**flow**ground :- Telekom iPaaS / furkot-com-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
