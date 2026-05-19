# OOP Quiz System in Dart

A simple console-based Quiz Application developed using Dart and Object-Oriented Programming (OOP) concepts.
The application supports two types of questions:

* Multiple Choice Questions (MCQ)
* True/False Questions

The quiz automatically checks answers, calculates scores, and displays the final result.

---

## Features

* Uses Abstract Class and Inheritance
* Supports Multiple Choice Questions
* Supports True/False Questions
* Automatic answer validation
* Score calculation system
* Console-based interactive quiz
* Clean OOP structure

---

## OOP Concepts Used

| Concept        | Usage                           |
| -------------- | ------------------------------- |
| Abstract Class | `Question`                      |
| Inheritance    | `MultipleChoice`, `TrueFalse`   |
| Polymorphism   | `checkAnswer()` and `display()` |
| Encapsulation  | Private score variables         |
| Getter         | `currentScore`                  |

---

## Technologies Used

* Language: Dart
* Library: `dart:io`

---

## How to Run

### 1. Install Dart

Download Dart SDK from:

[Dart Official Website](https://dart.dev/?utm_source=chatgpt.com)

---

### 2. Save the Program

Save the file as:

```bash id="0rb4gc"
quiz.dart
```

---

### 3. Run the Program

Open terminal and run:

```bash id="jlwmcm"
dart run quiz.dart
```

---

## Example Output

```bash id="h3pnf4"
Welcome to OOP Quiz

What is the main programming language of flutter? (10 pts)
  Java
  Kotlin
  JavaScript
  Dart
Your answer: Dart
Correct! +10 points

Dart is a statically typed language. (5 pts)
  True
  False
Your answer: true
Correct! +5 points

Quiz Completed! Your final score: 15/15
```

---

## Project Structure

```bash id="r0eeu5"
quiz.dart
README.md
```

---

## Future Improvements

* Add more question types
* Timer system for each question
* Randomized question order
* Save scores in files/database
* Add leaderboard system
* Create Flutter GUI version

---

## Author

Muhammad Hossain
Mobile App Developer
