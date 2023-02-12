# Social-Web-API

# Description
An API for a social network web application where users can share their thoughts, react to friends’ thoughts, and create a friend list.

# User Story 
- AS A social media startup
- I WANT an API for my social network that uses a NoSQL database
- SO THAT my website can handle large amounts of unstructured data

# Acceptance Criteria
- GIVEN a social network API
- WHEN I enter the command to invoke the application
- THEN my server is started and the Mongoose models are synced to the MongoDB database
- WHEN I open API GET routes in Insomnia for users and thoughts
- THEN the data for each of these routes is displayed in a formatted JSON
- WHEN I test API POST, PUT, and DELETE routes in Insomnia
- THEN I am able to successfully create, update, and delete users and thoughts in my database
- WHEN I test API POST and DELETE routes in Insomnia
- THEN I am able to successfully create and delete reactions to thoughts and add and remove friends to a user’s friend list

# GIFs
![18-nosql-homework-demo-01](https://user-images.githubusercontent.com/110949754/218331692-d6506e7f-1311-4feb-aebf-f7e3d6e3ba28.gif)
![18-nosql-homework-demo-02](https://user-images.githubusercontent.com/110949754/218331699-25d88a34-84a6-4a31-b1c9-7bcb80ee3bd4.gif)
![18-nosql-homework-demo-03](https://user-images.githubusercontent.com/110949754/218331710-c8c07f8e-0c4b-47dd-a5c2-9eb9d7ff6ac0.gif)
![18-nosql-homework-demo-04](https://user-images.githubusercontent.com/110949754/218331716-7ac6277a-2c8a-4354-a40e-11f2cf0cfcb8.gif)

# Installation
- npm i express
- npm i mongoose

# Usage
- npm start
- npm run watch
