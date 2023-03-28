
# Tech Time

Tech time is a web application built with Next.js that focuses on promoting the various courses to be offered by tech time and also gives users and potential students detailed information about the school.

Hosted on : (https://tech-time-talentplus.vercel.app/)

![Techtime Screenshot](https://github.com/sodiqmakinde/Tech-Time/blob/master/src/assets/images/MockUp.jpg?raw=true)

## Getting Started

### Prerequisites

-   Docker
-   Docker Compose

### Installation

1.  Clone the repository
    
    bashCopy code
    
    `git clone https://github.com/sodiqmakinde/Tech-Time.git` 
    
2.  Navigate to the project directory
    
    bashCopy code
    
    `cd Tech-Time` 
    
3.  Build the Docker image
    
    Copy code
    
    `docker build -t techtime .` 
    
4.  Run the Docker container
    
    arduinoCopy code
    
    `docker run -p 3000:3000 techtime` 
    
5.  Access the application in your browser at [http://localhost:3000](http://localhost:3000/)

## Building for Production

To build the application for production, run the following command:

arduinoCopy code

`npm run build` 

This will create an optimized build of the application in th `./out` directory.

To start the production server, run the following command:

sqlCopy code

`npm start` 

## Built With

-   [Next.js](https://nextjs.org/) - The web framework used
-   [React](https://reactjs.org/) - The JavaScript library used for building user interfaces
-   [styled-components](https://styled-components.com/) - The CSS-in-JS library used for styling components
-   [react-slick](https://react-slick.neostack.com/) - The carousel component used for handling the testimonial slider


## Authors

-   [Sodiq Makinde](https://github.com/sodiqmakinde) - Github
- [Sodiq Makinde](https://www.linkedin.com/in/sodiq-makinde-926824216/) - LinkedIn
- [Sodiq Makinde](msodq2018@gmail.com) - Email


