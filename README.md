# SQL Client and Accountant Applications

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Repository Structure](#repository-structure)
- [Setup Instructions](#setup-instructions)
- [Usage](#usage)
- [Database Setup](#database-setup)
- [User Roles and Permissions](#user-roles-and-permissions)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Introduction

The **SQL Client and Accountant Applications** are Java-based GUI applications designed to interact with MySQL databases. The project comprises two main applications:

1. **SQL Client Application**: Allows users to connect to different databases, execute SQL commands, and view results.
2. **Accountant Application**: A specialized interface for accountants to monitor and query the `operationslog` database with restricted permissions.

Both applications share the same underlying databases but serve distinct user roles and functionalities.

## Features

### SQL Client Application

- **Database Connection**: Connect to `project3` or `bikedb` databases using different user credentials (`root`, `client1`, `client2`).
- **Execute SQL Commands**: Enter and execute `SELECT`, `INSERT`, `UPDATE`, and `DELETE` statements.
- **View Results**: Display query results in a tabular format.
- **Operation Logging**: Automatically log the number of queries and updates performed by each user.
- **User-Friendly GUI**: Intuitive interface built with Java Swing.

### Accountant Application

- **Fixed Database Connection**: Automatically connects to the `operationslog` database using predefined credentials.
- **Restricted Permissions**: Only allows `SELECT` queries to monitor operations.
- **Operation Monitoring**: View the `operation_counts` table to track user activities.
- **User Authentication**: Secure login based on the `theaccountant` user credentials.

## Technologies Used

- **Programming Language**: Java (JDK 8 or higher)
- **GUI Framework**: Java Swing
- **Database**: MySQL
- **Database Connectivity**: JDBC (Java Database Connectivity)
- **Build Tools**: [Optional: Maven/Gradle if used]
- **Version Control**: Git & GitHub

### Prerequisites

- **Java Development Kit (JDK)**: Ensure JDK 8 or higher is installed.
- **MySQL Server**: Install and configure MySQL Server.
- **IDE (Optional)**: Use an Integrated Development Environment like Eclipse, IntelliJ IDEA, or NetBeans for easier project management.

### Clone the Repository

```bash
git clone https://github.com/nickklos10/SQL-Client-App.git
cd SQL-Client-App
```


