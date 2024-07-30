# System Design Overview
## Introduction
This is a simple yet feature-rich Todo List application built using React. It allows users to manage their tasks efficiently with functionalities to create, update, mark as done, search, and view tasks in an expandable format. The application also demonstrates responsive design principles for an enhanced user experience across devices.

## Core Features
### Create Task: Users can add new tasks with a title and description.
### Update Task: Users can edit the title and description of existing tasks.
### Mark as Done: Users can mark tasks as completed, and toggle this status.
### Search Tasks: Users can filter tasks based on a search term.
### Expandable List: Each task can be expanded to show its description and the last updated timestamp.

## Data Storage
The application uses a dummy JSON file (tasks.json) as a data repository. This simulates a backend data source for the tasks.
Framework

### React: The application is built using React, a popular JavaScript library for building user interfaces.

## Components Overview
### App.js: The main component that manages the state and integrates all other components.
### SearchBar.js: A component for the search input to filter tasks.
### Task.js: A component that represents an individual task, including its title, description, and controls for editing and marking as done.
### TaskForm.js: A form component for adding new tasks.
### TaskList.js: A component that renders the list of tasks, filtered by the search term.
### tasks.json: A dummy data file containing initial tasks.

## Styling
The application uses CSS for styling, defined in index.css and App.css, to provide a modern and clean user interface.


# How to run the application

### Install Node JS
Refer to https://nodejs.org/en/ to install nodejs

### Install create-react-app
Install create-react-app npm package globally. This will help to easily run the project and also build the source files easily. Use the following command to install create-react-app

```bash
npm install -g create-react-app
```

## Cloning and Running the Application in local

Clone the project into local

Install all the npm packages. Go into the project folder and type the following command to install all npm packages

```bash
npm install
```

In order to run the application Type the following command

```bash
npm start
```

The Application Runs on **localhost:3000**
