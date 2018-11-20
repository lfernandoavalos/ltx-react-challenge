# LTX React Challenge
Please fork or clone this repo (which contains the dataset) and submit your solution to the following problem. You have 180 minutes to complete as much of this as possible (including initial requirements and extra credit). Note that the 180 minutes does not include any research or planning – we highly recommend taking some time beforehand to plan out your approach. For any unfinished extra credit, please write a quick sentence about what you would do for that entry. Please feel free to reach out for any questions or issues


You are free to use whatever technologies you want to use, as long as the project or container is all self-contained. It is highly recommended to use node if you need to run a local webserver to deliver the project on a browser; if you need any other dependencies outside of node please include it in the project README. In the README please provide instructions on how to run the application e.g.; within the project root run npm i && npm start. You are free to use whatever web libraries that are needed to achieve the exercise.  You are free to mutate or transform the source dataset to another type but the values and its columns should be preserved.

***SPOILER ALERT***: The dataset may spoil major plot points of Game of Thrones. If that is an issue, we can anonymize the data for you

## Initial Requirements

* Create a view that displays entries from the dataset as rows in a table with at least the name, popularity, and isAlive fields visible
* If there are any empty results with any of the user interactions, please display an appropriate error message (preferably a Sean Bean reference)
* When the user clicks on an entry, enable the user to view additional available information about the entry in a separate component called DetailView on the same page: 
    * Title = title, 
    * Gender = isMale, 
    * Culture = culture,
    * DOB = dateOfBirth


* Each of the below user-abilities can be reset by a hard refresh of the browser by the user
    * Enable the user the ability to show all entries in no particular order
    * Enable the user the ability to show the entries by its corresponding isAlive value
    * Enable the user the ability to show the entries by their popularity in descending order

## Extra Credit
* Use [Ag-grid](https://www.ag-grid.com/) to display the entries as a separate presentational component called DataTable
* Enable the user to reset the view back to the initially loaded view to avoid a hard refresh
* Enable random order of entries when initially loaded
* Incorporate deferred loading instead of loading all entries at once in the beginning
* Enable the user to show the entries by their popularity in ascending order as well
* Enable the user to display an area that has a pie chart of the proportional genders of the entries
* Use [redux](https://redux.js.org/) to handle global state
