# Weight Controller

## Introduction

This app helps users to control or reduce their body weight by restricting daily calorie intake. New registered users will need to create a profile by providing: 
- Age 
- Gender
- Weight
- Height
- Life style

Once profile is created, appropriate daily calorie intake target will be set. The user then needs to record the food consumption, the app will calculate the calorie of the food and provide the remaining calorie for the day. Once the target is hit, app will alert the user to stop any further consumption for the rest of the day.

## Extension

Following features are intended in the future releases:
- Target on losing weight
- Calculate calorie for an uploaded picture(food)
- Burning calorie by activity tracker

## Installation Guides

- First clone down the repo
- Create a new virtual environment and activate it
- install all the packages necessary which is listed in the requirements file 
- At last, run the app 

## Wireframes

### Landing Page

<img src="./docs/wireframes/Landing_page_2.png" width="200"/><img src="./docs/wireframes/Landing_page.png" width="500" height="400" style="margin-left: 35px;" />



### Signup Page

<img src="./docs/wireframes/Signup_2.png" width="200"/> <img src="./docs/wireframes/Signup.png" width="500" height="400" style="margin-left: 35px;"/>



### Login Page

<img src="./docs/wireframes/Login_2.png" width="200"/> <img src="./docs/wireframes/Login.png" width="500" height="400" style="margin-left: 35px;"/>



### Dashboard Page

<img src="./docs/wireframes/Dash_board_2.png" width="200"/> <img src="./docs/wireframes/Dash_board.png" width="500" height="400" style="margin-left: 35px;"/>



### Profile Page

<img src="./docs/wireframes/Profile_2.png" width="200"/> <img src="./docs/wireframes/Profile.png" width="500" height="400" style="margin-left: 35px;"/>



### Blog Page

<img src="./docs/wireframes/Recipes_2.png" width="200"/> <img src="./docs/wireframes/Recipes.png" width="500" height="400" style="margin-left: 35px;"/>


## Database schema

- A user can have zero or multiple blogs, but a blog belongs to only one user.
- A user can set only one goal weight.
- a user can have at least one weight history and a weight history belongs to only one user.


![](docs/DB_schema.png)







