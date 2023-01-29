# Workout tracker

## How the project works

- The project uses the browsers geolocation api and leaflet maps library to show the user their current location.
- The user can then click anywhere on the map to record a workout at that location.
- A form will then render on the side panel where the user can input details about the workout.
- After the form is submitted it will be hidden and a new marker will be placed on the map with workout information.

#### Other notable features

Using local storage the state of the app persists between page reloads
Map location changes when clicking a workout on the sidebar.

## Project planning

Designed first with user stories with the format:

> "As a **[user type]**, I would like to **[action]**, so that I can achieve **[benefit]**"

After deciding user stories such as , "As a user, I want to log my running workouts with location, distance, time, pace and steps/minute, some features were planned for implementation and organized into a flowchart.

After this the architecture of the app was considered with UML diagrams to consider the flow of data, making use of inheritance and code reuse.

This project was completed as part of a Udemy Javascript course
https://www.udemy.com/course/the-complete-javascript-course/
