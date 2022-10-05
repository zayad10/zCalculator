## zCalculator
This is my second year project for CS2800, Software Engineering. Ive been assigned the task to create a graphical calculator program which evaluates both Infix and Postfix expressions, outputs error messages depending on the error case, aswell as reset the answer(clear the answer), set the type (infix or postfix) of operation.

## Version
* Version 0.1 - Tag creation for the first vertical slice. First release of the Calculator.
* Version 0.2 - Version with GUI View.
No functionality implemented yet but text input-able and buttons click-able. Initial Gui Release.
* Version 0.22 - Changed the Calculate Button to blue colour for a better looking Gui.
* Version 0.24 - Added an additional button called "Reset" which will reset the answer to 0 upon clicking.
* Version 0.3 - This release has a bug fix which stopped users being able to interact with the calculator. The buttons now have some functionality.
* Version 0.4 - Includes Evaluate function of Infix expressions and bug fixes to handle differnet types of exceptions such as Empty Expression being input.
* Version 0.5 - Includes a bug fix with "test" being printed on the command prompt upon execution.
Includes new functionality such as evaluation Postfix Expressions and toggling between the two types when evaluating expressions.
* Version 0.6 - includes Version number and brand name in the application title for added Business Value.
Improved GUI Design for better user experience.
* Version 0.7 - More user friendly with a new textField which displays the current Operation Mode (Infix or Postfix) so that users know which mode is currently selected.
Also implemented a new static variable for the the version number which makes it easier to set the version number of new releases.
* Version 0.72 - Fixed a bug in which dividing by 0 would give an answer of infinity rather than throw an InvalidExpression exception.
Also added a missing space in the title of the calculator.

## Project status
I have been able to implement all of the requirements of the Graphical Calculator aswell as the features to make it work successfully. It is successful in evaluating postfix and infix expressions, handling and outputting specicialised errors based on different illegal expressions, and reset the answer (clear the answer field). The Graphical Calculator was tested multiple times with multiple releases and is very functional however I was unable to implement the AsciiView thus far.

## How to use
The calculator named zCalculator is very easy to use. The calulator has a very simple and easy to use Graphical User Interface with functional clickable buttons "Calculate", "Reset Answer", "Infix" and "Reverse Polish(RPN)". In order to use the calculator, you must first select a mode of operation, either click Infix for Infix expression evaluation or "Reverse Polish(RPN)" for PostFix expression evaluation. Next, you must observe whether the Current Mode text field displays the correct mode you would like to use. Afterwards, you may enter an expression of the corresponding mode you have chosen into the expression text field and then click "Calculate", if you would like to clear the answer field, click on "Reset Answer". The calculator is susceptible to user errors, you must ensure that the correct mode is displayed next to the "Current Mode" text field and that the expression you enter is of the correct type. For example, you may not enter a PostFix expression whilst you have "Reverse Polish(RPN)" mode enabled. In addition, in order to evaluate expressions, there must be single spaces in between each character of input, for example, "2 + 4" and "( 2 + 2 )" is valid however "2+2" and "(2+2)" is invalid.



