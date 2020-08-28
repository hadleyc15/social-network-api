# <div align="center">**Social Network API**</div>

## **Project Description**
> Your challenge is to build an API for a social network web application where users can share their thoughts, react to friends’ thoughts, and create a friend list. You’ll use Express.js for routing, a MongoDB database, and the Mongoose ODM. In addition to using the Express.js and Mongoose packages, you’ll need to use the Moment.js package to format time.

## **Table of Contents** 
* [Project Description](#project-description)  
* [Table of Contents](#table-of-contents)  
* [Application Links](#application-links)  
* [Contributors](#contributors)  
* [Development](#development)  
* [User Story](#user-story)  
* [Acceptance Criteria](#acceptance-criteria)  
* [Screenshots](#screenshots)
* [Questions](#questions)  

## **Application Links**
> [Video Demonstration](<iframe src="https://drive.google.com/file/d/1wuT6dOUTqp5dEUoOHgA0sj4g8Stturyc/preview" width="640" height="480"></iframe>)  
> [GitHub Repository](https://github.com/hadleyc15/social-network-api)

## **Contributors** 
> Christopher Hadley | <hadleyc15@yahoo.com> | [github](https://github.com/hadleyc15)    

## **Development**
This application was developed with the following application structures:

1. [Node.js](https://nodejs.org/en/)
2. [Express.js](http://expressjs.com/)
3. [Moment.js](https://momentjs.com/docs/)
4. [Mongoose](https://mongoosejs.com/)

---

## **User Story**

> AS A social media startup 
> I WANT an API for my social network that uses a NoSQL database
> SO THAT my website can handle large amounts of unstructured data

## **Acceptance Criteria**
> GIVEN a social network API
> WHEN I enter the command to invoke the application
> THEN my server is started and the Mongoose models are synced to the MongoDB database
> WHEN I open API GET routes in Insomnia Core for users and thoughts
> THEN the data for each of these routes is displayed in a formatted JSON
> WHEN I test API POST, PUT, and DELETE routes in Insomnia Core
> THEN I am able to successfully create, update, and delete users and thoughts in my database
> WHEN I test API POST and DELETE routes in Insomnia Core
> THEN I am able to successfully create and delete reactions to thoughts and add and remove friends to a user’s friend list

## **Screenshots**

### <div align="center">**GET Route to see all users**</div>
<img src="/assets/images/Screenshot%20(101).png" />

### <div align="center">**POST Route to create a new user**</div>
<img src="/assets/images/Screenshot%20(102).png" />

### <div align="center">**POST Route to create a new thought**</div>
<img src="/assets/images/Screenshot%20(103).png" />

### <div align="center">**POST Route to add a new friend**</div>
<img src="/assets/images/Screenshot%20(104).png" />

### <div align="center">**POST Route to create a new reaction**</div>
<img src="/assets/images/Screenshot%20(105).png" />

### <div align="center">**DELETE Route to delete a user**</div>
<img src="/assets/images/Screenshot%20(106).png" />

## **Questions**
>If you have any questions, please contact me (contact info is listed in the CONTRIBUTORS section of this README).