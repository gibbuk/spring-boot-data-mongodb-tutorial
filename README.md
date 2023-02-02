# Spring Boot Tutorial

<details>
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#about-the-project">About The Project</a></li>
    <li><a href="#built-with">Built With</a></li>
    <li><a href="#getting-started">Getting Started</a></li>
    <li><a href="#problem-statements">Problem Statements</a></li>
    <li><a href="#project-review-and-roadmap">Project Review and Roadmap</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>

---

## About The Project

This is the implementation of [a BezKoder.com tutorial for build a Spring Boot REST API with CRUD functionality using MongoDB and Maven](https://www.bezkoder.com/spring-boot-mongodb-crud/).

The purpose of the project was to familiarise myself with the framework and implementing a simple server in Java before progressing onto using the framework in my own projects.

The server stores Tutorials (consisting of details about courses) in MongoDB.

---

## Built With

Built in `java 8`  using `Spring Boot 2.6.3` and `Maven`.

## Getting Started

1. Clone the repo.

2. Open the project in the IDE of your choice and obtain dependencies via Maven (e.g. `mvn clean dependency:copy-dependencies`)

3. Ensure you have MongoDB running on `localhost:27012`.

4. `mvn spring-boot:run` to run the server.

5. The server runs on `localhost:8080`. Use an HTTP client (e.g. Postman) to make requests to the server. 

---

## Problem Statements

Produce a REST API server in Java and Spring Boot that is capable of CRUD resources on a MongoDB database.

---

## Project Review and Roadmap

My key learnings from project:

- Spring Boot basic concepts such as initializing the project skeleton using [https://start.spring.io/](https://start.spring.io/). Updating the `pom.xml` to ensure correct dependencies and versions are used. As I was using Java 8 this was important as Spring Boot requires newer versions of Java from version 3.
- Mapping my understanding of server creation using `Node.js` and `Express` into `Spring`. E.g. Express uses routes whereas Spring defines a RestController to do similar. Models carry out similar functions in defininig the strucutre of the data and are used to create links to the desired MongoDB collection. 
- Extending Spring Data's `MongoRepositry` interface in order to provide additional customer functions to interact with the database.

---

## Acknowledgments
- BezKoder.com for providing the tutorial!
