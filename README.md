# Employee Dataset for API Testing and Data Analysis
This repository contains a dataset comprising demographic and employment information for employees, suitable for API testing, data analysis, and related purposes.

# Overview
The dataset includes the following attributes for each employee:

ID: Unique identifier for each employee.
Gender: Gender of the employee.
Birthdate: Date of birth of the employee.
Education Level: Level of education attained by the employee.
Job Category: Category of job held by the employee.
Salary: Current salary of the employee.
Starting Salary: Initial salary of the employee.
Job Tenure: Tenure in the current job (in months).
Previous Experience: Previous work experience (in months).
Minority Status: Indicates if the employee belongs to a minority group (Yes/No).
Purpose
This dataset is suitable for various purposes including:

API Testing: Use the data to test API endpoints that handle employee information.
Data Analysis: Analyze the dataset to derive insights into employee demographics, salary trends, job tenure, and more.
Research: Utilize the dataset as a sample for research or academic projects related to human resources, employment, or demographic studies.



______________________________________________________________________________________________________________________________________________________________________________________






# API Testing Guidelines

## Overview
This API provides endpoints to retrieve employee data from a CSV file. It supports basic authentication for login.

## Base URL
The base URL for this API is [https://ahsansaeed.pythonanywhere.com](https://ahsansaeed.pythonanywhere.com)

## Endpoints

### 1. Get Server Status

- **URL**: `/status`
- **Method**: GET
- **Description**: Retrieves the server status to confirm that the API is up and running.

### 2. Get All Employee Data

- **URL**: `/employees`
- **Method**: GET
- **Description**: Retrieves all employee data available in the CSV file.

### 3. Get Specific Employee Data

- **URL**: `/employee`
- **Method**: GET
- **Description**: Retrieves specific employee data based on provided query parameters.
- **Parameter Required**. Example: `/employee?id=1` or `/employee?id=1.0`

#### Query Parameters
- `id`: Filter employees by their ID. Example: `/employee?id=1`
- Add more query parameters as needed.

### Using Parameters
- To use parameters, append them to the endpoint URL in the format `?parameter=value`.
- For example: `/employee?id=1`

### Using Multiple Parameters
- To use multiple parameters, separate them with `&` in the URL.
- For example: `/employee?id=1&jobcat=Manager`

### Authentication Endpoint

- **URL**: `/login`
- **Method**: POST
- **Description**: Login endpoint requiring authentication.


## Authentication
- **Basic Authentication**: Use username and password.
- **Bearer Token Authentication**: Use an API key.


## Credentials 

- **Basic Authentication**: Provide username and password. Username: `admin` and Password: `admin123@`
- **Bearer Token Authentication**: Provide Bearer Token in the request headers. `as-tT4RzY9mZKpG7qBwxZydKpYdS3vFjJkNpQsT1uWxZy`


# Usage
You can clone this repository or download the dataset directly for use in your projects. Ensure to comply with any licensing or usage requirements specified in this repository.

# Contribution
Contributions to enhance or expand this dataset are welcome. If you have additional data to contribute or suggestions for improvement, feel free to open an issue or submit a pull request.

### Developer Contact Information
Ahsan Saeed
- [Linkedin](https://www.linkedin.com/in/ahsensaeed/)
- [Github](https://github.com/thehsansaeed)
- [Microsoft Marketplace](https://marketplace.visualstudio.com/publishers/ahsansaeed)

# License
The dataset in this repository is provided under the [MIT License](https://github.com/thehsansaeed/Sample-Employee-Data/blob/main/LICENSE).

