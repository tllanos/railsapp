# README


Things you may want to cover:

* Ruby version *

  >= 5.0.0.1

* System dependencies *

  docker-compose version 1.10.0 or higher.

* Configuration *

  All configurations needed to run the project are properly set up and can
  be changed by modifying the following files:

     ./Gemfile: A format for describing gem dependencies for Ruby programs.
     
     ./Dockerfile: A text document that contains all the commands a user
     could call on the command line to assemble an image.
     
     ./docker-compose.yml: YAML file defining services, networks and volumes.
     
     ./config/database.yml: YALM file defining database type and its configurations.
     
     ./config/puma.rb: Ruby file defining general Puma Server configurations.

* Deployment instructions *

  Run the "docker-compose build" command in order to build the required services.
  REMARK: It will read the "Dockerfile" to know which orders to execute.

  Run the "docker-compose up" command, which aggregates the output of each container.
  When the command exits (by pressing Ctrl + C), all containers are stopped.

  Once "Puma" is running, you will have to open a web-browser and go to
  http://localhost:300/notes in order to interact with the web-page.
