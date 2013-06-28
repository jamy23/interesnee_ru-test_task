Simple single page shop

Page online store, everything must be done on 1st page without a server (js / html / css). WITHOUT using javascript MVC frameworks.

The input of JSON (eg dropbox) like this

```JSON
[
    {
        id  : 1,
        name : "item1",
        desc : "blalblal",
        picture : "http://"
        price : 41.24
    },
    {
        id  : 2,
        name : "item2",
        desc : "blabla2",
        picture : "",
        price : 23.01
    }
]
```

There are two tabs:

view1 - tiles (picture, name), sort by name

view2 - list (name, desc, price), sort by price
 
Can switch between them. When you click on the product popap opens, where you
can edit the information about it (view1/view2 thus need to be updated.)

+ Bonus-search, select sorting
   
  How to: Organize your code / files to get a MVC model. Lay in this example
  a base to expand to scale online store.
   
  How wrong: Do everything in a single file with a "spaghetti" code that the
  expansion will not be possible to extend the functionality and support.
   
  It is desirable to use:
  Event Dispatcher; Dependency Injection.
