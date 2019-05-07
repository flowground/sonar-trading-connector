# ![LOGO](logo.png) Sonar Trading **flow**ground Connector

## Description

A generated **flow**ground connector for the Sonar Trading API (version 1.0).

Generated from: https://api.apis.guru/v2/specs/sonar.trading/1.0/swagger.json<br/>
Generated at: 2019-05-07T17:44:08+03:00

## API Description

Currency Authority: Exchange Rate of 1453 country currencies and crypto currencies

## Authorization

This API does not require authorization.

## Actions

### Convert a currency amount to multiple other currencies

*Tags:* `Currencies`

#### Input Parameters
* `from` - _required_ - Currency you want to convert. For example, EUR
* `to` - _required_ - Comma separated list of currencies codes. For example, USD
* `amount` - _optional_ - This parameter can be used to specify the amount you want to convert. If an amount is not specified then 1 is assumed.
* `decimal_places` - _optional_ - This parameter can be used to specify the number of decimal places included in the output. If an amount is not specified then 12 is assumed.

### Return a list of all currencies of countries, available via service

*Tags:* `Currencies`

#### Input Parameters
* `language` - _optional_ - Parameter used to specify the language in which you would like the currency names to be provided. If not specified, EN is used. Now availeble only EN language.

### Return a list of all digital currencies, available via service

*Tags:* `Currencies`

#### Input Parameters
* `language` - _optional_ - Parameter used to specify the language in which you would like the currency names to be provided. If not specified, EN is used. Now availeble only EN language.

### Return a historic rate for a currencies

*Tags:* `Currencies`

#### Input Parameters
* `from` - _required_ - Currency you want to convert. For example, EUR
* `to` - _required_ - Comma separated list of currencies codes. For example, USD
* `date` - _required_ - UTC date should be in the form of YYYY-MM-DD, for example, 2018-06-20. Data available from 2018-06-19 only.
* `amount` - _optional_ - This parameter can be used to specify the amount you want to convert. If an amount is not specified then 1 is assumed.
* `decimal_places` - _optional_ - This parameter can be used to specify the number of decimal places included in the output. If an amount is not specified then 4 is assumed.

## License

**flow**ground :- Telekom iPaaS / sonar-trading-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
