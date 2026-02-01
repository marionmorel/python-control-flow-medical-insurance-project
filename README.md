# Python Control Flow: Medical Insurance Project
## Data Scientist: Analytics - Codecademy

In this project, you will examine how factors such as age, sex, number of children, and smoking status contribute to medical insurance costs.

You will apply your knowledge of Python control flow to write code that gives people advice on how to lower their medical insurance costs.

### Tasks

1. First, take a look at the code in script.py.

The function <code>estimate_insurance_cost()</code> estimates the medical insurance cost for an individual, based on four variables:

* <code>age</code>: age of the individual in years
* <code>sex</code>: 0 for female, 1 if male
* <code>num_of_children</code>: number of children the individual has
* <code>smoker</code>: 0 for a non-smoker, 1 for a smoker

These variables are used in the following formula to estimate an individual’s insurance cost:

*insurance_cost* = 400 ∗ *age* − 128 ∗ *sex* + 425 ∗ *num_of_children* + 10000 ∗ *smoker* − 2500
​ 
Click “Save” to see the estimated medical insurance cost for Keanu, a 29 year-old male smoker with three children.

2. Currently, our function prints out the estimated insurance cost based on the values passed into the function. But it doesn’t do much beyond that.

It would be much more helpful if our function could provide more insight into how we can lower our insurance cost. We’ll learn to do exactly that by using control flow – <code>if</code>, <code>elif</code>, and <code>else</code> statements – in our code.

When you’re ready, move on to the next step.

#### Analyzing Smoker Status

3. In general, insurance costs are higher for smokers. We can use data from the <code>smoker</code> variable to provide advice on how to lower insurance costs.

Let’s create a function that analyzes an individual’s smoking status.

At the top of your code, define a function called <code>analyze_smoker()</code> that takes an input <code>smoker_status</code>. For now, the function should print <code>smoker_status</code>.

4. Inside of the <code>analyze_smoker()</code> function, replace the print statement you wrote in the previous step with an <code>if/else</code> statement that does the following:

If <code>smoker_status</code> is equal to <code>1</code>, print <code>"To lower your cost, you should consider quitting smoking."</code>
Otherwise, print <code>"Smoking is not an issue for you."</code>

5. Now that we’ve written the <code>analyze_smoker()</code> function, let’s make use of it.

In the <code>estimate_insurance_cost()</code> function, go to the line of code that prints the estimated insurance cost. On the next line, make a function call to<code> analyze_smoker()</code>, passing in the <code>smoker</code> variable as an argument.

Click “Save” to see the result.

#### Analyze your own insurance cost

6. Now that we’ve estimated and analyzed Keanu’s insurance cost, let’s see if we can do the same for our own!

At the bottom of your code, create a new insurance cost variable for yourself, similar to how we did it for Keanu.

Set the variable equal to a function call to estimate_insurance_cost(), passing in your own age, sex, number of children, and smoker status.

Click “Save” to see the result. Do you see any ways that you can potentially lower your insurance cost?

#### Extra

7. Great job! In this project, you used control flow in your code – using <code>if</code>, <code>elif</code>, and <code>else</code> statements – to provide advice on how individuals can lower their medical insurance costs.

As a data scientist, it’s important to have an understanding of control flow as you’ll eventually work with and build complex decision tree algorithms. You are now better equipped to move forward in your data science journey!

If you’d like additional practice on control flow, feel free to experiment with ways you might extend this project!

Happy coding!