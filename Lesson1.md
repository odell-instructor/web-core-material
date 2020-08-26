# Lesson 1 - Introduction to HTML

## **Topics discussed in this lesson are:**
- What is HTML?
- A basic HTML page
- What are Elements?
- Basic content using lipsum
- Adding comments

---

### **What is HTML?**
HTML stands for **H**yper **T**ext **M**arkup **L**anguage and is the basic language for creating web pages. It consists ofa series of elements that a browser can follow to render the content for a given page. We will talk more about these elements shortly.

## The basic HTML Page

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Web Core Material</title>
</head>
<body></body>
</html>
```

| Element Type | Description |
| ------------------------- |--------------------------------- |
| `<!DOCTYPE html>` | This declaration says that the file is an HTML5 Document |
| `<html>` | This element is the root of an HTML page |    
|`<head> </head>` | This element serves as a section of information about the webpage |
|`<meta>`| They identify information about the HTML document such as viewport, device width and intial scale. More on this later.|
|`<title>Page Title</title>` | The element defines that title of the webpage and is what you see in the browswer tab |
|`<body> </body>` | This element serves as the container that has the main content of the webpage. All visible elements go into this element. |  
---
<br>

## What are elements?
An HTML element is a tag and in certain circumstances is an interchangeable statement. Most elements end with the same tag, but with a / prior to the name of the tag. Elements that don't define and ending tag are referred to as empty elements. We will identify both types throughout this material.

HTML tags are also non case-sensitive. This means you can use either upper or lower case spelling. It is however recommended that you use lower case. We will discuss the below element tags in this lesson. They all will be uses in the body tag.

| element type | Description |
| ------------ | ------------------------------ |
| `<h1>` to `<h6>` | These are heading tags that range from 1 to 6 with 1 being the largest size and 6 being the smallest |
| `<p>` | This tag is a paragraph tag and is the most used tag on web pages |
| `<div>` | Defines a section of divider in a document. They are used for organizing groups of other elements. |
| `<br />` | This tag provides a line break and is typically used inside other element's data. |
|
<br>

## Basic content using lipsum
We don't always know what content we want to add to our web pages when we are creating them. Designers and Developers will often use what is referred to as *Lorem Ipsum* in there projects.
We utilize this site [lipsum.com](https://lipsum.com) to help generate text as a placeholder until such time as you have real text to replace it later. This is great for mocking up a site while waiting on the acual content.

<br>

## Adding Comments
Sometimes you want to add information to a HTML page that you do not want to show in the browser. This information can be in the form of a comment. The below tag can span multiple lines or a single line. It can also be used to turn off code, but you don't want to remove it.

` <!-- This is a comment --> `

You can see that it too has a beginning and ending tag. We will utilize comments in the HTML files in this material. It is great for note taking on web pages as well, or even reminders or todo information.