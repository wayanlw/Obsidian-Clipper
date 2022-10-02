# Obsidian-Clipper

A Simple Bookmarklet Clipper for Obisidian

The code is copied from [kepano/obsidian-web-clipper.js](https://gist.github.com/kepano/90c05f162c37cf730abb8ff027987ca3?permalink_comment_id=3905251)

Depending on the requirement the below code can be edited.

```javescript
  /* Optional vault name */
  const vault = "";

  /* Optional folder name such as "Clippings/" */
  const folder = "";

  /* Optional tags  */
  const tags = "#clippings";
```

Once changed, the code needs to be URI encoded. [Bookmarklet Maker](https://caiorss.github.io/bookmarklet-maker/) can be used for this.

## An excerpt from the original author

Installation
Create a new bookmark in your browser, then copy/paste the minified code below into the URL field.

You can customize the output using the optional variables at the top, and the template at the bottom. The default template is designed for use with the Dataview plugin. If you make changes I recommend using Bookmarklet Maker to minify and URI encode the bookmarklet.

Usage
By default, clicking the bookmarklet creates a new Obsidian file from the main body of the article (similar to Readability view). Alternatively you can choose to create a file from a selection, by either selecting all (CMD+A), or just a portion of the page.

Any images in the content will be embedded as external references. If you want to download images locally you can use the Local Images plugin which allows you to download images for a note.