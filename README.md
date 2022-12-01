# flx-006-js-5-debrief

## In this exercise you will create your own Random Name Generator!

### **Directions:**

### _Create a Random Name Generator using HTML, CSS, and JavaScript._

### **Your application should meet the requirements listed below:**

1. Selects from a pool of at least ten names of your classmates
2. Contains `Generate Random Names` button that initiates the selection of 4 random names (duplicate names are OK)
3. The selected random names are displayed to the browser
4. Each time the `Generate Random Names` button is pressed, a new set of names appears (replacing the previous set of 4 random names)
5. Contains button named `Clear` that removes the populated list from the screen
6. Once you have completed steps 1-6, try to complete the Stretch Goals listed below.

### Stretch Goals

- Use `window.prompt()` to allow the user to enter the number of names they want (up to 20 names).
  - Info on `window.prompt()`: https://www.w3schools.com/jsref/met_win_prompt.asp
- The Random Name Generator should select and display the specified number of names to the browser window.
- If the user inputs a number higher than 20, an `alert` box should appear informing the user that they should enter a number below 20.
  - Info on `alert()`: https://www.w3schools.com/jsref/met_win_alert.asp  

## Part 1 - Fork and Clone the project

- Begin by _forking_ this project into a personal repository.
  - To do this, click the `Fork` button located at the top right of this page.
- Navigate to your github profile to find the _newly forked repository_.
- Clone the repository from **your account** into the directory on your computer that you use to keep your projects (ex. `dev` directory).
  - Remember this from the lessons on Git and Github?
    - Go to the green `Code` button in the top right of this repository
    - Select `https` and then COPY that url
    - Open Git Bash (Windows) or Termial (Mac) on your computer, and `cd` to a directory where you wish to save this assignment to work on
    - Type `git clone ` followed by the URL you copied from Github
    - `cd` into the repository for this assignment that you have just cloned.
- Open the newly cloned project in a code editor (ex. Visual Studio Code).

### Part 2 - Edit the _cloned_ project

- from a text editor (i.e. - Visual Studio Code, Notepad ++, etc...), select:
  - `File` > `Open`
    - Select the directory you use to store your projects (ex. `dev` directory)
    - From the text editor,in the directory you use to store your projects (ex. `dev` directory), locate the newly cloned project folder.
    - Expand the project from the _project explorer (may just be called `explorer`)_
    - Create your file structure (html, css and js files)
    

### Part 3 - _Pushing_ new changes to repository

- From a _terminal_ navigate to the root directory of the _cloned_ project.
- From the root directory of the project, execute the following commands:
  - `git add .`
    - Add all files in current directory to the staging area
  - `git commit -m 'I have made an edit to a file!'`
    - Save all staged changes to local repository
  - `git push -u origin main`
    - Push changes from local repository to remote repository

### Part 4 - Submitting assignment

- From the browser, navigate to the _forked_ project from **your** Github account.
- Click the `Pull Requests` tab.
- Select `New Pull Request`