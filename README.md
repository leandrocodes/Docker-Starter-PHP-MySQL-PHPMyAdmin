### Make sure that you have **docker** and **docker-compose** installed in your system.

#### If not, follow the instructions to install it on your machine (Linux, macOS or Windows)
[Install docker](https://docs.docker.com/install/)

[Install docker-compose](https://docs.docker.com/compose/install/)

## Follow the steps to build up a complete PHP environment
    git clone https://github.com/leandrocodes/Docker-Starter-PHP-MySQL-PHPMyAdmin.git
    
    cd Docker-Starter-PHP-MySQL-PHPMyAdmin/

    sudo docker-compose up -d

And voah-la! After installation complete, you will have an awesome docker container with PHP, PHPMyAdmin and MySQL!

#### Your PHP source code will be handled at `www` folder
#### PHP will run at `localhost:8001`
#### MySQL will run at `localhost:3306`
#### PHPMyadmin will run at `localhost:8000`

### To stop the server, run the following command line:  
    sudo docker-compose stop

### To run it again:  
    sudo docker-compose start