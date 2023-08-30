# Bearing_Capacity_of_pile_using_python

The provided Python program is for calculating the bearing capacity of piles based on various input parameters. 
**It takes user inputs**, **performs calculations**, and** generates a report with the results**.

# Brief overview of what the program does:

The program begins by **importing required libraries** and defining functions for various tasks, such as clearing the screen, checking and installing packages, updating run counts, generating report indexes, displaying instructions, showing information about the developers, performing computations, and displaying the report index.

The computation() function is the core of the script. It calculates the bearing capacity of piles using either the Static Analysis method or the SPT (Standard Penetration Test) method. It takes user inputs related to pile and soil properties, performs the required calculations, and generates the ultimate and allowable bearing load capacity, as well as the total pile settlement.

The results are then presented to the user, and an option is provided to print the report in either CSV or XLSX format.

The show_report() function displays the report index, showing saved reports along with timestamps and comments.

The main_screen() function displays the main menu to the user, offering options to compute pile bearing capacity, access the report index, read instructions, learn about the developers, or quit the program.

The Table class is defined to help format the report index output in a tabular form with proper text wrapping.

The script also includes a check for whether it's being run as the main script, and it starts by checking and installing required packages. Then, it initializes counters and enters the main loop of displaying the main screen and handling user choices.

Please note that this script uses various input parameters that need to be provided by the user to perform the calculations. The script provides a user interface to input these values and get the corresponding results
