# react-demo
##### This repo has been created to display some of my work from past projects using react.js
##### A live demo can be found at: http://tapdev.kinapptech.com
 - you can use the quick login options to login
##### I have also created a Todo App using Angular 7
 - The GH repo can be found here: https://github.com/william13murphy/ang-todo
 ---
### File Details
 - [**AllSchoolsContainer.jsx**](https://github.com/william13murphy/react-demo/blob/master/AllSchoolsContainer.jsx) - This is an example container used to retrieve data from the DB. Utilizes react-redux and the API functions that are defined.
 - [**_base.js**](https://github.com/william13murphy/react-demo/blob/master/_base.js) - Defined functions to handle API requests to the DB. Functions include GET/POST/PUT/DELETE requests, as well as the ability to post/retrieve PDF and Excel files.
 - [**_elements.less**](https://github.com/william13murphy/react-demo/blob/master/_elements.less) - Global styling of various HTML elements and custom components that are used throughout the app. This file imports the variables used in _base.less which allows for reusable and easy-to-read code/variables.
 - [**allSchools.js**](https://github.com/william13murphy/react-demo/blob/master/allSchools.js) - Example redux action creator that is used in conjunction with redux reducers, store, and containers. The action creator lets our app communicate with the redux store which manages the entire data set.
 - [**index.js**](https://github.com/william13murphy/react-demo/blob/master/index.js) - reusable functions to handle both UTC/local date & time conversions. Utilized moment/moment-timezone to handle these procedures.
 - [**index.test.js**](https://github.com/william13murphy/react-demo/blob/master/index.test.js) - a few test cases to ensure the functions defined in the index file are working properly. Utilizes both Jest/Enzyme libraries.
 - [**index.jsx**](https://github.com/william13murphy/react-demo/blob/master/index.jsx) - The smart list is one of many important features I built that allows Administrators to perform an action on their student(s). The smart list includes a form for filtering the data, a form to enable/disable the columns to be displayed, a grid to display all/filtered students, and buttons that allow the user to save/load a report, message the selected students, or export the results to a pdf/excel file.
