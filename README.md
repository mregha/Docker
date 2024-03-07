## Cara Install Docker
1. wget https://download.docker.com/linux/debian/gpg
2. apt-key add gpg 
3. nano /etc/apt/sources.list.d/docker.list
4. apt-get update -y
5. apt install docker-ce -y

6. Cek status docker
	systemctl status docker
	
	
''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''
# Kalau Error
''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''''

1. sudo apt update
2. sudo apt install apt-transport-https ca-certificates curl gnupg2 software-properties-common
3. curl -fsSL https://download.docker.com/linux/debian/gpg | sudo apt-key add -
4. sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/debian $(lsb_release -cs) stable"
5. sudo apt update
6. apt-cache policy docker-ce
7. sudo apt install docker-ce

8. Cek status docker
	systemctl status docker
