In Class exercise
============
1. Open Processing and copy the code from Thingies.pde into Processing.
2. Save your programs as "ThingiesProgram" or just "Thingies" but NOT "Thingy."
3. Open a new tab in processing and name the file "Thingy.java." Copy in the code for the Thingy class.
6. Run the program. You should get an error message that says `The field Thingy.myX is not visible` because the *client* code in `setup()` is trying to access `private` member variables.
7. Fix the program by 
  * finishing the four setter and getter functions in `Thingy.java`
  * rewriting the *client* code in `setup()` to use the four setter and getter functions
8. The finished program should print `Distance between bob and mary is 56.568542`
9. Show your teacher the finished program.
