# DockerCheatSheet
Docker Cheat Sheet

## Containers

 ```docker
  docker container run --name sampleContainerName -p 80:80 pathToImage

  docker container run --name sampleContainerName --it -p 80:80 pathToImage sh

  docker container run/exec --it pathToImage sh

  docker container run --it -v existingVolumeName:/foldername imageName/pathToImage  sh     -> connects volume to a folder inside this container.
```

## Volumes

```docker
  docker volume create sampleVolumeName

  docker volume run 
```
 ## Shell Commands

 ls     -> show
 ps     -> shows containers
 echo   -> print
 touch  -> create
 exit
 rm     -> remove
 cat    -> 
