# SmartQuiz - Interactive Console Application

## 📖 About The Project
SmartQuiz is a console-based interactive quiz application built entirely from scratch using **C# and .NET**. 
This project was created to practice and master **Object-Oriented Programming (OOP)** principles and clean software architecture.

## Architecture
The solution is divided into three separate layers to ensure separation of concerns and maintainability:
*   **`SmartQuiz.Models` (Class Library):** Contains the core data structures, including abstract classes and inheritance (e.g., `Question`, `User`).
*   **`SmartQuiz.Services` (Class Library):** Contains the business logic, such as quiz management, user inputs, and scoring (e.g., `QuizManager`).
*   **`SmartQuiz.ConsoleApp` (Console Application):** The entry point and user interface where the interaction happens.

## Key Features & Concepts Applied
*   **OOP:** Mastery of Inheritance, Polymorphism (`virtual`, `override`), and Abstraction (`abstract`).
*   **Data Structures:** Utilization of `List<T>` and dynamic collections.
*   **Error Handling:** Implementation of `try-catch` blocks to handle invalid user inputs (e.g., entering letters instead of numbers for age).
*   **Clean Code:** Following naming conventions and modular design.

## Built With
*   C#
*   .NET 8.0

## How to Run
1. Clone the repository.
2. Open `SmartQuiz.sln` in Visual Studio.
3. Build and run the `SmartQuiz.ConsoleApp` project.

## Future Roadmap (Coming Soon)
- [ ] Reading questions from an external JSON/TXT file.
- [ ] Connecting to a SQL Database using Entity Framework Core.
- [ ] Building a Web API using ASP.NET Core.
- [ ] Creating a graphical user interface (UI).

## Author
**Mohammad** - Aspiring Software Engineer.
