---
layout: multi
permalink: /modern.html
---

# A Basic Introduction to the Modern Web

The modern web is a critical enabler for data-driven sciences.  It extends the 
reach of information to many devices, many people, and many technologies.  

Discussions of research data must occur rapidly, in a digital ecosystem.  It now
should be a responsibility of the modern scientist to have general competancies
in how the modern web works.  Responsible software practices can enhance productivity,
collaboration, discussion, visualization.  

The scientific record moves too fast to live for static publication.  Consequently,
presentation, collaboration, and evaluation of science must be exepedited.

> There\'s no history-everything exists only in nanoseconds. - _Terry Gillaim - [Wired](http://www.wired.com/2014/09/zero-theorem/)_

# Table of Contents

# Challenges 

## Meaning over Naming

Naming information and knowledge often restricts discussion to specialized domains.  In software,
opinions are intrinsic in the codes you use; they were designed by people with your best interests 
in mind\... hopefully.

## Minimizing Choices

The current state of the modern web exists because of software.  Consequently, it is possible to
learn all you need to know about software through some simple web searches.

The downside of open source software is that there are a lot of it; an incredible [amount of entropy](https://www.youtube.com/watch?v=lKXe3HUG2l4).

It is important to form your own opinions about software so you can reduce choices.

### Start with Trusted Sources

* GitHub
* StackOverflow

# The Web is the Presentation Layer

Data-driven fields demand collaboration as the complexities of their problems scale.  Data-driven 
collaboration will occur with the Modern Web as the primary medium.

The modern web connects to many people, many devices, and many applications.  

## The Challenge

__Make information searchable, discoverable, and usable.__

> Data can be archived, but it fails because the process to maturing data to archive 
does not exist.  

# Designing\..

## Education

A small portion of the modern technologists education should include training
on web tools.  They are critical in collaborative work and education.

## Searchability

In collaboration\..

1. Metadata is data about the data.
2. If you cannot access that with code then it doesn't exist.

Searchability means that data is created and can be used elsewhere.

## Discoverability

Discoverability means that someone else can find your information.

### Webservers vs. Webservices

It is still common for organizations to host their own web servers; this incurs a substantial
investment.  

Web services provides specific pieces of a web server.  Often they are much quicker to use and scale.

#### Web-server Services

* [Heroku]()
* [AppEngine]()

#### Website Services

* [Jekyll]()
* [ngrok]()


#### File Storage

* [Dropbox]()
* [Box]()
* [Drive]()

#### Documents

* [Google Docs]()
* [Gist]()

#### Photos

* [Flickr]()

#### Code

* [Github]()

### Email, Google Hangouts, Google Docs Examples

## Usability

Collaborative software should be usable by a lot of people.  There is no 
doubt that the web browser the most common software tool; with Javascript is 
the most common programming language.  

Usability is very challenging to quantify.  It incurs all of the opinions of the 
observers.  Across devices\...

# What Makes a Webpage

* __HTML__ is standardized data about a webpage.
* __CSS__ adds style to the webpage.

  * tags - the html api
  * class - general properties for many features.
  * ID's - reserved for unique features.
  
* __Javascript__ adds dynamicism to HTML using CSS selectors 

  > Javascript connects to the Java Virtual Machine in the browser to execute cross-platform Java commands.

# Visual and Illustrate Relationship above.

# The Internet Runs on Strings

HTML, CSS, and Javascript are encoded in files as strings.  HTML accesses CSS and Javascript with ``<style>``
and ``<script>`` tags, respectively.

## Other Types


# Webpages are data-driven

1. HTML is loaded
2. Stylesheets and Scripts are Imported
3. [Upon completion](#events), Javascript is executed.

  Javascript modifies pieces of HTML using DOM manipulation 
  tools like [Jquery]() and [d3]().
  
4. Transformed data is inserted into HTML tags for presentation

## Gist API Example

[https://gist.github.com/tonyfast/091cbd9d9b134d063630](https://gist.github.com/tonyfast/091cbd9d9b134d063630)
[https://api.github.com/gists/091cbd9d9b134d063630](https://api.github.com/gists/091cbd9d9b134d063630)

# What\'s the Data

_Well\.. it\'s just a string_
__BUT__
_What **Type** of string?_

## JSON : Javascript :: XML : HTML

Javascript Object Notation + eXtensible Markup Language

### YAML

  > YAML is the easiest way to write JSON.
  Adds comments

# Javascript Objects

JSON is the most commonly used data
exchanges on the web.  It represents Javascript Objects.

## Objects

Objects are enclosed in ``{braces}``.  The use ``keys`` to access 
underlying values in the objects

## Arrays

Arrays are enclosed in ``[brackets]``.  They use integer values
to access underlying alues in the arrays.  

## Values

Values are Objects, Arrays, Numbers, or Strings that a ``key`` describes

### JSON-LD : Javascript :: RDF : HTML

Keys give meaning to values; Javascript uses keys to access and use the values. 
Keys do not independently have a meaning.

JSON-LD and RDF provide a semantic context to the keys.  If JSON-LD and RDF schemas are provided 
then the name of a ``key`` is only important to machines and the schemas are important to humans.

# Markdown, Markup, WTF

Markup Languages can be ingested by code and used as data.

Markdown is not that at all\... Not even a little bit close.

Markdown is a plain-text readable formatting syntax.  With a simple
syntax, markdown places hierarchy, ordering, and emphasis on pieces of ordinary text.

## Markdown Parser



# Importance of Hierarchies

# ArchieML as a hybrid

# Jekyll as Inspiration