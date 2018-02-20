## Project Name:  Tax Bracket Calculator Application

### Course Title:
Web Application Development

### Assignment Date:  
February 20, 2018

### Student Name:  
Laura Wright

### Project Description:
In this project we used the if/else statement to differentiate between tax brackets; the onclick method to correspond to the user clicking on a button and having this action cause the users input to be calculated and reset; the getElementById method to reference the HTML id's that link to user's input into JavaScript, so it can be calculated and returned back to display in HTML; the getElementById method along with the innerHTML property to return original default content; the toFixed method to ensure a fixed number of decimal places is displayed; and the clearButton method to return the page to its original default settings.

### View Project:
(Replace this statement with your Github Page URL that was created when you 
 published the project.)

### Lessons Learned in the Assignment:

* The if/else statement is used when there are varying conditions, and different code needs to be executed according to each condition. For example, in this assignment there are various tax brackets and different code needs to be executed according to which tax bracket someone falls into. If the user is single, they could need the code executed for if they earn less than $9525. The code would correspond: "if" the user earned $9525 or less, a code that calculates tax for this amount would be executed. "Else if" if the user earned more than $9525 but less than or equal to $38,700, a different code would run that calculates their tax according to the next tax bracket. This continues until all possible income types have been covered in the code, including a final "else" that has code executed for a condition that does not fit into any other category already mentioned.

* The clearButton method is used to clear the input that the user has entered into the calculator. This method corresponds to a user clicking the Clear Calculator button. It then uses the getElementById method to reference the HTML id's for taxEstimate and taxBracket and then uses the innerHTML "" property to clear the users input and return it to a blank space, ready for the next set of input to be entered.

* The toFixed method is used to designate a certain number of decimal places to be displayed. It is used in conjunction with the variable that it will be affecting, by putting a period after the variable name, followed by the word toFixed() and the number of decimal points in paranthesis afterwards. In the tax calculator, the variable 'tax' is affected by the toFixed method, and to have it display two decimal places it reads tax.toFixed(2).

