# Lesson 1 Practice Hands-On

# Setup And Rendering With React

# Directions

For your Lesson 1 Practice Hands-On, you will be working on a new project provided below. This Hands-On will not be graded, but we encourage you to complete it. The best way to become a great programmer is to practice! Once you have submitted your project, you will be able to access the solution on the next page.

# Setup

Start off by downloading the starter project and unzipping it. The starter project will be in a folder named React.

Starter Project

After unzipping, move the starter project folder to the FEFReact folder located inside the FullStackWeb folder and rename it from React to L01HandsOn.

Open up your terminal/command prompt.

Navigate to your desktop in your terminal.

cd Desktop
Next, navigate to the FullStackWeb directory in your terminal.

cd FullStackWeb
Then, navigate to the FEFReact directory in your terminal.

cd FEFReact
Navigate into the L01HandsOn directory:

cd L01HandsOn
Now that you are in the L01HandsOn directory, run the following:

npm install
Once npm has finished installing, you can test that the server is working with the following command:

npm start
You should now see your browser open up a blank page with an alert box saying "It's alive!".

Tip!
You can stop this process by pressing Control + C in the terminal, but for now, keep the server running.

Add the necessary import statements at the top of the src/index.js file and remove the alert that currently lives in that file:
import React from 'react';
import ReactDOM from 'react-dom';
Requirements
Write the React code needed to render the equivalent to the below HTML favorite things list. Add the code for the following requirements within the src/index.js file:

Based on the below list, keep the sections the same (i.e., Favorite Colors, Favorite Websites, etc.), but feel free to fill it in with your personal favorite things.
The list of your Favorite Websites should navigate the user to those specific websites, as you can below.
You should have three different websites listed under "Favorite Websites".
Add a class name to each of the subtopics (i.e., Favorite Colors, Favorite Websites, etc.). The class names should relate to their respective favorite thing topic.
For example, the Favorite Colors section should have a class name of something similar to "favoriteColors".
Use Variables in some way
Example
When you are done, it should look similar, but not exactly the same as the example below. Notice the use of unordered and ordered lists:

My Favorite Things
Favorite Colors
Green
Blue
Red
Favorite Music
Regina Spektor
Antonín Dvořák
Radiohead
Favorite Food
Pizza
Ceasar Salad
Gnocchi
Favorite Websites
www.google.com
www.facebook.com
www.instagram.com
Tip!
Remember that you can only have one parent element!