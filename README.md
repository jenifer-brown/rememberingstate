# rememberingstate
let your site remember the comments that have been written

In this assignment, you’ll be enhancing last week’s assignment to let your site remember the comments that have been written! You’ll also be using a library someone else has written in your work for the first time, which should be installed with NPM (similar to how you install ESLint, Vite, and Prettier). Being able to remember state and pick up where you left off is critical for most applications. Here, you’ll be saving and retrieving state locally, although in other instances you may call an API instead. You’ll also be enhancing your state manager to let comments be filtered, an interaction pattern common to large sets of data.


To complete the assignment, please do the following:
1. Create a new local project that uses Vite, Prettier, and ESLint
2. Create a branch from last week’s assignment for this week’s work
3. Update the previous week’s work to create an IndexedDB database, using the IDB NPM package, to store comments
     a. When a comment is valid and is submitted, it should be saved to the IndexedDB database
     b. When the page is loaded, it should load the comments from the IndexedDB database and display them
4. Update the comment component to allow a comment to be deleted
5. Add the ability to filter comments by author name, email address, and comment length. This filtering should drive your state manager and not require looking up comments from IndexedDB
6. The HTML, CSS, and JavaScript for the web page should be separate files. Use JavaScript module syntax (ES Modules) for your JavaScript. HTML and CSS defined as part of a custom element do not need to be in a separate file.
7. Submit your code by pushing it to GitHub, ensuring that there are no Prettier or ESLint errors
