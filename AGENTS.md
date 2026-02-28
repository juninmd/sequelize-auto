```markdown
# AGENTS.md - AI Coding Agent Guidelines

These guidelines are designed to ensure the consistent, high-quality development of AI coding agents within this repository. Adherence to these principles is mandatory for all development efforts.

## 1. DRY (Don't Repeat Yourself)

- All code should be reusable through functions, modules, or components.
- Avoid duplicating logic or data structures across different files.
- When necessary, create reusable functions or classes with well-defined interfaces.
- Favor single responsibility principles in individual components.

## 2. KISS (Keep It Simple, Stupid)

- Code should be as concise and readable as possible.
- Avoid unnecessary complexity.
- Prioritize clarity and maintainability.
- Strive for straightforward solutions to problems.

## 3. SOLID Principles

- **Single Responsibility Principle:** Each class/component should have one, and only one, reason to change.
- **Open/Closed Principle:** The system should be extensible without modifying its existing code.  New features should be added through new classes/components, not by modifying the core code.
- **Liskov Substitution Principle:**  Subclasses should be substitutable for their base classes without altering the correctness of the program.
- **Interface Segregation Principle:**  Clients should not be forced to depend on methods they don't use.
- **Dependency Inversion Principle:** Client code should not depend on implementation details.  They should depend on abstractions.

## 4. YAGNI (You Aren't Gonna Need It)

-  Implement only the necessary features and functionalities required for the current task.
-  Avoid adding features or logic that are not currently required.
-  Focus on achieving the desired outcome without unnecessary complexity or side effects.

## 5. Code Structure & Organization

- **File Size Limit:** Each file must be no more than 180 lines of code.
- **Modular Design:**  Break down large files into logical modules with well-defined interfaces.
- **Comments:** Provide clear and concise comments explaining complex logic, assumptions, and design choices.  Comments should clearly relate to the purpose of the code.
- **Naming Conventions:**  Use consistent and meaningful naming conventions (e.g., camelCase, snake_case).
- **Documentation:**  Include a brief description (1-2 lines) of each file's purpose at the top of each file.

## 6. Testing & Coverage

- **Unit Tests:** All code must have at least 80% test coverage.
- **Integration Tests:**  Comprehensive integration tests should be performed to ensure correct interactions between components.
- **Test Driven Development:** Tests should be written *before* the code being tested, providing the necessary preconditions.
- **Mocking:**  All mocks and fake implementations should be utilized exclusively for testing.  No real data is to be used in testing.
- **Automated Tests:** All tests must be automated and run as part of the CI/CD pipeline.

## 7.  Specific Requirements

- **Agent Initialization:**  All agent code must include a clear initialization sequence.
- **Data Handling:**  Strict adherence to data contracts and formats is required.
- **Error Handling:**  Implement robust error handling mechanisms with informative error messages.
- **Logging:**  Use logging effectively to track events, errors, and debugging information.
- **API Design:**  All API endpoints should be well-documented and follow best practices.


## 8.  Code Style & Formatting

-  Consistent indentation and spacing.
-  Use a code formatter (e.g., black, prettier) to ensure readability.
-  Follow established style guidelines.

## 9.  Commit Practices

- All commits must be accompanied by a clear commit message explaining the change being made.
-  Small, focused commits.
-  Code review process is mandatory.


## 10.  Dependencies

- All dependencies must be managed through a dependency management system (e.g., Poetry, Pipenv).
- Ensure dependencies are up-to-date.
- Dependency versioning is crucial.



This document is a living guide and may be updated as needed to reflect evolving best practices.
```