# UX-testtask (Test task for prospective UX team members) #

### Setup  ###

1. Clone the repo
2. Install dependencies
	>npm install
3. build the app
	>grunt
4. run the server
	>node server

### Tasks ###

The test is implemented as a JS application using Less, grunt, jQuery, and Underscore templates, to present two forms (Person Form and Employee Form) on the user's screen.

Tasks:

1. Solve the problem with the "margin-left" being ignored in dropdown.less:4 (solve it in the Less file).
2. In all dropdown buttons, create a gap of 3px between the caret and the text.
3. The dropdown buttons are green (by default). If they are inside a container with style "form", they are red. Add code making the dropdown blue when it's inside the Person form.
4. Change the color of the label "Name" in the Person Form to blue.
5. The two forms are currently positioned vertically. Add code positioning them side by side, except on mobile devices.
6. Add a new form for Company, asking for company name and number of employees. This form should be 100% wide on all devices. Style the "number of employees" label to be red.

### Submitting the solution ###

Do not commit the modified files to this repository, and do not create a pull request. 

Instead, create a public repository under your own Github account, and provide the solution to each of the test tasks as a separate commit. Then send the repository link to skanareykin@dev.lawfirmmatrix.com.
