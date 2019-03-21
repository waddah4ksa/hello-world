
# hello-world
Just another repository

Write a bit about yourself?, well I'm <a href="https://github.com/waddah4ksa">Waddah4KSA</a>, and thats all ^_^.

<hr />
# GitHub Hello-World Exercise 10min Read , 20190320
<hr />

<hr />
# Intro
<hr />

<hr />
<b>You’ll learn how to:</b>
<br />
- Create and use a repository.
<br />
- Start and manage a new branch.
<br />
- Make changes to a file and push them to GitHub as commits.
<br />
- Open and merge a pull request.
<hr />

<hr />
# What is GitHub?
<hr />

<hr />
<b>What is GitHub?</b>
<br />
GitHub is a code hosting platform for version control and collaboration.
<br />
It lets you and others work together on projects from anywhere.

This tutorial teaches you GitHub essentials like <b>repositories</b>, <b>branches</b>, <b>commits</b>, and <b>Pull Requests</b>.
<br />
You’ll create your own Hello World repository and learn GitHub’s Pull Request workflow, a popular way to create and review code.

<b>No coding necessary</b>
<br />
To complete this tutorial, you need a <a href="http://github.com/">GitHub.com</a> account and Internet access.
<br />
You don’t need to know how to code, use the command line, or install Git (the version control software GitHub is built on).
<br />
<b>Tip:</b> Open this guide in a separate browser window (or tab) so you can see it while you complete the steps in the tutorial.
<hr />

<hr />
# Create a Repository
<hr />
<b>Step 1. Create a Repository:</b>
<br />
A <b>repository</b> is usually used to organize a single project.
<br />
Repositories can contain folders and files, images, videos, spreadsheets, and data sets – anything your project needs.
<br />
We recommend including a <b>README</b>, or a file with information about your project.
<br />
GitHub makes it easy to add one at the same time you create your new repository.
<br />
It also offers other common options such as a license file.

Your <strong>hello-world</strong> repository can be a place where you store ideas, resources, or even share and discuss things with others.

<b>To create a new repository:</b>
1. In the upper right corner, next to your avatar or identicon, click + and then select <b>New repository</b>.
2. Name your repository <strong>hello-world</strong>.
3. Write a short description.
4. Select <b>Initialize this repository with a README</b>.
<img src="https://guides.github.com/activities/hello-world/create-new-repo.png" />
5. Click <b>Create repository</b>.

<hr />
# Create a Branch
<hr />
<b>Step 2. Create a Branch:</b>
<br />
<b>Branching</b> is the way to work on different versions of a repository at one time.
<br />
By default your repository has one branch named <strong>master</strong> which is considered to be the definitive branch.
<br />
We use branches to experiment and make edits before committing them to <strong>master</strong>.

When you create a branch off the <strong>master</strong> branch, you’re making a copy, or snapshot, of <strong>master</strong> as it was at that point in time.
<br />
If someone else made changes to the <strong>master</strong> branch while you were working on your branch, you could pull in those updates.

This diagram shows:
- The <strong>master</strong> branch
- A new branch called <strong>feature</strong> (because we’re doing ‘feature work’ on this branch)
- The journey that <strong>feature</strong> takes before it’s merged into <strong>master</strong>
<img src="https://guides.github.com/activities/hello-world/branching.png" />

Have you ever saved different versions of a file? Something like:
- story.txt
- story-joe-edit.txt
- story-joe-edit-reviewed.txt

Branches accomplish similar goals in GitHub repositories.

Here at GitHub, our developers, writers, and designers use branches for keeping bug fixes and
feature work separate from our <strong>master</strong> (production) branch.
<br />
When a change is ready, they merge their branch into <strong>master</strong>.

<b>To create a new branch:</b>
1. Go to your new repository <strong>hello-world</strong>.
2. Click the drop down at the top of the file list that says <b>branch: master</b>.
3. Type a branch name, <strong>readme-edits</strong>, into the new branch text box.
4. Select the blue <b>Create branch</b> box or hit “Enter” on your keyboard.
<img src="https://guides.github.com/activities/hello-world/readme-edits.gif" />

Now you have two branches, <strong>master</strong> and <strong>readme-edits</strong>.
<br />
They look exactly the same, but not for long! Next we’ll add our changes to the new branch.

<hr />
# Make a Commit
<hr />
<b>Step 3. Make and commit changes:</b>
<br />
Bravo! Now, you’re on the code view for your <strong>readme-edits</strong> branch, which is a copy of <strong>master</strong>.
<br />
Let’s make some edits.

On GitHub, saved changes are called <b>commits</b>.
<br />
Each commit has an associated <b>commit message</b>, which is a description explaining why a particular change was made.
<br />
Commit messages capture the history of your changes, so other contributors can understand what you’ve done and why.

<b>Make and commit changes</b>
1. Click the <strong>README.md</strong> file.
2. Click the pencil icon in the upper right corner of the file view to edit.
3. In the editor, write a bit about yourself.
4. Write a commit message that describes your changes.
5. Click <b>Commit changes</b> button.
<img src="https://guides.github.com/activities/hello-world/commit.png" />
These changes will be made to just the README file on your <strong>readme-edits</strong> branch, so
now this branch contains content that’s different from <strong>master</strong>.
<br />

<hr />
# Open a Pull Request
<hr />
<b>Step 4. Open a Pull Request:</b>
<br />
Nice edits! Now that you have changes in a branch off of <strong>master</strong>, you can open a <b>pull request</b>.

Pull Requests are the heart of collaboration on GitHub.
<br />
When you open a pull <b>request</b>, you’re proposing your changes and requesting that someone review and
<br />
pull in your contribution and merge them into their branch.
<br />
Pull requests show <b>diffs</b>, or differences, of the content from both branches.
<br />
The changes, additions, and subtractions are shown in green and red.

As soon as you make a commit, you can open a pull request and start a discussion, even before the code is finished.

By using GitHub’s
<a href="https://help.github.com/articles/about-writing-and-formatting-on-github/#text-formatting-toolbar">@mention system</a>
in your pull request message, you can ask for feedback from specific people or teams, whether they’re
down the hall or 10 time zones away.

You can even open pull requests in your own repository and merge them yourself.
<br />
It’s a great way to learn the GitHub flow before working on larger projects.

<b>Open a Pull Request for changes to the README</b>
Click on the image for a larger version
<table>
          <th><b>Step</b></th>
          <th><b>Screenshot</b></th>
          <tr>
          <td>Click the <b>Pull Request</b> tab, then from the Pull Request page, click the green <b>New pull request</b> button.</td>
          <td><img src="https://guides.github.com/activities/hello-world/pr-tab.gif" /></td>
          </tr>
          <tr>
          <td>In the <b>Example Comparisons</b> box, select the branch you made, <strong>readme-edits</strong>, to compare with <strong>master</strong> (the original).</td>
          <td><img src="https://guides.github.com/activities/hello-world/pick-branch.png" /></td>
          </tr>
          <tr>
          <td>Look over your changes in the diffs on the Compare page, make sure they’re what you want to submit.</td>
          <td><img src="https://guides.github.com/activities/hello-world/diff.png" /></td>
          </tr>
          <tr>
          <td>When you’re satisfied that these are the changes you want to submit, click the big green <b>Create Pull Request</b> button.</td>
          <td><img src="https://guides.github.com/activities/hello-world/create-pr.png" /></td>
          </tr>
          <tr>
          <td>Give your pull request a title and write a brief description of your changes.</td>
          <td><img src="https://guides.github.com/activities/hello-world/pr-form.png" /></td>
          </tr>
</table>

When you’re done with your message, click <b>Create pull request!</b>

Tip: You can use 
<a href="https://help.github.com/articles/basic-writing-and-formatting-syntax/#using-emoji">emoji</a>
and
<a href="https://help.github.com/articles/file-attachments-on-issues-and-pull-requests/">drag and drop images and gifs</a>
onto comments and Pull Requests.

<hr />
# Merge Pull Request
<hr />
<b>Step 5. Merge your Pull Request:</b>
<br />
In this final step, it’s time to bring your changes together – merging your <strong>readme-edits</strong> branch into the <strong>master</strong> branch.
<br />
1. Click the green <b>Merge pull request</b> button to merge the changes into <strong>master</strong>.
<br />
2. Click <b>Confirm merge</b>.
<br />
3. Go ahead and <b>delete the branch</b>, since its changes have been incorporated, with the Delete branch button in the purple box.
<br />
<img src="https://guides.github.com/activities/hello-world/merge-button.png" />
<img src="https://guides.github.com/activities/hello-world/delete-button.png" />

<hr />
<b>Celebrate!</b>
<hr />
<br />
By completing this tutorial, you’ve learned to create a project and make a pull request on GitHub!

Here’s what you accomplished in this tutorial:
<br />
Created an open source repository
<br />
Started and managed a new branch
<br />
Changed a file and committed those changes to GitHub
<br />
Opened and merged a Pull Request

Take a look at your GitHub profile and you’ll see your new
<a href="https://help.github.com/articles/viewing-contributions">contribution squares</a>!

To learn more about the power of Pull Requests, we recommend reading the
<a href="http://guides.github.com/overviews/flow/">GitHub flow Guide</a>.
<br />
You might also visit <a href="http://github.com/explore">GitHub Explore</a> and get involved in an Open Source project.

Tip: Check out our other
<a href="http://guides.github.com/">Guides</a>, 
<a href="http://youtube.com/githubguides">YouTube Channel</a>
and
<a href="https://services.github.com/on-demand/">On-Demand Training</a>
for more on how to get started with GitHub.

<a href="https://guides.github.com/activities/hello-world/">Source</a>
Last updated April 7, 2016

