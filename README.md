# WEB102 Prework - SeaMonster Crowdfunding Website

Submitted by: Usman Saeed

SeaMonster Crowdfunding is a website for the company Sea Monster Crowdfunding that displays information about the games they have funded.

Time spent: 9 hours spent in total

## Required Features

The following **required** functionality is completed:

* [x] The introduction section explains the background of the company and how many games remain unfunded.
* [x] The Stats section includes information about the total contributions and dollars raised as well as the top two most funded games.
* [x] The Our Games section initially displays all games funded by Sea Monster Crowdfunding
* [x] The Our Games section has three buttons that allow the user to display only unfunded games, only funded games, or all games.

The following **optional** features are implemented:

* [x] The Our Games section has a search functionality where the user search for a specific game
* [x] The Game Cards have more information on them such as Goal, Pledged, and Backers, allowing for people to have more information about each game.

## Video Walkthrough

Here's a walkthrough of implemented features: https://i.imgur.com/JgEwJa9.gif

You can find the GIF in this repo or view it online through the link.

GIF created with LiceCap: https://www.cockos.com/licecap/

## Notes

Dynamic Data Handling: Dealing with dynamic content updates, like filtering games or showing the top contributions for a specific game was difficult for me. I did not have much exposure to DOM (Document Object Model) and in order to have successful data manipulation use of JavaScript functions and DOM manipulation was crucial. For example, in Challenge 5, when implementing functions to filter funded and unfunded games to dynamically update games according to the user clicks required careful handling of data manipulation so that errors don't arise and the correct games are showcased in the "Our Games" section. CodePath did a great job by providing clear steps I could follow to achieve those results. Their description of the DOM as nodes/trees, by giving a diagram to explain it further, and by providing links to other materials I can use helped clear my concepts and put them into practice during this project. 

Another challenge that I faced was implementing the display of the top 2 funded games. The destructing assignment and the spread operator were essential to grab and display the top 2 games, which again required knowledge of DOM manipulation. The help provided by CodePath allowed me to successfully follow the steps and clearly understand how each component works and therefore played a crucial role in overcoming this challenge.

## License

    Copyright [yyy] [name of copyright owner]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
