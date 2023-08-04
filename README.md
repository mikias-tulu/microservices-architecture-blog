# Microservices Architecture Blog

This repository is dedicated to implementing a microservices architecture for a blog application. In a microservices architecture, the application is divided into smaller, independent services that communicate with each other through APIs. Each service represents a specific business capability and can be developed, deployed, and scaled independently. 

**The main features are:**

- User can post a blog
- User can make comments on a blog post

## Technologies Used

- React
- Node.js
- Axios
- Nodemon
- Express


## Microservices

The Microservices Architecture Blog application consists of the following microservices:

### Client:
- Description: The client microservice is responsible for the user interface of the blog application. It handles user interactions and displays blog posts and comments.

- Getting Started:

```
cd client
npm install
npm start
```
### Event-bus:
- Description: The event-bus microservice acts as a central communication hub for all the other microservices. It allows communication between different services using a publish-subscribe pattern.

- Getting Started:
```
cd event-bus
npm install
npm start
```
### Post:
- Description: The post microservice is responsible for managing blog posts. It handles creating, updating, and deleting blog posts.

- Getting Started:
  
```
cd post
npm install
npm start
```
### Comment:
- Description: The comment microservice handles the creation of comments on blog posts.

- Getting Started:
```
cd comment
npm install
npm start
```
### Query:
- Description: The query microservice is responsible for querying and fetching data from other microservices to display on the user interface.

- Getting Started:
```
cd query
npm install
npm start
```

## API Endpoints

The following API endpoints are available for interacting with the blog application:

### Client Microservice:

- `GET /` - Get all blog posts and comments
- `POST /posts` - Create a new blog post
- `POST /comments` - Create a new comment on a blog post

### Event-bus Microservice:

- `POST /events` - Publish events to be received by other microservices

### Post Microservice:

- `GET /posts` - Get all blog posts
- `GET /posts/:id` - Get a specific blog post by ID
- `POST /posts` - Create a new blog post
- `PUT /posts/:id` - Update an existing blog post by ID
- `DELETE /posts/:id` - Delete a blog post by ID

### Comment Microservice:

- `GET /comments` - Get all comments
- `GET /comments/:id` - Get a specific comment by ID
- `POST /comments` - Create a new comment
- `PUT /comments/:id` - Update an existing comment by ID
- `DELETE /comments/:id` - Delete a comment by ID

### Query Microservice:

- `GET /posts` - Get all blog posts
- `GET /posts/:id` - Get a specific blog post by ID
- `GET /comments` - Get all comments
- `GET /comments/:id` - Get a specific comment by ID


 ## Contact

If you have any questions or suggestions, please feel free to contact the project maintainers.

- Name: Mikias Tulu
- Email: miki.tulu@gmail.com
- GitHub: [GitHub Profile](https://github.com/mikias-tulu)

  
