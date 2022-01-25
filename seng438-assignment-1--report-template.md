>   **SENG 438 - Software Testing, Reliability, and Quality**

**Lab. Report \#1 – Introduction to Testing and Defect Tracking**

| Group \#2:       |   |
|-----------------|---|
| Student Names:  |  Andres Caicedo |
|                 |  Evyn Rissling |
|                 |  Kyle Hasan |
|                 |  John Abo |

**Table of Contents**

(When you finish writing, update the following list using right click, then
“Update Field”)

[1 Introduction	1](#_Toc439194677)

[2 High-level description of the exploratory testing plan	1](#_Toc439194678)

[3 Comparison of exploratory and manual functional testing	1](#_Toc439194679)

[4 Notes and discussion of the peer reviews of defect reports	1](#_Toc439194680)

[5 How the pair testing was managed and team work/effort was
divided	1](#_Toc439194681)

[6 Difficulties encountered, challenges overcome, and lessons
learned	1](#_Toc439194682)

[7 Comments/feedback on the lab and lab document itself	1](#_Toc439194683)

# Introduction

In this lab we explored different techniques used to test software. Exploratory testing is the more intuitive and natural technique to use since it is one of the first techniques you would think of when testing a software system. We explored manual scripted testing and it mainly reminded us of unit testing since we are testing specific functionalities individually. We revisited the defects reported for an updated version of the software to see if all bugs were fixed or if any new defects were introduced.   

# High-level description of the exploratory testing plan

We wanted to focus on generic input testing as well as withdrawing and depositing from every type of account available in the system. We also wanted to test boundary cases for each interaction such as depositing and withdrawing large sums of money or amounts of money that either the machine or account didn't have. Testing inputs not shown on the screen as well as consistent behaviour between card 1 and card 2 were also important in our plan as an inconsistent ATM would lose money in transactions. 

# Comparison of exploratory and manual functional testing

Manual functional testing is noticibly more structured and refined than the exploratory testing method. The exploratory testing seemed to possess a greater capability for catching niche bugs that might not appear on most manual tests as many times the circumstances for them to occur were very specific. Exploratory testing was also quick to perform, but this speed of testing was countered by defects being more challenging to log because of the less structured testing plan. Manual testing made it easier to keep track of defects since the structure allowed for better logging of each testcase. This streamlining of the test execution comes at the cost of time and effort as the team is required to both write a test suite for the software under test and manually execute every test in the test suite. This means the manual functional testing has a higher time overhead when compared to the exploratory method. However, this extra time helps to develop a more comprehensive test suite with more code coverage which is a notable benefit when compared to the exploratory testing. Overall, the manual functional testing helps to streamline the testing progress whereas exploratory testing allows a quick exploration of the system's shortcomings. 

# Notes and discussion of the peer reviews of defect reports

As soon as a bug report was submitted we had our partner recheck the format of the report. This was to ensure that the reports submitted had enough information to properly deduce what was causing the defect and why it was occurring. We tried to stick the suggested format for bug reports that the lab manual proposed, each one containing the function being tested, the initial state of the program, what steps are necessary to reproduce the bug, and the expected outcome (or oracle) as well as the actual outcome of the test being performed.  

# How the pair testing was managed and team work/effort was divided 

In our pair testing, one partner was chosen to navigate the software and share their screen while the other partner chose the test cases and logged each defect. For the exploratory testing, each partner helped to think of effective and efficient tests of the system's requirements while reporting the defect soon after it occurred. The manual functional testing was performed in pairs once again by one partner navigating the software and the other member going down the test suite and telling the other what to do for each test. This allowed each partner to observe the tests from a different perspective, allowing more bugs to be caught than if just one person was testing the system.  

# Difficulties encountered, challenges overcome, and lessons learned

The lack of format for the exploratory testing was hard to report and keep track of as the circumstances that caused the bug were less structured. Although exploratory testing proved to be more effective at finding niche bugs, the issues with keeping track of them was a problem. This problem was remedied by submitting the defect report for each bug as soon as the defect was found. We learned that while manual scripted testing takes more time to set up, it streamlines testing process and allows for easier documentation and communication. 

# Comments/feedback on the lab and lab document itself

We thought that the submission through Github for a formal report is not as suitable. This is mainly due to the limitations in formatting and spellchecking. We believe that a PDF file submission would be clearer and easier to do. The lab had plenty of information to guide us through it though and it was very comprehensive. 
