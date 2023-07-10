# LiteraTrail Blog Website

Welcome to LiteraTrail, a blog website that allows users to create and share their own blogs. This website is built using EJS, Express, Node.js, MongoDB, and other relevant technologies. The main file for this application is app.js.

## Features

- User-friendly interface for creating and publishing blog posts.
- Utilizes EJS (Embedded JavaScript) templates for dynamic rendering of blog pages.
- Implements Express.js as the web application framework.
- Leverages the power of Node.js for server-side logic and functionality.
- Utilizes MongoDB for data storage and retrieval.


## Prerequisites
Before running the LiteraTrail blog website locally or deploying it to a server, ensure you have the following software and dependencies installed:

MongoDB: Make sure MongoDB is installed and running on your machine or server.

Node.js: Install the latest stable version of Node.js from the official website.

Install the required dependencies by running the following command: _npm install_

## Configuration

Before running the application, you need to configure the MongoDB connection settings. Open the app.js file and find the following line:
mongoose.connect('mongodb://localhost:27017/blogDB');
Replace 'mongodb://localhost:27017/blogDB' with your MongoDB connection string. If you're using a remote MongoDB server, replace localhost with the server address.

Running the Application: _node app.js_

The application will start running on the default port 3000. 

To access the website, open your web browser and enter the following URL: http://localhost:3000.

## Usage

To create a new blog post, navigate to the "Compose" section of the website.

Fill in the necessary details.

Click the "Publish" button to publish your blog post.

To view a published blog post, click on the corresponding title on Home page.

## Contributions

Contributions to this project are welcome. If you encounter any issues or have suggestions for improvement, please feel free to submit a pull request or open an issue in the repository.

## Acknowledgments

Special thanks to the developers and contributors of EJS, Express, Node.js, and MongoDB for providing the powerful tools and frameworks used in this project.
