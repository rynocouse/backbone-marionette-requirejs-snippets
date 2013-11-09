backbone-marionette-requirejs-snippets
======================================

RequireJS/Backbone/Marionette Snippets for Sublime Text

## Installation
Clone or Download repo into ~/library/Application Support/Sublime Text [2 or 3]/Packages/User/

## How to use
Create a JavaScript File. And use the keywords defined below.

### Keywords (use tab to insert)

**Define** : Insert a RequireJS Module (CommonJS Simplified) with sensible default modules.

```
/**
 * FILENAME.js
 * The FILENAME module.
 */

define(function(require){

    var app = require('app'),
        _ = require('underscore'),
        $ = require('jquery'),
        Backbone = require('backbone'),
        Marionette = require('marionette');

    return ;

});
```

**Backbone** : Insert a Backbone Classes. Available Classes:

- Backbone.Model
- Backbone.View
- Backbone.Collection

**Marionette** : Insert any of Marionette Classes. Available Classes:

- Backbone.Marionette.ItemView
- Backbone.Marionette.CollectionView
- Backbone.Marionette.CompositeView
- Backbone.Marionette.Layout
