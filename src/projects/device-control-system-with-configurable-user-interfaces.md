---
title: Device Control System With Configurable User Interfaces
emoji: 🖥️
date: 2025-06-15T12:30:39.124Z
summary: >-
  IN-EARLY-DEVELOPMENT

  Larger group project to provide the client with an application that allows for creating, configuring and deleting control panels and using those control panels to run specified scripts on the server to make it possible to control devices in different lecture halls.
tags:
  - in-development project group-project React PHP University post
---
T﻿his project is currently in early stages of development and not in it's final form as of yet. This is a group project.

## T﻿ask

T﻿he task was to create a web application to allow controlling the devices in lecture halls from a control panel mounted on the wall in each room. The application should run a script in the server based on what button is pressed. Seems simple enough so far, but the application should also have an admin-interface where you can configure each user's interface to your liking - moving around elements like buttons and text boxes, adding new ones and deleting existing ones, changing the styling of each element separately and all at the same time. To this end we decided to use React and TypeScript on the frontend and PHP + Symfony on the backend. My role in this project is that of a frontend developer and we are currently working on making the UI configuration part of the application using react-rnd to make resizable and draggable components and react-redux to store the state of the application during configuration before sending the state to the backend through an API to be stored in the database.

## P﻿review

A﻿ll preview images are of an earlier prototype with no backend connection (data pertaining to rooms and devices in the rooms are all hardcoded into the React application and large amounts of functionality are missing or not finished).

![Action selection page of the Prototype](/src/assets/img/image_2025-06-15_154324861.png "Action selection page of the Prototype")

![Preview of modified device control panel in A-001](/src/assets/img/image_2025-06-15_154410099.png "Preview of modified device control panel in A-001")

![Preview of configuration of device control panel in A-001](/src/assets/img/image_2025-06-15_154519165.png "Preview of configuration of device control panel in A-001")

[G﻿itHub repo](https://github.com/tammmatTLU/suvepraktika_tiim2)