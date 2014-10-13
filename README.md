> Popular tools and frameworks you should know about, even if you don't use
them.

# Overview

This is a collection and summary of popular tools and frameworks. Occasionally
I'll come across a github project, realize it is exactly what I've been looking
for, and then see that it has thousands of stars and everyone already knows
about it. This collection should give you a good place to start looking for
useful and popular tools, especially if you're new to a language.

> This started with just Android, which is much easier to maintain. If this
starts getting too hard to maintain or too to be useful, it will be split up.


# Android

## Testing

1. [**Robolectric**](https://github.com/robolectric/robolectric): A testing
framework that provides much more functionality than Android's stock testing
support and does not require an attached device.
1. [**AssertJ Android**](https://github.com/square/assertj-android): Provides an
intuitive fluent-style assertion syntax for Android (formerly FEST Android).
1. [**Espresso**](https://code.google.com/p/android-test-kit/wiki/Espresso): A
UI unit testing framework. Provides an API to interact
with and assert things about UI elements. Supported by Google.
1. [**deckard-gradle**](https://github.com/robolectric/deckard-gradle): Sample
project demonstrating how to use Robolectric to test and Gradle to build.

## Persistence

1. [**SQLite Asset Helper**](https://github.com/jgilfelt/android-sqlite-asset-helper):
Simplifies the process of shipping with and updating SQLite databases.

## Network

1. [**Robospice**](https://github.com/stephanenicolas/robospice): Attempts to
simplify the process of dealing with async tasks and network requests.
1. [**Android Async HTTP**](https://github.com/loopj/android-async-http):
Simplifies network requests by abstracting away direct interactions with the
apache http client.

## Build

1. [**Gradle Build System**](http://tools.android.com/tech-docs/new-build-system):
The site for the Gradle build system, including usage and release notes.

## Code

1. [**Android Annotations**](https://github.com/excilys/androidannotations/wiki):
Heavy use of annotations in an effort to make code more readable and
maintainable by abstracting away some complexities of Android development.
1. [**Butter Knife**](https://github.com/JakeWharton/butterknife):
Uses annotations to inject and manage views.

# HTML / JavaScript

## Including Scripts

1. [**Require JS**](http://requirejs.org/): A script import system optimized
for the browser, but that runs in other contexts, including Node. Uses script
tags.

1. [**Browserify**](http://browserify.org/): Lets you include scripts using
Node's `require()` syntax. Package things up using browserify, include the
output in a script tag, and access the module using `require()`.

## Testing

1. [**Mocha**](http://visionmedia.github.io/mocha/): A testing framework with
pretty output in the browser. Relies on other assertion frameworks.

1. [**Jasmine**](http://jasmine.github.io/2.0/introduction.html): A testing
framework with a similar look and feel to Mocha.

1. [**Chai**](http://chaijs.com/): An assertion library that pairs with other
testing frameworks.

1. [**Tape**](https://github.com/substack/tape): Another test framework, Tape
uses its own assertions and uses a pure Node `require()` style. No functions
or variables automatically appear.

## Server Side

1. [**Node JS**](http://nodejs.org/): Server-side framework that lets you write
the back end for applications in javascript. Includes modules for access to the
file system and other things you can't do as easily in the browser.

## Package Management

1. [**NPM**](https://github.com/npm/npm): Package management for Node modules,
which is often useful even if you're not working on a stricly Node project.

1. [**Bower**](http://bower.io/): Package management for projects that do not
want to adopt the Node project structure or that want to install things that
don't depend whatsoever on node.

## Creating Projects

1. [**Bootstrap**](http://getbootstrap.com/): Extremely popular website styling
for responsive, mobile-first webpages. Dollars to doughnuts, you've seen a site
that uses bootstrap.

1. [**Yeoman**](http://yeoman.io/): Scaffolds various projects by creating
directory structures for specific project types.

1. [**Backbone**](http://backbonejs.org/): System for separating model
objects from UI.

1. [**Angular JS**](https://angularjs.org/): Another system for separating
model objects and UI.

1. [**Grunt**](http://gruntjs.com/): Essentially a build system (think
makefile) for javascript and web projects that is capable of doing a huge
number of useful things. (Many projects scaffolded with yeoman will use grunt,
which can be a helpful way to get started.)

## Core Libraries

1. [**JQuery**](http://jquery.com/): Provides a huge number of basic functions
for selecting and manipulating the DOM, as well as everything else. Perhaps
the most popular javascript framework. Functions bound to a global `$` object.

1. [**d3**](http://d3js.org/): Data visualization framework responsible for
many of the gorgeous visualizations on the web.

1. [**Underscore**](http://underscorejs.org/): Additional functions useful in
many cases and that go beyond those provided by JQuery.

# Java

## Testing

1. [**JUnit**](http://junit.org/): The most popular Java testing framework.
Provides both the test structure itself as well as assertions.

1. [**AssertJ**](http://joel-costigliola.github.io/assertj/): Easier to use
assertions for Java using a 'fluent' syntax. Formely FEST.

## Basic Library Extensions

1. [**Guava**](https://code.google.com/p/guava-libraries/wiki/GuavaExplained):
Google's core Java libraries that expand on the common modules with some things
they thought were missing.

1. [**Joda-Time**](http://www.joda.org/joda-time/): Simplification and
improvements on Java's native support for dates and times.

## JSON Serialization

1. [**Jackson**](https://github.com/FasterXML/jackson): JSON serialization
with emphasis on efficiency.

1. [**GSON**](https://code.google.com/p/google-gson/): Google's JSON
serialization.

## Persistence

1. [**Hibernate**](http://docs.jboss.org/hibernate/orm/4.2/quickstart/en-US/html/):
An Object Relational Mapping (ORM) framework for Java. Maps simple Java objects
to database objects, handling persistence for you.
