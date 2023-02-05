# WEB STACK IMPLEMENTATION ( LEMP STACK )

### - Developing Web Solutions using LEMP stack

### Preparing Prerequisites :
### Create a new EC2 instance of t2.nano family with ubuntu server 22.04 LTS (HVM) image.


### SSH into the created EC2 instance
`ssh -i "abass2-ec2.pem" ubuntu@ec2-3-15-208-30.us-east-2.compute.amazonaws.com`

# STEP 1 - INSTALL NGINX WEB SERVER
## Update the Server's package index
`sudo apt update`
`sudo apt install nginx`
![install nginx](/images/install-nginx.PNG)

## Verify NGINX installation
`sudo systemctl status nginx`
![verify nginx](./images/verify-nginx.PNG)

## Test the NGINX server from the web
`http://<Public-IP-Address>:80`
![nginx web](./images/nginxe-web.PNG)

