# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version
ruby "3.2.1"
gem "rails", "~> 7.0.6"
* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...
# blogRails
Follow the tutorial

Getting Started with Rails
This guide covers getting up and running with Ruby on Rails.

https://guides.rubyonrails.org/getting_started.html?fbclid=IwAR2S2H7Z9m7_c0k9GHKyVFt4wcXb9p0Xekxsywg0cxPzCDR8ZSbVrI_af0Y

Error en update


ArgumentError in ArticlesController#edit
wrong number of arguments (given 1, expected 0)
Extracted source (around line #25):

23
24
25
26
27
28
              

	

  #add edit 
  def edit
    @article = Article.find (params [:id])
       
    if @article.update(article_params)
      redirect_to @article

Rails.root: /home/miguel/jekyll/ruby/blog
Application Trace | Framework Trace | Full Trace
app/controllers/articles_controller.rb:25:in `edit'
Request

Parameters:

{"id"=>"4"}

Toggle session dump
Toggle env dump
Response

Headers:

None

