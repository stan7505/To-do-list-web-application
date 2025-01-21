# To-do-list-web-application
This HTML and JavaScript code creates a Task List web application with a clean, responsive design. It includes a "Task List 2023" title in the header, an input field, and a button for adding new tasks. Existing tasks are stored in local storage for persistence. Users can add, edit, delete, and mark tasks as completed or uncompleted
This HTML and CSS code creates a web page for a "Task List" application. The page features a form to input and manage tasks. Here is a description of the code:

1. `<!DOCTYPE html>`: This declaration specifies that the document is an HTML5 document.

2. `<html lang="en">`: The HTML document starts, and the `lang` attribute is set to "en" to indicate the content is in English.

3. `<head>`: This section contains metadata and links to external resources.

   - `<meta charset="UTF-8">`: Defines the character encoding as UTF-8.
   - `<meta name="viewport" content="width=device-width, initial-scale=1.0">`: Sets the viewport for responsive design.
   - `<title>Task List 2023</title>`: Specifies the title of the web page.
   - `<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.1/css/all.min.css">`: Imports the Font Awesome icon library for icons.

4. `<style>`: Contains the embedded CSS for styling the web page.

   - Defines CSS variables for color.
   - Sets default styles for various elements like `body`, `header`, `input`, buttons, and various classes.
   - Includes media queries for responsive design, adjusting styles for smaller screens.

5. `<body>`: The main content of the web page.

   - `<header>`: The page's header section, containing a title and a form for adding new tasks.

   - `<main>`: The main content of the page, wrapped in a `main` element.

   - `<section class="task-list">`: A section for listing tasks.

     - `<h2>Tasks</h2>`: A title for the task list.

     - `<div id="tasks">`: An empty `div` element with the ID "tasks" where tasks will be added dynamically using JavaScript.

6. `<script>`: JavaScript code is embedded at the end of the document.

   - JavaScript is used to interact with the DOM, manage tasks, and update the local storage for task persistence.

   - It includes event listeners for loading tasks, adding tasks, editing tasks, and marking tasks as completed or uncompleted.

   - When a new task is added, a new task element is dynamically created and appended to the task list.

   - It uses local storage to store and retrieve task data.

In summary, this code creates a web page for managing tasks. Users can input tasks, edit them, mark them as completed or uncompleted, and delete them. The tasks are stored locally in the browser's storage, allowing for persistence across page reloads. The page is designed to be responsive, adapting its layout for different screen sizes. It also includes some basic styling to make the task list visually appealing.

![Screenshot (11)](https://github.com/user-attachments/assets/feca7708-87d6-4571-802c-cbb038b2e484)


