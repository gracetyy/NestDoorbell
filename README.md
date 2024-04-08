# NestDoorbell

A doorbell for visitors of nestspace to alert us they are outside innowing

## preview
![Screenshot 2024-03-28 010208_2](https://github.com/gracetyy/NestDoorbell/assets/145827531/81aab852-935e-4762-a95a-74a683455269)

## functional requirements (Todo)
- visitor can input their name into the website
- RESTful api for the website client to post a HTTP request to the server
- python server will send visitor name to ESP32 pixel LED display doorbell through another RESTful request
- get visitor IP address, datetime of the visit, and their name and store them in Postgres database

## non-functional requirements
- pretty

## file structure
```
nestdoorbell
├── frontend
│   ├── html.html
│   ├── css.css
│   └── nestspace_icon.jpg
│   └── logowhite.png
├── backend
│   └── flask
└── api
    └── schemas
```
(https://www.text-tree-generator.com/)
