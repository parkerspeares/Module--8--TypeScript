# 08 TypeScript and OOP: Vehicle Builder

## Introduction
This project demonstrates the fundamentals of Typescript & OOP

View the code on GitHub:
https://github.com/parkerspeares/Module--8--TypeScript

##Description
This project builds vehicles, illustrating core Object-Oriented Programming (OOP) concepts in Typescript. A base Vehicle class serves as the foundation, with derived classes like Car, Truck, and Motorbike representing specific vehicle types, exemplifying inheritance. The inclusion of "Driveable" functions—such as start, accelerate, decelerate, stop, turn, and reverse—in the Vehicle class demonstrates polymorphism in action. Additionally, the Truck class showcases composition by integrating truck-specific methods, such as towingCapacity and tow. 

##Installation
Clone the repository: start by cloning the repository to your local machine using Git. Open your terminal or command prompt and run git clone <repository_url>. Replace the <repository_url> with the URL of the repository you want to clone.
Navigate to the project directory: change your current directory to the project directory by running cd <project_directory>. Replace <project_directory> with the name of the directory where the project is located.
Install dependencies: run npm i to install the dependencies listed in the package.json file.
Run the project: run npm run start to compile the TypeScript files into the JavaScript files and to run the node dist/index.js file.

##Usage
Select “Create a new vehicle” or “Select an existing vehicle”
If you select “Create a new vehicle”, then select “Car”, “Truck”, or “Motorbike”
Enter the details for the vehicle until prompted with “Select an action”
Select an action for the vehicle. For example, if you selected “Truck” then you may select “Tow another vehicle”.
If you selected a Truck followed by “Tow another vehicle” then select the vehicle you would like to tow, for example “Harley Davidson Sportster”. The output will display in the command interface.
You may then select another action. Select “Exit” to exit the application.

##License 
MIT license

##Contributing
Author:Parker Speares
Other: W3Schools
