
| Command                 | Description                                                                                     |
| ----------------------- | ----------------------------------------------------------------------------------------------- |
| ApplyOrderedListStyle   | Converts the current selection to an ordered list. Accepts an object specifing the list type.   |
| ApplyUnorderedListStyle | Converts the current selection to an unordered list. Accepts an object specifing the list type. |

For information on available list types, see: [MDN web docs - list-style-type](https://developer.mozilla.org/en-US/docs/Web/CSS/list-style-type#Values).

**Examples**

```js
tinymce.activeEditor.execCommand('ApplyOrderedListStyle', false, {
  'list-style-type': 'disc'
});
tinymce.activeEditor.execCommand('ApplyUnorderedListStyle', false, {
  'list-style-type': 'decimal'
});
```