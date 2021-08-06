# Sprint Challenge: User Interface and Git - Multi-Page Website

This challenge allows you to practice the concepts and techniques learned over the past week and apply them in a concrete project. This Sprint explored User Interface and Git. During this Sprint, you studied Semantic HTML, CSS Fundamentals, CSS Flexbox Module, and Git. In your challenge this week, you will demonstrate proficiency by creating a multi page website that has some missing HTML elements as well as CSS specificity problems that need to be solved.  You will also create an additional web page that will be linked to from a navigation you will build.

## Instructions

**Read these instructions carefully. Understand exactly what is expected _before_ starting this Sprint Challenge.**

This is an individual assessment. All work must be your own. Your challenge score is a measure of your ability to work independently using the material covered through this sprint. You need to demonstrate proficiency in the concepts and objectives introduced and practiced in preceding days.

You are not allowed to collaborate during the Sprint Challenge. Your work reflects your proficiency in user interface and your command of the concepts and techniques in semantic HTML, CSS fundamentals, CSS flexbox module, and git.


## Commits

Commit your code regularly and meaningfully. This helps both you (in case you ever need to return to old code for any number of reasons)

## Description

In this challenge, you build a missing header (navigation and image) on the home page, update some CSS styling on the home page, and create an additional page (About) which will link from the navigation you created.

In meeting the minimum viable product (MVP) specifications listed below, your web page should look like the solution screen shots of the home and about pages (found in the design-files folder):

[Click here for the home page example](https://tk-assets.lambdaschool.com/39a49225-8ac9-43da-aa90-514fd60ae99a_sprint-challenge-ui-home-example.png)

[Click here for the about page example](https://tk-assets.lambdaschool.com/ede1bb1a-63ff-4801-8c02-3efa2f603190_sprint-challenge-ui-about-example.png)

## Self-Study Questions 
### (please edit this file and write your answer below each question. In addition, you may also review these questions with your mentor)

Demonstrate your understanding of this week's concepts by answering the following free-form questions.

Edit this document to include your answers after each question. Make sure to leave a blank line above and below your answer so it is clear and easy to read.

1. If you were to describe semantic HTML to the next cohort of students, what would you say?

HTML is a hyper text markup language. The language that our internet browser reads (google chrome, firefox etc..). 
Semantic HTML is a type of HTML which gives meaning to your content. 
It provides accessibility, improves SEO (search engine optimization), help other developes to read other people's tags. 
A few examples are <header> element which is a container for introductory content like the heading or titles.<h1> through <h6> which are headings that goes in order of importance just like in an essay where there is an introduction, body, conclusion and references.
<section> element tag helps to define a section in a document, <nav> element will contain a set of navigation links that takes you to mutliple links or websites or images throughout your webpage, <address>for when you have address on the page and <footer> elements contains the footer information on the page like copyrights, contact information.
Semantic HTML elements make it easier to read a website, provides accessibility to screen readers and will lead to consistent code. 

2. Name two big differences between ```display: block;``` and ```display: inline;```.

Block are elements that generally encompass inline elements. Block elements break onto a new line and arent used for doing things within a line of text. Block elements accept a width which why is we use them to lay out our page. Some examples of block elements are <div>, <h1> and <p>.
Inline elements can be nested inside of block elements. They can be inserted inside of other elements and not break into a new line. Some examples of inline elements are <a>, <em>, <strong>, and <span>.

If a box has an outer display type of block, it will behave in the following ways:

The box will break onto a new line.
The box will extend in the inline direction to fill the space available in its container. In most cases this means that the box will become as wide as its container, filling up 100% of the space available.
The width and height properties are respected.
Padding, margin and border will cause other elements to be pushed away from the box
Some HTML elements, such as <h1> and <p>, use block as their outer display type by default.

If a box has an outer display type of inline, then:

The box will not break onto a new line.
The width and height properties will not apply.
Vertical padding, margins, and borders will apply but will not cause other inline boxes to move away from the box.
Horizontal padding, margins, and borders will apply and will cause other inline boxes to move away from the box.
Some HTML elements, such as <a>, <span>, <em> and <strong> use inline as their outer display type by default.


3. What are the 4 areas of the box model?

Box model places all HTML elements into boxes. 
4 area of the box model are:
Content box: The area where your content is displayed, which can be sized using properties like width and height.
Padding box: The padding sits around the content as white space; its size can be controlled using padding and related properties.
Border box: The border box wraps the content and any padding. Its size and style can be controlled using border and related properties.
Margin box: The margin is the outermost layer, wrapping the content, padding, and border as whitespace between this box and other elements. Its size can be controlled using margin and related properties.

4. While using flexbox, what axis does the following property work on: ```align-items: center```?

when we use the property: "align-items" with the value "center"; all flex items are placed at the center of the cross axis. The cross axis is perpendicular to the main axis.


5. Explain why git is valuable to a team of developers.

Git is an open source distributed version control system. 
It maintains a history of all changes made to the code. The changes are stored in a special database called repository. 
The git is valuable to a team of developers because it keeps track of the changes and updates.
It enables us to see who made which changes. It also provides when and why a change was made. 
It provides developers with a systematic way of doing the project together; allowing the developers to focus on their section of the project. 
It allows developers to collaborate when working together.

The five advantages of using Git are:

Performance: Git performs very strongly and reliably when compared to other version control systems. New code changes can be easily committed, version branches can be effortlessly compared and merged, and code can also be optimized to perform better.
Security: Git is designed specially to maintain the integrity of source code. 
Flexibility: A key design objective of Git is the kind of flexibility it offers to support several kinds of nonlinear development workflows and its efficiency in handling both small scale and large scale projects as well as protocols. It is uniquely designed to support tagging and branching operations and store each and every activity carried out by the user as an integral part of “change” history. 
Wide acceptance: Git offers the type of performance, functionality, security, and flexibility that most developers and teams need to develop their projects. 
Quality open source project: Git is a widely supported open source project with over ten years of operational history. 

You are expected to be able to answer all these questions. Your responses contribute to your Sprint Challenge grade. Skipping this section *will* prevent you from passing this challenge.

## Project Set Up

- [ ] Create a forked copy of this project.
- [ ] Clone your OWN version of the repository (Not Lambda's by mistake!).
- [ ] Create a new branch: git checkout -b `<firstName-lastName>`.
- [ ] Implement the project on your newly created `<firstName-lastName>` branch, committing changes regularly.
- [ ] Push commits: git push -u origin `<firstName-lastName>`.
 
Follow these steps for completing your project.

- [ ] Submit a Pull-Request to merge <firstName-lastName> Branch into master (student's  Repo). **Please don't merge your own pull request**



## Minimum Viable Product

Your finished project must include all of the following requirements:

### Home Page

[Review the provided design file for the home page](design-files/home.png).  Notice the navigation and header images are missing.

* [ ] Build the HTML and CSS to create the missing navigation and header.
* [ ] Link the `About` navigation item to the [about.html](about.html) page

You will also notice there are 10 boxes on the home page that need background colors.  Use this list below to correctly style each box (Note: inline styles are not acceptable. All styles should be written in your index.css file):

* [ ] box1: `teal`
* [ ] box2: `gold`
* [ ] box3: `cadetblue`
* [ ] box4: `coral`
* [ ] box5: `crimson`
* [ ] box6: `forestgreen`
* [ ] box7: `darkorchid`
* [ ] box8: `hotpink`
* [ ] box9: `indigo`
* [ ] box10: `dodgerblue`

### About Page

[Review the provided design file for the about page](design-files/about.png). You have been provided the HTML wrapper, footer, and page content for the about page. Create the rest of the missing HTML and CSS to match the design file.

* [ ] Copy and paste your home page navigation and header into the about page
* [ ] Update the header image with the about page image
* [ ] Link the `Home` navigation item back to the `index.html` page.
* [ ] Build the rest of the about page layout to match the design

In your solution, it is essential that you follow best practices and produce clean and professional results. Schedule time to review, refine, and assess your work and perform basic professional polishing including spell-checking and grammar-checking on your work. It is better to submit a challenge that meets MVP than one that attempts too much and does not.

Note: Please make sure you are using flexbox to layout your website. Floats, inline-block, tables, etc, should not be used for layout. 

## Submission Instructions 
 
Please submit the url to your pull request in Canvas
