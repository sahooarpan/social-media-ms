# Database per service

Database per service, RabbitMQ and Aggregator Pattern.

## Table of Contents

- [Overview](#overview)
- [Prerequisites](#prerequisites)
- [Folder Structure](#folder-structure)
- [Installation](#installation)
- [Configuration](#configuration)
- [Running the Services](#running-the-services)
- [API documentation](#api-documentation)

## Overview
In this POC i have covered Database per service,Internal Communication with RabbitMQ and Aggregator Pattern. for detailed explaination please read this blog.

## Prerequisites

List the prerequisites for running your project. For example:

- [Node.js](#https://nodejs.org/en/download)
- npm (Node Package Manager)
- [MongoDB](#https://www.mongodb.com/docs/manual/installation/)
- [RabbitMQ](#https://www.rabbitmq.com/download.html)
- [Thunder client (for API documentation)](#https://www.thunderclient.com/)



## Folder Structure
- `aggregator-service/`: Contains the code for the aggregator service.
- `comment-service/`: Contains the code for the comment service.
- `user-service/`: Contains the code for the user service.
- `post-service/`: Contains the code for the post service.



## Installation

In each service folder (`aggregator-service/`, `comment-service/`, `user-service/`, `post-service/`), run the following command to install dependencies:

```bash
cd aggregator-service  # Navigate to aggregator-service folder
npm install

cd ../comment-service  # Navigate to comment-service folder
npm install

cd ../user-service  # Navigate to user-service folder
npm install

cd ../post-service  # Navigate to post-service folder
npm install
```

## Configuration
Port, RabbitMQ, MongoDB and other details can be confired in index.js file of relevant service

> `Note:` carefully configure User service, Post service and Post service URLs in Aggregator service.

## Running the Services

In each service folder (`aggregator-service/`, `comment-service/`, `user-service/`, `post-service/`), run the following command to install dependencies:

```bash
cd aggregator-service  # Navigate to aggregator-service folder
npm start

cd ../comment-service  # Navigate to comment-service folder
npm start

cd ../user-service  # Navigate to user-service folder
npm start

cd ../post-service  # Navigate to post-service folder
npm start
```

## API Documentation
For API Doc we used Thunder Client VSCode Plugin. every service has api doc filder which has API Doc file . which can be imported in VSCode.


[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax)

   [dill]: <https://github.com/joemccann/dillinger>
   [git-repo-url]: <https://github.com/joemccann/dillinger.git>
   [john gruber]: <http://daringfireball.net>
   [df1]: <http://daringfireball.net/projects/markdown/>
   [markdown-it]: <https://github.com/markdown-it/markdown-it>
   [Ace Editor]: <http://ace.ajax.org>
   [node.js]: <http://nodejs.org>
   [Twitter Bootstrap]: <http://twitter.github.com/bootstrap/>
   [jQuery]: <http://jquery.com>
   [@tjholowaychuk]: <http://twitter.com/tjholowaychuk>
   [express]: <http://expressjs.com>
   [AngularJS]: <http://angularjs.org>
   [Gulp]: <http://gulpjs.com>

   [PlDb]: <https://github.com/joemccann/dillinger/tree/master/plugins/dropbox/README.md>
   [PlGh]: <https://github.com/joemccann/dillinger/tree/master/plugins/github/README.md>
   [PlGd]: <https://github.com/joemccann/dillinger/tree/master/plugins/googledrive/README.md>
   [PlOd]: <https://github.com/joemccann/dillinger/tree/master/plugins/onedrive/README.md>
   [PlMe]: <https://github.com/joemccann/dillinger/tree/master/plugins/medium/README.md>
   [PlGa]: <https://github.com/RahulHP/dillinger/blob/master/plugins/googleanalytics/README.md>
