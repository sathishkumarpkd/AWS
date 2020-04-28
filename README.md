# AWS
https://calculator.s3.amazonaws.com/index.html
https://aws.amazon.com/solutions/case-studies/all/


sudo apt-get update
sudo apt-get upgrade -y
sudo apt-get install apache2 -y

cd /var/www/htmlrm *

sudo nano index.html
<h1>Whatever you want</h1>
Ctrl + X, Y, Enter


efs
1  apt-get update
    2  apt-get upgrade -y
    3  apt-get install nfs-common
    4  sudo mkdir efs
    5  ls
    6  sudo mount -t efs fs-dc2c9c5d:/ efs
    7  sudo mount -t nfs4 -o nfsvers=4.1,rsize=1048576,wsize=1048576,hard,timeo=600,retrans=2,noresvport fs-dc2c9c5d.efs.us-east-1.amazonaws.com:/ efs
    8  ls
    9  cd efs/
   10  df -h
   11  nano testfile
   12  ls -al
   13  wget http://releases.ubuntu.com/18.04.3/ubuntu-18.04.3-desktop-amd64.iso
   14  df -h
   15  ls -al
   16  df -h
   17  history

lscpu
EC2 works on XEN Hypervisor


Increasing Load: yes > /dev/null &
from Chinmay Anaokar to All Participants:
Decreasing Load: sudo killall yes

https://pastebin.com/NqKYWJy6

https://aws.amazon.com/getting-started/projects/build-serverless-web-app-lambda-apigateway-s3-dynamodb-cognito/

https://docs.aws.amazon.com/cli/latest/reference/index.html#cli-aws

https://docs.aws.amazon.com/AmazonS3/latest/dev/UploadingObjects.html (Multpart upload)

http://simplilearn-demo-website.s3-website-us-east-1.amazonaws.com: static webhosting.

{
    "Version": "2012-10-17",
    "Statement": [
        {
            "Sid": "PublicReadGetObject",
            "Effect": "Allow",
            "Principal": "*",
            "Action": "s3:GetObject",
            "Resource": "arn:aws:s3:::simplilearn-demo-website/*"
        }
    ]
}

page load time plugin

https://d3es8mviu9a3xr.cloudfront.net/

https://docs.aws.amazon.com/AmazonS3/latest/dev/NotificationHowTo.html : SNS
https://docs.aws.amazon.com/AmazonS3/latest/dev/NotificationHowTo.html

https://docs.aws.amazon.com/AmazonS3/latest/dev/Versioning.html#MultiFactorAuthenticationDelete  : mfa delete

https://github.com/aws-samples/aws-serverless-workshops/tree/master/WebApplication/1_StaticWebHosting/website : static web

git hub from aakash:

https://github.com/Aakashdeveloper

https://rainbowspuppiessunshine.com/tools/dbtest/

https://aws.amazon.com/getting-started/projects/boosting-mysql-database-performance-with-amazon-elasticache-for-redis/

https://docs.aws.amazon.com/cloudformation/

https://aws.amazon.com/certification/certified-solutions-architect-associate/

https://d1.awsstatic.com/training-and-certification/docs-sa-assoc/AWS_Certified_Solutions_Architect_Associate-Exam_Guide_EN_1.8.pd

imggur

 https://www.mouthshut.com/websites/Simplilearn-com-reviews-925669028-srch 

https://www.quora.com/topic/Simplilearn/top_questions

https://www.google.co.in/maps/place/Simplilearn/@12.9029488,77.6459338,17z/data=!3m1!4b1!4m10!1m2!2m1!1ssimplilearn+address+hsr!3m6!1s0x3bae149f4c3c0001:0x5ff9ef635c7efe1a!8m2!3d12.9029122!4d77.6481761!9m1!1b1


