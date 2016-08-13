# Unique File ID

Inserts into the current selection the text and md5 hash of the current file's relative path.

## TL;DR ##

This package facilitates laziness.

## Description ##

This is a simple package that inserts text for file identification. The text will replace the current selection with the relative file path and it MD5 sum. You can activate it from the context menu, command palette, or using ctrl-cmd-i.

I find it useful to have comment markers sprinkled about my template code to ease tracing on the web. The MD5 sum gives you a double click-able section of text to copy and search for in your source code.

Go ahead, try to select README.md without using the keyboard or moving the mouse. You can triple-click, but that will select the whole line. The entire line could include text that is not a part of the template code.

```html
<!-- README.md 04c6e90faac2675aa89e2176d2eec7d8 -->
```

**Raw Text Insert**
![Raw Text Insert](https://github.com/infomaniac50/atom-unique-file-id/raw/master/assets/raw-text-insert.png)

**Line Comments Toggled**
![Editor Toggle Line Comments](https://github.com/infomaniac50/atom-unique-file-id/raw/master/assets/editor_toggle-line-comments.png)

## Security Caveats ##

The MD5 hash is insecure and using it to verify anything is ill advised. For generating a unique id from a small set of file paths, the MD5 is perfect.

## Kudos ##

The [Hemingway Editor](http://www.hemingwayapp.com/) helped me write this README in a bold and clear manner.
