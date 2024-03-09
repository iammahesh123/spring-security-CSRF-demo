# Spring Security CSRF Demo

This project demonstrates how to integrate CSRF protection in a Spring Boot application using Spring Security.

## Overview

Cross-Site Request Forgery (CSRF) is a type of attack that tricks the user's browser into performing an unwanted action on a trusted site where the user is authenticated. Spring Security provides built-in support for CSRF protection to mitigate such attacks.

In this demo, we'll showcase how to configure and use CSRF protection in a Spring Boot application.

## Features

- Integration of Spring Security with CSRF protection
- Customization of CSRF token handling and behavior
- Demonstration of how to secure endpoints against CSRF attacks

## Project Structure

- `src/main/java`: Contains the Java source code for the Spring Boot application.
- `src/main/resources`: Contains configuration files and static resources.
- `pom.xml`: Maven project configuration file.

## Usage

1. Clone the repository:

```bash
git clone https://github.com/your-username/spring-security-csrf-demo.git
```
2. Navigate to the project directory:
 ```bash
  cd spring-security-csrf-demo
 ```
3. Build the project using Maven:
 ```bash
mvn clean package
 ```
4. Run the application:
```bash
mvn run
 ```
5. Access the application in your web browser: http://localhost:8080
6. Try accessing protected endpoints and observe how CSRF protection works.
## Configuration
- application.properties: Contains application-specific configurations.
- SecurityConfig.java: Spring Security configuration class where CSRF protection is enabled and customized.
## Dependencies
- Java 8 or higher
- Spring Boot
- Spring Security
## Contributing
Contributions are welcome. Please fork the repository, make your changes, and submit a pull request.

## License
This project is licensed under the MIT License. 

