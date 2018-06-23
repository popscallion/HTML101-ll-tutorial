#HTML 101 Journal
1. Make a new GitHub repository *"HTML101-ll-tutorial"*
    * Yes readme, MIT license
2. Clone the new repo to your Development directory
    1. `cd Development`
    2. `git clone [URL]`
    3. `cd [Project Name]` then `ls` to list contents
3. Make a journal file
    1. `atom .` to open project in Atom
    2. **CMD + N** to create a new file in the root directory, then **CMD + S** to save as **.md** Markdown.
4. Make a new HTML file
    1. Name it **index.html**
    2. Paste in `<!DOCTYPE html><html><head></head><body></body></html>`, separating each new tag `><` with a new line. This is the basic structure of every HTML document.
        * Everything after the `DOCTYPE` declaration has a pair of **opening** `<>` and **closing** `</>` **tags.** <html></html> wraps around both <head></head> and <body></body>.
          * You'll see this nested structure in all kinds of code.
        * `<!DOCTYPE html>`  simply declares this as an HTML document. It does not have a corresponding `</!DOCTYPE html>` closing tag.
        * `<html>` tells the browser that everything between the opening and closing tags is HTML code. Any attributes applied to `<html>` are inherited by its contents.
        * `<head>` contains metadata for the document. These are mostly instructions for browsers and search engines.

5. Let's flesh out the document a little and add some important information.
    1. Modify the `<html>` opening tag to read `<html lang="en-US">`
        * This tells the browser that the page is written in English.
    2. Between the `<head>` and `</head>` tags, add:
          1. `<title>HTML 101</title>`

              * This is the title of the document, as displayed in your browser tab.

          2. `<meta charset="utf-8">`, followed by `<meta name="viewport" content="width=device-width, initial-scale=1">`

              * `<meta>` contains metadata used by browsers and search engines. The only things we really need to define here are the set of characters the page is going to use (or *charset*), and the *viewport,* which is how the browser scales the content of the page to the size of the browser window.
          3. `<style>` holds inline styling for the document. It's better to use CSS stylesheets for a number of reasons, so let's forget about this for now.








<!---1. Create a new GitHub repository:

    1. [Create a GitHub account](https://github.com/join?source=header-home) if you don't already have one. See [Git 101](placeholder) for more details.

    2. Click the **+** button in the top right corner, then select **New repository** from the dropdown.

    3. Give your new repository a name! You'll want something descriptive and memorable, like "HTML101-LLtutorial"--->
