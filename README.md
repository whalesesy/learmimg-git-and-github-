# learmimg-git-and-github-
About GitHub
GitHub is a cloud-based platform where you can store, share, and work together with others to write code.

Storing your code in a "repository" on GitHub allows you to:

Showcase or share your work.
Track and manage changes to your code over time.
Let others review your code, and make suggestions to improve it.
Collaborate on a shared project, without worrying that your changes will impact the work of your collaborators before you're ready to integrate them.
Collaborative working, one of GitHub’s fundamental features, is made possible by the open-source software, Git, upon which GitHub is built.

# About Git
Git is a version control system that intelligently tracks changes in files. Git is particularly useful when you and a group of people are all making changes to the same files at the same time.

Typically, to do this in a Git-based workflow, you would:

Create a branch off from the main copy of files that you (and your collaborators) are working on.
Make edits to the files independently and safely on your own personal branch.
Let Git intelligently merge your specific changes back into the main copy of files, so that your changes don't impact other people's updates.
Let Git keep track of your and other people's changes, so you all stay working on the most up-to-date version of the project.
If you want to learn more about Git, see (About Git)

How do Git and GitHub work together?
When you upload files to GitHub, you'll store them in a "Git repository." This means that when you make changes (or "commits") to your files in GitHub, Git will automatically start to track and manage your changes.

There are plenty of Git-related actions that you can complete on GitHub directly in your browser, such as creating a Git repository, creating branches, and uploading and editing files.

However, most people work on their files locally (on their own computer), then continually sync these local changes—and all the related Git data—with the central "remote" repository on GitHub. There are plenty of tools that you can use to do this, such as GitHub Desktop.

Once you start to collaborate with others and all need to work on the same repository at the same time, you’ll continually:

Pull all the latest changes made by your collaborators from the remote repository on GitHub.
Push back your own changes to the same remote repository on GitHub.
Git figures out how to intelligently merge this flow of changes, and GitHub helps you manage the flow through features such as "pull requests."

# Where do I start?
If you're new to GitHub, and unfamiliar with Git, we recommend working through the articles in the "Start your journey" category. The articles focus on tasks you can complete directly in your browser on GitHub and will help you to:

Create an account on GitHub.
Learn the "GitHub Flow", and the key principles of collaborative working (branches, commits, pull requests, merges).
Personalise your profile to share your interests and skills.
Explore GitHub to find inspiration for your own projects and connect with others.
Learn how to download interesting code for your own use.
Learn how to upload something you're working on to a GitHub repository.
# Next steps
(Creating an account on GitHub)
Creating an account on GitHub
Create a personal account to get started with GitHub.

In this article
About your personal account on GitHub
Signing up for a new personal account
Next steps
Further reading
About your personal account on GitHub
To get started with GitHub, you'll need to create a free personal account and verify your email address.

Every person who uses GitHub signs in to a user account. Your user account is your identity on GitHub and has a username and profile. For example, see @octocat's profile.

Later, you can explore the different types of accounts that GitHub offers, and decide if you need a billing plan. For more information, see "Types of GitHub accounts" and "GitHub’s plans."

Note that the steps in this article don't apply to Enterprise Managed Users. If your GitHub account has been created for you by your company, you can skip this article and continue to "Hello World."

Signing up for a new personal account
Navigate to https://github.com/.
Click Sign up.
Follow the prompts to create your personal account.
During sign up, you'll be asked to verify your email address. Without a verified email address, you won't be able to complete some basic GitHub tasks, such as creating a repository.

If you're having problems verifying your email address, there are some troubleshooting steps you can take. For more information, see "Verifying your email address."

Next steps
Now that you've created your personal account, we'll start to explore the basics of GitHub. In the next tutorial, "Hello World," you'll learn about repositories and how to create one, and you'll be introduced to concepts such as branching, commits, and pull requests.
We strongly recommend that you configure 2FA for your account. 2FA is an extra layer of security that can help keep your account secure. For more information, see "Configuring two-factor authentication."
# creating repos
Hello World
Follow this Hello World exercise to learn GitHub's pull request workflow.

In this article
Introduction
Step 1: Create a repository
Step 2: Create a branch
Step 3: Make and commit changes
Step 4: Open a pull request
Step 5: Merge your pull request
Conclusion
Next steps
Further reading
Introduction
This tutorial teaches you GitHub essentials like repositories, branches, commits, and pull requests. You'll create your own Hello World repository and learn GitHub's pull request workflow, a popular way to create and review code.

In this quickstart guide, you will:

Create and use a repository.
Start and manage a new branch.
Make changes to a file and push them to GitHub as commits.
Open and merge a pull request.
Prerequisites
You must have a GitHub account. For more information, see "Creating an account on GitHub."

You don't need to know how to code, use the command line, or install Git (the version control software that GitHub is built on).

Step 1: Create a repository
The first thing we'll do is create a repository. You can think of a repository as a folder that contains related items, such as files, images, videos, or even other folders. A repository usually groups together items that belong to the same "project" or thing you're working on.

Often, repositories include a README file, a file with information about your project. README files are written in Markdown, which is an easy-to-read, easy-to-write language for formatting plain text. We'll learn more about Markdown in the next tutorial, "Setting up your profile."

GitHub lets you add a README file at the same time you create your new repository. GitHub also offers other common options such as a license file, but you do not have to select any of them now.

Your hello-world repository can be a place where you store ideas, resources, or even share and discuss things with others.

In the upper-right corner of any page, select , then click New repository.

Screenshot of a GitHub dropdown menu showing options to create new items. The menu item "New repository" is outlined in dark orange.
In the "Repository name" box, type hello-world.

In the "Description" box, type a short description. For example, type "This repository is for practicing the GitHub Flow."

Select whether your repository will be Public or Private.

Select Add a README file.

Click Create repository.

Step 2: Create a branch
Branching lets you have different versions of a repository at one time.

By default, your repository has one branch named main that is considered to be the definitive branch. You can create additional branches off of main in your repository.

Branching is helpful when you want to add new features to a project without changing the main source of code. The work done on different branches will not show up on the main branch until you merge it, which we will cover later in this guide. You can use branches to experiment and make edits before committing them to main.

When you create a branch off the main branch, you're making a copy, or snapshot, of main as it was at that point in time. If someone else made changes to the main branch while you were working on your branch, you could pull in those updates.

This diagram shows:

The main branch
A new branch called feature
The journey that feature takes before it's merged into main
Diagram of the two branches. The "feature" branch diverges from the "main" branch, goes through stages for "Commit changes," "Submit pull request," and "Discuss proposed changes," and is then merged back into main.

Creating a branch
Click the Code tab of your hello-world repository.

Above the file list, click the dropdown menu that says main.

Screenshot of the repository page. A dropdown menu, labeled with a branch icon and "main", is highlighted with an orange outline.
Type a branch name, readme-edits, into the text box.

Click Create branch: readme-edits from main.

Screenshot of the branch dropdown for a repository. "Create branch: readme-edits from 'main'" is outlined in dark orange.
Now you have two branches, main and readme-edits. Right now, they look exactly the same. Next you'll add changes to the new readme-edits branch.

Step 3: Make and commit changes
When you created a new branch in the previous step, GitHub brought you to the code page for your new readme-edits branch, which is a copy of main.

You can make and save changes to the files in your repository. On GitHub, saved changes are called commits. Each commit has an associated commit message, which is a description explaining why a particular change was made. Commit messages capture the history of your changes so that other contributors can understand what you’ve done and why.

Under the readme-edits branch you created, click the README.md file.
To edit the file, click .
In the editor, write a bit about yourself.
Click Commit changes.
In the "Commit changes" box, write a commit message that describes your changes.
Click Commit changes.
These changes will be made only to the README file on your readme-edits branch, so now this branch contains content that's different from main.

Step 4: Open a pull request
Now that you have changes in a branch off of main, you can open a pull request.

Pull requests are the heart of collaboration on GitHub. When you open a pull request, you're proposing your changes and requesting that someone review and pull in your contribution and merge them into their branch. Pull requests show diffs, or differences, of the content from both branches. The changes, additions, and subtractions are shown in different colors.

As soon as you make a commit, you can open a pull request and start a discussion, even before the code is finished.

In this step, you'll open a pull request in your own repository and then merge it yourself. It's a great way to practise the GitHub flow before working on larger projects.

Click the Pull requests tab of your hello-world repository.

Click New pull request.

In the Example Comparisons box, select the branch you made, readme-edits, to compare with main (the original).

Look over your changes in the diffs on the Compare page, make sure they're what you want to submit.

Screenshot of a diff for the README.md file. 3 red lines list the text that's being removed, and 3 green lines list the text being added.
Click Create pull request.

Give your pull request a title and write a brief description of your changes. You can include emojis and drag and drop images and gifs.

Click Create pull request.

Reviewing a pull request
When you start collaborating with others, this is the time you'd ask for their review. This allows your collaborators to comment on, or propose changes to, your pull request before you merge the changes into the main branch.

We won't cover reviewing pull requests in this tutorial, but if you're interested in learning more, see "About pull request reviews." Alternatively, try the GitHub Skills "Reviewing pull requests" course.

Step 5: Merge your pull request
In this final step, you will merge your readme-edits branch into the main branch. After you merge your pull request, the changes on your readme-edits branch will be incorporated into main.

Sometimes, a pull request may introduce changes to code that conflict with the existing code on main. If there are any conflicts, GitHub will alert you about the conflicting code and prevent merging until the conflicts are resolved. You can make a commit that resolves the conflicts or use comments in the pull request to discuss the conflicts with your team members.

In this walk-through, you should not have any conflicts, so you are ready to merge your branch into the main branch.

At the bottom of the pull request, click Merge pull request to merge the changes into main.
Click Confirm merge. You will receive a message that the request was successfully merged and the request was closed.
Click Delete branch. Now that your pull request is merged and your changes are on main, you can safely delete the readme-edits branch. If you want to make more changes to your project, you can always create a new branch and repeat this process.
Click back to the Code tab of your hello-world repository to see your published changes on main.
Conclusion
By completing this tutorial, you've learned to create a project and make a pull request on GitHub.

As part of that, we've learned how to:

# Create a repository.
Start and manage a new branch.
Change a file and commit those changes to GitHub.
Open and merge a pull request.
Next steps
Take a look at your GitHub profile and you'll see your work reflected on your contribution graph.
If you want to practice the skills you've learned in this tutorial again, try the GitHub Skills "Introduction to GitHub" course.
In the next tutorial, "Setting up your profile," you'll learn how to personalize your profile and you'll also learn some basic Markdown syntax for writing on GitHub.
