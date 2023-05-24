
![node-docker-logo](https://github.com/fabiobatoni/modelo-docker/assets/57717982/ede9ad0a-5067-47e5-ac41-00b7c10ccdb6)


# Instalar Docker no Linux 
https://docs.docker.com/engine/install/ubuntu/

https://www.vivaolinux.com.br/dica/Instalacao-do-Docker-no-Linux-Mint-20

# modelo-docker
template docker - NodeJS

# criar package json
npm init -y
npm install nodemon

# criar arquivos
touch index.js
touch Dockerfile

# instalar express
npm install express


# Criar docker
sudo docker build -t @nomedocontainer/projeto . 


# Rodar aplicação 
docker run -p @porta:@portacontainer -d @nomedocontainer/projeto

# Visualizar projeto rodando
docker ps

# docker-compose up
