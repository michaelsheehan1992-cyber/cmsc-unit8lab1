# Lab Reflection: Unit 8 Lab 1 - Git Version Control + Debugging (BuggyProgram)

## Student Name
Michael Sheehan

## GitHub Repository URL
https://github.com/michaelsheehan1992-cyber/cmsc-unit8lab1.git

---

# Commit 1: Initial Commit

## What did you include in this commit?
- I commited the entire unit8_lab1 folder

## What was the purpose of this commit?
-Starting point for debugging in case I need to go back and start over.

---

# Commit 2: Task 1 (getGrade)

## Which tests in Task1Test were failing before your fix?
-testGrades and testEdges failed.

## What was the issue in the code?
-In-correct order, Exceeds and Meets were reversed and it was missing =.

## What change did you make to fix it?
-Corrected the order so 90 or higher returned exceeds.

## How did the tests help guide your fix?
-

---

# Commit 3: Task 2 (sumEvenNumbers)

## Which tests in Task2Test were failing before your fix?
-testEmpty, testOddNumbers, and testSumEvenNumbers 

## What was the issue in the code?
-An array that didn't exist was being access and the sum needed to be 0 instead of 1

## What change did you make to fix it?
-Sum changed from 1 to 0 and removed the =

## How did the tests help guide your fix?
-ArrayIndexOutOfBoundsException was an error

---

# Commit 4: Task 3 (sumRange)

## Which tests in Task3Test were failing before your fix?
-testSumRangeReverseOrder 

## What was the issue in the code?
-Loop was incomplete, reversing the order caused the loop to fail.

## What change did you make to fix it?
-Added both directions for counting up and down when less than or equal to.

## How did the tests help guide your fix?
-Reverse-order test failed so I only had to fix descending numbers.

---

# Overall Reflection

## Which task was the easiest to fix? Why?
-

## Which task was the most difficult? Why?
-

## How did Git help you track your progress through the debugging process?
-

## Why is it important to make small, frequent commits when debugging code?
-

## What did you learn about using JUnit tests to guide debugging?
-

---

# Commit 5: Final Reflection

## What did you complete or update before making this final commit?
-debugging tasks, JUnit passes, and updated README.md

## Why is it useful to document your work after completing a programming task?
-An order of fixed code so if it happens again it can be reviewed for future programs
Also, tells others why/what it was changed.