# Notes

## Ready for environment

- Install Terraform from HashiCorp apt repository.
- Install AWS cli v2 from official zip because the apt package is outdated.
- Set a budjet alert.
- Create IAM user "tf-lab" with priviledge of both no console access and AmazonEC2FullAccess.
- Accesskey has to be created on GUI if it is the first time to create because CLI needs the accesskey.

- Lock file should be better to be added in Git repository.


## Destroy procedures

aws ec2 delete-key-pair --key-name tf-lab-key

