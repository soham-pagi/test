<img width="40%" alt='OrangeHRM' src='https://raw.githubusercontent.com/wiki/orangehrm/orangehrm/logos/logo_dark_mode.svg#gh-dark-mode-only'/>

# OrangeHRM Demo Selenium Testing

## Overview

This project aims to automate the testing of the demo.orangehrm website using Selenium and TestNG. The purpose is to ensure the reliability and functionality of the OrangeHRM application through automated tests, providing a robust testing framework for continuous integration and deployment.

## Table of Contents

- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Configuration](#configuration)
- [Running Tests](#running-tests)
  - [Using TestNG XML](#using-testng-xml)
- [Test Reports](#test-reports)

## Prerequisites

Before running the tests, make sure you have the following prerequisites installed:

- Java JDK 1.8 (Azul - Zulu)
- Maven 3.8.6
- Selenium 4.0
- TestNG 7.8.0
- AutoIT 3.3.16
- Eclipse IDE

API Testing:
- Postman 10.18.9
- Node 20.5.1
- Newman 6.1.1
- html, htmlextra

Performance Testing:
- JMeter 5.6.2


## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/GEMS-Training/GEMSFY24Batch02_Group10.git

2. Navigate to the project directory:

   ```bash
   cd GEMSFY24Batch02_Group10

3. Install dependencies using Maven:

   ```bash
   mvn clean install

## Configuration

Configure the test settings by updating the config.properties file in the src/main/java/com/OrangeHRM/config directory. Provide the appropriate values for:

- baseUrl: URL of the OrangeHRM demo website
- browser: Choose the browser for testing (e.g., chrome, firefox, safari)

## Running Tests
 - ### Using TestNG XML
    1. Open Eclipse IDE and import the project.
    2. Configure the XML file with the desired test suite, test classes, and parameters.
    3. Right-click on the XML file and select "Run As" > "TestNG Suite" to execute the tests.


## Test Reports

After running the tests, the reports will be generated in the automation_test_output/Reports/{date} directory. Open the HTML report in a browser to view detailed test results.
