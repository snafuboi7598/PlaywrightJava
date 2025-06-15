# 🎭 Playwright Java Automation Framework

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Build Status](https://img.shields.io/badge/build-passing-brightgreen.svg)]()
[![Java](https://img.shields.io/badge/Java-17%2B-orange.svg)](https://www.oracle.com/java/)

A robust and scalable **end-to-end test automation framework** built using [Playwright for Java](https://playwright.dev/java/). Designed to support cross-browser testing with speed, reliability, and flexibility.

---

## 🚀 Features

- ⚡ Fast and reliable Playwright test execution
- 🧪 Supports TestNG or JUnit integration
- 🌐 Cross-browser support (Chromium, Firefox, WebKit)
- 📸 Automatic screenshot on failure
- 📊 Test reports (HTML/XML)
- ♻️ CI/CD ready (GitHub Actions, Jenkins, etc.)
- 🔧 Easy-to-configure using Maven

---

## 📁 Project Structure

testplaywright/
├── src/
│ ├── main/java/ # Main logic (if any)
│ └── test/java/ # Test cases
│ └── YourTests.java
├── pom.xml # Maven config
└── testng.xml / junit.conf # Test suite config


---

## 🛠️ Getting Started

### 🔧 Prerequisites

- Java 17 or higher
- Maven 3.6+
- Git

### 📦 Clone and Install

```bash
git clone https://github.com/snafuboi7598/PlaywrightJava.git
cd PlaywrightJava
mvn clean install
# Run using TestNG
mvn test

# Or run specific suite
mvn test -DsuiteXmlFile=testng.xml
