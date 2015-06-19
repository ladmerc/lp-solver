# lp-solver
A Python app that solves a linear programming problem using the two-phase method. The underlying solver is scipy's optimize.linprog. JQuery does all the front end heavy-lifting: generates the required tables, transforms the data to a format suitable for scipy.optimize.linprog, handles frontend validation. Flask handles request to and fro the server - serves webpage, handle routing, etc

Server validation not yet implemented. Just a demo app. 

##TODO
1. Server Validation
2. Cap number of constraints and decision variables
3. Choose method to solve, ie simplex or otherwise
4. View output phase by phase
5. View graph 
6. Return result in simple terms, in terms of the objective function and decision variables


