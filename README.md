# Power Workshop Assessment Task

Task I
------------

Build Docker Image
``` bash
docker build -t pranaya123/php-hello-world:latest .
```

Run Docker Image
``` bash
docker run -dp 0.0.0.0:8080:8080 php-hello-world
```

Build and Run Docker Image using docker-compose
``` bash
docker-compose build
docker-compose up -d
```

Output

![image1](https://github.com/pra-naya/php-hello-world/assets/85820204/a8e7fd1f-aa0e-4619-9b8f-054a0da7949d)


Login to DockerHub
``` bash
docker login
```

Push Image to DockerHub
``` bash
docker push pranaya123/php-hello-world:latest
```
![image3](https://github.com/pra-naya/php-hello-world/assets/85820204/8a3b8de2-c614-4a61-b5bb-0c4058833d2f)


Task II
------------

Configure GitHub Actions
![image2](https://github.com/pra-naya/php-hello-world/assets/85820204/acb3c420-316a-45a5-a03f-439bc3207faf)
