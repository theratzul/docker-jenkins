### Install docker debian
sudo apt install docker.io  
sudo systemctl enable docker  
sudo usermod -aG docker bogdan  
docker ps  

### Install docker-compose  
curl -SL https://github.com/docker/compose/releases/download/v2.24.5/docker-compose-linux-x86_64 -o ~/kits/docker-compose  
chmod +x ~/kits/docker-compose  

### Install Jenkins  
docker pull jenkins/jenkins  
docker info |grep -i root  
