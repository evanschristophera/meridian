# meridian
meridian research


1. Install WSL Ubuntu distro
```PS
wsl --install Ubuntu-24.04
```

1. Install Docker
   
    [Instructions are here](https://docs.docker.com/engine/install/ubuntu/)

   1. [Do post install so the ubuntu user can run docker and docker daemon starts on boot](https://docs.docker.com/engine/install/linux-postinstall/)
  
   
1. Modify Windows ~/.wslconfig file to allocate processors and memory.  [Example](/exampleConfigurationFiles/Windows_user_directory/.wslconfig)

2. Modify
    1. boot and other options

        [/etc/wsl.conf](/exampleConfigurationFiles/ubuntu/wsl.conf)

    1. Add host name from wsl.conf to make su work correctly    

        [/etc/hosts](/exampleConfigurationFiles/ubuntu/hosts)


