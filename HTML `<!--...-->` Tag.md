# HTML `<!--...-->` Tag



### Example

An HTML comment:

> `<!--This is a comment. Comments are not displayed in the 	browser-->`

>`<p>This is a paragraph.</p>`


### Definition and Usage

The comment tag is used to insert comments in the source code. Comments are not displayed in the browsers.

You can use comments to explain your code, which can help you when you edit the source code at a later date. This is especially useful if you have a lot of code.



<span style="color: red">reference</span> : [checkingbrowse support and others](https://www.w3schools.com/tags/tag_comment.asp)



# HTML <!DOCTYPE> Declaration

### Example


> `<!DOCTYPE html>`

> `<html>`

> `<head>`

> `<title>Title of the document</title>`

> `</head>`

>`<body>`

>`The content of the document......`

>`</body>`

>`</html>`


<span style="color: red">reference</span>: [checkingbrowse support and others](https://www.w3schools.com/tags/tag_doctype.asp)


### Definition and Usage

The <!DOCTYPE> declaration must be the very first thing in your HTML document, before the <html> tag.

The <!DOCTYPE> declaration is not an HTML tag; it is an instruction to the web browser about what version of HTML the page is written in.

In HTML 4.01, the <!DOCTYPE> declaration refers to a DTD, because HTML 4.01 was based on SGML. The DTD specifies the rules for the markup language, so that the browsers render the content correctly.

HTML5 is not based on SGML, and therefore does not require a reference to a DTD.

**Tip**: Always add the <!DOCTYPE> declaration to your HTML documents, so that the browser knows what type of document to expect.



# HTML `<a>` Tag

### Example

> `<a href="https://www.w3schools.com">Visit W3Schools.com!</a>`

### Definition and Usage

The `<a>` tag defines a hyperlink, which is used to link from one page to another.

The most important attribute of the `<a>` element is the href attribute, which indicates the link's destination.

By default, links will appear as follows in all browsers:

* An unvisited link is underlined and blue
* A visited link is underlined and purple
* An active link is underlined and red


<span style="color: red">reference</span> : [checkingbrowse support and others](https://www.w3schools.com/tags/tag_a.asp)



# HTML `<abbr>` Tag

>`The <abbr title="World Health Organization">WHO</abbr> was founded in 1948.`

### Definition and Usage
The <abbr> tag defines an abbreviation or an acronym, like "Mr.", "Dec.", "ASAP", "ATM".

**Tip**: An abbreviation and an acronym are both shortened versions of something else. Both are often represented as a series of letters.

Marking up abbreviations can give useful information to browsers, translation systems and search-engines.

<span style="color: red">reference</span> : [checkingbrowse support and others](https://www.w3schools.com/tags/tag_abbr.asp)




# HTML `<acronym>` Tag. <span style="color: red">Not Supported in HTML5**</span>

An acronym is marked up as follows

>`Can I get this <acronym title="as soon as possible">ASAP</acronym>?`

### Definition and Usage

<span style="color: red">
The `<acronym>` tag is not supported in HTML5. Use the `<abbr>` tag instead.</span>

The `<acronym>` tag defines an acronym.

An acronym must spell out another word. For example: NASA, ASAP, GUI.

Marking up acronyms can give useful information to browsers, translation systems and search-engines.


<span style="color: red">reference</span> : [checkingbrowse support and others](https://www.w3schools.com/tags/tag_acronym.asp)
