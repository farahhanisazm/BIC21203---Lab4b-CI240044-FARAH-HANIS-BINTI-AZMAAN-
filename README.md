# LAB 4B – CLIENT-SIDE SCRIPTING (JSON and jQuery)

**Course:** BIC21203 – Web Development  
**Lab:** Lab 4B – Client-Side Scripting  
**Topic:** JSON, JavaScript and jQuery  
**Name:** Farah Hanis Binti Azaman  
**Matric Number:** CI240044

## 1. Project Overview

This project was developed as part of Lab 4B for the BIC21203 Web Development course. The main purpose of this lab is to understand how JSON, JavaScript, and jQuery can be used to create dynamic and interactive web pages. The lab focuses on creating structured JSON data, retrieving and displaying information using the JavaScript Fetch API, and performing DOM manipulation and event handling using jQuery.

## 2. Project Objectives

The objectives of this lab are:

1. To create and structure valid JSON data using appropriate data types.
2. To retrieve JSON data using the JavaScript `fetch()` API.
3. To display JSON information dynamically on a webpage.
4. To manipulate HTML elements using jQuery methods.
5. To understand the differences between native JavaScript and jQuery.

## 3. Project Files

The project consists of four main files:

| File | Description |
|---|---|
| `books.json` | Stores information about two books in JSON format. |
| `books.html` | Retrieves and displays book information using JavaScript `fetch()`. |
| `jquery-dom.html` | Demonstrates DOM manipulation and click event handling using jQuery. |
| `README.md` | Provides project documentation and setup instructions. |

## 4. Lab Activities

### Question 1: Create and Structure JSON Data

In Question 1, a JSON file named `books.json` was created to store information about two books: *The Great Gatsby* and *To Kill a Mockingbird*. Each book contains four properties, including title, author, publication year, and genres. The JSON data uses a top-level `books` array containing two book objects. This activity demonstrates how structured information can be stored using valid JSON syntax.


### Question 2: Retrieve and Display JSON Data

In Question 2, a webpage named `books.html` was developed using HTML, CSS, and JavaScript. The webpage uses the `fetch()` API to retrieve information from `books.json`. The retrieved data is displayed dynamically, including the title of the first book, the author of the second book, and the genres of both books. The webpage also includes error handling to display a user-friendly message if the JSON file cannot be loaded.


### Question 3: Compare Native JavaScript and jQuery

In Question 3, a webpage named `jquery-dom.html` was created to demonstrate DOM manipulation and event handling using jQuery.

Three jQuery methods were implemented:

- `.text()` – Changes the original text to "Modified Text".
- `.addClass()` – Adds the `myStyle` CSS class to an HTML element, changing its background colour to coral.
- `.on("click", ...)` – Displays an alert message saying "Button clicked!" when the user clicks the button.

This activity demonstrates how jQuery simplifies common JavaScript operations and provides convenient methods for creating interactive webpages.

## 5. Tools and Technologies Used

- **HTML5:** Structures the content of the webpages.
- **CSS3:** Styles the webpages and improves their appearance.
- **JavaScript:** Retrieves JSON data and updates webpage content.
- **JSON:** Stores structured book information.
- **jQuery 4.0.0:** Performs DOM manipulation and handles user interactions.
- **Visual Studio Code:** Used to write and edit the source code.
- **Live Server:** Runs the project through a local development server.
- **Google Chrome:** Used to test the webpages.

## 6. Setup and Running Instructions

Follow these steps to run the project:

1. Download or clone this GitHub repository.
2. Extract the downloaded folder if necessary.
3. Open the project folder using Visual Studio Code.
4. Install the Live Server extension in VS Code if it is not already installed.
5. Right-click `books.html` and select **Open with Live Server**.
6. The browser will display the book information retrieved from `books.json`.
7. Open `jquery-dom.html` using Live Server to test the jQuery functions.
8. Click the **Click me** button to display the alert message.

## 7. Reflection

Throughout Lab 4B, I learned how to create and structure JSON data to store book information. I also gained experience using the JavaScript `fetch()` API to retrieve and display JSON data on a webpage. Besides that, I learned how to use jQuery to modify HTML elements, apply CSS classes, and handle button click events. This lab helped me understand the differences between native JavaScript and jQuery. Overall, I improved my knowledge and skills in client-side web development.

## 8. Conclusion

In conclusion, Lab 4B provided practical experience in working with JSON, JavaScript, and jQuery. All three questions demonstrate important concepts in client-side scripting, including structured data storage, dynamic data retrieval, DOM manipulation, and event handling. The knowledge gained from this lab can be applied to the development of more interactive and user-friendly web applications.
