# ABAP_PROJECTS

*Repository for Projects based on ABAP Programming language.*

## License
This project is licensed under the [MIT License](https://github.com/greltel/ABAP-PROJECTS/blob/Main/LICENSE). See the LICENSE file for details.

## Motivation for Creating the Repository

The motivation for creating the current repository was my desire to share my knowledge and progress in ABAP.
I would be very happy if through this initiative, I could help ABAPers to develop their skills and increase their productivity.
I strongly believe that because the number of ABAP Developers is limited, our libraries and code foundings must be shared. 
Any suggestions are always welcome regarding code optimization, addition of new functions or even ideas for projects.

## Contributors-Developers

The repository was created by George Drakos.

## Design Goals

* Copy-Paste Installation
* Code based on New ABAP Syntax. 7.50 and later
* Comments throughout the Code(when necessary)
* Public repository
* No Text Elements-Selection Texts must be created.

## Project 1: Dynamic SALV Console

Display any table using cl_salv_Table alv. Scope of this project is to create a cl_salv_table based alv which is
as dynamic as possible. There are no data declarations(wherever possible), no custom screen, no gui status etc.
Also many custom functions have been added to ALV toolbar like custom details screen( se16n inspired ), 
hide/show empty columns of table and edit button. The whole point of this project is to reveal the real potential of 
cl_salv_table based ALV even though there are limitations compared to cl_gui_alv_grid. We call this project Console because
you can use it as a utility to display any table of the system plus display your own Excel file.

## Project 2: Dynamic XML To Internal Table

Upload XML file and map it directly to Internal Table.

## Project 3: Dynamic Count of Unique-Multiple Values of Internal Table

Use the Static Class Method to Retrieve Unique and Multiple values of Any Table.

## Project 4: Dynamic Texts Export

Download any Text Object of SAP System into Excel File directly.

## Project 5: Dynamic Input-Output Convertion

Dynamically convert a DDIC value to Input/Output format.

## Project 6: Dynamic Split of Table into Smaller Ones

Split Internal Table into Smaller ones specifying split segments.
Especially useful for parallel processing tasks.
