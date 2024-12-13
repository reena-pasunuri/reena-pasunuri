# Banking Application Testing Project

## Overview

Welcome to the **Banking Application Testing Project**! 
This repository demonstrates how to implement automated testing for a banking application, covering both **web** and **mobile** platforms. 
The project showcases the use of modern testing frameworks such as **Selenium**, **Appium**, **Cypress**, and **Cucumber**, in combination with tools like **JIRA** for test management and **AWS** for CI/CD pipeline automation.
The main objective is to simulate a real-world environment for testing a banking application’s core functionalities, ensuring the application works efficiently across platforms and environments. 
This includes both functional testing (ensuring features work as expected) and non-functional testing (such as performance and security testing).
In this project, you'll find test automation scripts, user stories, and real-time test reports.
The repository also provides step-by-step guidance for setting up your testing environment, running tests, and integrating them into a continuous integration (CI) pipeline.

## Project Structure

The structure of this project follows a modular and organized approach, making it easy for testers and developers to navigate, contribute, and extend the test cases. 
Below is a breakdown of the key directories and files within the repository:


### **Key Directories & Files**:

- **`test-scripts/`**:
  - Contains all test scripts for both web and mobile platforms.
  - Web tests are implemented with **Selenium** and **Java**, and mobile tests are implemented with **Appium** and **JavaScript**.
  - Includes an `integration/` folder for API tests (e.g., payment gateway or transaction APIs).
  
- **`user-stories/`**:
  - Contains markdown files outlining detailed user stories and scenarios for each feature of the banking application.
  - Each user story corresponds to specific features such as login, account transfers, or transaction history.

- **`reports/`**:
  - This folder will contain HTML test reports generated after running the test scripts.
  - It helps in tracking test results and issues. These reports are designed to be easy to read and include detailed error logs and stack traces.

- **`data/`**:
  - Stores sample test data (e.g., for account credentials, transaction details) that will be used during the tests.

- **`.github/workflows/`**:
  - Contains the GitHub Actions configuration file (`ci.yml`) to automate the testing process and create a CI/CD pipeline.
  - This setup ensures that tests are executed every time code is pushed to the repository.

## Tools and Technologies Used

This project leverages a variety of tools to facilitate test automation and manage test cases. Here's a detailed list of technologies used in this project:

- **Selenium**: A powerful tool for automating web browsers. Selenium will be used to automate the testing of the banking web application. 
  - **Java** is the language used for writing Selenium tests.
  
- **Appium**: An open-source tool for automating mobile applications. Appium will be used for automating mobile banking apps on Android and iOS platforms.
  - **JavaScript** will be used for writing mobile test scripts with Appium.

- **Cypress**: A modern testing framework that will be used for front-end testing of web applications. It provides fast, reliable testing in a real browser environment.

- **JUnit and TestNG**: Testing frameworks for Java. These will be used to execute the test scripts and generate reports.

- **Cucumber (BDD)**: Behavior-Driven Development (BDD) tool used to write tests in plain language. It helps in bridging the communication gap between developers, testers, and stakeholders.

- **Jira**: A popular test management tool used for tracking bugs, features, and test cases.

- **AWS**: Cloud platform used to run the CI/CD pipeline. We will integrate AWS for continuous integration, enabling automated execution of test scripts in the cloud every time code is pushed to the repository.

## Features

- **Web Automation Tests**: Automates key workflows like login, account transfer, and balance checking in the web banking application using **Selenium**.
  
- **Mobile Automation Tests**: Automates key functionalities such as login, money transfer, and transaction history in the mobile banking app using **Appium**.

- **Behavior-Driven Development (BDD)**: Write tests in natural language using **Cucumber** for better collaboration with stakeholders.

- **CI/CD Pipeline**: Automates the testing and deployment pipeline using **GitHub Actions** and **AWS**. It ensures that every change made to the codebase is tested automatically.

- **Comprehensive Reporting**: After test execution, **HTML reports** are generated for easy review. These reports include detailed information on passed/failed tests, logs, and error traces.

## Getting Started

To set up the project locally and run the tests, follow the instructions below.

### Prerequisites

Before setting up the project, ensure you have the following installed on your local machine:

1. **Java**: JDK 11 or higher.
   - [Download JDK](https://adoptopenjdk.net/)
   
2. **Node.js** and **npm**: Required for Cypress and Appium.
   - [Download Node.js](https://nodejs.org/en/)
   
3. **Git**: Version control system to clone the repository.
   - [Download Git](https://git-scm.com/)

4. **Maven** or **Gradle**: Dependency management tools for Java.
   - [Install Maven](https://maven.apache.org/install.html)

5. **Appium**: For mobile automation testing.
   - [Install Appium](http://appium.io/docs/en/about-appium/intro/)

6. **AWS Account**: Set up an AWS account if you're using the cloud infrastructure for CI/CD.

### Clone the Repository

First, clone the repository to your local machine:

```bash
git clone https://github.com/reena-pasunuri/banking-application-testing-project.git

### Continuous Integration
This project includes GitHub Actions for CI/CD. The workflow runs the tests automatically every time code is pushed or a pull request is made.

The configuration file for CI/CD is located in .github/workflows/ci.yml.

### Contributing
We welcome contributions to this project. If you'd like to contribute:

### Fork the repository.
Create a new branch (git checkout -b feature-name).
Commit your changes (git commit -am 'Add new feature').
Push to the branch (git push origin feature-name).
Submit a pull request.
Please ensure that your code follows the coding conventions and includes appropriate test cases and documentation.


### What's New in This Extended Version:

1. **Detailed Project Description**: Provides more context about the project's goals, its purpose, and the tools used.
2. **Detailed Directory Breakdown**: Helps users understand where to find various files in the project.
3. **Tools and Technologies**: Detailed explanation of the tools used in the project.
4. **Setup Instructions**: Clear steps for setting up the environment and running the tests.
5. **Contributing Guidelines**: Instructions on how others can contribute to the project.

Let me know if you need more adjustments!
Let's keep learning!
