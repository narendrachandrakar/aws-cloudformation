# aws-cloudformation

Commandline to create Stack:
aws cloudformation create-stack --template-body file://AWS_EC2_Instance.yml --stack-name single-instance --parameters ParameterKey=Subnets,ParameterValue=subnet-8aa5cbf0


Delete the exisiting stack:
aws cloudformation delete-stack --stack-name single-instance
