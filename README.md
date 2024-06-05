Name: Md Arshad
Company: CODETECH IT SOLUTIONS
ID: CT6WDS152
Domain: Web Development
Duration: 5th june to 17th july
Mentor: Neelam Harish

 OVERVIEW OF THE PROJECT:
                         In our index.html file, we have included a <title> and <link> element inside of the <head>. For the title we set the name of the app to TO-DO List. We also linked the style.css file because, trust, styling is gonna make it look super cool later.

Toward the end of our code we need to include our <script> tag. This will link our JS file where we will create variables and functions that will make everything work just right.

OBJECT:
       Let's set up our editor. For this application, we will be using our PC terminal and Visual Studio Code (VS Code). If you prefer an online editor such as Codédex Builds, you are more than welcome to do so.

First, we need to create a directory and files for our project using the terminal. Once you open the terminal, cd into your Desktop. This is where we will add our directory. You can name it anything you like but to make it easier, let's name it todo-list-project:

KEY ACTIVITIES:
               The following files have been created in our todo-list-project folder:

index.html: We will write our HTML code, and this is what will be displayed on our webpage.
style.css: We will write our CSS code to design how our application looks.
script.js: Our JavaScript code is where we will add our interactions


First, we make a <div> and give it an id of "todo-container", to act as a container for our todo list.
We create another <div> and give it an id of "header". Inside of the <div> we create an <h1> tag with the title "To-Do List".
Then, inside of the <div id="todo-form"> create an <input> element. This will be used for the new task in which the user writes the name of the task.
We then create a <button> tag with an id of "input-button" for our "Add" button to add our task to the list.
Right beneath that, we create an <h2> tag with the title "Task List" along with a <ul> unordered list element, and give it an id of "list-container" this is where we will display each task.


TECHONOLOGY USED:
                 JavaScript!

Above, we set up the structure for our todo list using HTML. Here, we're about to create a function that will let us seamlessly add our tasks to the list. Let's open our script.js file where we will first create two variables.

We will use these variables for our input and todo list container:

const inputBox = document.getElementById("input-box");
const listContainer = document.getElementById("list
