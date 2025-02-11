sudo su
apt update
apt upgrade -y
apt install openjdk-21-jdk -y
mkdir buildmc
cd buildmc
wget "jar link"
java -Xmx12288M -Xms12288M -jar jar_name.jar nogui
