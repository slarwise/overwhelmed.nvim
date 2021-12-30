# Overwhelmed.nvim

Configuring my neovim setup feels like an endless task to me. It is fun, but can
also be overwhelming and stressful. In this repo, I'll list the requirements I
need when programming/using a text editor, without specifying how to do it.
There are many ways to do the same thing, and I think that listing the
requirements before digging into exactly what tools to use will give a good
overview.

## Requirements

### Linting

- Syntax errors
- Spelling mistakes
- Grammatical errors
- Suggestions

### Formatting (including indentation)

### Syntax highlighting

### Completion

### Navigation

- Go to definition
- Go to the next function
- Go to file under cursor

### Searching

- Grep for strings and navigate to the matches
- Search for a symbol
- Search for a file

### Information

- Get documentation
- Where is a function, symbol etc. used?

### Folding

### Git

- Line blame
- Show what is unstaged
- Navigate through a set of changes

### Refactoring

- Rename a module, function etc.

### Running commands

- Compile the current file/project. Useful to do from the editor if it produces
  errors that needs to be navigated to. Otherwise, this can be done from the
  terminal
- Run tests. Useful to do from the editor if you want to run the test under
  cursor for example, and also for navigating the errors
- Ask the build system what can be done from the current cursor position
- Run an arbitrary command that may be dependent on the cursor position, and
  consume the output from this command

### Previewing compiled documents

For example, previewing a markdown document as an html page. The preview window
can be outside of the editor, and a file watcher that refreshes the window can
also be outside. It can be nice to start these processes from the editor, if you
want to start previewing the currently opened file.

## Iterable items

Many of the requirements above produce lists of items that can be iterated
through. For example, running a test may produce multiple errors that can be
navigated through. Searching for a word may produce another set of locations.
For these things it is nice to have a way to put these items somewhere, and be
able to navigate through them.
