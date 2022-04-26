# Condensation

This is a video game database where users can create an account, view games, wishlist games, and write reviews for games they enjoyed! This site is influenced by Steam. 

Key Features: 
- view games
- add new games based on API
- edit games

Design Improvement:
- updated color scheme

Database Models: 
- pull from video game API(maybe)
- games schema

Game Schema: 
![image](https://user-images.githubusercontent.com/34723980/165342963-e42ff616-488f-4391-b707-3da3c2e51e99.png)

ROUTES: 
/games - GET - index - retrieves all games and lists title and photo
/games/new - GET - new - form to create a new game
/games/:id - GET - show - retrieve one game with more info
/games/:id/edit - GET - edit - retrieve one game with form to edit current info
/games - POST - create - sends new game data
/games/:id - PUT - update - sends edited game data to existing game
/games/:id - DELETE - destroy - delete game from existence


![image](https://user-images.githubusercontent.com/34723980/165326354-98f22a80-e027-4ac1-aa33-d56da724fdb0.png)

WIREFRAMES:
Home Page:
![image](https://user-images.githubusercontent.com/34723980/165319240-85175766-6bb8-446a-8f7e-9c07adb5af9c.png)

Game Index:
![image](https://user-images.githubusercontent.com/34723980/165320646-4f7b9eba-eef2-4e21-a0af-9d7eed00f940.png)

User Profile: STRETCH
![image](https://user-images.githubusercontent.com/34723980/165321355-397d3401-c55e-4bce-b1f4-8a32d5eaa6d7.png)

Game Show Page:
![image](https://user-images.githubusercontent.com/34723980/165328271-fa919dad-b846-4d3f-8562-2b5323c03b6e.png)

New User Page: STRETCH
![image](https://user-images.githubusercontent.com/34723980/165327388-bb264a22-73a3-414e-a6bd-be8e64d8dece.png)

Jonathan's Responsibilities:
- set up models

Megan's Responsibilities:
- CSS

Collaborations:
- express app functionality
- ejs pages

MVP GOALS: 
- game index is viewable
- can create new game that pulls info from API
- can edit game info or delete game

STRETCH GOALS: 
- create users
- create reviews on game page
