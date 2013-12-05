# openlayers-rails

[OpenLayers](http://openlayers.org/) library packed for use in Ruby on Rails asset pipeline. Currently includes OpenLayers version 2.12

## Installation

Add this line to your application's Gemfile:

    gem 'openlayers-rails'

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install openlayers-rails

## Usage

Add the following lines to your `app/assets/javascripts/application.js` manifest file.
```
// app/assets/javascripts/application.js
// Choose your openlayers version
//= require openlayers-full-debug
//
// Then require rails assets integration
//= require openlayers-rails
```
