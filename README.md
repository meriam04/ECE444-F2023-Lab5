# Meriam Fourati Lab 5: Test-Driven Development

## Link to Unit Test in Blue Surf
I added a unit test to ensure that database fields can be updated once they have been committed. View the unit test [here](https://github.com/ECE444-2023Fall/Blue-Surf/blob/143daf231fc114648353a94417b6b51d8637e971/backend/tests/test_database.py#L77-L104)
## Pros and Cons of TDD
Here are a few pros and cons for test-driven development:
### Pros

- **Specification Clarification**: TDD ensures a clear understanding of software requirements by writing tests before code, clarifying expected behavior.

- **Early Issue Detection**: It helps catch and address issues at an early stage, reducing the accumulation of bugs and maintaining high code quality.

- **Regression Testing**: TDD enables confident refactoring and modifications, as existing functionality is automatically validated by tests.

- **Documentation**: Test cases can serve as practical documentation, providing examples of how code is supposed to work.

- **Design Improvement**: It often results in better software design, with modular and loosely-coupled code for improved maintainability and extensibility.

### Cons

- **Initial Time Investment**: TDD may seem slower initially due to writing tests before coding, which can be a drawback in fast-paced projects.

- **Learning Curve**: Developers may need to adapt to a new mindset and learn how to write effective tests.

- **Maintenance Overhead**: Managing a suite of tests can be time-consuming, requiring updates when requirements change.

- **False Sense of Security**: A comprehensive test suite doesn't guarantee a bug-free product as it relies on the understanding of requirements.

- **Over-testing**: Over-testing can lead to unnecessary complexity and reduced productivity by focusing on trivial code.

- **Test Fixation**: Developers might overly focus on passing tests, potentially overlooking other critical aspects of the software.
