# Run following command on terminal

docker build -t 101276708_hello_docker .

docker image ls

docker run -p 4000:80 101276708_hello_docker

docker run -d --name=lab11_DevOps -p 4000:80 101276708_hello_docker

docker container stop CONTAINER_ID

docker container ls