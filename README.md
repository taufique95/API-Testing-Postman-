# How to run this project
- Clone this project
- Open with Postman / Command Shell
- Run Command:
    ```sh
    newman run apitest.postman_collection.json -e fortest.postman_environment.json -r cli,htmlextra 
    ```
# Technology used:
- Postman
- Newman

# Prerequisite:
- Node Js
- Postman
- Newman
- Jdk
- HTML Report Liabrary

# Newman and Report Installation Process:
- Newman Install Command:
    ```sh
    npm install -g newman
    ```
- Newman Html Report Install Command:
    ```sh
    npm install -g newman-reporter-html
    npm install -g newman-reporter-htmlextra
    ```
# API Documentation:
- https://documenter.getpostman.com/view/26162718/2s93Y3vg2v

# Newman Report Summary:
- https://imgur.com/a/3PyrgcA
