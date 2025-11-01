# Java-Lambda-Stream-Examples

A comprehensive collection of Java programs demonstrating the use of lambda expressions and stream operations for common data processing tasks.

## Overview

This repository contains three distinct Java projects that showcase modern Java features including lambda expressions, functional interfaces, and the Stream API. Each project focuses on practical applications of these concepts.

## Projects

### Part A: EmployeeSort
**Sorting Employee Objects Using Lambda Expressions**

**Objective:** To develop a Java program that sorts a list of Employee objects based on various fields like name, age, or salary using lambda expressions.

**Features:**
- Employee class with properties (name, age, salary)
- Multiple sorting strategies using lambda expressions
- Demonstration of Comparator functional interface
- Sorting by single and multiple criteria

**Location:** `EmployeeSort/`

### Part B: StudentFilter
**Filtering and Sorting Students Using Streams**

**Objective:** To create a Java program that uses lambda expressions and stream operations to filter students scoring above 75%, sort them by marks, and display their names.

**Features:**
- Student class with properties (name, marks, percentage)
- Stream filtering operations
- Stream sorting with lambda expressions
- Data transformation and display

**Location:** `StudentFilter/`

### Part C: ProductStream
**Stream Operations on Product Dataset**

**Objective:** To process a large dataset of products using Java streams for grouping, finding maximum values, and calculating averages.

**Features:**
- Product class with multiple attributes
- Advanced stream operations (grouping, max, average)
- Collectors API usage
- Large dataset processing demonstrations

**Location:** `ProductStream/`

## Getting Started

### Prerequisites
- Java Development Kit (JDK) 8 or higher
- Any Java IDE (Eclipse, IntelliJ IDEA, NetBeans, or VS Code with Java extensions)

### Running the Projects

1. Clone this repository:
   ```bash
   git clone https://github.com/krish-1219/Java-Lambda-Stream-Examples.git
   cd Java-Lambda-Stream-Examples
   ```

2. Navigate to the specific project directory:
   ```bash
   cd EmployeeSort  # or StudentFilter or ProductStream
   ```

3. Compile and run the Java files:
   ```bash
   javac *.java
   java Main
   ```

## Key Concepts Covered

- **Lambda Expressions**: Anonymous functions for implementing functional interfaces
- **Stream API**: Processing collections of objects in a functional style
- **Functional Interfaces**: Comparator, Predicate, Function, Consumer
- **Stream Operations**:
  - Intermediate operations: filter(), map(), sorted()
  - Terminal operations: forEach(), collect(), max(), average()
- **Collectors**: groupingBy(), averagingDouble(), maxBy()

## Project Structure

```
Java-Lambda-Stream-Examples/
├── EmployeeSort/
│   └── (Java source files for employee sorting)
├── StudentFilter/
│   └── (Java source files for student filtering)
├── ProductStream/
│   └── (Java source files for product stream operations)
├── .gitignore
└── README.md
```

## Learning Outcomes

After working through these projects, you will understand:
- How to use lambda expressions for cleaner, more concise code
- How to leverage the Stream API for data processing
- Best practices for functional programming in Java
- Practical applications of modern Java features

## Contributing

Feel free to fork this repository and submit pull requests for improvements or additional examples.

## License

This project is open source and available for educational purposes.

## Author

Created as part of a Java programming curriculum focusing on functional programming concepts.
