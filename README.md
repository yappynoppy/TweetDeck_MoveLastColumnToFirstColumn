# TweetDeck_MoveLastColumnToFirstColumn

TweetDeck Bookmarklet.

```javascript
javascript:(
    function(){
      var container = document.getElementById("container");
      container.lastElementChild.insertBefore(container.lastElementChild.lastElementChild, container.lastElementChild.firstChild);
    }
  )();
```

This is a <a href="http://en.wikipedia.org/wiki/Bookmarklet">bookmarklet(Wikipedia)</a> 
you can use to move last column to first column in TweetDeck.

