# Finance-tracker
Application created by following the assignments from the "[The Complete Ruby on Rails Developer Course](https://www.udemy.com/course/the-complete-ruby-on-rails-developer-course/)".

It uses Rails 6.

## Requirements
- Rails 2.7.0 at least.
- Postgresql.

## Install and use the apps
Download or clone the git repository with

```
git clone git@github.com:gabrielTach/photo-app.git
cd photo-app
```

Then install all dependancies with __Bundler__

```
bundle install
```

And finally start the RoR server
```
rails s
```

## Stripe set-up
To set-up the public and private key in stripe, you will have to edit the YML credentials file. To do so, use the following command:

```
rails credentials:edit
```

Then in the YML file, add the following lines
```
stripe:
  public_key: <your public key>
  secret_key: <your secret key>
```
Replace the text between and including `<`,`>` with your keys.

## Contribute
As it is an exercice, there is no need to contribute. Feedback are welcome, but see it as what it is: an exercice.
