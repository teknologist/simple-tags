# Simple Tags [![Build Status](https://travis-ci.org/bompi88/simple-tags.svg)](https://travis-ci.org/bompi88/simple-tags)

Adds bootstrap 3 tag input for Meteor, with autocomplete (typeahead).

### Installation

Simple Tags can be installed with Meteorite:

``` sh
$ mrt add simple-tags
```

### Usage

Datastructure:

``` javascript
// tags retrieved from a database 
var tags = ["Awesome", "Birds", "Crazy", "Soulsalicious"];
```

In your template, add:

``` html
{{> TagsInput values=tags placeholder="Insert tags here" id="tags" minChars="2"}}
```

### License

MIT