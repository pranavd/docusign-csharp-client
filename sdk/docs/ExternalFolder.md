# DocuSign.eSign.Model.ExternalFolder
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**EndPosition** | **string** | The last position in the result set.  | [optional] 
**ErrorDetails** | [**ExternalDocServiceErrorDetails**](ExternalDocServiceErrorDetails.md) |  | [optional] 
**Id** | **string** |  | [optional] 
**Items** | [**List&lt;ExternalFile&gt;**](ExternalFile.md) |  | [optional] 
**Name** | **string** |  | [optional] 
**NextUri** | **string** | The URI to the next chunk of records based on the search request. If the endPosition is the entire results of the search, this is null.  | [optional] 
**PreviousUri** | **string** | The postal code for the billing address. | [optional] 
**ResultSetSize** | **string** | The number of results returned in this response.  | [optional] 
**StartPosition** | **string** | Starting position of the current result set. | [optional] 
**TotalSetSize** | **string** | The total number of items available in the result set. This will always be greater than or equal to the value of the property returning the results in the in the response. | [optional] 

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

