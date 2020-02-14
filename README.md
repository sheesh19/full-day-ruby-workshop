# Welcome to the Full Day Ruby Workshop! 💎


Solve the following challenges with your workshop buddy (pair programming).

Here are the [Slides with Examples](https://bit.ly/2XVdfpl)

Cheatsheet for [Mac & Linux Users](https://www.slideshare.net/paalringstad/command-cheatsheets-mac)

Cheatsheet for [Windows Users](https://www.slideshare.net/paalringstad/command-cheatsheets-windows-138186563)


You can either use an online tool: 
Use the online Ruby compiler [here](https://repl.it/languages/ruby)

OR

If you have downloaded a text editor like [Sublime](http://www.sublimetext.com/3) & downloaded Ruby you can: 

1. Create a new file <example_name.rb>
2. Run your ruby file from your terminal with "ruby <example_name.rb>"


---

### Section 1 | Data Types & Variables

---

**Challenge 1 - Integers**


Create a new variable. Assign it to an integer. 
Create another variable. Assign it to another integer. 
Print out the results of the following: 
1. Add the two variables together
2. Subtract one variable from the other
3. Multiply the two variables together
4. Divide one variable from the other


**Challenge 2 - Strings & Concatenation**


Create a new variable. Assign it a string value. 
Create another variable. Assign it to another string value. 
Concatenate (add) the two strings together. Should there be a space between the two strings? If so, add in the space as well.


**Challenge 3 - Strings & Interpolation**


Create a new variable called `name` which is assigned to your own name.  
Print out a string that says `Hello, your_name - welcome to coding!` . Replace `your_name` with the variable `name` via interpolation (i.e. `#{variable_placed_here}`).


**Challenge 4 - Arrays**


Create a new variable.
Assign your variable to an array full of animals. Have at least 4 animals in your array. 
Add another item into your array. Use the `<<` syntax. 
Add another item into your array. Use the `+` syntax.


**Challenge 5 - Arrays & Indices**


Use the array below:

`students = ["Draco", "Harry", "Hermione", "Frodo", "Samwise"]`

1. Print out the first student of this array.
2. Print out the third student of this array. 


**Challenge 6 - Arrays & Values**


`students = ["Draco", "Harry", "Hermione", "Frodo", "Samwise"]`

Print out the first letter of the first element of this array. 

---

### Section 2 | Conditionals, Loops, & Iterators

---

**Challenge 7 - Conditionals**

`students = ["Draco", "Harry", "Hermione", "Frodo", "Samwise"]`

Print out the second element of the array, but only after having checked if it starts with an "H". Use an if statement.


**Challenge 8 - Loops & Each Iterator**

`students = ["Draco", "Harry", "Hermione", "Frodo", "Samwise"]`

1. Print out all names in this array using `for`.
2. Print out all the names in this array using `while`.
3. Print out all the names in this array using `each`.



**Challenge 9 - Conditionals & Iterators**

`students = ["Draco", "Harry", "Hermione", "Frodo", "Samwise"]`

Time to combine everything you learned! Print out all names that start with an "H". You must use an `each` loop and an if statement. 

---

### Section 3 | Methods

---

**Challenge 10 - Methods**

students = ["Draco", "Harry", "Hermione", "Luna"]

Create a method that prints out all students names (on one line) that start with a specific letter. The method must take two parameters: 1) An array of students 2) A letter

**Challenge 11 - Methods**

Create a method called `dating_app` that takes 2 or more aguments (hobbies, age, IQ, sense of humor, etc.). This method should let you know whether the person is a good match for you. 😉

---

**Challenge 12 - User Input**

Create a new file named `user_input.rb`. 
1. Puts out a line to your terminal. 
2. Save user input to a variable. Make sure to use `gets.chomp`
3. Puts out the user input back to the terminal. 
4. Run the program with `ruby user_input.rb` and make sure it works! 

---

### Section 3 | Create a Ruby Program

---

1. Create a new folder
2. Inside the new folder, create a new file `interface.rb`
3. Inside the folder, create another file `responses.rb`
4. Run your ruby file from your terminal with `ruby responses.rb`

**Challenge 12 - Create Your Interface**

Open your `responses.rb` file in Sublime. 

Let's build a terminal application that takes inputs from users and responds directly in the terminal. 

1. Create a new method called `response`. Have it take one parameter- which will be a sentence from the user. 
2. Lets create the conditions: 
- If the parameter is `I will take the Ring to Mordor.` Return with `You have my bow and my axe.`
- If the parameter is `You're a wizard, Harry.` Return with `I'm a what?`.
- If the parameter ends with a "?", return with `I'm the captain now!`. 
- If the parameter is `Gotta catch em all.` return with `Pokemon`. 
- If the parameter is `G'day, mate`, return an empty string: `''`. 

3. Test out your code! Call the method at the bottom of your `responses.rb` file and provide different parameters to see if your code works- make sure each of the scenarios work. 


4. Next, navigate to your `interface.rb` file. At the top, write `require_relative 'response'`. This will let you use the code in the `response.rb` file. 
5. Next, write an intro line for your code. Print this line to your terminal. Test that it works by running `ruby interface.rb` in your terminal- you should see your intro line on your terminal. 
6. You want the program to take user input. Make sure to ask for input & save the user input to a variable. 
7. How can you pass the user input & get the `response` method to response? How do you call the method? Call the method & save the result to a variable. 
7. Next, we'll use `while` loops! We want the program to loop until the the `response` method returns an empty string: `''`. 
8. Puts out a final line to end the program. 
9. Run your `interface.rb` file with `ruby interface.rb` & make sure your application work!

