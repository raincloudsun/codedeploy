# Auto Setup for CodeDeploy Agent






```ruby
]$ aws ec2 describe-instances --filters "Name=tag-key,Values=Deploy" | grep InstanceId
                    "InstanceId": "i-0xxxxxxxxxxx",
                    "InstanceId": "i-1xxxxxxxxxxx",
                    
```
