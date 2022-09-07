- command to deploy stack from CLI: 

aws cloudformation create-stack --stack-name testclistack --template-body file://13-04-RootStack-EC2-SG.yml --parameters file://param.json

- command to delete stack from CLI:

aws cloudformation delete-stack --stack-name testclistack
