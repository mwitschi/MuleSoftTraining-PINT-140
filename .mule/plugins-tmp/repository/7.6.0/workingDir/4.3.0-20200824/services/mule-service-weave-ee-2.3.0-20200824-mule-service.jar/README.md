DataWeave - Support 2.3.0
===========
Update: 2.3.0-20200824

## Patches Release Notes

| Issue | Description |
|----------------|----------------|
|**SE-15904**| Fixes CSE reducing two expression without taking into account middle nodes. |
|**SE-15918**| Adding support for escaped char sequences on settings.|
|**SE-16292**| Json with spaces after array value was failing in in-memory parser.|
|**SE-16389**| Nested Dynamic Objects is skipping elements.|
|**SE-16381**| Add an alternative migration to date - date for 4.3.x|
|**SE-16431**| Cache compiled expressions based on string script|
|**SE-16468**| Map with value null should not be ignored|
|**SE-15453**| Includes a new property to handle the escaping of `>` in the XML module.|
|**SE-16915**| Remove troubleshooting log mistakenly introduced as part of SE-16389.|
|**SE-16539**| Fixes error while parsing JSON with whitespaces between array elements. |
|**SE-15894**| Json Binary is not encoded into string the same way as 2.1.x|
|**SE-16462**| Single Key Value Pair was not parsed correctly when mixed with conditional|
|**SE-16620**| Avro Should take into account logical types for conversion of types|
|**SE-16534**| Adding support for mule.verbose.exceptions to print DW addintional stacktrace exception|
|**SE-15362**| Fixes NPE in XML module.|
|**SE-16534**| Adding support for mule.verbose.exceptions to print DW additional stacktrace exception|
|**SE-15249**| Attribute selector not dispatching to the correct implementation|
|**SE-15834**| Don't store the inferred type as outputMimetype but as a property. So that TypedValues always return the typed value.|
|**DW-184**  | Write function should keep the correct mimeType and also keep the original inferred mimeType|
|**SE-17193**| Fix deployment freeze when having several nested function calls such as ++|

