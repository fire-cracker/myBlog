# MyBlog
[![Code Climate](https://codeclimate.com/github/codeclimate/codeclimate/badges/gpa.svg)](https://codeclimate.com/github/oyedejipeace/myBlog)

## Table of Contents

- [Project Overview](#Project-Overview)
- [Features](#Features)
- [Built with](#Built-with)
- [Documentation](#Documentation)
- [Known Issues](#Known-Issues)
- [Installation](#Installation)
- [Contributing](#Contributing)
- [License](#License)

## Project Overview

MyBlog is a discussion and information website which allows users to reflect,share opinions and discuss various topics. It was built using Django, Html, Css,Bootstrap and ORMs

## Features

- Users can create an account and log in,
- A user can write and post,
- A user can see a history of posts,
- The user can add, edit or delete posts,

## Built with

- Django,
- Html, 
- Css,
- Bootstrap
- ORMs

## End Points
- `get(localhost:5000/)`                 -  Shows all Post
- `get(localhost:5000/post/:id)`         -  Shows a particular Post
- `post(localhost:5000/post/new)`        -  Saves and publishes a post 
- `put(localhost:5000/post/:id/edit)`    -  Edit/Update a particular post
- `delete(localhost:5000/post/:id)`      - Deletes a particular post

## Known issues

Everything works as expected; However:
- there are more features to be added e.g User profile account, User recent posts , User can post comment,User can delete comment and posts, post upvote and downvote

## Installation

- $ git clone `https://github.com/oyedejipeace/myBlog.git`
- $ cd Djangogirls
- $ pip install , to install dependencies
- $ python manage.py runserver, to start the server. Once the server starts-up, you can query the site at `http://localhost:8000/` using the end points stated above.


## Contributing

> Feel free to 🍴 fork this repository
> 👯 Clone this repository to your local machine using https://github.com/oyedejipeace/myBlog.git

> Make Contributions
> Contributions to the project are welcome! Before contributing, look through the branch naming, commit message and pull request conventions here. When you are all done, follow the guidelines below to raise a pull request:

> 🔃 Create a new pull request using https://github.com/oyedejipeace/myBlog/compare.

## License
![GitHub](https://img.shields.io/github/license/mashape/apistatus.svg?style=plastic)

- Copyright 2018 © <a href="https://oyedejipeace.github.io/myBlog/" target="_blank">MyBlog</a>