Original App Design Project - README Template
===

# App Name: GeoFlick

## Table of Contents

1. [Overview](#Overview)
2. [Product Spec](#Product-Spec)
3. [Wireframes](#Wireframes)
4. [Schema](#Schema)

## Overview

### Description

Users will be given a location on a map in NYC for them to go to and take a picture. These locations will be given out at a random point in the day just like be real, most likely in the afternoon/off hours for people. Users are allowed to filter their borough so as to not have too much hassle reaching their location. Pictures will be posted to the main page and most liked picture will be the goal. Your pictures will be saved in a your pictures tab. Can also favorite the pictures of others. Maybe add friends in a friend tab. 

### App Evaluation

- **Category:** Social Networking/Photography
- **Mobile:** Mobile is essential for the photos taken. Since users will need to go to a specific location, desktops will not be able to accomplish this task.The camera is used to share images with other users. Will be utilizing both maps and camera.
- **Story:** Creates a community of like minded extroverted people who are into taking cool photographs. Allows people to share photos and make friends, additionally, the winner feels sense of accomplishment for having the most liked photo. I believe my friends and I would use and enjoy this app.
- **Market:** Any individual could utilize this app. As long as they have a phone and are able to get to the location. The scale is large. Not neccessarily niche but I assume mostly teenagers and young adults would use this.
- **Habit:** People are using this app daily as a new location is dropped each day and the liked leaderboard would reset daily. Very habit forming, users do not just consume, they create.
- **Scope:** Base version would allow users to take pictures and post them to the board. V2 with filters would allow users to only get locations in their specific borough. V3 would add a friends tab. This would be technically challenging for the full app, people would have to check that pictures are valid and not offensive. Measures would have to be put in place to ensure locations are all public and safe. However a stripped down version seems interesting to build anyway. The product is clearly defined.

## Product Spec

### 1. User Stories (Required and Optional)

**Required Must-have Stories**

* [ ]Allow users to see a map with the location chosen.
* [x] Allow users to take a picture using the camera of their device.
* [x]Allows Users to see posts of others in a tableview format
* [ ]Allow users to post their picture to a tableview of posts. This will include their picture in an imageview followed by username.
* [ ]User posts will be saved in a my posts tab.

**Optional Nice-to-have Stories**

* A friends tab
* A favorites tab
* A login

### 2. Screen Archetypes

* **Screen 1-** [Shows a map with a marker on the spot for the day]
* **Story-** [Allows users to see a map with the location chosen]
* **Screen 2-** [A screen that includes a take picture button and area where picture appears. Users will be able to crop and then post.]
* **Story-** [Allow users to take a picture using the camera of their device and allows users to post their picture to a tableview of posts. This will include their picture in an imageview followed by username.]
* **Screen 3-** [Shows the tableview of other user posts]
* **Story-** [Allows Users to see posts of others in a tableview format]
* **Screen 4-** [Shows your previous posts]
* **Story-** [User posts will be saved in a my posts tab.]


### 3. Navigation

**Tab Navigation** (Tab to Screen)
* [User posts]
* [Map Tab]
* [Picture Tab]
* [Myposts Tab]

**Flow Navigation** (Screen to Screen)

- [x] [User Posts]
* [Tab bar on the bottom links to map,picture and myposts]
- [x] [Map Tab]
* [Tab bar on the bottom links to user posts,picture and myposts]
- [x] [Picture Tab]
* [Tab bar on the bottom links to user posts,map and myposts]
- [x] [MyPosts Tab]
* [Tab bar on the bottom links to user posts,map and picture]


## Wireframes

<img src="https://github.com/marenas1/codepath-capstone/blob/main/Wireframe.jpeg" width=600>

### [BONUS] Digital Wireframes & Mockups

### [BONUS] Interactive Prototype

## Schema 

[This section will be completed in Unit 9]

### Models

[Add table of models]

### Networking

- [Add list of network requests by screen ]
- [Create basic snippets for each Parse network request]
- [OPTIONAL: List endpoints if using existing API such as Yelp]
