---
title: String.prototype.lastIndexOf
---
## String.prototype.lastIndexOf

This is a stub. <a href='https://github.com/freecodecamp/guides/tree/master/src/pages/javascript/standard-objects/string/string-prototype-lastindexof/index.md' target='_blank' rel='nofollow'>Help our community expand it</a>.

<a href='https://github.com/freecodecamp/guides/blob/master/README.md' target='_blank' rel='nofollow'>This quick style guide will help ensure your pull request gets accepted</a>.

<!-- The article goes here, in GitHub-flavored Markdown. Feel free to add YouTube videos, images, and CodePen/JSBin embeds  -->

The `lastIndexOf()` returns the index of the last occurance of a specified value in a string, starting the search from the end to the beginning, but returns the index starting at the beginning. It will return -1, if the specified string isn't found.

The `lastIndexOf()` method is case sensitive.

**Syntax**

```
string.lastIndexOf(searchValue, [fromIndex])
```

### Parameters 

- **searchValue** - A string that represents the value to search for.
- **fromIndex** - Optional.The location to start the search from. It can be integer between 0 and the length of the string.

### Return Value

Returns the index of the last found occurence, or -1 if not found.

### Examples

```javascript
'canal'.lastIndexOf('a');     // returns 3
'canal'.lastIndexOf('a', 2);  // returns 1
'canal'.lastIndexOf('a', 0);  // returns -1
'canal'.lastIndexOf('x');     // returns -1
'canal'.lastIndexOf('c', -5); // returns 0
'canal'.lastIndexOf('c', 0);  // returns 0
'canal'.lastIndexOf('');      // returns 5
'canal'.lastIndexOf('', 2);   // returns 2
```

### More Information:
<!-- Please add any articles you think might be helpful to read before writing the article -->
* MDN Documentation: <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/lastIndexOf">MDN</a>


