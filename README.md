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

* ...

```bash
rails new bloqueira-de-baixa-renda --database=postgresql

rails s

rails generate controller Articles index --skip-routes

rails generate model Article title:string body:text

rails generate model Comment commenter:string body:text article:references

rails generate controller Comments

rails db:migrate
```