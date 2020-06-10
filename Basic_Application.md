- Set up your Docker environment (on this page)
*![Setting up Docker](https://github.com/pyruskimo/G4-Test/blob/master/Docker%20container%20name%20my-hello.png)


- Build and run your image
*![Build and run](https://github.com/pyruskimo/G4-Test/blob/master/Build%20and%20run%20your%20image.png)
*![Share images](https://github.com/pyruskimo/G4-Test/blob/master/Share%20images%20on%20Docker%20Hub.png)



- Share images on Docker Hub
*![share images](https://github.com/pyruskimo/G4-Test/blob/master/Share%20images%20on%20Docker%20Hub.png)

docker container run -it -p 80:80 <image>

-it (Interactive mode)
-ip  (publish)

In order to push an image up on to hub where a repo has been created, tag it - docker tag <image> <repo name> 
