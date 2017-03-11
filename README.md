## Business Issue Tracking System

Business Issue Tracking System / BITS is a Web Application made with different technologies. Those technology stacks are divided into the frontend, the middleware, the backend, the cloud, and the API.

### Frontend
This simplifies the user-to-machine interaction by giving a user-friendly interfaces. I used markup/web languages such as HTML (Hypertext Markup Language), Javascript and CSS (Cascading Style Sheets) for developing the user interface. Also I used front-end frameworks such as:
- **Twitter Bootstrap** - Bootstrap is a free and open source front end development framework for the creation of websites and web apps.
- **jQuery** - jQuery is a Javascript Library that simplifies Javascript Programming.  

To simplify, HTML is just a string of words interpreted by the web browsers, the CSS allows us to style our HTML, and the javascript adds the interactive features like animations, etc..

### Language/Framework
The programming language acts as a middleware between the frontend and the backend. This concerns the actual processing of the data. So basically the frontend accepts the inputs, processed by the **middleware** which in our case *python* then saves it to the database.
- **Python** - Python is an interpreted, object-oriented, high-level programming language with dynamic semantics.
- **Django** - Django is a high-level Python Web framework that encourages rapid development and clean, pragmatic design. Built by experienced developers, it takes care of much of the hassle of Web development, so you can focus on writing your app without needing to reinvent the wheel.

### Database
A database is a collection of information that is organized so that it can be easily accessed, managed and updated. Data is organized into rows, columns and tables, and it is indexed to make it easier to find relevant information. Think of it as a digital ledger wherein you put all your records except that in the database, the data you store can be analyzed, query, searched, updated instantly. I have two choices to use for our database:
- SQLite
- PostgreSQL

Basically both of them functions well but there are pros and cons. SQLite is a lightweight database that can handle only small to medium data traffic, but it doesn't need to have a dedicated separate server so it cuts the cost of the development. On the other hand, PostgreSQL is an advanced Database Engine that can handle tons of data, but it needs a dedicated database server which adds up to the cost.

### Deployment
  PythonAnywhere  
  AWS Elastic Beanstalk  
### Others
  Globelabs API  
  Chrome Application Wrapper  
