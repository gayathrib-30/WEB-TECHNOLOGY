[22/05/2026]
1. WHAT IS HTML ?
- HTML Stands for **Hyper Text Markup Language**
- It is used for creating the structure of Webpage
- To create a structure we have to use Tags in HTML

2. WHAT IS HYPERTEXT ?
- Any Text that contains link of any other webpage is called as Hypertext.

3. WHY IT IS CALLED AS MARKUP LANGUAGE ?
- Because by using HTML we are not writing any logics,only we are creating the structure.

4. WHAT IS TAGS ?
- Tag is predefined words enclosed with angular brackets <>
- There are two types of Tags ---> 1.PAIRED TAGS 2.UNPAIRED TAGS/SELF-CLOSING TAGS

5. PAIRED TAGS :
- Any tag having both opening tag and closing tag is called as Paired tags
  Example : <h1>CONTENT</h1>
  Syntax :<tagname> </tagname>

6. UNPAIRED TAGS :
- Any tags having only opening tag and no closing tag is called as unpaired tags
  Example : <meta>
  Syntax : <tagname>

7. STRUCTURE OF HTML CODE :
    <!DOCTYPE html>
    <html>
    <head>
        <title>Document</title>
    </head>
    <body>
        <!-- CONTENT -->
    </body>
    </html>

8. <!DOCTYPE html> :
- It is used to tell the browser which version of HTML we are using.
- Currently We are using HTML version 5

9. <html></html> :
- It is the root tag of HTML structure
- All the contents should be inside this root tag

10. <head></head> :
- It is used to provide the meta information

11. <title></title> :
- It is used to give the name of the tag.

12. <body></body> :
- The content we want to display in the browser, everything will be written inside body tag.

[23/05/26]

13. HEADING TAGS:
- In html for providing headlines(heading/subheading) we need heading tags.
- There are 6 haeding tags in html:
    <h1></h1>...<h6></h6>
- Heading tags are Paired tags.
- All the heading tags are **Block level Element**.
- Eg:
    <body>
      <h1>This is heading tag 1</h1>      
      <h2>This is heading tag 2</h2>
      <h3>This is heading tag 3</h3>  
      <h4>This is heading tag 4</h4>  
      <h5>This is heading tag 5</h5>  
      <h6>This is heading tag 6</h6>  
    </body>
- NOTE:<h1></h1>tag is the biggest and <h6></h6> tag is the smallest.
       The default size of h1 tag is "32 px"

14. PARAGRAPH TAG:
- In HTML if we want to write any text content that should be written by using paragraph tag.
- Paragraph tag is denoted by using <p></p>.
- Paragraph tags are Paired tags.
- It is "Block  Level Element".
- By default the size of <p></p> tag is "16 px".
 
[25/05/2026]
15. FORMATTING TAGS:
- It is used to change the apperance or format of the text content.
- Example:
-<br></br>-->It is used to make the content bold.
-<strong></strong>-->It is also used to amke the content bold but this tag having **higher priority** compare to <b></b> tag.
-<i></i>-->It is used to make the content italic.
-<em></em>-->It is also used to make the content italic same like <i> tag.
-<u></u>-->This tag is used to provide underline for the text.
-<ins></ins>-->similar to <u> tag.
-<mark></mark>-->This tag is used to make the text highlight.
-<sub></sub>-->It is used to write the content to the base.
-<sup></sup>-->It is used to write any content to the power.
-<q></q>-->It is used to provide double qoutes around the text.
-<pre></pre>-->It is pre-formatted tag.Inside how we will write the content it will display as it is.
-<del></del>-->It is used to give strike through the text.
----------------------------------------------------------------------------------------------------------------------------------
-<br>-->This tag is ude to break the line,It helps to make the content in the next line,It is unpaired tag.
-<hr>-->It is used to provide horizontal line,it is unpaired tag.

16. ELEMENTS:
- The combination of Tags and content inside the tag is called as Element.
- Types of Element:
    We have 3 types of Element:
        *Block Level Element
        *Inline Level Element
        *Inline Block Level Element
- Block Level Element:
    -->These elements will be taking full width of its parent and it all of them will be dispalyed in the next line.
    -->We can provide **Height and Width** for this elements.
    -->Ex:Heading tags,<p></p>,<div></div>.
- Inline Level Element:
    -->These elements will be displaying in the same line,
    -->Here **we can't provide Height and Width** for this element.
    -->It is occuyping the content width/area.
    -->Ex:All the formatting tags(<u></u>,<b></b>,<span></span>,etc..).
- Inline Block Level Element:
    -->It is the combination of inline and block level elements.
    -->These elements will **dispaly in same line but we can provide height and width**.
    -->Ex:<button></button>,<input></input>,<img>.

[26/05/2026]

17. ATRRIBUTES:
- Attributes are used to provide additional information to the tags.
- Attributes should be written in the opening tags
- SYNTAX:
    <tagname attributename="value"> </tagname>

18. <img> TAG:
- It is to add the image in the webpage.
- In this tag we have four attributes:
   -> *src*-It is used to provide path of the image
   ->*alt*-It is used to aternate message(If the img is not displaying that time this alt msg will disaplay on the page).
   ->*height* & *width*-Used for resizing the img.
- <img> tag is Self-closing/Unpaired Tag.
- It is one **Inline-Block** Level Element.

[27/05/26]

19. <marquee> TAG:
- It is used to make any content scrollable on the webpage.
- By default the content will scroll from right to left.
- Attributes of marquee tag:
    1.**scrollamount**:
        -It is used to determine the speed of the scrolling content.
        -By default value is '6'.
    2.**direction**:
            - It is used to determine the direction of the scrolling content.
            - Value: => 'left', 'right', 'up', 'down'
    3.**behavior**:
        -It is used to determine how the scrolling content will behave.
        -values:'scroll','slide','alternate'.
    4.**loop**:
        -It determines how many times the content should scroll.
    5.**height & width**:
        -used to resize the marquee tag area

[29/05/2026]

20. LIST:
- List is used to group the related elements together
- In HTML we have three types of list:
    1.Ordered List
    2.UnOrdered List
    3.Discriptive List
-->**Ordered list**:
    -It is used to group and arrange the elements in particular order.
    -For creating this we need <ol></ol> Tag.
    -Inside the <ol> for writing the items we need <li></li> Tag.
    -These tags are block-level element.
    -**ATTRIBUTES IN <ol></ol> TAG**:
        1.type:
            -This attribute is used to change the list-style.
            -values:a,A,i,I,numbers(default).
        2.start:
            -This is used to specify the specify the starting value of the list-style.
        3.reversed:
            -It is used to dispaly the list-style in reverse order.
        Example:
        <ol type="1" start="50" reversed>
            <li>Java</li>
            <li>Python</li>
            <li>JS</li>
        </ol>
        'o/p'-->50.Java
              49.Python
              48.JS
-->**UnOrdered List**:
    -It is created by using <ul></ul> Tag.
    -Here we are grouping the elements together but they are not arranged in specific oreder.
    -Inside the <ul> for writing the items we need <li></li> Tag.
    -By default it disaplays the list-style as "Disc" or "Bullet point".
    -Here we can provide only **type attribute**.
    -Values: 'disc','square','circle','none'.
    Example:
    <ul type="circle">
        <li>sql</li>
        <li>web-tech</li>
        <li>adv.java</li>
    </ul>
-->**Description List**:
    -For creating description list we need <dl></dl> Tag.
    -Inside that we have to use <dt></dt> and <dd></dd> Tag.
    -<dt></dt> Tag is used to provide the description term and <dd></dd> Tag is used to provide the  description definition for that term.
    Example:
    <dl>
        <dt>HTML</dt>
        <dd>Hyper Text Markup Language</dd>
    </dl>
    'o/p'-->HTML
                Hyper Text Markup Language

[30/05/2026]

21. <audio></audio> TAG:
- It is used to provide the audio or music in our webpage.
- **ATTRIBUTES**:
    1.src->It is used to provide path of the audio.
    2.controls->If we give this attribute then only audio will be visible in webpage and we can control the audio(play,pause,skip).
    3.autoplay-> For this attribute music will start automatically whenever our page will be loading.
    4.muted-> It makes the audio mute.
    5.loop->This attribute is used to play the audio infinite time in a loop.
22. <video></video> TAG:
- This tag is used to dispaly the video in our webpage.
- **ATTRIBUTES**:src,controls,loop,autoplay,muted(these attributes are same as <audio> Tag).
    1.poster->This attribute is used to provide image or thumbnail for the video.
            ->In this attribute we have to provide the path of the image.
    2.height,weight->It is used for resizing the video.
23. <iframe></iframe> TAG:
- It is used to add different webpage in our current webpage.
- It is **inline-block level** element.
- **ATRRIBUTES**:
    1.src->In this attribute we have to provide the path of the webpage we want to add in our webpage.
    2.frameborder->It is used to provide the outline/border around the content.
                 ->By default value is '0'.
    3.height & width->It is used to provide resize of the content.

[01-06-2026]

24. ANCHOR TAG:
- Anchor tag is denoted by <a></a> Tag.
- Anchor Tag is used to create the hyperlink.
- It helps to navigate/redirect from one page to another page or in the same page from one section to another section.
- It is **inline level element**.
- *Attributes*
    1.href : It is used to take the path where we want to navigate
    2.target : By default if we click any hyperlink it opens in the same tab if we want to open in a different tab we need     target attribute
    Values->  _self(default) 
            ->  _blank is used to open the page in next tab
    3.title : When we hover on the element the title attribute is used to display some msg
    Example :
    <a href="https://www.instagram.com/" target="_blank" title="Insta">INSTAGRAM</a>

    **How to navigate in the same page ?**
    Step-1: In Which tag we want to navigate there we have to provide 'id' attribute
    Step-2: Which Value we are giving forthe id attribute taht same value we have to provide in href attribute with '#'symbol
    Example :
     Step 2:
     <a href="#projectS">My Project</a>
     Step 1 :
     <h3 id="projects">MY PROJECTS</h3>

[02-06-2026]

25. TABLE IN HTML
- Table is a combination of rows and columns.
- For creating table in HTML, we need <table></table> tag.
- Inside the table if we want to create row, we need <tr></tr> tag.
- Inside row for giving data in table we need <td></td> tag.
- For providing heading data in table we need <th></th> tag.
- For giveing the caption/name/title of the table we need <caption></caption> tag.
- Attributes in <table></table> tag:
    1. border: 
        - used to provide the border/outline to the total table.
    2. height, width: 
        - used to resize the table length.
    3. cellspacing: 
        - used to provide the space between the cells.
    4. cellpadding: 
        - used to provide space inside the cell between the content and border.

[04-06-2026]

 **ATTRIBUTES FOR <td></td> AND <th></th> tags:**
    *rowspan* : This attribute is used to combine two or more rows.
    *colspan* : This attribute is used to combine two or more columns.
    *NOTE* 
        We have some extra tags in table like
        <thead></thead>
        <tbody></tbody>
        <tfoot></tfoot>
 
[06-06-2026]

26. <div></div> TAG:
- It is one **Block Level Element** used to make division.
- Inside this tag we can write inline,block and inline-block level elements.
- We can provide height and height.
 
27. <span></span> TAG:
- It i9s **Inline Level Element** used to select some part of block level Element.
- We cannot provide height and width.

28. Forms in HTML
Forms in HTML are used to collect user information.
Forms are block-level elements, while most of the form elements inside them 
are inline-level. 
Tags Used in Forms:
1. <form>: 
- It is a semantic element that defines the beginning of the form.
- It contains all the form-related elements.
Example:
<formaction="/submit" method="post">
<!-- form elements go here -->
</form>
2. <label>:
- Specifies the purpose of the input field.
- It's linked to the <input> field using the for attribute, which matches the id
of the input element.
Example:
<label for="userName">Name:</label>
<input type="text" id="userName">
3. <input>:
- Used to collect user data.
- There are various types such as text, email, password, number, etc.
Example:
<input type="email" id="userEmail"> 4. <select>:
- Creates a dropdown list from which users can select options.
Example:
<label for="skills">Skills:</label>
<select id="skills">
<option value="html">HTML</option>
<option value="css">CSS</option>
</select>
5. <option>:
- Defines the options within a dropdown list.
6. <fieldset>:
- Groups form elements together and provides a border around them.
Example:
<fieldset>
<legend>Personal Information</legend>
<label for="name">Name:</label>
<input type="text" id="name">
</fieldset>
7. <legend>:
- Provides a caption for the <fieldset> group.
8. <textarea>:
- Used to collect multi-line text input.
- The rows and cols attributes specify the visible height and width.
Example:
<textarea rows="5" cols="30"></textarea> 9. <button>:
- Creates a clickable button in the form. It can be used to submit or reset the 
form based on the type attribute.
Example:
<button type="submit">Submit</button>
Attributes of the <form> Tag:
1. action: Specifies the URL where form data will be submitted.
Example:
<formaction="/submit-data">
2. method: Specifies how the data is sent to the server (GET or POST).
- GET: Sends data in the URL, not secure.
- POST: Sends data securely in the HTTP body.
Example:
<formmethod="post">
3. autocomplete: Defines whether form inputs should have auto-complete 
enabled (on or off).
Example:
<formautocomplete="on"> Attributes of the <input> Tag:
1.type: Specifies the type of input field (e.g., text, email, password, etc.).
2. id: Provides a unique identifier for the input element.
3. name: Associates a name with the input field, used for form submission.
4. value: Defines the initial value of the input field.
5.required: Makes the field mandatory to fill before submission.
6.readonly: Prevents users from modifying the input field value.
7. disabled: Disables the input field.
8. min, max, minlength, maxlength: Used to define the minimum and 
maximum values or lengths for input.
9. placeholder: Displays a hint text inside the input field.
Values of type Attribute in HTML <input> Tag
The type attribute of the <input> tag in HTML determines the kind of input 
field displayed on the webpage. Here are the common values of the type
attribute:
1.text:
- Allows users to enter regular text.
- Default input type.
Example:
<input type="text">
2. email:
- Used for email input. It automatically validates the input for an email 
format.
Example:
<input type="email"> 3. password:
- Displays input as masked characters (dots or asterisks), hiding the user's 
input.
Example:
<input type="password">
4. number:
- Allows users to enter numerical values. It can have min, max, and step 
attributes for validation.
Example:
<input type="number" min="1" max="100" step="1">
5.tel:
- Allows users to input telephone numbers. It doesn't enforce specific 
validation but provides a numeric keyboard on mobile devices.
Example:
<input type="tel">
6.radio:
- Creates a radio button, allowing users to select one option from a group.
Example:
<input type="radio" name="gender" value="male"> Male
<input type="radio" name="gender" value="female"> Female 7. checkbox:
- Creates a checkbox, allowing users to select multiple options 
independently.
Example:
<input type="checkbox" value="subscribe"> Subscribe
8. button:
- Creates a clickable button. Typically, you can use JavaScript to define what 
happens when it’s clicked.
Example:
<input type="button" value="Click Me">
9.submit:
- Creates a submit button that submits the form data to the server.
Example:
<input type="submit" value="Submit Form">
10.reset:
- Resets all the form fields to their default values.
Example:
<input type="reset" value="Reset Form"> 11. date:
- Allows users to select a date using a date picker.
Example:
<input type="date">
12.time:
- Allows users to select a time.
Example:
<input type="time">
13. week:
- Allows users to select a specific week in a year.
Example:
<input type="week">
14. month:
- Allows users to select a specific month and year.
Example:
<input type="month">
15. color:
- Allows users to select a color from a color picker.
Example:
<input type="color"> 16. image:
- Creates a submit button in the form of an image.
Example:
<input type="image" src="submit.png" alt="Submit">
17. file:
- Allows users to upload files from their device.
Example:
<input type="file">
18.range:
- Creates a slider input that allows users to select a numeric value within a 
specific range.
Example:
<input type="range" min="1" max="100">

29. <div> and <span> Tag:
<!-- ! div And span Tag -->
<div> Tag (Block-Level Element)
- The <div> tag is a block-level container used to group elements together 
for styling and layout purposes. It doesn't inherently have any meaning or 
style.
- Characteristics:
- Block-level element: Occupies the full width available.
- Can contain any HTML elements such as text, images, other divs, forms, 
etc.
- Useful for dividing a webpage into sections.
- Usage:
- Ideal for creating large structural sections like headers, footers, 
content areas, and navigation menus.
- Helps in applying CSS styles and JavaScript functionality to groups of 
elements.
<span> Tag (Inline-Level Element)
- The <span> tag is an inline-level container used to group text or other 
inline elements. Like <div>, it has no default styling or meaning but is 
useful for applying specific styles to inline content.
- Characteristics:
- Inline-level element: Occupies only the space it needs (doesn't start on a 
new line).
- Cannot contain block-level elements (like <div>, <h1>, etc.).
- Mainly used for styling a specific part of the text or inline elements.
- Usage:
- Ideal for applying styles or JavaScript to a small portion of text or 
elements within a larger block of content.
- Commonly used within paragraphs (<p>) to style or modify part of the text.
### When to Use:
- Use <div>: When you need to group large sections of content or create page 
layout structures.
- Use <span>: When you want to apply styles or modify small parts of inline 
content without affecting the overall layout. 

30. SEMANTIC TAGS: 
Semantic tags are HTML elements that clearly describe their meaning both to 
the browser and to developers. 
Unlike non-semantic tags (<div>, <span>), semantic tags provide meaning to the 
content enclosed within them.
- Purpose: The primary purpose of semantic tags is to improve the structure, 
readability, and accessibility of web pages, making it easier for search 
engines, screen readers, and developers to understand the layout and content.
### Common Semantic Tags
1. <header>
- Definition: Represents the introductory section or a group of navigation 
links in a webpage.
- Usage: Typically contains logo, site name, and navigation elements.
- Example:
<header>
<h1>My Website</h1>
<nav>
<a href="#">Home</a>
<a href="#">About</a>
<a href="#">Contact</a>
</nav>
</header>
2. <nav>
- Definition: Represents a section of the page that links to other pages or 
to parts within the same page.
- Usage: Usually used for navigation bars or menus.
- Example:
<nav>
<ul>
<li><a href="#">Home</a></li>
<li><a href="#">Services</a></li>
<li><a href="#">Contact</a></li>
</ul>
</nav> 3. <main>
- Definition: Represents the main content of the webpage that is unique to 
the document, excluding headers, footers, and sidebars.
- Usage: Used for the central content of the webpage.
- Example:
<main>
<h2>Welcome to Our Website</h2>
<p>This is the primary content of the page.</p>
</main>
4. <article>
- Definition: Represents an independent piece of content that could be 
independently distributed or reused, such as blog posts, news articles, or 
user comments.
- Usage: Used for self-contained, reusable content.
- Example:
<article>
<h3>Blog Post Title</h3>
<p>This is a blog post description.</p>
</article>
5. <section>
- Definition: Represents a generic section of a document or application. 
Used to group related content together.
- Usage: Used for thematic grouping of content.
- Example:
<section>
<h2>Our Services</h2>
<p>We provide high-quality services to our customers.</p>
</section>
6. <aside>
- Definition: Represents content that is tangentially related to the 
content around it, such as sidebars or pull quotes.
- Usage: Typically used for supplementary content.
- Example:
<aside>
<h4>Related Articles</h4>
<p>Check out these articles for more information.</p>
</aside> 7. <footer>
- Definition: Represents the footer of a section or page, typically 
containing copyright information, links to privacy policies, or contact 
details.
- Usage: Found at the bottom of the page or section.
- Example:
<footer>
<p>&copy; 2024 My Website. All rights reserved.</p>
</footer>
8. <figure>
- Definition: Represents self-contained content, like images, diagrams, or 
illustrations, along with their caption.
- Usage: Used for media elements with captions.
- Example:
<figure>
<img src="image.jpg" alt="A beautiful scenery">
<figcaption>Beautiful mountain scenery at sunrise.</figcaption>
</figure>
9. <figcaption>
- Definition: Used to define a caption for a <figure> element.
- Usage: Describes or gives context to the content within the <figure>.
- Example: (See the example for <figure> above)
10. <mark>
- Definition: Represents text that has been highlighted for reference 
purposes.
- Usage: Used to emphasize or highlight parts of the text.
- Example:
<p>The most <mark>important</mark> part of this paragraph is marked.</p> 11. <details>
- Definition: The <details> tag is used to create a collapsible section that 
users can open and close to reveal or hide additional information.
- Purpose: Provides a way to display optional or hidden information, which can 
be toggled by the user.
- Behavior: By default, the content inside the <details> tag is hidden, but it 
can be revealed when the user clicks on it.
- Syntax:
<details>
<summary>Click to view more details</summary>
<p>This is additional information that can be toggled.</p>
</details>
12. <summary>
- Definition: The <summary> tag is used inside the <details> tag to provide a 
heading or summary of the content that can be toggled.
- Purpose: Acts as a label or title that is clickable, and clicking on it 
reveals or hides the associated content.
- Behavior: It is always visible and is used to control the visibility of the 
rest of the content within the <details> tag.
- Syntax:
<details>
<summary>Click here for details</summary>
<p>Hidden content goes here.</p>