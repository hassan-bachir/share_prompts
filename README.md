<img src="./readme/title1.svg"/>

<br><br>

<!-- project philosophy -->
<img src="./readme/title2.svg"/>

> The project philosophy is creating a simple app that utilize tools and frameworks like Next.js, MongoDB, and Google services with Next auth to create a handy prompts sharing platform
>
> This app aims to make it simple and convenient for individuals to use the AI chatbots in the most efficient by avoiding writing redundant prompts, just search for the suitable tag and thats it !

### User Stories

1. User Registration and Authentication<br>
   As a new user, I want to sign up using my Google account.<br>
   As a registered user, I want to log in using my Google account.<br>
2. Prompt Creation and Editing<br>
   As a user, I want to create new AI prompts and share them.<br>
   As a user, I want to edit or update the prompts I've created.<br>
3. Prompt Viewing and Interaction<br>
   As a user, I want to view AI prompts created by others.<br>
   As a user, I want to upvote or downvote prompts to express my opinion.<br>
4. Prompt Searching and Filtering<br>
   As a user, I want to search for prompts by keywords or phrases.<br>
   As a user, I want to filter prompts by tags or categories.<br>
5. User Profile Management<br>
   As a user, I want to view and edit my profile information.<br>
   As a user, I want to upload or change my profile picture.<br>


<br><br>

<!-- Implementation -->
<img src="./readme/title4.svg"/>

> Using the wireframes and mockups as a guide, we implemented the Wallii app with the following features:

### User Screens

| Welcome screen                                      | Advisor screen                                     | Register screen                                  | Login screen                                          |
| --------------------------------------------------- | -------------------------------------------------- | ------------------------------------------------ | ----------------------------------------------------- |
| ![Landing](./readme/implementation/welcome.PNG)     | ![fsdaf](./readme/implementation/advisor.PNG)      | ![fsdaf](./readme/implementation/register.PNG)   | ![fsdaf](./readme/implementation/login.PNG)           |
| Home screen                                         | Wallet Screen                                      | Update Screen                                    | Expense Screen                                        |
| ![Landing](./readme/implementation/home.PNG)        | ![fsdaf](./readme/implementation/wallet.PNG)       | ![fsdaf](./readme/implementation/add_income.PNG) | ![fsdaf](./readme/implementation/add_expense.PNG)     |
| Advisor screen                                      | Advisor Screen                                     | Calender Screen                                  | Calender Screen                                       |
| ![Landing](./readme/implementation/bad_advisor.jpg) | ![fsdaf](./readme/implementation/good_advisor.PNG) | ![fsdaf](./readme/implementation/calender1.PNG)  | ![fsdaf](./readme/implementation/calender2.PNG)       |
| Budget screen                                       | Goals Screen                                       | Admin Screen                                     | Wallet settings Screen                                |
| ![Landing](./readme/implementation/Budget.PNG)      | ![fsdaf](./readme/implementation/goals.PNG)        | ![fsdaf](./readme/implementation/admin.PNG)      | ![fsdaf](./readme/implementation/Wallet_settings.PNG) |

<br><br>

<!-- Tech stack -->
<img src="./readme/title5.svg"/>

### Wallii is built using the following technologies:

-   🚨 The Wallii app is built using a stack that includes Node.js, Express, and MongoDB for the backend and React Native for the frontend.
-   For the user interface design, the app uses the material design principles for a clean and intuitive user experience.
-   The app features custom animations and transitions to enhance the user experience and make it feel more fluid and natural.
-   To facilitate seamless communication between the frontend and backend, the app uses RESTful APIs and JSON data exchange formats.
-   Wallii offers robust security features to protect user data and ensure the privacy of their information.
-   The app features a powerful search functionality that allows users to easily find what they're looking for within the app's content.
-   Wallii offers a range of customization options, allowing users to personalize their experience and tailor the app to their preferences.

<br><br>

<!-- How to run -->
<img src="./readme/title6.svg"/>

> To set up Wallii locally, follow these steps:

### Prerequisites

This is an example of how to list things you need to use the software and how to install them.

-   Download and install from https://nodejs.org/en/download/

-   npm
    ```sh
    npm install -g expo-cli
    ```

### Installation

1.  Get a free API Key for OpenAI at https://openAi.com
2.  Clone the repo
    ```sh
    git clone https://github.com/hassan-bachir/Wallii/
    ```
3.  Install NPM packages

    ````sh
    cd /wallii_server
    npm install
    cd /aiwallet_mobile
    npm install

        ```

    ````

4.  Enter your API in `config.js`
    ```js
    const API_KEY = "ENTER YOUR API";
    ```
5.  Set up your MongoDB database by following the instructions at https://www.mongodb.com/ and update the database connection string in the backend/config/db.js file
    ```js
    const CONNECTION_STRING = "ENTER YOUR MONGODB CONNECTION STRING";
    ```
6.  initialize App

    ```js
    //mobile
    npm start
    //server
    nodemon index.js
    ```

Now, you should be able to run Wallii locally and explore its features.
