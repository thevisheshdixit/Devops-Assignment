# DevOps Assignment

## AWS Services Used

- EC2
- Security Group

## Linux Commands

sudo apt update

sudo apt install nginx

systemctl status nginx

systemctl restart nginx

df -h

free -h

top

## Website Deployment

Installed nginx.

Replaced default page.

Hosted custom HTML.

Website available on EC2 Public IP.

## Bonus Task

### Elastic IP

Allocated and associated an Elastic IP with the EC2 instance to ensure a static public IP.

### Shell Script

Created a shell script (`restart_nginx.sh`) to restart the Nginx service and verify its status.

Run using:

bash
chmod +x restart_nginx.sh
./restart_nginx.sh

### Docker Commands

bash
sudo apt install docker.io -y
sudo systemctl status docker
sudo docker run hello-world
sudo docker ps -a
