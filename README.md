# AWS - Cloud Formation

### AWS resource and property types reference

https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-template-resource-type-ref.html

### Intrinsic function reference

https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/intrinsic-function-reference.html

Use scp command to copy your .pem key from your machine to the the public instance so you can access via ssh the private instance.

scp -i "key.pem" key.pem ubuntu@dns.compute-1.amazonaws.com:
