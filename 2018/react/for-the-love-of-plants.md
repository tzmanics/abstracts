# For the Love of Plants starring Tessel and React

## Abstract
Join me in coding out a system for your plants that updates you on light and moisture levels using a Tessel board and React UI. Understand how to retrieve and utilize sensor data. May another plant never die on your watch!

## Details
I've killed a lot of plants. I love building electronics projects. Non sequitur? No way. In order to stop the flora massacre this project ties in a database of plant information with sensor data of the plant's current moisture and light conditions.

In this session, we'll code up the sensors using the Tessel open source libraries and microcontroller. Once we have the data being sent to our database, we can move on to the UI. We'll spin up the UI using create-react-app, then combine the plant database and the sensor database. Once we have all the data we can set up push notifications to remind us NOT to kill plants 😁

This project is specific to plants, but the concept of connecting static information and dynamic data from sensors into a handy web app can be used as you wish. Come ready to code and save some plants from imminent demise.

## Takeaways
Learn how to use the Tessel open source libraries to collect sensor data. Build a UI that utilizes that sensor data to send notifications using service workers.

## Pitch
This talk will take the steps from back to front of a full project:
- building a database and API using `graphql create` with Prisma
- quickly spinning up a UI with create-react-app and a component library
- incorporating progressive web app strategies
- hooking this all up with data from a microcontroller

Building this project, it was hard to find what steps to take, so I want to make it avaiable for more devs. I've spoken and lead workshops teaching all of these pieces separately. Now, it's time for the whole journey to come together in one cohesive session :)
