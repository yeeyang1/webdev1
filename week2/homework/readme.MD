# Homework Instructions - Week 2

To review the [lecture](../lecture/).

## Directions and Homework Requirements
+ Create a file inside the `week2/homework` folder named `index.html`
+ In the `index.html` file, set up the `doctype`, `head`, and `body`. 
+ Create a title inside the `head`: title the page, Homework 2 - by [Your Name]

Tell the story of your life in HTML!

Write a webpage that tells the story of your life. You can get creative with how you do this. But I want you to at least include the following
tags:
+ <h1>, <h2>...
+ <p>
+ <ul>, <ol>, or <dl>
+ <a> - can be to your favorite website • a table
+ <img>
+ <header>
+ <section>
+ <footer>
+ Upload the week2 folder to your Circuslabs web server (using FTP)
+ In a browser window, browse to the week2 folder you just uploaded to your server and copy the URL
+ Upload and commit your changes to Github
+ **Due by Monday morning @ 2:00 am**

## Form Elements
```
<FORM> </FORM>
    action = URL
    method = get/post
    id

<INPUT />
    type=text
        name
        size - use CSS instead
        maxlength
    type=password
        name
        size - use CSS instead
        maxlength
    type=radio
        name - same for all in the set
        value - different for each
        checked
    type=checkbox
        name - same for all in the set
        value - different for each
        checked
    type=file * form's method must be POST
        name
    type=submit
        name
        value - text inside the button
    type=image - uses an image as a button
        src
        width
        height
    type=hidden - do not show up, used to send additional information from the form
        name
        value

<BUTTON> </BUTTON> - can have IMG tags inside
    

<TEXTAREA> </TEXTAREA>
    cols - use CSS instead
    rows - use CSS instead

<SELECT> </SELECT> = drop down list
    name
    size - if used, it turns it shows multiple options at once *kinda funky, must test in multiple browsers
    multiple - allows user to select more than 1 option
<OPTION> </OPTION>
    value
    selected

<LABEL> </LABEL> - can wrap around the text & input OR be separate & use the for attribute
    for = same as the input's ID it's attached to
    *BEST PRACTICES
    Above or to the left = text input, text area, select boxes, file uploads
    To the right = checkboxes, radio buttons

<FIELDSET> </FIELDSET>

<LEGEND> </LEGEND>

NEW IN HTML5
<INPUT />
    type=date
        name
    type=email
        name
    type=url
        name
    type=search
        name
        placeholder
```

## Tables
Tables are great for presenting tabular data. Think Microsoft Excel or Google Spreadsheets and should only be used in this fashion. 

Unfortunately, tables have been used for the creation and construction of web pages *(pretty much a huge no-no)* and are still used on the web in the form of emails. A majority of the emails you recieve from marketers are typically in a `<table>`.

```
        <table>
            <tr>
                <td>Jill</td>
                <td>Smith</td>
                <td>50</td>
            </tr>
            <tr>
                <td>John</td>
                <td>Jones</td>
                <td>32</td>
            </tr>
        </table>
```

Tables may also take on the structural look of the `<html>` tag as well, which has a `head` and `<body>` tag. Tables may have a `<thead>` and `<tbody>` to separate your table further.

```
        <table>

            <thead>
                <tr>
                    <th>Jill</th>
                    <th>Smith</th>
                    <th>50</th>
                </tr>
            </thead>

            <tbody>
                <tr>
                    <td>Jill</td>
                    <td>Smith</td>
                    <td>50</td>
                </tr>
                <tr>
                    <td>John</td>
                    <td>Jones</td>
                    <td>32</td>
                </tr>
            </tbody>

        </table>
```