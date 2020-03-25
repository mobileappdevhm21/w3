W3 Assignment - Timer
=====================
This is assignment 3 of the 'mobile applications' course at 'university of applied sciences munich'.

## Basics for this assignment
Read either on [udacity course](https://www.udacity.com/course/developing-android-apps-with-kotlin--ud9012)
and follow lesson 4 'Activity & Fragment Lifecycle'.
You also can read [04.1 and 04.2](https://codelabs.developers.google.com/android-kotlin-fundamentals/)
Go to [https://classroom.github.com/a/ljZBw4Ir](https://classroom.github.com/a/ljZBw4Ir) and accept this week's assignment.
There are no style guide-rules how the app has to look like, so feel free to experiment.

## Working with the Course Code

The basic steps are:

1. Clone the repo
2. Create your own branch, name it e.g. devlope
Tipp: Name your developement branch according to the ticket or feature you are working on
3. Read the TODOs and assignment guideline on www.moodle.hm.edu and further down below
4. Start coding and have fun

## Requirements
Create an application with a timer where you can do the following:
* Show the currently updated timer value in the activity
* Set the start value for the timer (See the dialog fragment in the code or think about an own idea)
* Start the timer via a button
* Pause the timer via a button
* Stop the timer via a button and set the timer back to its start value

The app should also have the following features:
* If you switch the app to the background the timer should pause
* If you bring the app to the foreground the timer should continue where it was paused
* If you flip the phone the timer value should not be reset
* The countdown should also be logged to the LogCat (Tipp: Use Timber as suggested in the udacity course or codelabs material)

The timer can either infinitely count up or count down, also think maybe about a limit!

!!! Do not forget commit and push your changes AND link your repository in moodle

Example how the app could look like:
<p align="center">
  <img style=max-width: 30; src="https://github.com/mobileappdevhm20/w3/blob/master/doc/timer_example.png">
</p>

## Git basics
The basics are for console users. There are also buttons for these commands in Android-Studio.
See [this](https://stackoverflow.com/questions/52565212/how-to-easy-commit-android-studio) for graphical use.

```
git clone <repository-url> - Clone a repository you want to work on
```
```
git checkout -b <new_branchname>  - check out all the content you are working on to a new branch with specified name
```
```
git checkout <branchname>  - check out to another already existing branch
```
```
git stash - store all changes made to the stash so the working directory is 'clean' and you can e.g. switch branches
```
```
git stash apply - apply all changes stored to the stash back to the working directory
```
```
git add <files>  - To add files you want to commit later locally
```
```
git commit -m "<message>" - Commit your added changes to the staging phase locally
```
```
git push - Push your changes to the remote repository
```

For interested command-line users read [this](https://git-scm.com/doc)

### How to make useful git messages (git commit -m "<message>)
* Do not make it longer than 50 characters
* Describe what you changed
* Start with a ver e.g. Added, Fixed, Removed, etc.
* Stick to either present or past tense overall your commits
Further [reading](https://dev.to/jacobherrington/how-to-write-useful-commit-messages-my-commit-message-template-20n9)

## Any further questions?
* Make posts in the [moodle](https://moodle.hm.edu) course of mobile applications
* Email the student assistant (tutor) of this course: <jeremias.wiedmann@hm.edu>
* Email the professir of this course: <gudrun.socher@hm.edu>




