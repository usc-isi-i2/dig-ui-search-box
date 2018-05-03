# search-box

A Polymer Element using for free text search.

### Example
```html
<search-box
  date-config='{"dateStart": "postingDate", "dateEnd": "postingDate"}'
  search-fields-config="[[searchFieldsConfig]]"
  free-text-search-fields="[[freeTextSearchFields]]"
  search-parameters="{{searchParameters}}"
  process-request="{{processRequest}}">
</search-box>
```

### Dependencies

Dependencies are installed using [Bower](http://bower.io/):

    npm install -g bower
    bower install


### Demonstration & Documentation

Demonstration and documentation are viewed using [Polymer CLI](https://www.polymer-project.org/2.0/docs/tools/polymer-cli):

    npm install -g polymer-cli
    polymer serve