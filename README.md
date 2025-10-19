**Project Report: Simple JavaScript Program**

**1. Introduction**

JavaScript (JS) is a lightweight, interpreted programming language widely used for developing interactive and dynamic web applications. It runs directly inside web browsers without requiring any additional software installation. The following section explains how to create, execute, and understand a simple JavaScript program using Visual Studio Code (VS Code).


**2. Objective**

The objective of this report is to:

* Demonstrate how to write and execute a simple JavaScript program in VS Code.
* Explain the purpose of each line of code.
* Provide clarity on how JavaScript interacts with HTML in a basic setup.


**3. Tools and Software Requirements**

| **S.No** | **Tool / Software**                       | **Description**                                                         |
| -------- | ----------------------------------------- | ----------------------------------------------------------------------- |
| 1        | **Visual Studio Code (VS Code)**          | A free, open-source code editor developed by Microsoft.                 |
| 2        | **Web Browser (Chrome / Edge / Firefox)** | To execute and view JavaScript output.                                  |
| 3        | **Node.js (Optional)**                    | Allows running JavaScript directly from the terminal without a browser. |


**4. Steps to Execute JavaScript Code in VS Code**

**Step 1: Create a New Project Folder**

* Create a folder named `JS_Project` on your desktop.
* Open it using **VS Code**.

**Step 2: Create HTML and JavaScript Files**

* Inside the folder, create two files:

  * `index.html`
  * `script.js`

**Step 3: Write the HTML Code**

Paste the following code in **index.html**:

```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>JavaScript Example</title>
</head>
<body>
  <h1>Welcome to My JavaScript Project</h1>
  <p id="message"></p>

  <!-- Linking external JS file -->
  <script src="script.js"></script>
</body>
</html>
```

**Step 4: Write the JavaScript Code**

Paste the following code in **script.js**:

```javascript
// Display a welcome message in the browser console
console.log("JavaScript program is running successfully!");

// Display a message on the webpage
document.getElementById("message").textContent = "Hello, Vibin! This is your first JavaScript project.";
```

**Step 5: Run the Code**

* Open the **index.html** file in your browser (Right-click → *Open with Chrome*).
* You will see:

  * A message displayed on the webpage.
  * A confirmation message in the **Console tab** of the browser (press **F12 → Console**).


**5. Code Explanation**

| **Line No.** | **Code**                                                                                                   | **Description**                                                             |
| ------------ | ---------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------- |
| 1            | `console.log("JavaScript program is running successfully!");`                                              | Prints a message to the browser console to confirm the JS script is active. |
| 2            | `document.getElementById("message").textContent = "Hello, Vibin! This is your first JavaScript project.";` | Finds the `<p>` element with ID “message” and changes its text content.     |


**6. Output Screenshot (Example)**

**Webpage Output:**

> “Hello, Vibin! This is your first JavaScript project.”

**Console Output:**

> “JavaScript program is running successfully!”

**7. Advantages of Using VS Code**

1. Syntax highlighting and IntelliSense for JavaScript.
2. Built-in terminal for quick testing using Node.js.
3. Extension marketplace for debugging and live server preview.
4. Auto-save and error detection for smooth coding experience.


**8. Conclusion**

This experiment demonstrates the basic execution of a JavaScript program using Visual Studio Code and a web browser. It provides an understanding of how HTML and JavaScript files work together to produce dynamic web content. This foundation can be extended to develop complex applications such as calculators, games, and web-based dashboards.
