docker-compose build
docker-compose up

docker ps

docker exec -it <mycontainer> bash  

docker exec -it   flask_hello_flask_1  bash

docker exec -it   flask_hello_flask_1  python train_model.py

testing  requests via curl
curl  --header "Content-Type: application/json" \
    --request POST \
    --data '{"flower": "1,2,3,7"}' \
    http://localhost:5000/iris_post

testing via postman application


-----
In Dockerfile put 1 worker and debug variable for terminal watching

