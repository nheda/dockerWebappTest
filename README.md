# dockerWebappTest

mkdir dockerfile

cd dockerfile/

vim Dockerfile

--- edit the file

docker build -t my-webapp .

docker images

docker run -itd --name web-host -p 5004:8080 my-webapp

docker exec -it web-host service tomcat7 start
