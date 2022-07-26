# DIO: Expert class - Development of unit tests to validate a Beer inventory management REST API

## All code was done during a 'live coding' event, available as a course of the [DIO](https://www.dio.me/) - TQI Fullstack Developer Bootcamp

The main concepts and advantages of creating unit tests with JUnit and Mockito were presented.
The following themes were aproached:

- Download a project through Git to develop our unit tests.
- Conceptual presentation on tests: the test types pyramid, and also the importance of each test type during the development cycle.
- Focus on unit tests: show why it is important to develop these types of tests as part of the software development cycle.
- Main frameworks for unit testing in Java: JUnit, Mockito and Hamcrest.
- Development of unit tests for validation of basic functionalities: creation, listing, query by name and exclusion of beers.
- TDD: presentation and practical example in 2 important features: increase and decrease in the number of beers in stock.

To run the project in the terminal, type the following command:

```shell script
mvn spring-boot:run
```

To run the test suite developed during 'live coding', simply run the following command:

```shell script
mvn clean test
```

After executing the above command, just open the following address and view the project execution:

```browser link
http://localhost:8080/api/v1/beers
```
