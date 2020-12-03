#Lesson 4: Data Frames and More Functions

You might have been wondering about the other things that a health tracker app collects. What about hours of sleep? What about distance walked? What about heart rate?

We could store all of this information in separate vectors, and in fact that's what we are going to do.

To keep all of these vectors in one place when we're coding, we can use data frames. Think of a data frame as a data table and a vector as a column in that table.

For our app, we've made a data frame with sample health data and named it `tracker`. Type its name in the window below to view it.

**DF**

Note that each row represents the step count, heart rate, distance, and amount of sleep for a different day. For now, you don't have to know how to create a data frame. But it's useful, when you're coding,  to know how to use them.

To view one variable of a data frame, we use `$`. For example, you could type `df$var` to view a variable named `var`. What do you think `df` stands for?

Try viewing just the `heart_rate` variable from our data frame.

**DF**

Well done! Next, let's try using a new function. Many functions are meant to work with data frames. So, they take at least two arguments:

* the data frame you are analyzing
* the column you want to focus on

Use the `arrange()` function to sort the data in ascending order by `distance`.

**DF**

Notice that since each row represents one day's data, all the data from that day (row) moves together when we rearrange the data frame.

What if we want to see the longest distance first? We can use the `desc()` function to arrange distance from highest to lowest.

Try using `arrange()` and `desc()` together to view the longest distance first

**DF**
