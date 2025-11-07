#  CashCard JSON Testing Project

This project demonstrates how to test **JSON serialization and deserialization** in a Spring Boot application using **JUnit 5**, **Spring Boot’s @JsonTest**, and **JacksonTester**.

It’s a learning project that shows how a simple `CashCard` object can be converted to and from JSON, and how automated tests ensure this process works correctly.

---

##  Features

- **Serialization Test:**  
  Converts a `CashCard` Java object into JSON and checks that the JSON output matches the expected format.

- **Deserialization Test:**  
  Converts JSON data back into a `CashCard` Java object and verifies that all values are correctly restored.

- **Test-First Approach:**  
  Demonstrates writing a failing test first, then fixing it to confirm that JSON parsing works as intended.

---

##  Tech Stack

- **Java 17+**
- **Spring Boot**
- **JUnit 5 (Jupiter)**
- **Spring Boot Test Starter**
- **AssertJ** – for fluent assertions
- **Jackson** – for JSON mapping

---

## 🗂️ Project Structure

