# User Guide: Grade Calculator

## Introduction
This program is a Grading Calculator. It's meant to help students figure out how well they are doing in class, instead of trying to do the math themselves. Just type in your scores, and this will tell you your percent and final grade letter 

## Getting Started
To use this program, you will need to build it first. Please follow the "How to Build" instructions in the main README.md file of this repository. Once built, run the program to see your greeting and start entering data.

## Step-by-Step Walkthrough
1. **Total Points Possible:** When you first run the program, you are prompted to enter the total number of points available in the entire course (e.g., 1000). This should be a whole number.
2. **Grading Scheme:** The program will ask for the minimum points needed to earn an A, B, C, and D. Enter these numbers one by one as prompted. (e.g., A = 900, B = 800, and so on.)
3. **Grade Calculation:** - First, type the **Name** of the assignment (e.g., Homework 1). Then type the **Score** you earned (e.g., 95). Till you've input all your scores and Names into the program.
4. **Stopping the Program:** When you have no more assignments to enter, type any **negative number** (like -1) for the score. This tells the program to stop and calculate your final grade from Highest to Lowest

**This is a sample of what should be displayed on your screen**
```text
Good Evening!

Welcome to Your Grade Calculator!

Grading Scheme Setup
====================
Please input the Total Points Possible: 100
Please input the Minimum Points for a 'A': 90
Please input the Minimum Points for a 'B': 80
Please input the Minimum Points for a 'C': 70
Please input the Minimum Points for a 'D': 60

The Grading Scheme You Input
============================
Total Points Possible in the Course: 100
Points needed for an 'A': 90
Points needed for a 'B': 80
Points needed for a 'C': 70
Points needed for a 'D': 60

Grade Calculation
You will be prompted to input scores for all assignments.
(Input a negative number to cease input and calculate letter grade.)

Please input the points earned for Assignment 1: 10
Please input the name for Assignment 1: hmwrk 1
Please input the points earned for Assignment 2: 15 
Please input the name for Assignment 2: quiz 1
Please input the points earned for Assignment 3: 18
Please input the name for Assignment 3: Test 1
Please input the points earned for Assignment 4: 6
Please input the name for Assignment 4: hmerk 2
Please input the points earned for Assignment 5: 10
Please input the name for Assignment 5: quiz 2 
Please input the points earned for Assignment 6: 15
Please input the name for Assignment 6: test 2
Please input the points earned for Assignment 7: -1

Assignments Sorted by Score (Highest to Lowest)
===============================================
Test 1: 18 points
quiz 1: 15 points
test 2: 15 points
hmwrk 1: 10 points
quiz 2 : 10 points
hmerk 2: 6 points


Final Results
Total Points Earned: 74
Total Points Possible: 100
Total Percentage: 74%
Final Letter Grade: C
