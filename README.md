#i done project in virtual box using vagrant .the project deploy in docker-compose container
# Clone source code of Emart App
git clone https://github.com/ghkkdswvgg/emart.git
ls
cd emartapp/
ls

# Bring up  containers from docker-compose file
vim docker-compose.yaml
docker-compose up -d
docker ps
ip addr show

# Go to browser enter http://VMIp:80

# Clean up
docker-compose down
