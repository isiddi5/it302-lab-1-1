lab 1-1: Codio and GitHub basics
Make some modifications to the Node/Express install, and push changes to GitHub.

Review the app file
Open the app.js file; scan through it. You (probably) won’t understand much, but we’ll review it.

Open the routes folder, and look at index.js

After we review those…

Create a new route named "stuff", use the “index” view

Create a new view for "stuff", and update the route

Test in your browser (check the README)

Create a GitHub account and repository
If you don’t have one, create a free account on https://github.com

Create a new repository, named it302-lab1-1; do NOT “Initialize this repository with a README”

Add a Git to your Codio project
On Codio, open a terminal window (Tools > Terminal)

At the prompt, type in “git init” . This will create a new Git on your project.

Connect your Codio Git to your GitHub repository
On your GitHub repo page, copy the address in the Quick Setup section.

In your Codio terminal window, type git remote add origin followed by your repo address.

Run the following commands, reading the console output after each:

git status
git add *
git status
git commit -m "initial load"
git status
git push origin master (you’ll be prompted for your GitHub username and password)