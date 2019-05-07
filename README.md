# ![LOGO](logo.png) Japanese WordNet APIs MSP Connector

## Description

A generated MSP connector for the Japanese WordNet APIs API (version 0.0.1).

Generated from: https://api.apis.guru/v2/specs/apitore.com/japaneseWordnetApis/0.0.1/swagger.json<br/>
Generated at: 2019-05-07T11:17:01+03:00

## API Description

Return all WordNet words.<BR />[Endpoint] https://api.apitore.com/api/40

## Authorization

This API does not require authorization.

## Actions

### Simple WordNet WebAPI. Return words such as synonyms, hypernyms, etc...

> Japanese WordNet.<BR />Response<BR />&nbsp; Github: <a href="https://github.com/keigohtr/apitore-response-parent/tree/master/wordnet-response">wordnet-response</a><BR />&nbsp; Class: com.apitore.banana.response.de.sciss.ws4j.LinksResponseEntity<BR />

*Tags:* `wordnet-simple-controller`

#### Input Parameters
* `access_token` - _required_ - Access Token
* `word` - _required_ - Word
* `pos` - _optional_ - Part-of-speech. You can specify several pos by csv format. [n:noun,v:verb,a:adjective,r:adverb]

## License

flowground :- Telekom iPaaS / apitore-com-japanese-wordnet-apis-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
