rails-bootstrap-demo
====================

A first demo for study purpose of rails &amp; bootstrap
Use rails and bootstrap:
https://github.com/seyhunak/twitter-bootstrap-rails

http://railscasts.com/episodes/328-twitter-bootstrap-basics?autoplay=true

not gonna use Less, but only CSS:
add to Gemfile:
	gem "twitter-bootstrap-rails"  
> bundle install
#Then run the bootstrap generator to add Bootstrap includes into your assets:

> rails generate bootstrap:install less
# If you need to skip coffeescript replacement into app generators, use:

> rails generate bootstrap:install --no-coffeescript
>
> rails generate scaffold Product \
> title:string description:text image_url:string price:decimal
>
> rake db:migrate
> rails g bootstrap:themed Products


# validate of ROR doesn't work with bootstrap, trying https://github.com/danryan/jquery-validation-rails,
# failed.

# try later: http://twitterbootstrap.org/bootstrap-form-validation/

#how to destroy a gem:
1) still keep the gem in Gemfile
2) rails d xxx:install
3) remove the gem from Gemfile
4) bundle


