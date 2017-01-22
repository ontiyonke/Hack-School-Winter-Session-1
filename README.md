# Welcome this is the official repo for project 1
##UCLA ACM HACK

If you've missed the first session, check out the blog post first: http://hackucla.com/blog/session-1-intro-to-android/

##What do I turn in
For beginners you can should solve all of the listed short exercises and receive points for completing those. These are unrelated to the project skeleton in this repo. For intermediate/advanced students you can work on the weekly project with your team, and receive points for completing that. You can only get credit for one or the other, but not for both so choose the one most appropriate for your skill level. Please only submit one .zip file per team. Include the contents of your entire android project, and also provide your team access code (Found on Hack School Dashboard) in a text file. Otherwise you will not receive credit! 

##Grading
Projects will be due 1 week from the session, but we will accept late submissions taking some points for each day it is late. The lateness penalty for an assignment that is submitted between N and N+1 full days late (where N is nonnegative) is 2^N % of the assignment's value. That is, the penalty is 1% for being up to 1 day late, 2% for being from 1 to 2 days late, 4% for being from 2 to 3 days late, and so forth.

##Beginner Project

####Exercise 1: TextView
Create a TextView, “I Love Android!” and style it too.

####Exercise 2: Button
Create a button that outputs how many times the button has been clicked, if this count is greater than or equal to 3 times.

#####Hints
* Don’t forget to create the button in activity_main.xml
* How do you refer to this button?
* You can create a count variable in your setOnClickListener function, (above the onClick function)
* You can use if statements that are similar to C++

####Exercise 3: TextField (EditText)
Given user input into an EditText field, create a Toast with this input on button click. Note: A toast is a way to display information as a popup.

#####Hints
* Toast.makeText(getApplicationContext(), string, Toast.LENGTH_LONG);
Toast.show();
* Call getText().toString() on your textfield to get your input
* Don’t forget to properly create your button and EditText fields.

####Exercise 4: ImageView
Add another image resource and upon clicking a button, change from the original image to this new image.

#####Hints
* Your new image also belongs in drawable > src
* You only need one ImageView for this exercise
* Consider changing the source of this ImageView
* Look up the setImageResource() function


##Intermediate/Advanced Project
The project is for intermediate/advanced students. If you are feeling confident you can attempt to 
complete the project without the skeleton, but it will be a lot easier to use it. We will be uploading the project solution later on, so if you haven't cracked it by then look at the solution to learn the correct implementation.

###Hints
* Start with the xml layout. 
* Add missing textviews and image buttons for the other 
two professors, you should base their styling off the first one. 
* Add ID’s for UI objects that you want to interact with in the code.
* Finally go to the Main Activity to setup all the components, and add the correct 
behavior for random quote generation.

###End Product Goal
![Quote Generator](https://s3-us-west-1.amazonaws.com/acm-hack-ghost/2017/01/hack-school-winter-project1.png)
