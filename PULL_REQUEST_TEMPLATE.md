Please make sure to provide all the fields! Example below!

* Service: 
* Action: 
* Action documentation: 
* Resources:
* Conditions: 
* Source: 

## Example

* Service: ec2
* Action: DeleteCustomerGateway
* Action documentation: http://docs.aws.amazon.com/AWSEC2/latest/APIReference/API_DeleteCustomerGateway.html
* Resources: arn:aws:ec2:region:account:customer-gateway/*, arn:aws:ec2:region:account:customer-gateway/cgw-id
* Conditions: ec2:Region, ec2:ResourceTag/tag-key
* Source: http://docs.aws.amazon.com/AWSEC2/latest/APIReference/ec2-api-permissions.html