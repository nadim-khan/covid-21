# Bocovid-21okme
This app has been creted for Movie Booking UI problem for Tech Verito.

It consists of two Views,

1) Home 
    - Contains 4 Tabs, 
    I) Book Me - Details about how app should generate result.
    II) Show 1 - Arrangement of seats in auditorium 1.
    III) Show 2 - Arrangement of seats in auditorium 2.
    IV) Show 3 - Arrangement of seats in auditorium 3.

2) Book
    - After viewing seat arrangment from Home page , User has to book the seats.
    - On this page User has to select the Show number from after that there will be a button that gets enabled as soon as user selects the show
    - User will be redirected to select the seats, seats will be shown according to the show number selection.
    - After selecting the seats for a show user has to click on the Book seats button, based on the seat selection bill will be generated for the current show. If the seat is alredy booked then it will show an error on UI page.
    - User can click on Continue to book the next ticket or can generate the bill for checkout.

Additionally, Application is responsive and User can change the theme from top right corner on the Tab.


# Book Me additional Information
The project has been created using Angular, Material(for UI)

- The seat details were generated from a json file stored in `assets/data` folder
- Uses a service for all the logic behind the seat selection, booking seats and generating bill.
- Application uses simple code for better undestanding and concept of OOP.

# While developing the project , below things have been kept in mind:

- SOLID principles have been applied to best the possible extent although there are some more ways of   implement the logics but i have applied the simple logics for it.
- Classes/modules are highly cohesive and loosely coupled.
-  YAGNI and KISS principles have been taken care while developing the projects as the logic that has been used is simple and functionalities has been implemented as per the necessity by covering all the aspects of principles.
- Coding conventions of the language has been used .

# Instructions on installation

1) Copy the project and run `npm install` to install the dependencies.
2) run command `ng serve` 

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 9.0.7.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

