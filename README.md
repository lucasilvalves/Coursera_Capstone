# Coursera Capstone - Applied Data Science
This is a repository on which I'm going to develop my capstone project with Python and its Data Science libraries, in order to achieve the Applied Data Science certificate. Feel free to see my work! :)

The notebook used to launch the challenge is [here on Gist](https://gist.github.com/lucasilvalves/407d24ce5bd5b274efdb6b048efe06f4).

## Activity #1 - Clustering the Neighborhoods of Toronto

This first activity is more detailed on my notebook [published on Gist](https://gist.github.com/lucasilvalves/35d8defb98f5d8a5bec640190c41998f)

## Activity #2 - The Battle of Neighborhoods

### Introduction to the problem

It's hard to say in an instant how two neighborhoods differ, unless you know them pretty well. What about the differences between two cities? There are some struggles when it comes to understand previously what you're going to find in an area inside the city you may be considering moving to, opening a restaurant or just staying for work for a few days.<br>
The main objective with this project is <b>to provide a reliable way to understand if you would like some place based on another city</b> you may like.<br>
The big challenge here was to provide a considerably agnostic way to provide information regardless of the social or geographical differences: you can compare Paris to Brisbane, Scranton to Rio de Janeiro, or so and so. The solution is called <i>"agnostic"</i> in a way that it gathers only the information about the venues in the towns, so someone interested on it can attain the analysis solely on the characteristics of the local market instead of considering their proportions - a further analysis of how this solution works will be provided next.<br>

### How it works

Here are some of the technologies used on this solution:
- <b>Geopy:</b> this is the solution applied on the problems of determining the city radius and locating the coordinates of latitude and longitude of the city itself.
- <b>Foursquare:</b> the Foursquare API was used throughout the project to retrieve the data of the venues within an area.
- <b>Pandas:</b> Pandas library is used here to visualize and manipulate the data retrieved.

### Conclusions and future improvements

The funny thing of getting in touch with Data Science is this: you have always room to grow and improve.<br>
There were some parts of the code that required a more empirical approach (the problem of getting the radius of the city) and may not work well on every city's geography, given the difference of its perimeter and the surrounding cities that the code may unproperly assign within the radius of search.<br>
Specifically for the end of this project - a brief showcase of the abilities I have developed with the series of courses -, I think it does the job pretty well and I'm willing to make more amazing projects, always contributing with the community and growing exponentially in knowledge!<br>
Thanks Coursera, IBM and everyone that, directly or not, contributed to this project!
