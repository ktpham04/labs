# Lab Report 4: Git and GitHub using Terminal & Vim

## Step 1: Logging on to IENG6
With using the ssh key made from lab 7, we are able to log into ieng6 without needing to use a password. In order to log in, we used `ssh cse15lsp23bc@ieng6.ucsd.edu`
![Image](ieng.png)

## Step 2: Cloning Lab 7 Repo
We used `git clone` and the link from ssh lab 7 repo into our terminal. To clone lab 7, `git clone git@github.com:ktpham04/lab7.git`
![Image](clone.png)

## Step 3: Running Failed Test
After cloning lab 7 repo, we must run the tests with the given commands: `javac -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar *.java <enter> java -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar org.junit.runner.JUnitCore ListExamplesTests <enter>` which will give you the output in the image below.
![Image](failed.png)
As you can see, once running these commands we are given 2 failed tests
The errors we had was in the file of `ListExamples.java`, in order to fix these errors we had to used the following keys `vim ListExamples.java <enter>` which takes our terminal to vim and show us the following code
