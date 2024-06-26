# Cpluplus-Program
### For Class 

#### Summarize the project and what problem it was solving:

The program that I am showcasing is going to be the inventory tracker program. This program takes a input file from an inventory in a store. It then has menu options to output the following: Number of times an item is present in the file. All of the items in the file in the form of a histogram with + denoting how many times each item appears. Finally a unordered list that displays the items and how many times each one appears with a number by it. 

#### What did you do particularly well?

  For this particular project I thought that I handled my input validation very well. It took me some time to get it right but I am really happy with how easy it is to read and how effective it really was. 

  #### Where could you enhance your code? How would these improvements make your code more efficient, secure, and so on?

  I could enhance my code two different ways based on my research. I could implament `std::unordered_map` instead of `std::map`  for my itemFrequencies functtion to improve the lookup, insertion and deletion performance. Another one is my use of the ANSII escape codes for formatting. This is an athestic pleasing thing that I did to make my code look better in the terminal. However, not all systems support ANSII escape codes and it wouldn't display in this case. 

   The final thing with regards to things I could do better would be enhancing my input validation. I could primarily do this using external C++ libaries such as Qt framework and Boost libaries. 

#### Which pieces of the code did you find most challenging to write, and how did you overcome this? What tools or resources are you adding to your support network?

   The most challenging thing that I ran into in this was the implamentation of the menu choice handler. I had to really think about how I would verify that the user choice was an option that was available to the user but also how I could throw an error apporpriatly with any thing else besides 1-4. I used stackoverflow, google, youtube and reddit. Stack overflow was the easiest and best out of the three that I used and now I am going to use it more in future courses and programs.

   #### What skills from this project will be partiularly transferable to other projects or course work?

  I think the skills that are going to be the most transferable are going to be refactoring code and research skills. While the documentation for most things is robust it doesn't always give the best answers to the questions that you have and being able to research a specific topic or how to implament something is quite helpful. 

  #### How did you make this program maintainable, readable, and adaptable?

  I amde this program maintainable, readable and adaptable by refactoring the code. Everything is outside of main and all main is used for is calling the functions. By doing this I clean up main and make it easier to read but also everyting is labeled and easy to find in the class. By doing this I have made it more maintainable because it's easy to find, and I have made it more readable becuase again it's broken up into easy to read sections and finally I made it adaptable becasue I can extend the program and know exactly what each things does.


  ==============================================================================
  ### CS 250
  There are a few different ways that you can interpret user needs. You could do surverys, usability testing, or focus groups. All of these can help you create your user stories. User stories are important because, they help you understand what users are asking for. Then you can disseminate them into working models that help to create the things that end users actually want to see in a deliverable. 

   Currently I develop my code top down. What I mean by that is I create the outline of my code first. Then start from the top and work my way down. Which in praticallity is not the smartest way to code. I really need to be working in a modular fashion and testing my code each time I add something new. I want to incorporate Scrum into my programming pipeline. I say this because from everything I have learned in this course, Scrum is the easiest to implement and seems to be the most useful. I really think that being a good team member is to communicate effectively with your team. Always being on the same page and really making sure that the deliverables that you are putting out meet the standards and if you can't asking for help and helping others. 
   
