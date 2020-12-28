# mysql-container
 MySql 5.7, 8.0.2

# PreRequesite
1. Install Docker Desktop
On Windows:
  Make sure you have WSL 2 version set as default.
  Install Windows Terminal
  
# How To

1. Copy env.example to create a .env file
2. Go to Terminal and run
   - docker-compose -p {projectname} up  (Run the services)
   
   Other Helpful commands
     - docker-compose -p {projectname} stop (Stop the service)
     - docker-compose -p {projectname} build  (Build/Rebuild the image)
     - docker-compose -p {projectname} ps (Check the project status or state)
   
   -- check with google to search for more docker commands

# Default port & access
## mysql 5.7
> - host: localhost
> - port: 3306
 
## mysql 8.0.2
> - host:localhost
> - port: 3308
 
## Default Access
- username: root
- password: "set to env file"

## Adminer Access
- http://localhost:8082
- mysql 8.0.2 access server : mysql-dev
- mysql 5.7 access server :  mysql-legacy
