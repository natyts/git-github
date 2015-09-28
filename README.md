![General Assembly Logo](http://i.imgur.com/ke8USTq.png)

## Objectives
- Manage change in a project.
- Collaborate over time and space.
- Fork a repository.
- Clone a repository
- Synchronize repositories locally.
- Synchronize repositories remotely.


## Prerequisites
- Complete [Git Basics](https://github.com/ga-wdi-boston/git-basics)

## Overview 

Continuing in our project, [Git Basics](https://github.com/ga-wdi-boston/git-basics) we are going to use Github to manage a project.

Each person that is working in project will be working on their own computer. They will have a local copy of the project and will be using Git to manage change.
The challenge is to be able to manage change across all the local copies of a project distributed over multiple computers!

In order to do this we will create a repository on github that will be the definitive version of the project. This "repo" will live in a github account owned by the company or project team. This is the *project owner's repo*.

And each person/developer that would like to contribute their changes to the project will also have a github account. As we'll see we **fork** or copy the repo from the project owner's github account into our github account.

DRAW PICTURE HERE.


## Forking a Repository.

Given a project repository in an account owned by the project team we will create create a copy or **fork the repo**.

## We Do

Let's walk through [Github's fork a repo page](https://help.github.com/articles/fork-a-repo/)

## You Do 

We don't like how all the employee information is in the staff.csv files. Really, this file is a mapping between people and thier roles in a specific department.

We may have employees working in different departments and if so the employee information will be duplicated. This is a problem. We want to keep information in one place if possible. Otherwise the info or data that should be same may become different in across files.

For example, Joy Gillis is a manager in the Electrical Department but she sometime works as an associate in the Tools department. 

The record for her in Electrical is:
Joy Gillis,978-238-9894,joyg@example.com,manager

The record for her in Tools is: 
Joy A Gillis,617-987-9894,joygillis@gmail.com

The info for Joy is **inconsitent** because it's difficult to manage info in many places. It a big cause of errors.


* Create a file name employes with their info and a unique id, employee id for them.

employees.csv
Name, Phone, Email, ID

* Refer to employees by their ID's in the staff.csv files.

**Remember to create a branch for these changes/commits**

## You Do

Create a products CSV file that will hold product info.  Each product will have an ID.

Refer to the product ONLY by ID in the inventory files.


## References
* [Git Commands](command-reference.md)
* [Github's fork page](https://help.github.com/articles/fork-a-repo/)


