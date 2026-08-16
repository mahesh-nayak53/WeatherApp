# WeatherApp

A web-based weather application developed using **Java Servlets** that allows users to search for a location and view its current weather information. The application demonstrates backend development using Servlets, API integration, HTTP requests, and dynamic web content generation.

## Features

* Search weather information by city name
* Displays current weather details
* Integrates with a weather API to fetch real-time data
* Handles HTTP requests and responses using Java Servlets
* Dynamic weather information based on user input
* Simple and user-friendly interface
* Error handling for invalid city names and API requests

## Tech Stack

### Backend

* Java
* Java Servlets
* Apache Tomcat
* HTTP/REST API

### Frontend

* HTML
* CSS
* JavaScript

### Tools

* Eclipse 
* Apache Tomcat
* Git & GitHub
* Postman

## Project Structure

```text
WeatherApp/
│
├── src/
│   └── main/
│       ├── java/
│       │   └── com/
│       │       └── weatherapp/
│       │           └── WeatherServlet.java
│       │
│       └── webapp/
│           ├── index.html
│           ├── css/
│           │   └── style.css
│           └── js/
│               └── script.js
│
├── pom.xml
└── README.md
```

> The exact structure may vary depending on how the project was created.

## How It Works

1. The user enters a city name in the application.
2. The frontend sends the request to the Java Servlet.
3. The Servlet receives the city name through an HTTP request.
4. The application sends a request to the weather API.
5. The API returns the weather information.
6. The Servlet processes the API response.
7. The weather details are sent back to the client.
8. The user can view the weather information on the webpage.

## Weather Information

Depending on the API used, the application can display information such as:

* City name
* Temperature
* Weather condition
* Humidity
* Wind speed
* Weather description
* Feels-like temperature

## Prerequisites

Before running the project, make sure you have:

* Java JDK 8 or higher
* Apache Tomcat
* Eclipse / IntelliJ IDEA
* Maven (if the project uses Maven)
* An API key from your chosen weather API provider

## Configuration

Add your weather API key to the appropriate configuration file or Servlet configuration.

For example:

```text
API_KEY=your_api_key_here
```

**Do not upload your actual API key to GitHub.**

Instead, keep sensitive credentials in environment variables or a local configuration file that is excluded using `.gitignore`.

## Running the Project

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/WeatherApp.git
```

### 2. Open the Project

Open the project in Eclipse or IntelliJ IDEA.

### 3. Configure Apache Tomcat

Add Apache Tomcat as the application server and configure the project to run on Tomcat.

### 4. Configure the API Key

Add your weather API key to the project's configuration.

### 5. Run the Application

Start the Tomcat server and open the application in your browser.

```text
http://localhost:8080/WeatherApp/
```

## Example

Enter:

```text
Bangalore
```

The application sends the city information to the Servlet, retrieves the current weather information from the weather API, and displays the result to the user.

## Concepts Demonstrated

This project helped demonstrate practical implementation of:

* Java Servlets
* HTTP GET/POST requests
* Request and Response handling
* Servlet lifecycle
* API integration
* JSON response processing
* Exception handling
* Dynamic web applications
* Client-server communication
* Apache Tomcat deployment

## Future Enhancements
 
* Add search history
* Add responsive mobile UI
* Add loading animations
* Add weather-based background changes
* Add multiple-city comparison
* Improve error handling and validation

## Author

**Mahesh**

Java Full Stack Developer | Java | Servlets | Spring Boot | Hibernate | React | MySQL

---

If you found this project useful, consider giving the repository a ⭐ on GitHub.
