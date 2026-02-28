```markdown
# AGENTS.md File Guidelines

These guidelines are designed to ensure the development of our AI coding agents follows best practices, promoting maintainability, robustness, and efficiency. Adherence to these principles is mandatory for all development activities.

## 1. DRY (Don't Repeat Yourself)

*   All logic, data structures, and algorithms must be defined in a single, reusable component.
*   Avoid duplicating code across different agents.
*   When a component needs to be reused, it should be implemented as a separate module.
*   Leverage existing libraries and frameworks when appropriate, but avoid unnecessary dependencies.

## 2. KISS (Keep It Simple, Stupid)

*   Prioritize clarity and readability over complex solutions.
*   Strive for minimal code – reduce complexity wherever possible.
*   Use descriptive variable and function names.
*   Avoid overly clever or obscure solutions.
*   Focus on core functionality; avoid unnecessary features.

## 3. SOLID Principles

*   **Single Responsibility Principle:** Each class or module should have a single, well-defined responsibility.
*   **Open/Closed Principle:**  The system should be extensible without modifying its existing code.  New features should be added as separate, independent components.
*   **Liskov Substitution Principle:**  Subclasses should be substitutable for their base classes without altering the correctness of the program.
*   **Interface Segregation Principle:** Clients should not be forced to depend on methods they do not use.
*   **Dependency Inversion Principle:**  High-level modules should not depend on low-level modules.  Interfaces should define the expected contracts.

## 4. YAGNI (You Aren't Gonna Need It)

*   Implement only the functionality explicitly required.
*   Avoid adding features or code that isn’t currently needed.
*   Refactor only when a requirement changes; avoid adding new functionality for the sake of it.
*   Minimize the creation of auxiliary code.

## 5. Code Style & Formatting

*   Follow a consistent code style (e.g., PEP 8 for Python).
*   Use a code formatter (e.g., Black for Python) to automatically enforce formatting rules.
*   Indentation should be consistent (4 spaces).
*   Use blank lines to separate logical blocks of code.
*   Comments should explain the *why* not just the *what*.

## 6. File Structure & Organization

*   Each file should represent a single, self-contained module.
*   File names should be descriptive and follow a consistent pattern (e.g., `agent_module.py`).
*   Include a clear README file at the top explaining the purpose of the file.
*   Separate code into logical sections:  `src/`, `tests/`, `data/`, `docs/` (example).
*   Maintain a dependency graph diagram within the README.

## 7. Test Coverage Requirements

*   Achieve an *minimum* of 80% test coverage.  Coverage will be automatically measured using the provided coverage tool.
*   Include unit tests for all functions and classes.
*   Write integration tests to verify interactions between agents.
*   Focus on testing edge cases and boundary conditions.

## 8. Code Length Restrictions

*   Maximum file length: 180 lines of code.
*   Each module should ideally have a limited number of functions and classes.

## 9. Production-Ready Considerations

*   Prioritize readability and maintainability.
*   Use meaningful variable and function names.
*   Document code thoroughly with docstrings.
*   Include comments to explain complex logic.
*   Consider error handling and logging appropriately.

## 10.  Tools & Technologies

*   Utilize a specific version control system (e.g., Git).
*   Employ a linter for code style and potential errors.
*   Utilize a code formatter.
*   Document dependencies clearly using a format (e.g., `requirements.txt`).


These guidelines are subject to review and updates. Any deviation from these principles will be considered a violation of this document.
```