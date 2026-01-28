# Purpose
This repository is a place for students to test preliminary code prior to final submissions for Project 2 of Brigham Young University's CE 321, Structural Analysis, class.
Particularly, it will allow you to check that your Structure_Operations.py file is functioning correctly for your first Project 2 homework assignment.
Later, it will allow you to check that your Geometry_Operations.py file is functioning correctly for your second and third Project 2 homework assignments.
Students should duplicate this repository and then use it to test their answer submissions.

# Setup
To interact with this toolset, you will need to create an account on GitHub if you do not already have one. 
Because you likely already completed Project 1, you should already have an account at this time.
If you indeed do not have an account, to learn how to create an account, click [here](https://docs.github.com/en/get-started/start-your-journey/creating-an-account-on-github).
You may want to create this account using your BYU e-mail address, though that is not necessary.

After creating an account, navigate back to this repository. Then, near the top right of the webpage, click the button "**Use this template**" and select "Create new repository."
(If you do not see the "Use this template" button, try logging into your GitHub account before navigating to this repository.)
After selecting "Create new repository," you will then be asked to give the repository a name (e.g. CE_321_W26_Proj2_Preliminaries)
You will also be asked whether to make your repository public or private. **Make your repository private.** If you accidentally make it public, you will need to start over with a private repository.
**Also, if you fork this repository (rather than duplicating it), it may cause problems that result your repository being deleted. DO NOT FORK THE REPOSITORY!**

# Uploading Submission Results
After duplicating this repository as a private repository, you can interact with it in a number of ways.
The best way will be to modify your Python files on your own machine and then upload them here when you would like them tested.
(Recall that for project 1 you modified files online and then resubmitted them; this is not a good approach to being successful here.)
You should only need to edit/upload two files: (1) Structure_Operations.py, (2) Geometry_Operations.py.

Alternatively, anyone who is comfortable with command line and has used git repositories before may prefer downloading this to their machine, filling in data locally, and then uploading their submission.
Additional instructions on how to proceed in this manner will not be given, but you can look online to find out more.

As an aside, there is no doubt that you will be able to break this testing software.
The purpose of this is to allow you to check your results prior to submitting your final answers.
If you treat it nicely, it should perform well for you.
If you believe that your submission should be performing correctly and it is not, please contact the instructor for assistance.

# Checking Submission Results
Once you have uploaded the appropriate files, navigate to the "Actions" tab near the top left of the webpage.
The topmost workflow run is testing your submission against the grading software.
It should complete the testing within ~30 seconds of submitting your results.
**Your code will not necessarily give you a green check mark upon completion. Please read further to interpret results.**

## Structure Operations
Upon completion of your first homework, Structure_Operations.py should be complete.
Upload your Structure_Operations.py file.
Upon completion of the testing framework, you will not receive a green check mark.
Click on the topmost workflow run.
Then click on the "build" button under "TestingFunctions.yaml".
If there is a check mark next to "Test Structure Operations with unittest," your Structure_Operations.py code functions correctly. 
If this is the case, you will likely see an error on "Test Geometry Operations Part1 with unittest".
This is okay.
You have finished this assignment correctly.
Otherwise, you may click on "Test Geometry Operations Part1 with unittest" to see where you made a mistake. 
If your code passes the Example 3.2 test, but not the Example 3.3 test, you likely (but not necessarily) have an error in your sum of forces in x and y code, but not in your sum of moments code.

## Geometry Operations
Unless you have completed your Structure_Operations.py file correctly and uploaded it, you may be unable to continue with testing your Geometry_Operations.py file.
You will complete your Geometry_Operations.py file in two different homework assignments. 
After both, you will upload Geometry_Operations.py here.
In the first, Geometry_Operations.py will only be partially completed.
If you completed it correctly, you will see a check mark next to "Test Geometry Operations Part1 with unittest" but an error on "Test Complete Geometry Operations with unittest".
Otherwise, click on the error button for "Test Geometry Operations Part1 with unittest" to determine which functions you had that fail and proceed accordingly.

When you successfully complete the final Geometry_Operations.py homework and have uploaded it and your Structure_Operations.py file, you should finally receive a green check mark on your GitHub action indicating that these two files are functioning correctly.

# Grading
To test that your files are correct, please upload them here. 
To get full credit for the project submissions, you will need to upload your Python files on Learning Suite.
To get full credit for assessments, you will either need to submit your Python file **AND** a screenshot of your GitHub screen indicating that your file completes the required tests, **OR** you will need to upload your Python file **AND** send me or a TA an e-mail requesting to meet to get help in completing the assignment.
Without doing both of these, you will not receive credit for your assessment submissions.

# GitHub Testing Hours
As a final note, you are allocated 2000 minutes per month to test your software on GitHub.
Each of these submissions should take at most a minute, which means you could have up to 2000 of these submissions.
You will also need to submit your results for Project 2.
Please be prudent in the number of submissions you complete so that you do not max out the number of hours you can use for GitHub testing. 
If you do max out these hours, you will no longer be able to test your results, though you will still be expected to complete the appropriate assignments and projects.
