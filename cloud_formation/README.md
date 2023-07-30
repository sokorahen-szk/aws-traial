# aws-traial

## cloudFormation

### Stack 作成

aws cloudformation deploy \
 --template ./vpc/create_vpc.json \
 --stack-name vpc-test \
 --parameter-overrides SampleVPCCidr=192.168.0.0/16

### Stack 削除

aws cloudformation delete-stack \
 --stack-name vpc-test
