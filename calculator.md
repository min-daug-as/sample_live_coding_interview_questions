## Live Coding Task: Building a C# Calculator Application

**Task:** Create a calculator application using C# and object-oriented programming (OOP) principles, adhering to SOLID principles. The calculator should be able to evaluate **mathematical expressions** entered as strings.

**Requirements:**
* **Language:** C#
* **Framework:** .NET Framework or .NET Core
* **Functionality:**
  * Accept a **mathematical expression** as a string (e.g., "1 - 3 + 8").
  * Evaluate the expression and provide the result.
  * Support basic arithmetic operations (+, -, *, /).
* **Design Principles:** Adhere to **OOP** and **SOLID** principles (Single Responsibility, Open-Closed, Liskov Substitution, Interface Segregation, Dependency Inversion).
* **Design Patterns:** Consider implementing at least one design pattern (e.g., Factory, Singleton, Strategy) to improve code structure and maintainability.

**Evaluation Criteria:**

| Criteria | Weight | Description |
|---|---|---|
| **Functionality** | 30% | Correctly evaluates mathematical expressions. |
| **Code Quality** | 30% | Adheres to SOLID principles, OOP principles, is well-structured, and uses meaningful naming conventions. |
| **Design Patterns** | 20% | Implements a relevant design pattern effectively. |
| **Error Handling** | 10% | Handles potential errors (e.g., invalid expressions, division by zero) gracefully. |
| **User Interface** | 10% | Provides a basic and user-friendly interface (e.g., console-based). |

**Estimated Time to Complete:** 90-120 minutes

**Example Input/Output:**

```
Enter a mathematical expression: 1 - 3 + 8
Result: 6
```

**Tips:**
* **Single Responsibility:** Create separate classes for different responsibilities (e.g., a `Token` class, an `ExpressionEvaluator` class, an `Operator` class).
* **Open-Closed:** Design classes to be open for extension but closed for modification (e.g., use inheritance or interfaces to add new operators).
* **Liskov Substitution:** Ensure that derived classes can be substituted for base classes without affecting the correctness of the program.
* **Interface Segregation:** Avoid forcing clients to depend on interfaces they don't use (e.g., create smaller, more specific interfaces).
* **Dependency Inversion:** Depend on abstractions, not concretions (e.g., use interfaces or abstract classes).
* Use a parser or regular expressions to break down the expression into tokens (numbers, operators).
* Implement a stack-based algorithm (e.g., Shunting-yard algorithm) to evaluate the expression.
* Consider creating separate classes for operators and operands.
* Use a factory pattern to create operator instances dynamically.
* Implement error handling to prevent unexpected behavior (e.g., invalid expressions, division by zero).
* Consider using a simple console-based interface for input and output.

