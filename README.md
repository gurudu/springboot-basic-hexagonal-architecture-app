# springboot-web-hexagonal-architecture-app
  Basic springboot rest jpa application implemented following priciples of Hexagonal Architecture and monitored using Prometheus and Grafana.
## Requirements:
   * Java 17 Installed
   * Gradle (or any other build tool for Java)
   * Any Java IDE
   * Docker or Rancher desktop installed and running
   * Testing (Optional): Postman and Tableplus to follow along, but any testing tool will work

## Features
 1. Sample Springboot web app using REST API, JPA, Hibernate
 2. Used Hexagonal architecture for the project
 3. Used techonologies : 
       * JAVA 17
       * Gradle as Build tool
       * Springboot version: 3.1.4
       * PostgreSQL 14
 4. Used Docker (Dockerfile and Docker compose) to containerize the application :
    * commands to use to run the project:
        *  gradle build
        *  docker build -t order_management .
        *   Go to infrastructure directory :
              * start app: docker compose up
              * stop app: docker compose down -v
 5. Monitored using Prometheus and Grafana
 6.  To use Github actions #todo
