## Welcome to Rails

Rails is a web-application framework that includes everything needed to
create database-backed web applications according to the
[Model-View-Controller (MVC)](http://en.wikipedia.org/wiki/Model%E2%80%93view%E2%80%93controller)
pattern.

Understanding the MVC pattern is key to understanding Rails. MVC divides your
application into three layers, each with a specific responsibility.

The _View layer_ is composed of "templates" that are responsible for providing
appropriate representations of your application's resources. Templates can
come in a variety of formats, but most view templates are HTML with embedded
Ruby code (ERB files).

The _Model layer_ represents your domain model (such as Account, Product,
Person, Post, etc.) and encapsulates the business logic that is specific to
your application. In Rails, database-backed model classes are derived from
`ActiveRecord::Base`. Active Record allows you to present the data from
database rows as objects and embellish these data objects with business logic
methods. Although most Rails models are backed by a database, models can also
be ordinary Ruby classes, or Ruby classes that implement a set of interfaces
as provided by the Active Model module. You can read more about Active Record
in its [README](link:/activerecord/README.rdoc).

The _Controller layer_ is responsible for handling incoming HTTP requests and
providing a suitable response. Usually this means returning HTML, but Rails
controllers can also generate XML, JSON, PDFs, mobile-specific views, and
more. Controllers manipulate models and render view templates in order to
generate the appropriate HTTP response.

In Rails, the Controller and View layers are handled together by Action Pack.
These two layers are bundled in a single package due to their heavy interdependence.
This is unlike the relationship between Active Record and Action Pack, which are
independent. Each of these packages can be used independently outside of Rails. You
can read more about Action Pack in its [README](link:/actionpack/README.rdoc).

## Getting Started

1. Install Rails at the command prompt if you haven't yet:

        gem install rails

2. At the command prompt, create a new Rails application:

        rails new myapp

   where "myapp" is the application name.

3. Change directory to `myapp` and start the web server:

        cd myapp
        rails server

   Run with `--help` or `-h` for options.

4. Go to http://localhost:3000 and you'll see: "Welcome aboard: You're riding Ruby on Rails!"

5. Follow the guidelines to start developing your application. You may find
   the following resources handy:
    * [Getting Started with Rails](http://guides.rubyonrails.org/getting_started.html)
    * [Ruby on Rails Guides](http://guides.rubyonrails.org)
    * [The API Documentation](http://api.rubyonrails.org)
    * [Ruby on Rails Tutorial](http://ruby.railstutorial.org/ruby-on-rails-tutorial-book)

## Contributing

We encourage you to contribute to Ruby on Rails! Please check out the
[Contributing to Ruby on Rails guide](http://edgeguides.rubyonrails.org/contributing_to_ruby_on_rails.html) for guidelines about how to proceed. [Join us!](http://contributors.rubyonrails.org)

## Code Status

* [![Build Status](https://secure.travis-ci.org/rails/rails.png)](http://travis-ci.org/rails/rails)
* [![Dependencies](https://gemnasium.com/rails/rails.png?travis)](https://gemnasium.com/rails/rails)

## License

Ruby on Rails is released under the [MIT License](http://www.opensource.org/licenses/MIT).
