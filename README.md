# Me-tadah!

There are two types of metadata editors: those that don't work, and those that are just a tiny tiny part of a gigantic ebook management programme.

## Usage
If you just want to be able to modify the title and the author of your ebooks, you can just

```
tadah path_to_ebook new_title new_author
```

## Supported formats
- `.epub`
- `.pdf`

## Dependencies

- `pdfrw`
- `ebooklib`

## Installation
Just like any other Python program (assuming you have Python installed):

1. install the dependencies, for example with `pip install [dep]`
2. clone this reporitory
3. move inside it
4. mark the Python file as executable (`chmod +x`)
5. add, as the file's first line, the path to your Python interpreter (for example `#!/usr/bin/env python`)
6. copy or move the file to a folder in your `PATH`, e.g. `usr/bin`
7. optionally, you can rename it to just `tadah` (removing the extension). This will allow you to invoke the program by simply typing `tadah [args]`!
