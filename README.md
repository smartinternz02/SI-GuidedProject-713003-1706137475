# SI-GuidedProject-713003-1706137475

# Amazon-project-test-repository
Amazon guided project using Katalon studio

# Amazon Project with Katalon Studio - Test Automation

## Overview

This repository contains an automated testing project for the Amazon website using Katalon Studio. The project focuses on defining and solving problems related to the application's functionality, ensuring a seamless user experience across different scenarios.

## Problem Definition / Problem Understanding

The problem-understanding phase involves identifying challenges within the Amazon application. Challenges may include defects, inefficiencies, and compatibility issues across various browsers.

## Specify the Business Problem

The specified business problem revolves around the following:

- Ensuring a reliable and defect-free application.
- Achieving cost savings and faster time-to-market through automated testing.
- Enhancing brand reputation and increasing revenue with a seamless user experience.

## Business Impact

Addressing these problems will result in the following:

- Improved user satisfaction and trust.
- Cost savings and faster development cycles.
- Enhanced brand reputation and increased revenue.

## Test Case Preparation

## Test Cases

### 1. Login
- **Description**: Verifies the login functionality of the Amazon website.
- **Steps**:
  1. Open the Amazon website.
  2. Enter a valid username and password.
  3. Click on the login button.
- **Expected Outcome**: The user should be logged in successfully and redirected to the homepage.

### 2. Search for a Product
- **Description**: Tests the product search functionality on the Amazon website.
- **Steps**:
  1. Login to the Amazon website.
  2. Enter a product name in the search bar.
  3. Click on the search button.
- **Expected Outcome**: Relevant search results for the entered product should be displayed.

### 3. Add to Cart
- **Description**: Validates the functionality to add a product to the cart.
- **Steps**:
  1. Login to the Amazon website.
  2. Search for a product.
  3. Click on the product to view details.
  4. Click on the "Add to Cart" button.
- **Expected Outcome**: The selected product should be added to the cart successfully.

### 4. Navigate to a Different Tab
- **Description**: Tests the ability to navigate to different tabs on the Amazon website.
- **Steps**:
  1. Login to the Amazon website.
  2. Navigate to a different tab (e.g., "Today's Deals", "Your Orders").
- **Expected Outcome**: The user should be able to navigate to the selected tab without any errors.

### 5. Logout
- **Description**: Verifies the logout functionality on the Amazon website.
- **Steps**:
  1. Login to the Amazon website.
  2. Click on the user profile icon.
  3. Select the "Logout" option.
- **Expected Outcome**: The user should be logged out successfully and redirected to the login page.

### Analyze Requirements

Thoroughly understand project requirements, focusing on critical functionalities such as login, search, and checkout.

### Create Scenarios and Collect Input Data

Identify and document various scenarios based on user interactions, considering both positive and negative test cases. Collect input data needed for test case execution.

### Preparation of Test Cases

Document detailed steps for each scenario, including preconditions and expected outcomes. Identify and document test case dependencies and relationships.

### Test Data Preparation (Validation Table)

Prepare test data, considering boundary values, invalid inputs, and common use cases. Document test data in the form of a validation table, aligning it with the baseline document.

## Script / Test Case Execution

### Under Test Suite and Test Suite Collection Level

Organize test cases into test suites and test suite collections for efficient execution. Execute test cases at both levels to ensure comprehensive coverage.

### Handling and Validating Buttons

Write scripts to handle and validate various buttons within the application. Ensure the proper functioning of buttons under different scenarios.

### Test Listeners

Implement test listeners to capture events or perform specific actions during the test execution process. Utilize listeners for logging, reporting, and handling test events.

## Build Delivery

Ensure the delivery of a stable build with the latest changes, providing a reliable testing environment.

## Integrating Katalon to Git and Jenkins

### Integration with Git

Connect Katalon Studio to a Git repository to facilitate version control and collaboration. Use branches for parallel development and efficient code management.

### Integration with Jenkins

Configure Jenkins jobs to trigger automated test execution using Katalon Studio. Set up a continuous integration pipeline for automatic testing and reporting.

## Cross-Browser Testing using TestCloud


This repository contains automated cross-browser testing scripts using TestCloud, ensuring compatibility across various web browsers for your web application.

1. **Clone Repository**: Clone this repository.
2. **Test Scripts**: Write/update test scripts using Selenium or other tools.
3. **Dependencies**: Install necessary dependencies.


### Configure Cross-Browser Testing

Utilize TestCloud in Katalon Studio to perform cross-browser testing. Verify the application's compatibility across different browsers and ensure a consistent user experience.

## Generating and Analyzing Reports and Sending Reports through Email

### Generate Reports

Leverage Katalon Studio's reporting features to automatically generate reports after test execution. Use various report formats for detailed insights into test results.

### Analyze Reports

Analyze test reports to identify patterns, trends, and areas for improvement. Use reports for debugging, performance analysis, and making informed decisions.

### Send Reports through Email

Configure Katalon Studio to send automated test reports via email to relevant stakeholders. Enable notifications to keep the team informed about test

# Prior Knowledge:

 You must  have prior knowledge of the following topics to complete this project.

* Software testing concepts

* STLC	

* Manual Testing

* Automation Testing

* Software Automation process and tools 

* Automation testing process

* Classification of  automation testing tools

* Difference between Manual and Automation testing

* Advantages and need for automation testing tools

## Tech stacks used -
* Katalon Studio 
* Git 
* Jenkins
* Katalon TestCloud 

## Test cases automated - 
* Valid Amazon Login 
* Invalid Amazon Login
* Amazon logo on home page
* Footer link 
* Hyperlinks present
* List of countries available

## Data-driven testing
#### To check whether what forms of data are parsed and executed by the application, data-driven testing can be performed. In this project, I have used MS Excel data and CSV data to perform automated testing on Amazon login test cases. The data files used for login test cases can be found [here](https://github.com/smartinternz02/SI-GuidedProject-713003-1706137475/tree/master/Katalon_Amazon_Application_Testing_Project_Files/Data%20Files/Amazon_Test%20Data) and the corresponding test suite collection for CSV and xls data format can be found [here](https://github.com/smartinternz02/SI-GuidedProject-713003-1706137475/tree/master/Katalon_Amazon_Application_Testing_Project_Files/Test%20Suites)

## Cross-Browser Testing
#### For testing interoperability with different Operating Systems and Browsers, Katalon Studio provides Katalon TestCloud that can be used to execute the same test cases across different environments. The test suite for cross-browser testing is available [here](https://github.com/smartinternz02/SI-GuidedProject-713003-1706137475/tree/master/Katalon_Amazon_Application_Testing_Project_Files/Test%20Suites)

## Jenkins Integration with Katalon
#### Jenkins is used to automate build schedules with the help of Katalon Runtime Engine(KRE). The command script can be generated for any test suite in the Katalon Studio which then can be used to execute from Jenkins using the option of running Windows batch commands to start the build process. After the build process is executed via Jenkins, the test report is sent to Katalon TestOps. Here is the output of the console generated during the build process from [Jenkins](https://github.com/smartinternz02/SI-GuidedProject-713003-1706137475/blob/master/Amazon_Project_Documents/Jenkins_Integration.pdf)

## Test Reports
#### The test report is generated from running different test suites in this project. Here are the test reports generated in this [project](https://github.com/smartinternz02/SI-GuidedProject-713003-1706137475/tree/master/Amazon_Project_Documents/katalon_Reports_HTML%26PDFs/Test%20Suites)
  
# Project Structure:

![100](https://github.com/smartinternz02/SI-GuidedProject-713003-1706137475/blob/master/Screenshots/Screenshot%202024-02-12%20043644.png)
![100](https://github.com/smartinternz02/SI-GuidedProject-713003-1706137475/blob/master/Screenshots/Screenshot%202024-02-12%20044208.png)
![100](https://github.com/smartinternz02/SI-GuidedProject-713003-1706137475/blob/master/Screenshots/Screenshot%202024-02-12%20044317.png)

# Project Explanation Video Recording 
Link:

