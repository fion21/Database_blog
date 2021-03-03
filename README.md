# README

This README would normally document whatever steps are necessary to get the
application up and running.

* Ruby version ruby-2.7.0

* System dependencies
yarn.lock, rakefile, gemfile

* Configuration
`routes.rb`
* Database creation

* Database initialization


* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions
create a new ruby project from scratch

`rails new your-project-name` see the new rails file in vs code or similar, the work on routing and controller features

* generate
`rails generate controller pages`

To set a root route, navigate to config/routes.rb file and enter in the following code ->

`root 'pages#home'`

To start the rails console, type in `rails console`  or rails c from the terminal.

Once in the console, you can `exit` it at any time by typing in exit followed by enter/return.

worked with the database `Article.all` this is a class with capital `A`
turn it into a variable to change properties, lower case a, <<more about>> with dot notation
`article = Article.new
Article.create(title: "first article", description: "Description of first article") # make sure Article is capitalized if using this method
article = Article.new
article.title = "second article"
article.description = "description of second article"
article.save
article = Article.new(title: "third article", description: "description of third article")
article.save`

save changes `article.save`# Database_blog
