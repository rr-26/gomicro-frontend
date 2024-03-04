# Microservices API development using Hexagonal Architecture in Go

In this project, I have implemented Hexagonal architecture using Golang microservices. 

##### Run `./start.sh` to download the dependencies and run the the application

To run the application, you have to define the environment variables, default values of the variables are defined inside `start.sh`

- SERVER_ADDRESS    `[IP Address of the machine]`
- SERVER_PORT       `[Port of the machine]`
- DB_USER           `[Database username]`
- DB_PASSWD         `[Database password]`
- DB_ADDR           `[IP address of the database]`
- DB_PORT           `[Port of the database]`
- DB_NAME           `[Name of the database]`

# mysql database

1. `docker-compose.yml` file. For creating default data and start all the containers
 
2. `resources/database.sql` this contains the SQL for generating the tables.

# mocks generator
`./generate-mocks.sh`

# run unit tests
  `./run-tests.sh`
