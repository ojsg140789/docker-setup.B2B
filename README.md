# B2B

## Related repos

[Front-end](https://github.com/ojsg140789/angular.front.b2b-take-home)

[Back-end](https://github.com/ojsg140789/Api.B2B)

[Database](https://github.com/ojsg140789/DB.B2B)

## Related images

[Front-end](https://hub.docker.com/repository/docker/omarjsg/b2b-take-home-app/general)

[Back-end]([https://github.com/ojsg140789/Api.B2B](https://hub.docker.com/repository/docker/omarjsg/b2b-take-home-api/general))

[Database]([https://github.com/ojsg140789/DB.B2B](https://hub.docker.com/repository/docker/omarjsg/b2b-take-home-db/general))

## Usage
1.- Clone the repository

    ```bash
      git clone https://github.com/ojsg140789/docker-setup.B2B
      cd docker-setup.B2B
    ```
2.- Important, if you are using the ports:
    - 4200
    - 5089
    - 5432
    You can change the configuration in the docker-compose-yml
    
    ```
      # ports front-end:
        - "4200:4200" 
      # ports back-end:
        - "5098:80" 
      # ports DB:
        - "5432:5432"
    ```
    Change the first value, is the value of your computer

3.- Run the command: 

    ```  
      docker-compose up -d
    ```
4.- Open the browser and see the portal in 

    http://localhost:4200/
    
    (if you changed the port of the front-end adjust it)

5.- You can use the test user already register

    username: user@gmail.com
    password: user123

