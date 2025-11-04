# ECON 833: Computational Methods for Economists (Fall 2025) #

|  | [Jason DeBacker](http://jasondebacker.com) |
|--------------|--------------------------------------------------------------|
| Email | [jason.debacker@moore.sc.edu](mailto:jason.debacker@moore.sc.edu) |
| Office | 427B DMSB |
| Office Hours | Tuesday 2:45-4:45 pm and Thursday 2:45-3:45 pm; or by appointment |
| GitHub | [jdebacker](https://github.com/jdebacker) |

* **Meeting day/time**: T,Th 1:15-2:30am, DMSB, Room 108

## Course description ##

This course is designed to introduce PhD students to software applications and computational techniques to make them productive researchers. Students will be exposed to leading open source software packages (Python, R) and techniques for numerical computing and data analysis. The course will be taught through the application of these software packages and methods to economic research in applied microeconomics and quantitative macroeconomics.


## Course Objectives and Learning Outcomes ##

In this course students, through lecture and application, students will learn about:
* Software to increase research productivity including:
	* TeX
	* git
	* Python
	* R
* How to write custom estimation routines and use packages written by others for:
	* Generalized method of moments estimators
	* Maximum likelihood estimators
	* Maximum score estimators
	* Reduced form estimators such as regression discontinuity design
	* Simulated method of moment estimators
* Computational methods to:
	* Optimize and find roots of functions
	* Apply machine learning tools to economic and econometric models
	* Solve dynamic programming problems (discrete and continuous choice)
	* Solve general equilibrium, heterogeneous agent models
	* Perform Monte Carlo simulations
	* Bootstrap standard errors
	* Compute numerical derivatives
	* Use just-in-time compilation for efficient computation
	* Run computations in parallel using multiple processors
* Coding and collaboration techniques such as:
	* Writing modular code with functions and objects
	* Collaboration tools for writing code using [Git](https://git-scm.com/) and [GitHub.com](https://github.com/).
	* Best practices for Python coding ([PEP 8](https://www.python.org/dev/peps/pep-0008/))


## Grades ##

Grades will be based on the categories listed below with the corresponding weights.

Assignment                   | Points |   Percent  |
-----------------------------|--------|------------|
Problem Sets                 |   80   |    80%   |
Final Project                 |   10   |    10%   |
Class Participation                |   10   |    10%   |
**Total points**             | **100** | **100.0%** |

* **Homework:** I will assign 9 problem sets throughout the semester.
	* You must write and submit your own answers, although I encourage you to collaborate with your fellow students. I **DO NOT** want to see a bunch of copies of identical answers. I **DO** want to see each of you learning how to code these problems so that you could do it on your own.
	* Problem set solutions, both written answers and source code, will be turned in via a pull request from your private [GitHub.com](https://git-scm.com/) repository which is a fork of the class master repository on my account. (You will need to set up a GitHub account if you do not already have one.)
	* Written solutions must be submitted as pdf documents or Jupyter Notebooks.
	* Problem sets will be due on the day listed in the Daily Course Schedule section of this syllabus (see below) unless otherwise specified. Late homework will not be graded.


## Daily Course Schedule ##

| Date     | Day | Topic                               | Due    |
|----------|-----|-------------------------------------|--------|
| Aug. 19  | T  | Work Flow, Productivity Software    |        |
| Aug. 21  | Th   | Using AI in Research    |        |
| Aug. 26  | T  | Python/OOP                          | [PS #1](https://github.com/jdebacker/CompEcon_Fall25/blob/main/Productivity/PS1.pdf)  |
| Aug. 28  | Th   | Python/OOP                          |        |
| Sept. 2  | T  | Visualization tools |     [PS #2](https://github.com/jdebacker/CompEcon_Fall25/blob/main/Python/PS2.pdf)   |
| Sept. 4   | Th  | Numerical Optimization Theory       |   |
| Sept. 9 | T   | Numerical Optimization Theory | [PS #3](https://github.com/jdebacker/CompEcon_Fall25/blob/main/Visualization/PS3.pdf)  |
| Sept. 11 | Th  |  Optimizers, Root-Finders in Python  |      |
| Sept. 16 | T   | Optimization Application: GMM  |       |
| Sept. 18 | Th  | Two-Sided Matching Models       |        |
| Sept. 23 | T   |    Econometrics in Python                 |   |
| Sept. 25 | Th  | Programming in R                  |   [PS #4](https://github.com/jdebacker/CompEcon_Fall25/blob/main/Optimization/PS4.pdf)     |
| Sept. 30   | T   | Maximum Score Estimators                       |      |
| Oct. 2   | Th   | Review/Catch up       |       |
| Oct. 7  | T  | Machine Learning                |   [PS #5](https://github.com/jdebacker/CompEcon_Fall25/blob/main/Econometrics/PS5.pdf)      |
| Oct. 9  | Th   |   No class, Fall Break     ||
| Oct. 14  | T  | Machine Learning     |        |
| Oct. 16  | Th   | Machine Learning     |    [PS #6](https://github.com/jdebacker/CompEcon_Fall25/blob/main/Matching/PS6.pdf)     |
| Oct. 21  | T  | Machine Learning     |  |
| Oct. 23  | Th   | Machine Learning                 |        |
| Oct. 28  | T  | Dynamic Programming                 |      |
| Oct. 30   | Th   | Dynamic Programming              |  [PS #7](https://github.com/jdebacker/CompEcon_Fall25/blob/main/MachineLearning/PS7.pdf)   |
| Nov. 4   | T  | Discrete Choice Dynamic Programming      |         |
| Nov. 6  | Th   | TBD    |      |
| Nov. 11  | T  | Simulated Method of Moments          |        |
| Nov. 13  | Th   | Intro to Neural Networks             |        |
| Nov. 18  | T  | Overlapping Generations Models                  |        |
| Nov. 20  | Th  |   Overlapping Generations Models             |        |
| Nov. 25  | T   | No class, Thanksgiving      |  |
| Nov. 27  | Th   | No class, Thanksgiving     |  |
| Dec. 2   | T   |   Deep Nets in DPPs   |       [PS # 8](https://github.com/jdebacker/CompEcon_Fall25/blob/main/DynamicProgramming/PS8.pdf) |
| Dec. 4   | Th   | Deep Nets in DPPs     | [PS # 9](https://github.com/jdebacker/CompEcon_Fall25/blob/main/OverlappingGenerations/PS9.pdf)       |
|          |     |                                     |        |
| Dec. 11  | Th   | No Final Exam - **final project due**         |  [Final Project](https://github.com/jdebacker/CompEcon_Fall25/blob/main/FinalProject.pdf) |


## Helpful Links ##

* [QuantEcon](https://quantecon.org)
* [Notes on Machine Learning & Artificial Intelligence](https://chrisalbon.com) by Chris Albon
* Materials from Open Source Economics Lab Boot Camps: [2017](https://github.com/OpenSourceEcon/BootCamp2017), [2018](https://github.com/OpenSourceEcon/BootCamp2018), [2019](https://github.com/OpenSourceEcon/BootCamp2019)


## Reasonable Accommodations for Students with Disabilities: ##

If you have any condition, such as a physical or learning disability, which will make it difficult for you to carry out the work as I have outlined it or which will require academic accommodations, please notify me through email AND in person with the appropriate documentation within the first two weeks of the course.
