# Simple-DFQ-Apps

This is one of my favorite small projects from highschool; I was finishing up a differential equations course and learning 
node.js with HTML/CSS, I decided to make a couple of small calculators for a few of the more simple problem types in the course.
The objective was to make something that allowed me to check my work if I used random numbers as coefficients for made up 
problems that I didn't already have the solution to from my text book.

The math and functionality is written in a few lines of JS within each HTML page, and I found the equations used to convert the
inputs from the user to solutions to the differential equation just by writing out the general differntial equation and 
expressing the coefficients of the solution in terms of the arbitrary input variables. 

There are three mini apps that each solve a type of differential equation: eulerEq solves a second order Cauchy-Euler Equation,
linsolve solves a second order linear homogeneous equation, and systemsolver solve a linear system of differential equations 
in the form x'=Ax, with A being only a 2x2 coefficient matrix.

As for the design for the HTML pages, I wasn't going for any particular style, I mostly just wanted to decently space the input
fields and play around with a gradient background :)

As mentioned above, I was learning node.js at the time so all of the three apps are deployed on heroku:

Euler Equation: https://murmuring-shelf-51306.herokuapp.com/

2nd Order Linear Homogeneous ODE: https://polar-sands-48289.herokuapp.com/

2x2 Linear ODE System: https://damp-earth-90167.herokuapp.com/
