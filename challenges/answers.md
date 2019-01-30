1.Describe the biggest difference between .forEach & .map.
forEach:  iterates over a list and applies some operation with side effects to each list member.
map: iterates over a list, transforms each member of that list, and returns another list of the same size with the transformed members.

2.What is the difference between a function and a method?
A function is a written sections of code that when called does whatever the user has created and invokes.
A method is similar to a function that can attach to variables and execute the given command that the method holds. 

3.What is closure?
A closure is a feature in javascript where an inner function has access to the global and outer fuctions variables.

4.Describe the four rules of the 'this' keyword.
window binding: When the this keyword is used and is pointing to the window instead of a given specified object variable.
implict binding: When the this keyword is used in the same obect that the key is binded to. 
explicit binding: When using this in another object the .call or .apply method needs to be called to explicitly call what this is binding to.
new keyword binding: uses the new keyword to create a object with the same values as the parent it is copying.

5.Why do we need super() in an extended class?
The super() method needs to be used to acces the objects in the parent class. 