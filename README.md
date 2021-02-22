# Automating Docker installation
I will use ansible and create a playbook where I will automate the installation of Docker and run a simple index.html text using Apache on a EC2-instance
For this to work make sure you have boto3 and botocore. This is basically a python dependency that will allow you t write to ec2 & s3 buckets using aws cli.
Also, make sure you add your keys and regions to your .aws config and credentials
