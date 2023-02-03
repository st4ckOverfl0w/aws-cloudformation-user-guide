# AWS::ApiGatewayV2::ApiGatewayManagedOverrides RouteOverrides<a name="aws-properties-apigatewayv2-apigatewaymanagedoverrides-routeoverrides"></a>

The `RouteOverrides` property overrides the route configuration for an API Gateway\-managed route\. If you remove this property, API Gateway restores the default values\.

## Syntax<a name="aws-properties-apigatewayv2-apigatewaymanagedoverrides-routeoverrides-syntax"></a>

To declare this entity in your AWS CloudFormation template, use the following syntax:

### JSON<a name="aws-properties-apigatewayv2-apigatewaymanagedoverrides-routeoverrides-syntax.json"></a>

```
{
  "[AuthorizationScopes](#cfn-apigatewayv2-apigatewaymanagedoverrides-routeoverrides-authorizationscopes)" : [ String, ... ],
  "[AuthorizationType](#cfn-apigatewayv2-apigatewaymanagedoverrides-routeoverrides-authorizationtype)" : String,
  "[AuthorizerId](#cfn-apigatewayv2-apigatewaymanagedoverrides-routeoverrides-authorizerid)" : String,
  "[OperationName](#cfn-apigatewayv2-apigatewaymanagedoverrides-routeoverrides-operationname)" : String,
  "[Target](#cfn-apigatewayv2-apigatewaymanagedoverrides-routeoverrides-target)" : String
}
```

### YAML<a name="aws-properties-apigatewayv2-apigatewaymanagedoverrides-routeoverrides-syntax.yaml"></a>

```
  [AuthorizationScopes](#cfn-apigatewayv2-apigatewaymanagedoverrides-routeoverrides-authorizationscopes): 
    - String
  [AuthorizationType](#cfn-apigatewayv2-apigatewaymanagedoverrides-routeoverrides-authorizationtype): String
  [AuthorizerId](#cfn-apigatewayv2-apigatewaymanagedoverrides-routeoverrides-authorizerid): String
  [OperationName](#cfn-apigatewayv2-apigatewaymanagedoverrides-routeoverrides-operationname): String
  [Target](#cfn-apigatewayv2-apigatewaymanagedoverrides-routeoverrides-target): String
```

## Properties<a name="aws-properties-apigatewayv2-apigatewaymanagedoverrides-routeoverrides-properties"></a>

`AuthorizationScopes`  <a name="cfn-apigatewayv2-apigatewaymanagedoverrides-routeoverrides-authorizationscopes"></a>
The authorization scopes supported by this route\.  
*Required*: No  
*Type*: List of String  
*Update requires*: [No interruption](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/using-cfn-updating-stacks-update-behaviors.html#update-no-interrupt)

`AuthorizationType`  <a name="cfn-apigatewayv2-apigatewaymanagedoverrides-routeoverrides-authorizationtype"></a>
The authorization type for the route\. To learn more, see [AuthorizationType](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-resource-apigatewayv2-route.html#cfn-apigatewayv2-route-authorizationtype)\.  
*Required*: No  
*Type*: String  
*Update requires*: [No interruption](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/using-cfn-updating-stacks-update-behaviors.html#update-no-interrupt)

`AuthorizerId`  <a name="cfn-apigatewayv2-apigatewaymanagedoverrides-routeoverrides-authorizerid"></a>
The identifier of the `Authorizer` resource to be associated with this route\. The authorizer identifier is generated by API Gateway when you created the authorizer\.  
*Required*: No  
*Type*: String  
*Update requires*: [No interruption](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/using-cfn-updating-stacks-update-behaviors.html#update-no-interrupt)

`OperationName`  <a name="cfn-apigatewayv2-apigatewaymanagedoverrides-routeoverrides-operationname"></a>
The operation name for the route\.  
*Required*: No  
*Type*: String  
*Update requires*: [No interruption](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/using-cfn-updating-stacks-update-behaviors.html#update-no-interrupt)

`Target`  <a name="cfn-apigatewayv2-apigatewaymanagedoverrides-routeoverrides-target"></a>
For HTTP integrations, specify a fully qualified URL\. For Lambda integrations, specify a function ARN\. The type of the integration will be HTTP\_PROXY or AWS\_PROXY, respectively\.  
*Required*: No  
*Type*: String  
*Update requires*: [No interruption](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/using-cfn-updating-stacks-update-behaviors.html#update-no-interrupt)