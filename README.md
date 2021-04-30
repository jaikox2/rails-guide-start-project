# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* Rails command line
 - rails new "project name"                       #new project
 - rails server                                   #run server
 - rails routes                                   #list all routes
 - rails g controller "controller name"           #generate controller
 - rails g model Article title:string body:text   #generate model
 - rails db:migrate                               #migrate db


 * Rails console
 - article = Article.new(title: "Hello Rails", body: "I am on Rails!")
 - article.save
 - article
 - Article.find(1)
 - Article.all
