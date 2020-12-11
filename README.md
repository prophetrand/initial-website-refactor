# Initial Website Refactor - Horiseon

## Description
Welcome! This deployed webpage displays homepage content for the fictional company Horiseon. The majority of the elements in the page are solely visual, but the three links in the top-right of the header banner can be clicked to link to corresponding sections of the page.

## Table of Contents
* [Technologies Used](#technologies-used)
* [How to Access](#how-to-access)
* [What I Did](#what-i-did)
* [Code Snippets](#code-snippets)
* [Acknowledgments](#acknowledgments)
* [Who I Am](#who-i-am)

---

## Technologies Used
* [HTML](https://www.w3schools.com/html/) to structure the "skeleton" of the webpage and its elements
* [CSS](https://www.w3schools.com/css/) for visual styling to make that HTML much prettier
* [Git](https://git-scm.com/) for distributed version control, tracking changes over time and making them visible to collaborators
* [Github](https://github.com/) for version control in the cloud, saving my changes and presenting them clearly to myself and others.


## How to Access
[Click here](https://prophetrand.github.io/initial-website-refactor/) to view the deployed webpage, or copy-paste the following URL into your browser application of your choice.

https://prophetrand.github.io/initial-website-refactor/

--- 

## What I Did
For this project I have refactored the code for a single HTML webpage that represents a fictional company's home page. The HTML and CSS initially provided for the site were mostly functional, but included improper HTML semantics, broken links, inefficient and repetitive syntax, and a lack of comments describing code functionality. In the process of refactoring the code to amend these errors, I have improved the codeblock's adherence to accessibility standards so that the site is better suited for SEO, or search engine optimization. A few more methods I employed for this effort were: 
* Added a succinct but clear title to the webpage.
* Added alt tags to images in case images did not load properly.
* Adjusted numerous &lt;div&gt; tags to more descriptive HTML semantic tags, such as &lt;section&gt;, &lt;footer&gt;, and &lt;aside&gt;.

## Code Snippets 
The following snippet of CSS represents many elements being styled together, all within the &lt;aside&gt; semantic element. Prior to refactoring, the &lt;aside&gt; element was instead defined as a &lt;div&gt;, which provided the same functionality but far less clarity to the reader on how the element is different from others in the page. 

```
aside {
    margin-right: 20px;
    padding: 20px;
    clear: both;
    float: right;
    width: 20%;
    height: 100%;
    font-family:  'Trebuchet MS', 'Calibri', sans-serif;
    background-color: #2589bd;
}

aside div{
    margin-bottom: 32px;
    color: #ffffff;
}

aside h3{
    margin-bottom: 10px;
    text-align: center;
}

aside img{
    display: block;
    margin: 10px auto;
    max-width: 150px;
}
```
Additionally, the style tags for "aside div," "aside h3," and "aside img" were defined separately and individually for every single element housed in &lt;aside&gt;. This caused an unnecessary abundance of code that was roughly three times as large as the code snippet above, as each style element was repeated for three different assets. This is an example of how CSS tags can be used to be consise in syntax while affecting a broad number of elements.

---

## Acknowledgments
* [W3Schools](https://www.w3schools.com/) has been my go-to for descriptive tutorials on both HTML and CSS functionality, syntax, and best practices. For that I am grateful.
* UC Berkeley Coding Bootcamp provided the initial code to be refactored.

## Who I Am
My name is Rand Hale, and I am an aspiring programmer/web developer based in California.

* [LinkedIn](https://www.linkedin.com/in/rand-hale-83ba389b/)
* [Portfolio](https://prophetrand.github.io/prework-about-me/)