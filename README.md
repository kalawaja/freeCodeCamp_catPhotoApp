# Learn HTML by Building a Cat Photo App, Completed

> - HTML tags give a webpage its structure. You can use HTML tags to add photos, buttons, and other elements to your webpage. 
> - In this course, you'll learn the most common HTML tags by building your own cat photo app.
---
```html
<html>
  <body>
```

> **Step 1** <br>
HTML elements have opening tags like `<h1>` and closing tags like `</h1>`.<br>
Find the `h1` element and change its text to:<br>
`CatPhotoApp`<br>
Make sure that the text is between its opening and closing tags.

```html
<h1>CatPhotoApp</h1>
```
```html  
  </body>
</html>
```
> **Step 2** <br>
The `h1` to `h6` heading elements are used to signify the importance of content below them. The lower the number, the higher the importance, so `h2` elements have less importance than `h1` elements. Only use one `h1` element per page and place lower importance headings below higher importance headings.<br>
Below the `h1` element, add an `h2` element with this text:<br>
`Cat Photos`

```html
<html>
  <body>
```
```html
<h1>CatPhotoApp</h1>
```
```html
<h2>Cat Photos</h2>
```
```html  
  </body>
</html>
```
> **Step 3** <br>
The `p` element is used to create a paragraph of text on websites. Create a `p` element below your `h2` element and give it the following text:<br>
`Click here to view more cat photos.`

```html
<h2>Cat Photos</h2>
```
```html
<p>Click here to view more cat photos.</p>
```
```html  
  </body>
</html>
```
> **Step 4** <br>
Commenting allows you to leave messages without affecting the browser display. It also allows you to make code inactive. A comment in HTML starts with `<!--`, contains any number of lines of text, and ends with `-->`. For example, the comment `<!-- TODO: Remove h1 -->` contains the text `TODO: Remove h1`.<br>
Add a comment above the `p` element with this text:<br>
`TODO: Add link to cat photos`
```html
<html>
  <body>
    <h1>CatPhotoApp</h1>
    <h2>Cat Photos</h2>
```
```html
<!-- TODO: Add link to cat photos -->
```
```html
    <p>Click here to view more cat photos.</p>
  </body>
</html>
```
> **Step 5** <br>
HTML5 has some elements that identify different content areas. These elements make your HTML easier to read and help with Search Engine Optimization (SEO) and accessibility.<br>
Identify the main section of this page by adding a `<main>` opening tag after the `h1` element, and a `</main>` closing tag after the `p` element.

```html
<html>
  <body>
```
```html
    <h1>CatPhotoApp</h1>
```
```html
<main>
    <h2>Cat Photos</h2>
    <!-- TODO: Add link to cat photos -->
    <p>Click here to view more cat photos.</p>
</main>
```
```html
  </body>
</html>
```
> **Step 6** <br>
In the previous step, you put the `h2`, comment, and `p` elements inside the `main` element. This is called nesting. Nested elements should be placed two spaces further to the right of the element they are nested in. This spacing is called indentation and it is used to make HTML easier to read.<br>
The `h2` element and the comment are indented two spaces more than the `main` element in the code below. Use the space bar on your keyboard to add two more spaces in front of the `p` element so that it is indented properly as well.

```html
<html>
  <body>
      <h1>CatPhotoApp</h1>
```
```html
    <main>
      <h2>Cat Photos</h2>
      <!-- TODO: Add link to cat photos -->
      <p>Click here to view more cat photos.</p>
    </main>
```
```html
  </body>
</html>
```
> **Step 7** <br>
You can add images to your website by using the `img` element. `img` elements have an opening tag without a closing tag. A tag for an element without a closing tag is known as a self-closing tag.<br>
Add an `img` element below the `p` element. At this point, no image will show up in the browser.

```html
<html>
  <body>
    <h1>CatPhotoApp</h1>
    <main>
      <h2>Cat Photos</h2>
      <!-- TODO: Add link to cat photos -->
```
```html
      <p>Click here to view more cat photos.</p>
```
```html
      <img>
```
```html
    </main>
  </body>
</html>
```
> **Step 8** <br>
HTML attributes are special words used inside the opening tag of an element to control the element's behavior. The `src` attribute in an `img` element specifies the image's URL (where the image is located). An example of an `img` element using an `src` attribute: `<img src="https://www.example.com/the-image.jpg">`.<br>
Inside the existing `img` element, add an `src` attribute with this URL:<br>
`https://cdn.freecodecamp.org/curriculum/cat-photo-app/relaxing-cat.jpg`

```html
<html>
  <body>
    <h1>CatPhotoApp</h1>
    <main>
      <h2>Cat Photos</h2>
      <!-- TODO: Add link to cat photos -->
      <p>Click here to view more cat photos.</p>
```
```html
      <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/relaxing-cat.jpg">
```
```html
    </main>
  </body>
</html>
```
> **Step 9** <br>
All `img` elements should have an `alt` attribute. The `alt` attribute's text is used for screen readers to improve accessibility and is displayed if the image fails to load. For example, `<img src="cat.jpg" alt="A cat">` has an `alt` attribute with the text `A cat`.<br>
Inside the `img` element, add an `alt` attribute with this text:<br>
`A cute orange cat lying on its back`

```html
<html>
  <body>
    <h1>CatPhotoApp</h1>
    <main>
      <h2>Cat Photos</h2>
      <!-- TODO: Add link to cat photos -->
      <p>Click here to view more cat photos.</p>
```
```html
      <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/relaxing-cat.jpg" alt="A cute orange cat lying on its back">
```
```html
    </main>
  </body>
</html>
```
> **Step 10** <br>
You can link to another page with the anchor (`a`) element. For example, `<a href='https://freecodecamp.org'></a>` would link to `freecodecamp.org`.<br>
Add an anchor element after the paragraph that links to `https://freecatphotoapp.com`. At this point, the link won’t show up in the preview.

```html
<html>
  <body>
    <h1>CatPhotoApp</h1>
    <main>
      <h2>Cat Photos</h2>
      <!-- TODO: Add link to cat photos -->
```
```html
      <p>Click here to view more cat photos.</p>
```
```html
      <a href="https://freecatphotoapp.com"></a>
```
```html
      <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/relaxing-cat.jpg" alt="A cute orange cat lying on its back">
    </main>
  </body>
</html>
```
> **Step 11** <br>
A link's text must be placed between the opening and closing tags of an anchor (`a`) element. For example, `<a href="https://www.freecodecamp.org">click here to go to freeCodeCamp.org</a>` is a link with the text `click here to go to freeCodeCamp.org`.<br>
Add the anchor text cat photos to the anchor element. This will become the link's text.

```html
<html>
  <body>
    <h1>CatPhotoApp</h1>
    <main>
      <h2>Cat Photos</h2>
      <!-- TODO: Add link to cat photos -->
      <p>Click here to view more cat photos.</p>
```
```html
      <a href="https://freecatphotoapp.com">cat photos</a>
```
```html
      <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/relaxing-cat.jpg" alt="A cute orange cat lying on its back">
    </main>
  </body>
</html>
```
> **Step 12** <br>
You can see the words `cat photos` underlined next to the image in the preview now. That's your link; feel free to give it a click. In the text of your `p` element, turn the words `cat photos` into a link to `https://freecatphotoapp.com`. When you are done, remove the old anchor tag and text below the paragraph.

```html
<html>
  <body>
    <h1>CatPhotoApp</h1>
    <main>
      <h2>Cat Photos</h2>
      <!-- TODO: Add link to cat photos -->
```
```html
      <p>Click here to view more <a href="https://freecatphotoapp.com">cat photos</a>.</p>
```
```html
      <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/relaxing-cat.jpg" alt="A cute orange cat lying on its back">
    </main>
  </body>
</html>
```
> **Step 13** <br>
Add a `target` attribute with the value `_blank` to the anchor (`a`) element's opening tag, so that the link opens in a new tab.

```html
<html>
  <body>
    <h1>CatPhotoApp</h1>
    <main>
      <h2>Cat Photos</h2>
      <!-- TODO: Add link to cat photos -->
```
```html
      <p>Click here to view more <a href="https://freecatphotoapp.com" target="_blank">cat photos</a>.</p>
```
```html
      <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/relaxing-cat.jpg" alt="A cute orange cat lying on its back">
    </main>
  </body>
</html>
```
> **Step 14** <br>
Turn the image into a link by surrounding it with necessary element tags. Use `https://freecatphotoapp.com` as the anchor's `href` attribute value.

```html
<html>
  <body>
    <h1>CatPhotoApp</h1>
    <main>
      <h2>Cat Photos</h2>
      <!-- TODO: Add link to cat photos -->
      <p>Click here to view more cat photos.</p>
```
```html
      <a href="https://freecatphotoapp.com"><img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/relaxing-cat.jpg" alt="A cute orange cat lying on its back."></a>
```
```html
    </main>
  </body>
</html>
```
> **Step 15** <br>
Before adding any new content, you should make use of a `section` element to separate the cat photos content from the future content.<br>
Take all the elements currently located within the `main` element and nest them in a `section` element.

```html
<html>
  <body>
    <h1>CatPhotoApp</h1>
```
```html
    <main>
      <section>
      <h2>Cat Photos</h2>
      <!-- TODO: Add link to cat photos -->
      <p>Click here to view more <a target="_blank" href="https://freecatphotoapp.com">cat photos</a>.</p>
      <a href="https://freecatphotoapp.com"><img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/relaxing-cat.jpg" alt="A cute orange cat lying on its back."></a>
    </section>
    </main>
```
```html
  </body>
</html>
```
> **Step 16** <br>
It is time to add a new section. Add a second `section` element below the existing `section` element.

```html
<html>
  <body>
    <h1>CatPhotoApp</h1>
    <main>
```
```html
      <section>
      <h2>Cat Photos</h2>
      <!-- TODO: Add link to cat photos -->
      <p>Click here to view more <a target="_blank" href="https://freecatphotoapp.com">cat photos</a>.</p>
      <a href="https://freecatphotoapp.com"><img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/relaxing-cat.jpg" alt="A cute orange cat lying on its back."></a>
    </section>

    <section></section>
```
```html
    </main>
  </body>
</html>
```
> **Step 17** <br>
Within the second `section` element, add a new `h2` element with the text `Cat Lists`.

```html
<html>
  <body>
    <h1>CatPhotoApp</h1>
    <main>
      <section>
       <h2>Cat Photos</h2>
       <!-- TODO: Add link to cat photos -->
       <p>Click here to view more <a target="_blank" href="https://freecatphotoapp.com">cat photos</a>.</p>
       <a href="https://freecatphotoapp.com"><img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/relaxing-cat.jpg" alt="A cute orange cat lying on its back."></a>
     </section>
```
```html
     <section>
        <h2>Cat Lists</h2>
     </section>
```
```html
    </main>
  </body>
</html>
```
> **Step 18** <br>
When you add a lower rank heading element to the page, it's implied that you're starting a new subsection.<br>
After the last `h2` element of the second `section` element, add an `h3` element with this text:<br>
`Things cats love:`

```html
<html>
  <body>
    <h1>CatPhotoApp</h1>
    <main>
      <section>
       <h2>Cat Photos</h2>
       <!-- TODO: Add link to cat photos -->
       <p>Click here to view more <a target="_blank" href="https://freecatphotoapp.com">cat photos</a>.</p>
       <a href="https://freecatphotoapp.com"><img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/relaxing-cat.jpg" alt="A cute orange cat lying on its back."></a>
     </section>
```
```html
     <section>
        <h2>Cat Lists</h2>
        <h3>Things cats love:</h3>
     </section>
```
```html
    </main>
  </body>
</html>
```
> **Step 19** <br>
After the `h3` element with the `Things cats love:` text, add an unordered list (`ul`) element. Note that nothing will be displayed at this point.


```html
<html>
  <body>
    <h1>CatPhotoApp</h1>
    <main>
      <section>
       <h2>Cat Photos</h2>
       <!-- TODO: Add link to cat photos -->
       <p>Click here to view more <a target="_blank" href="https://freecatphotoapp.com">cat photos</a>.</p>
       <a href="https://freecatphotoapp.com"><img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/relaxing-cat.jpg" alt="A cute orange cat lying on its back."></a>
     </section>
     <section>
```
```html
        <h2>Cat Lists</h2>
        <h3>Things cats love:</h3>

        <ul></ul>
```
```html
     </section>
    </main>
  </body>
</html>
```
> **Step 20** <br>
Use list item (li) elements to create items in a list. Here is an example of list items in an unordered list:
```html
<ul>
  <li>milk</li>
  <li>cheese</li>
</ul>
```
Within the ul element nest three list items to display three things cats love:<br>
`cat nip` | `laser pointers` | `lasagna`

```html
<html>
  <body>
    <h1>CatPhotoApp</h1>
    <main>
      <section>
       <h2>Cat Photos</h2>
       <!-- TODO: Add link to cat photos -->
       <p>Click here to view more <a target="_blank" href="https://freecatphotoapp.com">cat photos</a>.</p>
       <a href="https://freecatphotoapp.com"><img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/relaxing-cat.jpg" alt="A cute orange cat lying on its back."></a>
     </section>
     <section>
        <h2>Cat Lists</h2>
        <h3>Things cats love:</h3>
```
```html
        <ul>
          <li>cat nip</li>
          <li>laser pointers</li>
          <li>lasagna</li>
        </ul>
```
```html
     </section>
    </main>
  </body>
</html>
```
> **Step 21** <br>
After the unordered list, add a new image with an `src` attribute value set to:
`https://cdn.freecodecamp.org/curriculum/cat-photo-app/lasagna.jpg`<br>
And its `alt` attribute value to:<br>
`A slice of lasagna on a plate.`

```html
<html>
  <body>
    <h1>CatPhotoApp</h1>
    <main>
      <section>
       <h2>Cat Photos</h2>
       <!-- TODO: Add link to cat photos -->
       <p>Click here to view more <a target="_blank" href="https://freecatphotoapp.com">cat photos</a>.</p>
       <a href="https://freecatphotoapp.com"><img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/relaxing-cat.jpg" alt="A cute orange cat lying on its back."></a>
     </section>
     <section>
        <h2>Cat Lists</h2>
        <h3>Things cats love:</h3>
```
```html
        <ul>
          <li>cat nip</li>
          <li>laser pointers</li>
          <li>lasagna</li>
        </ul>
        <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/lasagna.jpg" alt="A slice of lasagna on a plate.">
```
```html
     </section>
    </main>
  </body>
</html>
```
> **Step 22** <br>
The `figure` element represents self-contained content and will allow you to associate an image with a caption.<br>
Nest the image you just added within a `figure` element.

```html
<html>
  <body>
    <h1>CatPhotoApp</h1>
    <main>
      <section>
       <h2>Cat Photos</h2>
       <!-- TODO: Add link to cat photos -->
       <p>Click here to view more <a target="_blank" href="https://freecatphotoapp.com">cat photos</a>.</p>
       <a href="https://freecatphotoapp.com"><img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/relaxing-cat.jpg" alt="A cute orange cat lying on its back."></a>
     </section>
     <section>
        <h2>Cat Lists</h2>
        <h3>Things cats love:</h3>
        <ul>
          <li>cat nip</li>
          <li>laser pointers</li>
          <li>lasagna</li>
        </ul>
```
```html
        <figure>
         <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/lasagna.jpg" alt="A slice of lasagna on a plate.">
        </figure>
```
```html
     </section>
    </main>
  </body>
</html>
```
> **Step 23** <br>
A figure caption (`figcaption`) element is used to add a caption to describe the image contained within the `figure` element. For example, `<figcaption>A cute cat</figcaption>` adds the caption `A cute cat`.<br>
After the image nested in the `figure` element, add a `figcaption` element with text set to:<br>
`Cats love lasagna.`

```html
<html>
  <body>
    <h1>CatPhotoApp</h1>
    <main>
      <section>
       <h2>Cat Photos</h2>
       <!-- TODO: Add link to cat photos -->
       <p>Click here to view more <a target="_blank" href="https://freecatphotoapp.com">cat photos</a>.</p>
       <a href="https://freecatphotoapp.com"><img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/relaxing-cat.jpg" alt="A cute orange cat lying on its back."></a>
     </section>
     <section>
        <h2>Cat Lists</h2>
        <h3>Things cats love:</h3>
        <ul>
          <li>cat nip</li>
          <li>laser pointers</li>
          <li>lasagna</li>
        </ul>
```
```html
        <figure>
         <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/lasagna.jpg" alt="A slice of lasagna on a plate.">
         <figcaption>Cats love lasagna.</figcaption>
        </figure>
```
```html
     </section>
    </main>
  </body>
</html>
```
> **Step 24** <br>
Emphasize the word `love` in the `figcaption` element by wrapping it in an emphasis `em` element.

```html
<html>
  <body>
    <h1>CatPhotoApp</h1>
    <main>
      <section>
       <h2>Cat Photos</h2>
       <!-- TODO: Add link to cat photos -->
       <p>Click here to view more <a target="_blank" href="https://freecatphotoapp.com">cat photos</a>.</p>
       <a href="https://freecatphotoapp.com"><img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/relaxing-cat.jpg" alt="A cute orange cat lying on its back."></a>
     </section>
     <section>
        <h2>Cat Lists</h2>
        <h3>Things cats love:</h3>
        <ul>
          <li>cat nip</li>
          <li>laser pointers</li>
          <li>lasagna</li>
        </ul>
        <figure>
         <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/lasagna.jpg" alt="A slice of lasagna on a plate.">
```
```html
         <figcaption>Cats <em>love</em> lasagna.</figcaption>
```
```html
        </figure>
     </section>
    </main>
  </body>
</html>
```
> **Step 25** <br>
After the `figure` element, add another `h3` element with the text:<br>
`Top 3 things cats hate:`

```html
<html>
  <body>
    <h1>CatPhotoApp</h1>
    <main>
      <section>
       <h2>Cat Photos</h2>
       <!-- TODO: Add link to cat photos -->
       <p>Click here to view more <a target="_blank" href="https://freecatphotoapp.com">cat photos</a>.</p>
       <a href="https://freecatphotoapp.com"><img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/relaxing-cat.jpg" alt="A cute orange cat lying on its back."></a>
     </section>
     <section>
        <h2>Cat Lists</h2>
        <h3>Things cats love:</h3>
        <ul>
          <li>cat nip</li>
          <li>laser pointers</li>
          <li>lasagna</li>
        </ul>
```
```html
        <figure>
         <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/lasagna.jpg" alt="A slice of lasagna on a plate.">
         <figcaption>Cats <em>love</em> lasagna.</figcaption>
        </figure>
        <h3>Top 3 things cats hate:</h3>
```
```html
     </section>
    </main>
  </body>
</html>
```
> **Step 26** <br>
The code for an ordered list (`ol`) is similar to an unordered list, but list items in an ordered list are numbered when displayed.<br>
After the second `section` element's last `h3` element, add an ordered list with these three list items:<br>
`flea treatment` | `thunder` | `other cats`

```html
<html>
  <body>
    <h1>CatPhotoApp</h1>
    <main>
      <section>
       <h2>Cat Photos</h2>
       <!-- TODO: Add link to cat photos -->
       <p>Click here to view more <a target="_blank" href="https://freecatphotoapp.com">cat photos</a>.</p>
       <a href="https://freecatphotoapp.com"><img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/relaxing-cat.jpg" alt="A cute orange cat lying on its back."></a>
     </section>
     <section>
        <h2>Cat Lists</h2>
        <h3>Things cats love:</h3>
        <ul>
          <li>cat nip</li>
          <li>laser pointers</li>
          <li>lasagna</li>
        </ul>
        <figure>
         <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/lasagna.jpg" alt="A slice of lasagna on a plate.">
         <figcaption>Cats <em>love</em> lasagna.</figcaption>
        </figure>
```
```html
        <h3>Top 3 things cats hate:</h3>
        <ol>
          <li>flea treatment</li>
          <li>thunder</li>
          <li>other cats</li>
        </ol>
```
```html
     </section>
    </main>
  </body>
</html>
```
> **Step 27** <br>
After the ordered list, add another `figure` element.

```html
<html>
  <body>
    <h1>CatPhotoApp</h1>
    <main>
      <section>
       <h2>Cat Photos</h2>
       <!-- TODO: Add link to cat photos -->
       <p>Click here to view more <a target="_blank" href="https://freecatphotoapp.com">cat photos</a>.</p>
       <a href="https://freecatphotoapp.com"><img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/relaxing-cat.jpg" alt="A cute orange cat lying on its back."></a>
     </section>
     <section>
        <h2>Cat Lists</h2>
        <h3>Things cats love:</h3>
        <ul>
          <li>cat nip</li>
          <li>laser pointers</li>
          <li>lasagna</li>
        </ul>
        <figure>
         <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/lasagna.jpg" alt="A slice of lasagna on a plate.">
         <figcaption>Cats <em>love</em> lasagna.</figcaption>
        </figure>
        <h3>Top 3 things cats hate:</h3>
```
```html
        <ol>
          <li>flea treatment</li>
          <li>thunder</li>
          <li>other cats</li>
        </ol>

        <figure></figure>
```
```html
     </section>
    </main>
  </body>
</html>
```
> **Step 28** <br>
Inside the `figure` element you just added, nest an `img` element with a `src` attribute set to `https://cdn.freecodecamp.org/curriculum/cat-photo-app/cats.jpg`.

```html
<html>
  <body>
    <h1>CatPhotoApp</h1>
    <main>
      <section>
       <h2>Cat Photos</h2>
       <!-- TODO: Add link to cat photos -->
       <p>Click here to view more <a target="_blank" href="https://freecatphotoapp.com">cat photos</a>.</p>
       <a href="https://freecatphotoapp.com"><img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/relaxing-cat.jpg" alt="A cute orange cat lying on its back."></a>
     </section>
     <section>
        <h2>Cat Lists</h2>
        <h3>Things cats love:</h3>
        <ul>
          <li>cat nip</li>
          <li>laser pointers</li>
          <li>lasagna</li>
        </ul>
        <figure>
         <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/lasagna.jpg" alt="A slice of lasagna on a plate.">
         <figcaption>Cats <em>love</em> lasagna.</figcaption>
        </figure>
        <h3>Top 3 things cats hate:</h3>
        <ol>
          <li>flea treatment</li>
          <li>thunder</li>
          <li>other cats</li>
        </ol>
```
```html
        <figure>
          <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/cats.jpg">
        </figure>
```
```html
     </section>
    </main>
  </body>
</html>
```
> **Step 29** <br>
To improve accessibility of the image you just added, add an `alt` attribute with the text:<br>
`Five cats looking around a field.`

```html
<html>
  <body>
    <h1>CatPhotoApp</h1>
    <main>
      <section>
       <h2>Cat Photos</h2>
       <!-- TODO: Add link to cat photos -->
       <p>Click here to view more <a target="_blank" href="https://freecatphotoapp.com">cat photos</a>.</p>
       <a href="https://freecatphotoapp.com"><img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/relaxing-cat.jpg" alt="A cute orange cat lying on its back."></a>
     </section>
     <section>
        <h2>Cat Lists</h2>
        <h3>Things cats love:</h3>
        <ul>
          <li>cat nip</li>
          <li>laser pointers</li>
          <li>lasagna</li>
        </ul>
        <figure>
         <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/lasagna.jpg" alt="A slice of lasagna on a plate.">
         <figcaption>Cats <em>love</em> lasagna.</figcaption>
        </figure>
        <h3>Top 3 things cats hate:</h3>
        <ol>
          <li>flea treatment</li>
          <li>thunder</li>
          <li>other cats</li>
        </ol>
        <figure>
```
```html
          <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/cats.jpg" alt="Five cats looking around a field.">
```
```html
        </figure>
     </section>
    </main>
  </body>
</html>
```
> **Step 30** <br>
After the last `img` element, add a `figcaption` element with the text<br> 
`Cats hate other cats.`

```html
<html>
  <body>
    <h1>CatPhotoApp</h1>
    <main>
      <section>
       <h2>Cat Photos</h2>
       <!-- TODO: Add link to cat photos -->
       <p>Click here to view more <a target="_blank" href="https://freecatphotoapp.com">cat photos</a>.</p>
       <a href="https://freecatphotoapp.com"><img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/relaxing-cat.jpg" alt="A cute orange cat lying on its back."></a>
     </section>
     <section>
        <h2>Cat Lists</h2>
        <h3>Things cats love:</h3>
        <ul>
          <li>cat nip</li>
          <li>laser pointers</li>
          <li>lasagna</li>
        </ul>
        <figure>
         <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/lasagna.jpg" alt="A slice of lasagna on a plate.">
         <figcaption>Cats <em>love</em> lasagna.</figcaption>
        </figure>
        <h3>Top 3 things cats hate:</h3>
        <ol>
          <li>flea treatment</li>
          <li>thunder</li>
          <li>other cats</li>
        </ol>
        <figure>
```
```html
          <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/cats.jpg" alt="Five cats looking around a field.">
          <figcaption>Cats hate other cats.</figcaption>
```
```html
        </figure>
     </section>
    </main>
  </body>
</html>
```
> **Step 31** <br>
The `strong` element is used to indicate that some text is of strong importance or urgent.<br>
In the `figcaption` you just added, indicate that `hate` is of strong importance by wrapping it in a `strong` element.

```html
<html>
  <body>
    <h1>CatPhotoApp</h1>
    <main>
      <section>
       <h2>Cat Photos</h2>
       <!-- TODO: Add link to cat photos -->
       <p>Click here to view more <a target="_blank" href="https://freecatphotoapp.com">cat photos</a>.</p>
       <a href="https://freecatphotoapp.com"><img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/relaxing-cat.jpg" alt="A cute orange cat lying on its back."></a>
     </section>
     <section>
        <h2>Cat Lists</h2>
        <h3>Things cats love:</h3>
        <ul>
          <li>cat nip</li>
          <li>laser pointers</li>
          <li>lasagna</li>
        </ul>
        <figure>
         <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/lasagna.jpg" alt="A slice of lasagna on a plate.">
         <figcaption>Cats <em>love</em> lasagna.</figcaption>
        </figure>
        <h3>Top 3 things cats hate:</h3>
        <ol>
          <li>flea treatment</li>
          <li>thunder</li>
          <li>other cats</li>
        </ol>
        <figure>
          <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/cats.jpg" alt="Five cats looking around a field.">
```
```html
          <figcaption>Cats <strong>hate</strong> other cats.</figcaption>
```
```html
        </figure>
     </section>
    </main>
  </body>
</html>
```
> **Step 32** <br>
It is time to add a new section. Add a third `section` element below the second `section` element.

```html
<html>
  <body>
    <h1>CatPhotoApp</h1>
    <main>
      <section>
       <h2>Cat Photos</h2>
       <!-- TODO: Add link to cat photos -->
       <p>Click here to view more <a target="_blank" href="https://freecatphotoapp.com">cat photos</a>.</p>
       <a href="https://freecatphotoapp.com"><img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/relaxing-cat.jpg" alt="A cute orange cat lying on its back."></a>
     </section>
```
```html
     <section>
        <h2>Cat Lists</h2>
        <h3>Things cats love:</h3>
        <ul>
          <li>cat nip</li>
          <li>laser pointers</li>
          <li>lasagna</li>
        </ul>
        <figure>
         <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/lasagna.jpg" alt="A slice of lasagna on a plate.">
         <figcaption>Cats <em>love</em> lasagna.</figcaption>
        </figure>
        <h3>Top 3 things cats hate:</h3>
        <ol>
          <li>flea treatment</li>
          <li>thunder</li>
          <li>other cats</li>
        </ol>
        <figure>
          <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/cats.jpg" alt="Five cats looking around a field.">
          <figcaption>Cats <strong>hate</strong> other cats.</figcaption>
        </figure>
     </section>

     <section></section>
```
```html
    </main>
  </body>
</html>
```
> **Step 33** <br>
Inside the third `section` element, add an `h2` element with the text:<br>
`Cat Form`

```html
<html>
  <body>
    <h1>CatPhotoApp</h1>
    <main>
      <section>
       <h2>Cat Photos</h2>
       <!-- TODO: Add link to cat photos -->
       <p>Click here to view more <a target="_blank" href="https://freecatphotoapp.com">cat photos</a>.</p>
       <a href="https://freecatphotoapp.com"><img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/relaxing-cat.jpg" alt="A cute orange cat lying on its back."></a>
     </section>
     <section>
        <h2>Cat Lists</h2>
        <h3>Things cats love:</h3>
        <ul>
          <li>cat nip</li>
          <li>laser pointers</li>
          <li>lasagna</li>
        </ul>
        <figure>
         <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/lasagna.jpg" alt="A slice of lasagna on a plate.">
         <figcaption>Cats <em>love</em> lasagna.</figcaption>
        </figure>
        <h3>Top 3 things cats hate:</h3>
        <ol>
          <li>flea treatment</li>
          <li>thunder</li>
          <li>other cats</li>
        </ol>
        <figure>
          <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/cats.jpg" alt="Five cats looking around a field.">
          <figcaption>Cats <strong>hate</strong> other cats.</figcaption>
        </figure>
     </section>
```
```html
     <section>
        <h2>Cat Form</h2>
     </section>
```
```html
    </main>
  </body>
</html>
```
> **Step 34** <br>
Now you will add a web form to collect information from users.<br>
After the `Cat Form` heading, add a `form` element.

```html
<html>
  <body>
    <h1>CatPhotoApp</h1>
    <main>
      <section>
       <h2>Cat Photos</h2>
       <!-- TODO: Add link to cat photos -->
       <p>Click here to view more <a target="_blank" href="https://freecatphotoapp.com">cat photos</a>.</p>
       <a href="https://freecatphotoapp.com"><img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/relaxing-cat.jpg" alt="A cute orange cat lying on its back."></a>
     </section>
     <section>
        <h2>Cat Lists</h2>
        <h3>Things cats love:</h3>
        <ul>
          <li>cat nip</li>
          <li>laser pointers</li>
          <li>lasagna</li>
        </ul>
        <figure>
         <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/lasagna.jpg" alt="A slice of lasagna on a plate.">
         <figcaption>Cats <em>love</em> lasagna.</figcaption>
        </figure>
        <h3>Top 3 things cats hate:</h3>
        <ol>
          <li>flea treatment</li>
          <li>thunder</li>
          <li>other cats</li>
        </ol>
        <figure>
          <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/cats.jpg" alt="Five cats looking around a field.">
          <figcaption>Cats <strong>hate</strong> other cats.</figcaption>
        </figure>
     </section>
     <section>
```
```html
        <h2>Cat Form</h2>

        <form></form>
```
```html
     </section>
    </main>
  </body>
</html>
```
> **Step 35** <br>
The `action` attribute indicates where form data should be sent. For example, `<form action="/submit-url"></form>` tells the browser that the form data should be sent to the path `/submit-url`.<br>
Add an `action` attribute with the value<br>
`https://freecatphotoapp.com/submit-cat-photo` to the `form` element.

```html
<html>
  <body>
    <h1>CatPhotoApp</h1>
    <main>
      <section>
       <h2>Cat Photos</h2>
       <!-- TODO: Add link to cat photos -->
       <p>Click here to view more <a target="_blank" href="https://freecatphotoapp.com">cat photos</a>.</p>
       <a href="https://freecatphotoapp.com"><img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/relaxing-cat.jpg" alt="A cute orange cat lying on its back."></a>
     </section>
     <section>
        <h2>Cat Lists</h2>
        <h3>Things cats love:</h3>
        <ul>
          <li>cat nip</li>
          <li>laser pointers</li>
          <li>lasagna</li>
        </ul>
        <figure>
         <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/lasagna.jpg" alt="A slice of lasagna on a plate.">
         <figcaption>Cats <em>love</em> lasagna.</figcaption>
        </figure>
        <h3>Top 3 things cats hate:</h3>
        <ol>
          <li>flea treatment</li>
          <li>thunder</li>
          <li>other cats</li>
        </ol>
        <figure>
          <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/cats.jpg" alt="Five cats looking around a field.">
          <figcaption>Cats <strong>hate</strong> other cats.</figcaption>
        </figure>
     </section>
     <section>
        <h2>Cat Form</h2>
```
```html
        <form action="https://freecatphotoapp.com/submit-cat-photo">
        </form>
```
```html
     </section>
    </main>
  </body>
</html>
```
> **Step 36** <br>
The `input` element allows you several ways to collect data from a web form. Like `img` elements, `input` elements are self-closing and do not need closing tags.<br>
Nest an `input` element in the `form` element.

```html
<html>
  <body>
    <h1>CatPhotoApp</h1>
    <main>
      <section>
       <h2>Cat Photos</h2>
       <!-- TODO: Add link to cat photos -->
       <p>Click here to view more <a target="_blank" href="https://freecatphotoapp.com">cat photos</a>.</p>
       <a href="https://freecatphotoapp.com"><img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/relaxing-cat.jpg" alt="A cute orange cat lying on its back."></a>
     </section>
     <section>
        <h2>Cat Lists</h2>
        <h3>Things cats love:</h3>
        <ul>
          <li>cat nip</li>
          <li>laser pointers</li>
          <li>lasagna</li>
        </ul>
        <figure>
         <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/lasagna.jpg" alt="A slice of lasagna on a plate.">
         <figcaption>Cats <em>love</em> lasagna.</figcaption>
        </figure>
        <h3>Top 3 things cats hate:</h3>
        <ol>
          <li>flea treatment</li>
          <li>thunder</li>
          <li>other cats</li>
        </ol>
        <figure>
          <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/cats.jpg" alt="Five cats looking around a field.">
          <figcaption>Cats <strong>hate</strong> other cats.</figcaption>
        </figure>
     </section>
     <section>
        <h2>Cat Form</h2>
```
```html
        <form action="https://freecatphotoapp.com/submit-cat-photo">
            <input>
        </form>
```
```html
     </section>
    </main>
  </body>
</html>
```
> **Step 37** <br>
There are many kinds of inputs you can create using the `type` attribute. You can easily create a password field, reset button, or a control to let users select a file from their computer.<br>
Create a text field to get text input from a user by adding the `type` attribute with the value `text` to the `input` element.

```html
<html>
  <body>
    <h1>CatPhotoApp</h1>
    <main>
      <section>
       <h2>Cat Photos</h2>
       <!-- TODO: Add link to cat photos -->
       <p>Click here to view more <a target="_blank" href="https://freecatphotoapp.com">cat photos</a>.</p>
       <a href="https://freecatphotoapp.com"><img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/relaxing-cat.jpg" alt="A cute orange cat lying on its back."></a>
     </section>
     <section>
        <h2>Cat Lists</h2>
        <h3>Things cats love:</h3>
        <ul>
          <li>cat nip</li>
          <li>laser pointers</li>
          <li>lasagna</li>
        </ul>
        <figure>
         <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/lasagna.jpg" alt="A slice of lasagna on a plate.">
         <figcaption>Cats <em>love</em> lasagna.</figcaption>
        </figure>
        <h3>Top 3 things cats hate:</h3>
        <ol>
          <li>flea treatment</li>
          <li>thunder</li>
          <li>other cats</li>
        </ol>
        <figure>
          <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/cats.jpg" alt="Five cats looking around a field.">
          <figcaption>Cats <strong>hate</strong> other cats.</figcaption>
        </figure>
     </section>
     <section>
        <h2>Cat Form</h2>
        <form action="https://freecatphotoapp.com/submit-cat-photo">
```
```html
            <input type="text">
```
```html
        </form>
     </section>
    </main>
  </body>
</html>
```
> **Step 38** <br>
In order for a form's data to be accessed by the location specified in the `action` attribute, you must give the text field a `name` attribute and assign it a value to represent the data being submitted. For example, you could use the following syntax for an email address text field:<br> 
`<input type="text" name="email">`.<br>
Add the `name` attribute with the value `catphotourl` to your text field.

```html
<html>
  <body>
    <h1>CatPhotoApp</h1>
    <main>
      <section>
       <h2>Cat Photos</h2>
       <!-- TODO: Add link to cat photos -->
       <p>Click here to view more <a target="_blank" href="https://freecatphotoapp.com">cat photos</a>.</p>
       <a href="https://freecatphotoapp.com"><img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/relaxing-cat.jpg" alt="A cute orange cat lying on its back."></a>
     </section>
     <section>
        <h2>Cat Lists</h2>
        <h3>Things cats love:</h3>
        <ul>
          <li>cat nip</li>
          <li>laser pointers</li>
          <li>lasagna</li>
        </ul>
        <figure>
         <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/lasagna.jpg" alt="A slice of lasagna on a plate.">
         <figcaption>Cats <em>love</em> lasagna.</figcaption>
        </figure>
        <h3>Top 3 things cats hate:</h3>
        <ol>
          <li>flea treatment</li>
          <li>thunder</li>
          <li>other cats</li>
        </ol>
        <figure>
          <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/cats.jpg" alt="Five cats looking around a field.">
          <figcaption>Cats <strong>hate</strong> other cats.</figcaption>
        </figure>
     </section>
     <section>
        <h2>Cat Form</h2>
        <form action="https://freecatphotoapp.com/submit-cat-photo">
```
```html
            <input type="text" name="catphotourl">
```
```html
        </form>
     </section>
    </main>
  </body>
</html>
```
> **Step 39** <br>
Placeholder text is used to give people a hint about what kind of information to enter into an input. For example, `<input type="text" placeholder="Email address">`.<br>
Add the placeholder text `cat photo URL` to your `input` element.

```html
<html>
  <body>
    <h1>CatPhotoApp</h1>
    <main>
      <section>
       <h2>Cat Photos</h2>
       <!-- TODO: Add link to cat photos -->
       <p>Click here to view more <a target="_blank" href="https://freecatphotoapp.com">cat photos</a>.</p>
       <a href="https://freecatphotoapp.com"><img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/relaxing-cat.jpg" alt="A cute orange cat lying on its back."></a>
     </section>
     <section>
        <h2>Cat Lists</h2>
        <h3>Things cats love:</h3>
        <ul>
          <li>cat nip</li>
          <li>laser pointers</li>
          <li>lasagna</li>
        </ul>
        <figure>
         <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/lasagna.jpg" alt="A slice of lasagna on a plate.">
         <figcaption>Cats <em>love</em> lasagna.</figcaption>
        </figure>
        <h3>Top 3 things cats hate:</h3>
        <ol>
          <li>flea treatment</li>
          <li>thunder</li>
          <li>other cats</li>
        </ol>
        <figure>
          <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/cats.jpg" alt="Five cats looking around a field.">
          <figcaption>Cats <strong>hate</strong> other cats.</figcaption>
        </figure>
     </section>
     <section>
        <h2>Cat Form</h2>
        <form action="https://freecatphotoapp.com/submit-cat-photo">
```
```html
            <input type="text" name="catphotourl" placeholder="cat photo URL">
```
```html
        </form>
     </section>
    </main>
  </body>
</html>
```
> **Step 40** <br>
To prevent a user from submitting your form when required information is missing, you need to add the `required` attribute to an `input` element. There's no need to set a value to the `required` attribute. Instead, just add the word `required` to the `input` element, making sure there is space between it and other attributes.

```html
<html>
  <body>
    <h1>CatPhotoApp</h1>
    <main>
      <section>
       <h2>Cat Photos</h2>
       <!-- TODO: Add link to cat photos -->
       <p>Click here to view more <a target="_blank" href="https://freecatphotoapp.com">cat photos</a>.</p>
       <a href="https://freecatphotoapp.com"><img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/relaxing-cat.jpg" alt="A cute orange cat lying on its back."></a>
     </section>
     <section>
        <h2>Cat Lists</h2>
        <h3>Things cats love:</h3>
        <ul>
          <li>cat nip</li>
          <li>laser pointers</li>
          <li>lasagna</li>
        </ul>
        <figure>
         <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/lasagna.jpg" alt="A slice of lasagna on a plate.">
         <figcaption>Cats <em>love</em> lasagna.</figcaption>
        </figure>
        <h3>Top 3 things cats hate:</h3>
        <ol>
          <li>flea treatment</li>
          <li>thunder</li>
          <li>other cats</li>
        </ol>
        <figure>
          <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/cats.jpg" alt="Five cats looking around a field.">
          <figcaption>Cats <strong>hate</strong> other cats.</figcaption>
        </figure>
     </section>
     <section>
        <h2>Cat Form</h2>
        <form action="https://freecatphotoapp.com/submit-cat-photo">
```
```html
            <input type="text" name="catphotourl" placeholder="cat photo URL" required>
```
```html
        </form>
     </section>
    </main>
  </body>
</html>
```
> **Step 41** <br>
Use the `button` element to create a clickable button. For example, `<button>Click Here</button>` creates a button with the text<br> `Click Here.`<br>
Add a `button` element with the text `Submit` below the `input` element. The default behavior of clicking a form button without any attributes submits the form to the location specified in the form's `action` attribute.

```html
<html>
  <body>
    <h1>CatPhotoApp</h1>
    <main>
      <section>
       <h2>Cat Photos</h2>
       <!-- TODO: Add link to cat photos -->
       <p>Click here to view more <a target="_blank" href="https://freecatphotoapp.com">cat photos</a>.</p>
       <a href="https://freecatphotoapp.com"><img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/relaxing-cat.jpg" alt="A cute orange cat lying on its back."></a>
     </section>
     <section>
        <h2>Cat Lists</h2>
        <h3>Things cats love:</h3>
        <ul>
          <li>cat nip</li>
          <li>laser pointers</li>
          <li>lasagna</li>
        </ul>
        <figure>
         <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/lasagna.jpg" alt="A slice of lasagna on a plate.">
         <figcaption>Cats <em>love</em> lasagna.</figcaption>
        </figure>
        <h3>Top 3 things cats hate:</h3>
        <ol>
          <li>flea treatment</li>
          <li>thunder</li>
          <li>other cats</li>
        </ol>
        <figure>
          <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/cats.jpg" alt="Five cats looking around a field.">
          <figcaption>Cats <strong>hate</strong> other cats.</figcaption>
        </figure>
     </section>
     <section>
        <h2>Cat Form</h2>
        <form action="https://freecatphotoapp.com/submit-cat-photo">
```
```html
            <input type="text" name="catphotourl" placeholder="cat photo URL" required>
            <button>Submit</button>
```
```html
        </form>
     </section>
    </main>
  </body>
</html>
```
> **Step 42** <br>
Even though you added your button below the text input, they appear next to each other on the page. That's because both `input` and `button` elements are inline elements, which don't appear on new lines.<br>
The button you added will submit the form by default. However, relying on default behavior may cause confusion. Add the `type` attribute with the value `submit` to the `button` to make it clear that it is a submit button.

```html
<html>
  <body>
    <h1>CatPhotoApp</h1>
    <main>
      <section>
       <h2>Cat Photos</h2>
       <!-- TODO: Add link to cat photos -->
       <p>Click here to view more <a target="_blank" href="https://freecatphotoapp.com">cat photos</a>.</p>
       <a href="https://freecatphotoapp.com"><img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/relaxing-cat.jpg" alt="A cute orange cat lying on its back."></a>
     </section>
     <section>
        <h2>Cat Lists</h2>
        <h3>Things cats love:</h3>
        <ul>
          <li>cat nip</li>
          <li>laser pointers</li>
          <li>lasagna</li>
        </ul>
        <figure>
         <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/lasagna.jpg" alt="A slice of lasagna on a plate.">
         <figcaption>Cats <em>love</em> lasagna.</figcaption>
        </figure>
        <h3>Top 3 things cats hate:</h3>
        <ol>
          <li>flea treatment</li>
          <li>thunder</li>
          <li>other cats</li>
        </ol>
        <figure>
          <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/cats.jpg" alt="Five cats looking around a field.">
          <figcaption>Cats <strong>hate</strong> other cats.</figcaption>
        </figure>
     </section>
     <section>
        <h2>Cat Form</h2>
        <form action="https://freecatphotoapp.com/submit-cat-photo">
            <input type="text" name="catphotourl" placeholder="cat photo URL" required>
```
```html
            <button type="submit">Submit</button>
```
```html
        </form>
     </section>
    </main>
  </body>
</html>
```
> **Step 43** <br>
You can use radio buttons for questions where you want only one answer out of multiple options.<br>
Here is an example of a radio button with the option of `cat`: `<input type="radio"> cat`. Remember that `input` elements are self-closing.<br>
Before the text input, add a radio button with the option set as:<br>
`Indoor`

```html
<html>
  <body>
    <h1>CatPhotoApp</h1>
    <main>
      <section>
       <h2>Cat Photos</h2>
       <!-- TODO: Add link to cat photos -->
       <p>Click here to view more <a target="_blank" href="https://freecatphotoapp.com">cat photos</a>.</p>
       <a href="https://freecatphotoapp.com"><img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/relaxing-cat.jpg" alt="A cute orange cat lying on its back."></a>
     </section>
     <section>
        <h2>Cat Lists</h2>
        <h3>Things cats love:</h3>
        <ul>
          <li>cat nip</li>
          <li>laser pointers</li>
          <li>lasagna</li>
        </ul>
        <figure>
         <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/lasagna.jpg" alt="A slice of lasagna on a plate.">
         <figcaption>Cats <em>love</em> lasagna.</figcaption>
        </figure>
        <h3>Top 3 things cats hate:</h3>
        <ol>
          <li>flea treatment</li>
          <li>thunder</li>
          <li>other cats</li>
        </ol>
        <figure>
          <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/cats.jpg" alt="Five cats looking around a field.">
          <figcaption>Cats <strong>hate</strong> other cats.</figcaption>
        </figure>
     </section>
     <section>
        <h2>Cat Form</h2>
        <form action="https://freecatphotoapp.com/submit-cat-photo">
```
```html
            <input type="text" name="catphotourl" placeholder="cat photo URL" required>
            <input type="radio">Indoor
```
```html
            <button type="submit">Submit</button>
        </form>
     </section>
    </main>
  </body>
</html>
```
> **Step 44** <br>
`label` elements are used to help associate the text for an `input` element with the input element itself (especially for assistive technologies like screen readers). For example, `<label><input type="radio"> cat</label>` makes it so clicking the word `cat` also selects the corresponding radio button.<br>
Nest your `radio` button inside a `label` element.

```html
<html>
  <body>
    <h1>CatPhotoApp</h1>
    <main>
      <section>
       <h2>Cat Photos</h2>
       <!-- TODO: Add link to cat photos -->
       <p>Click here to view more <a target="_blank" href="https://freecatphotoapp.com">cat photos</a>.</p>
       <a href="https://freecatphotoapp.com"><img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/relaxing-cat.jpg" alt="A cute orange cat lying on its back."></a>
     </section>
     <section>
        <h2>Cat Lists</h2>
        <h3>Things cats love:</h3>
        <ul>
          <li>cat nip</li>
          <li>laser pointers</li>
          <li>lasagna</li>
        </ul>
        <figure>
         <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/lasagna.jpg" alt="A slice of lasagna on a plate.">
         <figcaption>Cats <em>love</em> lasagna.</figcaption>
        </figure>
        <h3>Top 3 things cats hate:</h3>
        <ol>
          <li>flea treatment</li>
          <li>thunder</li>
          <li>other cats</li>
        </ol>
        <figure>
          <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/cats.jpg" alt="Five cats looking around a field.">
          <figcaption>Cats <strong>hate</strong> other cats.</figcaption>
        </figure>
     </section>
     <section>
        <h2>Cat Form</h2>
        <form action="https://freecatphotoapp.com/submit-cat-photo">
```
```html         
            <label><input type="radio"> Indoor</label>
```
```html
            <input type="text" name="catphotourl" placeholder="cat photo URL" required>
            <button type="submit">Submit</button>
        </form>
     </section>
    </main>
  </body>
</html>
```
> **Step 45** <br>
The `id` attribute is used to identify specific HTML elements. Each `id` attribute's value must be unique from all other `id` values for the entire page.<br>
Add an `id` attribute with the value `indoor` to the radio button. When elements have multiple attributes, the order of the attributes doesn't matter.

```html
<html>
  <body>
    <h1>CatPhotoApp</h1>
    <main>
      <section>
       <h2>Cat Photos</h2>
       <!-- TODO: Add link to cat photos -->
       <p>Click here to view more <a target="_blank" href="https://freecatphotoapp.com">cat photos</a>.</p>
       <a href="https://freecatphotoapp.com"><img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/relaxing-cat.jpg" alt="A cute orange cat lying on its back."></a>
     </section>
     <section>
        <h2>Cat Lists</h2>
        <h3>Things cats love:</h3>
        <ul>
          <li>cat nip</li>
          <li>laser pointers</li>
          <li>lasagna</li>
        </ul>
        <figure>
         <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/lasagna.jpg" alt="A slice of lasagna on a plate.">
         <figcaption>Cats <em>love</em> lasagna.</figcaption>
        </figure>
        <h3>Top 3 things cats hate:</h3>
        <ol>
          <li>flea treatment</li>
          <li>thunder</li>
          <li>other cats</li>
        </ol>
        <figure>
          <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/cats.jpg" alt="Five cats looking around a field.">
          <figcaption>Cats <strong>hate</strong> other cats.</figcaption>
        </figure>
     </section>
     <section>
        <h2>Cat Form</h2>
        <form action="https://freecatphotoapp.com/submit-cat-photo">
```
```html         
            <label><input id="indoor" type="radio"> Indoor</label>
```
```html
            <input type="text" name="catphotourl" placeholder="cat photo URL" required>
            <button type="submit">Submit</button>
        </form>
     </section>
    </main>
  </body>
</html>
```
> **Step 46** <br>
Nest another radio button with the option `Outdoor` in a new `label` element. The new radio button should be placed after the first one. Also, set its `id` attribute value to:<br>
`outdoor`

```html
<html>
  <body>
    <h1>CatPhotoApp</h1>
    <main>
      <section>
       <h2>Cat Photos</h2>
       <!-- TODO: Add link to cat photos -->
       <p>Click here to view more <a target="_blank" href="https://freecatphotoapp.com">cat photos</a>.</p>
       <a href="https://freecatphotoapp.com"><img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/relaxing-cat.jpg" alt="A cute orange cat lying on its back."></a>
     </section>
     <section>
        <h2>Cat Lists</h2>
        <h3>Things cats love:</h3>
        <ul>
          <li>cat nip</li>
          <li>laser pointers</li>
          <li>lasagna</li>
        </ul>
        <figure>
         <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/lasagna.jpg" alt="A slice of lasagna on a plate.">
         <figcaption>Cats <em>love</em> lasagna.</figcaption>
        </figure>
        <h3>Top 3 things cats hate:</h3>
        <ol>
          <li>flea treatment</li>
          <li>thunder</li>
          <li>other cats</li>
        </ol>
        <figure>
          <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/cats.jpg" alt="Five cats looking around a field.">
          <figcaption>Cats <strong>hate</strong> other cats.</figcaption>
        </figure>
     </section>
     <section>
        <h2>Cat Form</h2>
        <form action="https://freecatphotoapp.com/submit-cat-photo">
```
```html         
            <label><input id="indoor" type="radio"> Indoor</label>
            <label><input id="outdoor" type="radio"> Outdoor</label>
```
```html
            <input type="text" name="catphotourl" placeholder="cat photo URL" required>
            <button type="submit">Submit</button>
        </form>
     </section>
    </main>
  </body>
</html>
```
> **Step 47** <br>
Notice that both radio buttons can be selected at the same time. To make it so selecting one radio button automatically deselects the other, both buttons must have a `name` attribute with the same value.<br>
Add the `name` attribute with the value `indoor-outdoor` to both radio buttons.

```html
<html>
  <body>
    <h1>CatPhotoApp</h1>
    <main>
      <section>
       <h2>Cat Photos</h2>
       <!-- TODO: Add link to cat photos -->
       <p>Click here to view more <a target="_blank" href="https://freecatphotoapp.com">cat photos</a>.</p>
       <a href="https://freecatphotoapp.com"><img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/relaxing-cat.jpg" alt="A cute orange cat lying on its back."></a>
     </section>
     <section>
        <h2>Cat Lists</h2>
        <h3>Things cats love:</h3>
        <ul>
          <li>cat nip</li>
          <li>laser pointers</li>
          <li>lasagna</li>
        </ul>
        <figure>
         <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/lasagna.jpg" alt="A slice of lasagna on a plate.">
         <figcaption>Cats <em>love</em> lasagna.</figcaption>
        </figure>
        <h3>Top 3 things cats hate:</h3>
        <ol>
          <li>flea treatment</li>
          <li>thunder</li>
          <li>other cats</li>
        </ol>
        <figure>
          <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/cats.jpg" alt="Five cats looking around a field.">
          <figcaption>Cats <strong>hate</strong> other cats.</figcaption>
        </figure>
     </section>
     <section>
        <h2>Cat Form</h2>
        <form action="https://freecatphotoapp.com/submit-cat-photo">
```
```html         
            <label><input name="indoor-outdoor" id="indoor" type="radio"> Indoor</label>
            <label><input name="indoor-outdoor" id="outdoor" type="radio"> Outdoor</label>
```
```html
            <input type="text" name="catphotourl" placeholder="cat photo URL" required>
            <button type="submit">Submit</button>
        </form>
     </section>
    </main>
  </body>
</html>
```
> **Step 48** <br>
If you select the `Indoor` radio button and submit the form, the form data for the button is based on its `name` and `value` attributes. Since your radio buttons do not have a `value` attribute, the form data will include `indoor-outdoor=on`, which is not useful when you have multiple buttons.<br>
Add a `value` attribute to both radio buttons. For convenience, set the button's `value` attribute to the same value as its `id` attribute.

```html
<html>
  <body>
    <h1>CatPhotoApp</h1>
    <main>
      <section>
       <h2>Cat Photos</h2>
       <!-- TODO: Add link to cat photos -->
       <p>Click here to view more <a target="_blank" href="https://freecatphotoapp.com">cat photos</a>.</p>
       <a href="https://freecatphotoapp.com"><img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/relaxing-cat.jpg" alt="A cute orange cat lying on its back."></a>
     </section>
     <section>
        <h2>Cat Lists</h2>
        <h3>Things cats love:</h3>
        <ul>
          <li>cat nip</li>
          <li>laser pointers</li>
          <li>lasagna</li>
        </ul>
        <figure>
         <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/lasagna.jpg" alt="A slice of lasagna on a plate.">
         <figcaption>Cats <em>love</em> lasagna.</figcaption>
        </figure>
        <h3>Top 3 things cats hate:</h3>
        <ol>
          <li>flea treatment</li>
          <li>thunder</li>
          <li>other cats</li>
        </ol>
        <figure>
          <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/cats.jpg" alt="Five cats looking around a field.">
          <figcaption>Cats <strong>hate</strong> other cats.</figcaption>
        </figure>
     </section>
     <section>
        <h2>Cat Form</h2>
        <form action="https://freecatphotoapp.com/submit-cat-photo">
```
```html         
          <label><input id="indoor" type="radio" name="indoor-outdoor" value="indoor"> Indoor</label>
          <label><input id="outdoor" type="radio" name="indoor-outdoor" value="outdoor"> Outdoor</label>
```
```html
            <input type="text" name="catphotourl" placeholder="cat photo URL" required>
            <button type="submit">Submit</button>
        </form>
     </section>
    </main>
  </body>
</html>
```
> **Step 49** <br>
The `fieldset` element is used to group related inputs and labels together in a web form. `fieldset` elements are block-level elements, meaning that they appear on a new line.<br>
Nest the `Indoor` and `Outdoor` radio buttons within a `fieldset` element, and don't forget to indent the radio buttons.

```html
<html>
  <body>
    <h1>CatPhotoApp</h1>
    <main>
      <section>
       <h2>Cat Photos</h2>
       <!-- TODO: Add link to cat photos -->
       <p>Click here to view more <a target="_blank" href="https://freecatphotoapp.com">cat photos</a>.</p>
       <a href="https://freecatphotoapp.com"><img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/relaxing-cat.jpg" alt="A cute orange cat lying on its back."></a>
     </section>
     <section>
        <h2>Cat Lists</h2>
        <h3>Things cats love:</h3>
        <ul>
          <li>cat nip</li>
          <li>laser pointers</li>
          <li>lasagna</li>
        </ul>
        <figure>
         <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/lasagna.jpg" alt="A slice of lasagna on a plate.">
         <figcaption>Cats <em>love</em> lasagna.</figcaption>
        </figure>
        <h3>Top 3 things cats hate:</h3>
        <ol>
          <li>flea treatment</li>
          <li>thunder</li>
          <li>other cats</li>
        </ol>
        <figure>
          <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/cats.jpg" alt="Five cats looking around a field.">
          <figcaption>Cats <strong>hate</strong> other cats.</figcaption>
        </figure>
     </section>
     <section>
        <h2>Cat Form</h2>
        <form action="https://freecatphotoapp.com/submit-cat-photo">
```
```html    
        <fieldset>
          <label><input id="indoor" type="radio" name="indoor-outdoor" value="indoor"> Indoor</label>
          <label><input id="outdoor" type="radio" name="indoor-outdoor" value="outdoor"> Outdoor</label>
        </fieldset>
```
```html
            <input type="text" name="catphotourl" placeholder="cat photo URL" required>
            <button type="submit">Submit</button>
        </form>
     </section>
    </main>
  </body>
</html>
```
> **Step 50** <br>
The `legend` element acts as a caption for the content in the `fieldset` element. It gives users context about what they should enter into that part of the form.<br>
Add a `legend` element with the text `Is your cat an indoor or outdoor cat?` above both of the radio buttons.

```html
<html>
  <body>
    <h1>CatPhotoApp</h1>
    <main>
      <section>
       <h2>Cat Photos</h2>
       <!-- TODO: Add link to cat photos -->
       <p>Click here to view more <a target="_blank" href="https://freecatphotoapp.com">cat photos</a>.</p>
       <a href="https://freecatphotoapp.com"><img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/relaxing-cat.jpg" alt="A cute orange cat lying on its back."></a>
     </section>
     <section>
        <h2>Cat Lists</h2>
        <h3>Things cats love:</h3>
        <ul>
          <li>cat nip</li>
          <li>laser pointers</li>
          <li>lasagna</li>
        </ul>
        <figure>
         <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/lasagna.jpg" alt="A slice of lasagna on a plate.">
         <figcaption>Cats <em>love</em> lasagna.</figcaption>
        </figure>
        <h3>Top 3 things cats hate:</h3>
        <ol>
          <li>flea treatment</li>
          <li>thunder</li>
          <li>other cats</li>
        </ol>
        <figure>
          <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/cats.jpg" alt="Five cats looking around a field.">
          <figcaption>Cats <strong>hate</strong> other cats.</figcaption>
        </figure>
     </section>
     <section>
        <h2>Cat Form</h2>
        <form action="https://freecatphotoapp.com/submit-cat-photo">
```
```html    
        <fieldset>
            <legend>Is your cat an indoor or outdoor cat?</legend>
            <label><input id="indoor" type="radio" name="indoor-outdoor" value="indoor"> Indoor</label>
            <label><input id="outdoor" type="radio" name="indoor-outdoor" value="outdoor"> Outdoor</label>
        </fieldset>
```
```html
            <input type="text" name="catphotourl" placeholder="cat photo URL" required>
            <button type="submit">Submit</button>
        </form>
     </section>
    </main>
  </body>
</html>
```
> **Step 51** <br>
Next, you are going to add some new form `input` elements, so add another `fieldset` element directly below the current `fieldset` element.

```html
<html>
  <body>
    <h1>CatPhotoApp</h1>
    <main>
      <section>
       <h2>Cat Photos</h2>
       <!-- TODO: Add link to cat photos -->
       <p>Click here to view more <a target="_blank" href="https://freecatphotoapp.com">cat photos</a>.</p>
       <a href="https://freecatphotoapp.com"><img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/relaxing-cat.jpg" alt="A cute orange cat lying on its back."></a>
     </section>
     <section>
        <h2>Cat Lists</h2>
        <h3>Things cats love:</h3>
        <ul>
          <li>cat nip</li>
          <li>laser pointers</li>
          <li>lasagna</li>
        </ul>
        <figure>
         <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/lasagna.jpg" alt="A slice of lasagna on a plate.">
         <figcaption>Cats <em>love</em> lasagna.</figcaption>
        </figure>
        <h3>Top 3 things cats hate:</h3>
        <ol>
          <li>flea treatment</li>
          <li>thunder</li>
          <li>other cats</li>
        </ol>
        <figure>
          <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/cats.jpg" alt="Five cats looking around a field.">
          <figcaption>Cats <strong>hate</strong> other cats.</figcaption>
        </figure>
     </section>
     <section>
        <h2>Cat Form</h2>
        <form action="https://freecatphotoapp.com/submit-cat-photo">
```
```html    
        <fieldset>
            <legend>Is your cat an indoor or outdoor cat?</legend>
            <label><input id="indoor" type="radio" name="indoor-outdoor" value="indoor"> Indoor</label>
            <label><input id="outdoor" type="radio" name="indoor-outdoor" value="outdoor"> Outdoor</label>
        </fieldset>
```
```html
        <fieldset></fieldset>
```
```html
            <input type="text" name="catphotourl" placeholder="cat photo URL" required>
            <button type="submit">Submit</button>
        </form>
     </section>
    </main>
  </body>
</html>
```
> **Step 52** <br>
Add a `legend` element with the text `What's your cat's personality?` inside the second `fieldset` element.

```html
<html>
  <body>
    <h1>CatPhotoApp</h1>
    <main>
      <section>
       <h2>Cat Photos</h2>
       <!-- TODO: Add link to cat photos -->
       <p>Click here to view more <a target="_blank" href="https://freecatphotoapp.com">cat photos</a>.</p>
       <a href="https://freecatphotoapp.com"><img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/relaxing-cat.jpg" alt="A cute orange cat lying on its back."></a>
     </section>
     <section>
        <h2>Cat Lists</h2>
        <h3>Things cats love:</h3>
        <ul>
          <li>cat nip</li>
          <li>laser pointers</li>
          <li>lasagna</li>
        </ul>
        <figure>
         <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/lasagna.jpg" alt="A slice of lasagna on a plate.">
         <figcaption>Cats <em>love</em> lasagna.</figcaption>
        </figure>
        <h3>Top 3 things cats hate:</h3>
        <ol>
          <li>flea treatment</li>
          <li>thunder</li>
          <li>other cats</li>
        </ol>
        <figure>
          <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/cats.jpg" alt="Five cats looking around a field.">
          <figcaption>Cats <strong>hate</strong> other cats.</figcaption>
        </figure>
     </section>
     <section>
        <h2>Cat Form</h2>
        <form action="https://freecatphotoapp.com/submit-cat-photo">
```
```html    
        <fieldset>
            <legend>Is your cat an indoor or outdoor cat?</legend>
            <label><input id="indoor" type="radio" name="indoor-outdoor" value="indoor"> Indoor</label>
            <label><input id="outdoor" type="radio" name="indoor-outdoor" value="outdoor"> Outdoor</label>
        </fieldset>
```
```html
        <fieldset>
            <legend>What's your cat's personality?</legend>
        </fieldset>
```
```html
            <input type="text" name="catphotourl" placeholder="cat photo URL" required>
            <button type="submit">Submit</button>
        </form>
     </section>
    </main>
  </body>
</html>
```
> **Step 53** <br>
Forms commonly use checkboxes for questions that may have more than one answer. For example, here's a checkbox with the option of<br> 
`tacos: <input type="checkbox"> tacos`.<br>
Under the `legend` element you just added, add an `input` with its `type` attribute set to `checkbox` and give it the option of:<br>
`Loving`

```html
<html>
  <body>
    <h1>CatPhotoApp</h1>
    <main>
      <section>
       <h2>Cat Photos</h2>
       <!-- TODO: Add link to cat photos -->
       <p>Click here to view more <a target="_blank" href="https://freecatphotoapp.com">cat photos</a>.</p>
       <a href="https://freecatphotoapp.com"><img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/relaxing-cat.jpg" alt="A cute orange cat lying on its back."></a>
     </section>
     <section>
        <h2>Cat Lists</h2>
        <h3>Things cats love:</h3>
        <ul>
          <li>cat nip</li>
          <li>laser pointers</li>
          <li>lasagna</li>
        </ul>
        <figure>
         <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/lasagna.jpg" alt="A slice of lasagna on a plate.">
         <figcaption>Cats <em>love</em> lasagna.</figcaption>
        </figure>
        <h3>Top 3 things cats hate:</h3>
        <ol>
          <li>flea treatment</li>
          <li>thunder</li>
          <li>other cats</li>
        </ol>
        <figure>
          <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/cats.jpg" alt="Five cats looking around a field.">
          <figcaption>Cats <strong>hate</strong> other cats.</figcaption>
        </figure>
     </section>
     <section>
        <h2>Cat Form</h2>
        <form action="https://freecatphotoapp.com/submit-cat-photo">
```
```html    
        <fieldset>
            <legend>Is your cat an indoor or outdoor cat?</legend>
            <label><input id="indoor" type="radio" name="indoor-outdoor" value="indoor"> Indoor</label>
            <label><input id="outdoor" type="radio" name="indoor-outdoor" value="outdoor"> Outdoor</label>
        </fieldset>
        <fieldset>
```
```html
            <legend>What's your cat's personality?</legend>
            <input type="checkbox"> Loving   
```
```html
        </fieldset>
            <input type="text" name="catphotourl" placeholder="cat photo URL" required>
            <button type="submit">Submit</button>
        </form>
     </section>
    </main>
  </body>
</html>
```
> **Step 54** <br>
Add an `id` attribute with the value `loving` to the checkbox input.

```html
<html>
  <body>
    <h1>CatPhotoApp</h1>
    <main>
      <section>
       <h2>Cat Photos</h2>
       <!-- TODO: Add link to cat photos -->
       <p>Click here to view more <a target="_blank" href="https://freecatphotoapp.com">cat photos</a>.</p>
       <a href="https://freecatphotoapp.com"><img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/relaxing-cat.jpg" alt="A cute orange cat lying on its back."></a>
     </section>
     <section>
        <h2>Cat Lists</h2>
        <h3>Things cats love:</h3>
        <ul>
          <li>cat nip</li>
          <li>laser pointers</li>
          <li>lasagna</li>
        </ul>
        <figure>
         <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/lasagna.jpg" alt="A slice of lasagna on a plate.">
         <figcaption>Cats <em>love</em> lasagna.</figcaption>
        </figure>
        <h3>Top 3 things cats hate:</h3>
        <ol>
          <li>flea treatment</li>
          <li>thunder</li>
          <li>other cats</li>
        </ol>
        <figure>
          <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/cats.jpg" alt="Five cats looking around a field.">
          <figcaption>Cats <strong>hate</strong> other cats.</figcaption>
        </figure>
     </section>
     <section>
        <h2>Cat Form</h2>
        <form action="https://freecatphotoapp.com/submit-cat-photo">
```
```html    
        <fieldset>
            <legend>Is your cat an indoor or outdoor cat?</legend>
            <label><input id="indoor" type="radio" name="indoor-outdoor" value="indoor"> Indoor</label>
            <label><input id="outdoor" type="radio" name="indoor-outdoor" value="outdoor"> Outdoor</label>
        </fieldset>
        <fieldset>
            <legend>What's your cat's personality?</legend>
```
```html
            <input id="loving" type="checkbox"> Loving   
```
```html
        </fieldset>
            <input type="text" name="catphotourl" placeholder="cat photo URL" required>
            <button type="submit">Submit</button>
        </form>
     </section>
    </main>
  </body>
</html>
```
> **Step 55** <br>
There's another way to associate an `input` element's text with the element itself. You can nest the text within a `label` element and add a `for` attribute with the same value as the `input` element's `id` attribute.<br>
Associate the text `Loving` with the checkbox by only nesting the text `Loving` in a `label` element and place it to the right side of the checkbox `input` element.

```html
<html>
  <body>
    <h1>CatPhotoApp</h1>
    <main>
      <section>
       <h2>Cat Photos</h2>
       <!-- TODO: Add link to cat photos -->
       <p>Click here to view more <a target="_blank" href="https://freecatphotoapp.com">cat photos</a>.</p>
       <a href="https://freecatphotoapp.com"><img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/relaxing-cat.jpg" alt="A cute orange cat lying on its back."></a>
     </section>
     <section>
        <h2>Cat Lists</h2>
        <h3>Things cats love:</h3>
        <ul>
          <li>cat nip</li>
          <li>laser pointers</li>
          <li>lasagna</li>
        </ul>
        <figure>
         <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/lasagna.jpg" alt="A slice of lasagna on a plate.">
         <figcaption>Cats <em>love</em> lasagna.</figcaption>
        </figure>
        <h3>Top 3 things cats hate:</h3>
        <ol>
          <li>flea treatment</li>
          <li>thunder</li>
          <li>other cats</li>
        </ol>
        <figure>
          <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/cats.jpg" alt="Five cats looking around a field.">
          <figcaption>Cats <strong>hate</strong> other cats.</figcaption>
        </figure>
     </section>
     <section>
        <h2>Cat Form</h2>
        <form action="https://freecatphotoapp.com/submit-cat-photo">
```
```html    
        <fieldset>
            <legend>Is your cat an indoor or outdoor cat?</legend>
            <label><input id="indoor" type="radio" name="indoor-outdoor" value="indoor"> Indoor</label>
            <label><input id="outdoor" type="radio" name="indoor-outdoor" value="outdoor"> Outdoor</label>
        </fieldset>
        <fieldset>
            <legend>What's your cat's personality?</legend>
```
```html
            <input id="loving" type="checkbox"> <label for="loving"> Loving </label>
```
```html
        </fieldset>
            <input type="text" name="catphotourl" placeholder="cat photo URL" required>
            <button type="submit">Submit</button>
        </form>
     </section>
    </main>
  </body>
</html>
```
> **Step 56** <br>
Add the `name` attribute with the value `personality` to the checkbox `input` element.<br>
While you won't notice this in the browser, doing this makes it easier for a server to process your web form, especially when there are multiple checkboxes.

```html
<html>
  <body>
    <h1>CatPhotoApp</h1>
    <main>
      <section>
       <h2>Cat Photos</h2>
       <!-- TODO: Add link to cat photos -->
       <p>Click here to view more <a target="_blank" href="https://freecatphotoapp.com">cat photos</a>.</p>
       <a href="https://freecatphotoapp.com"><img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/relaxing-cat.jpg" alt="A cute orange cat lying on its back."></a>
     </section>
     <section>
        <h2>Cat Lists</h2>
        <h3>Things cats love:</h3>
        <ul>
          <li>cat nip</li>
          <li>laser pointers</li>
          <li>lasagna</li>
        </ul>
        <figure>
         <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/lasagna.jpg" alt="A slice of lasagna on a plate.">
         <figcaption>Cats <em>love</em> lasagna.</figcaption>
        </figure>
        <h3>Top 3 things cats hate:</h3>
        <ol>
          <li>flea treatment</li>
          <li>thunder</li>
          <li>other cats</li>
        </ol>
        <figure>
          <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/cats.jpg" alt="Five cats looking around a field.">
          <figcaption>Cats <strong>hate</strong> other cats.</figcaption>
        </figure>
     </section>
     <section>
        <h2>Cat Form</h2>
        <form action="https://freecatphotoapp.com/submit-cat-photo">
```
```html    
        <fieldset>
            <legend>Is your cat an indoor or outdoor cat?</legend>
            <label><input id="indoor" type="radio" name="indoor-outdoor" value="indoor"> Indoor</label>
            <label><input id="outdoor" type="radio" name="indoor-outdoor" value="outdoor"> Outdoor</label>
        </fieldset>
        <fieldset>
            <legend>What's your cat's personality?</legend>
```
```html
            <input name="personality" id="loving" type="checkbox"> <label for="loving"> Loving </label>
```
```html
        </fieldset>
            <input type="text" name="catphotourl" placeholder="cat photo URL" required>
            <button type="submit">Submit</button>
        </form>
     </section>
    </main>
  </body>
</html>
```
> **Step 57** <br>
Add another checkbox after the one you just added. The `id` attribute value should be `lazy` and the `name` attribute value should be the same as the last checkbox.<br>
Also add a `label` element to the right of the new checkbox with the text `Lazy`. Make sure to associate the `label` element with the new checkbox using the `for` attribute.

```html
<html>
  <body>
    <h1>CatPhotoApp</h1>
    <main>
      <section>
       <h2>Cat Photos</h2>
       <!-- TODO: Add link to cat photos -->
       <p>Click here to view more <a target="_blank" href="https://freecatphotoapp.com">cat photos</a>.</p>
       <a href="https://freecatphotoapp.com"><img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/relaxing-cat.jpg" alt="A cute orange cat lying on its back."></a>
     </section>
     <section>
        <h2>Cat Lists</h2>
        <h3>Things cats love:</h3>
        <ul>
          <li>cat nip</li>
          <li>laser pointers</li>
          <li>lasagna</li>
        </ul>
        <figure>
         <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/lasagna.jpg" alt="A slice of lasagna on a plate.">
         <figcaption>Cats <em>love</em> lasagna.</figcaption>
        </figure>
        <h3>Top 3 things cats hate:</h3>
        <ol>
          <li>flea treatment</li>
          <li>thunder</li>
          <li>other cats</li>
        </ol>
        <figure>
          <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/cats.jpg" alt="Five cats looking around a field.">
          <figcaption>Cats <strong>hate</strong> other cats.</figcaption>
        </figure>
     </section>
     <section>
        <h2>Cat Form</h2>
        <form action="https://freecatphotoapp.com/submit-cat-photo">
```
```html    
        <fieldset>
            <legend>Is your cat an indoor or outdoor cat?</legend>
            <label><input id="indoor" type="radio" name="indoor-outdoor" value="indoor"> Indoor</label>
            <label><input id="outdoor" type="radio" name="indoor-outdoor" value="outdoor"> Outdoor</label>
        </fieldset>
        <fieldset>
            <legend>What's your cat's personality?</legend>
```
```html
            <input id="loving" type="checkbox" name="personality"> <label for="loving">Loving</label>
            <input id="lazy" type="checkbox" name="personality"> <label for="lazy">Lazy</label>
```
```html
        </fieldset>
            <input type="text" name="catphotourl" placeholder="cat photo URL" required>
            <button type="submit">Submit</button>
        </form>
     </section>
    </main>
  </body>
</html>
```
> **Step 58** <br>
Add a final checkbox after the previous one with an `id` attribute value of `energetic`. The `name` attribute should be the same as the previous checkbox.<br>
Also add a `label` element to the right of the new checkbox with text `Energetic`. Make sure to associate the `label` element with the new checkbox.

```html
<html>
  <body>
    <h1>CatPhotoApp</h1>
    <main>
      <section>
       <h2>Cat Photos</h2>
       <!-- TODO: Add link to cat photos -->
       <p>Click here to view more <a target="_blank" href="https://freecatphotoapp.com">cat photos</a>.</p>
       <a href="https://freecatphotoapp.com"><img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/relaxing-cat.jpg" alt="A cute orange cat lying on its back."></a>
     </section>
     <section>
        <h2>Cat Lists</h2>
        <h3>Things cats love:</h3>
        <ul>
          <li>cat nip</li>
          <li>laser pointers</li>
          <li>lasagna</li>
        </ul>
        <figure>
         <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/lasagna.jpg" alt="A slice of lasagna on a plate.">
         <figcaption>Cats <em>love</em> lasagna.</figcaption>
        </figure>
        <h3>Top 3 things cats hate:</h3>
        <ol>
          <li>flea treatment</li>
          <li>thunder</li>
          <li>other cats</li>
        </ol>
        <figure>
          <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/cats.jpg" alt="Five cats looking around a field.">
          <figcaption>Cats <strong>hate</strong> other cats.</figcaption>
        </figure>
     </section>
     <section>
        <h2>Cat Form</h2>
        <form action="https://freecatphotoapp.com/submit-cat-photo">
```
```html    
        <fieldset>
            <legend>Is your cat an indoor or outdoor cat?</legend>
            <label><input id="indoor" type="radio" name="indoor-outdoor" value="indoor"> Indoor</label>
            <label><input id="outdoor" type="radio" name="indoor-outdoor" value="outdoor"> Outdoor</label>
        </fieldset>
        <fieldset>
            <legend>What's your cat's personality?</legend>
```
```html
            <input id="loving" type="checkbox" name="personality"> <label for="loving">Loving</label>
            <input id="lazy" type="checkbox" name="personality"> <label for="lazy">Lazy</label>
            <input id="energetic" type="checkbox" name="personality"> <label for="energetic">Energetic</label>
```
```html
        </fieldset>
            <input type="text" name="catphotourl" placeholder="cat photo URL" required>
            <button type="submit">Submit</button>
        </form>
     </section>
    </main>
  </body>
</html>
```
> **Step 59** <br>
Like radio buttons, form data for selected checkboxes are `name` / `value` attribute pairs. While the `value` attribute is optional, it's best practice to include it with any checkboxes or radio buttons on the page.<br>
Add a `value` attribute to each checkbox. For convenience, set each checkbox's `value` attribute to the same value as its `id` attribute.

```html
<html>
  <body>
    <h1>CatPhotoApp</h1>
    <main>
      <section>
       <h2>Cat Photos</h2>
       <!-- TODO: Add link to cat photos -->
       <p>Click here to view more <a target="_blank" href="https://freecatphotoapp.com">cat photos</a>.</p>
       <a href="https://freecatphotoapp.com"><img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/relaxing-cat.jpg" alt="A cute orange cat lying on its back."></a>
     </section>
     <section>
        <h2>Cat Lists</h2>
        <h3>Things cats love:</h3>
        <ul>
          <li>cat nip</li>
          <li>laser pointers</li>
          <li>lasagna</li>
        </ul>
        <figure>
         <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/lasagna.jpg" alt="A slice of lasagna on a plate.">
         <figcaption>Cats <em>love</em> lasagna.</figcaption>
        </figure>
        <h3>Top 3 things cats hate:</h3>
        <ol>
          <li>flea treatment</li>
          <li>thunder</li>
          <li>other cats</li>
        </ol>
        <figure>
          <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/cats.jpg" alt="Five cats looking around a field.">
          <figcaption>Cats <strong>hate</strong> other cats.</figcaption>
        </figure>
     </section>
     <section>
        <h2>Cat Form</h2>
        <form action="https://freecatphotoapp.com/submit-cat-photo">
```
```html    
        <fieldset>
            <legend>Is your cat an indoor or outdoor cat?</legend>
            <label><input id="indoor" type="radio" name="indoor-outdoor" value="indoor"> Indoor</label>
            <label><input id="outdoor" type="radio" name="indoor-outdoor" value="outdoor"> Outdoor</label>
        </fieldset>
        <fieldset>
            <legend>What's your cat's personality?</legend>
            <input id="loving" type="checkbox" name="personality" value="loving"> <label for="loving">Loving</label>
            <input id="lazy" type="checkbox" name="personality" value="lazy"> <label for="lazy">Lazy</label>
            <input id="energetic" type="checkbox" name="personality" value="energetic"> <label for="energetic">Energetic</label>
        </fieldset>
```
```html
            <input type="text" name="catphotourl" placeholder="cat photo URL" required>
            <button type="submit">Submit</button>
        </form>
     </section>
    </main>
  </body>
</html>
```
> **Step 60** <br>
Passed
In order to make a checkbox checked or radio button selected by default, you need to add the `checked` attribute to it. There's no need to set a value to the `checked` attribute. Instead, just add the word `checked` to the `input` element, making sure there is space between it and other attributes.<br>
Make the first radio button and the first checkbox selected by default.

```html
<html>
  <body>
    <h1>CatPhotoApp</h1>
    <main>
      <section>
       <h2>Cat Photos</h2>
       <!-- TODO: Add link to cat photos -->
       <p>Click here to view more <a target="_blank" href="https://freecatphotoapp.com">cat photos</a>.</p>
       <a href="https://freecatphotoapp.com"><img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/relaxing-cat.jpg" alt="A cute orange cat lying on its back."></a>
     </section>
     <section>
        <h2>Cat Lists</h2>
        <h3>Things cats love:</h3>
        <ul>
          <li>cat nip</li>
          <li>laser pointers</li>
          <li>lasagna</li>
        </ul>
        <figure>
         <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/lasagna.jpg" alt="A slice of lasagna on a plate.">
         <figcaption>Cats <em>love</em> lasagna.</figcaption>
        </figure>
        <h3>Top 3 things cats hate:</h3>
        <ol>
          <li>flea treatment</li>
          <li>thunder</li>
          <li>other cats</li>
        </ol>
        <figure>
          <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/cats.jpg" alt="Five cats looking around a field.">
          <figcaption>Cats <strong>hate</strong> other cats.</figcaption>
        </figure>
     </section>
     <section>
        <h2>Cat Form</h2>
        <form action="https://freecatphotoapp.com/submit-cat-photo">
```
```html    
        <fieldset>
            <legend>Is your cat an indoor or outdoor cat?</legend>
            <label><input id="indoor" type="radio" name="indoor-outdoor" value="indoor" checked> Indoor</label>
            <label><input id="outdoor" type="radio" name="indoor-outdoor" value="outdoor"> Outdoor</label>
        </fieldset>
        <fieldset>
            <legend>What's your cat's personality?</legend>
            <input id="loving" type="checkbox" name="personality" value="loving" checked> <label for="loving">Loving</label>
            <input id="lazy" type="checkbox" name="personality" value="lazy"> <label for="lazy">Lazy</label>
            <input id="energetic" type="checkbox" name="personality" value="energetic"> <label for="energetic">Energetic</label>
        </fieldset>
```
```html
            <input type="text" name="catphotourl" placeholder="cat photo URL" required>
            <button type="submit">Submit</button>
        </form>
     </section>
    </main>
  </body>
</html>
```
> **Step 61** <br>
Now you will add a footer section to the page.<br>
After the `main` element, add a `footer` element.

```html
<html>
  <body>
    <h1>CatPhotoApp</h1>
    <main>
      <section>
       <h2>Cat Photos</h2>
       <!-- TODO: Add link to cat photos -->
       <p>Click here to view more <a target="_blank" href="https://freecatphotoapp.com">cat photos</a>.</p>
       <a href="https://freecatphotoapp.com"><img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/relaxing-cat.jpg" alt="A cute orange cat lying on its back."></a>
     </section>
     <section>
        <h2>Cat Lists</h2>
        <h3>Things cats love:</h3>
        <ul>
          <li>cat nip</li>
          <li>laser pointers</li>
          <li>lasagna</li>
        </ul>
        <figure>
         <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/lasagna.jpg" alt="A slice of lasagna on a plate.">
         <figcaption>Cats <em>love</em> lasagna.</figcaption>
        </figure>
        <h3>Top 3 things cats hate:</h3>
        <ol>
          <li>flea treatment</li>
          <li>thunder</li>
          <li>other cats</li>
        </ol>
        <figure>
          <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/cats.jpg" alt="Five cats looking around a field.">
          <figcaption>Cats <strong>hate</strong> other cats.</figcaption>
        </figure>
     </section>
     <section>
        <h2>Cat Form</h2>
        <form action="https://freecatphotoapp.com/submit-cat-photo">
        <fieldset>
            <legend>Is your cat an indoor or outdoor cat?</legend>
            <label><input id="indoor" type="radio" name="indoor-outdoor" value="indoor" checked> Indoor</label>
            <label><input id="outdoor" type="radio" name="indoor-outdoor" value="outdoor"> Outdoor</label>
        </fieldset>
        <fieldset>
            <legend>What's your cat's personality?</legend>
            <input id="loving" type="checkbox" name="personality" value="loving" checked> <label for="loving">Loving</label>
            <input id="lazy" type="checkbox" name="personality" value="lazy"> <label for="lazy">Lazy</label>
            <input id="energetic" type="checkbox" name="personality" value="energetic"> <label for="energetic">Energetic</label>
        </fieldset>
            <input type="text" name="catphotourl" placeholder="cat photo URL" required>
            <button type="submit">Submit</button>
        </form>
     </section>
```
```html    
    </main>

    <footer></footer>

  </body>
</html>
```
> **Step 62** <br>
Nest a `p` element with the text `No Copyright - freeCodeCamp.org` within the `footer` element.

```html
<html>
  <body>
    <h1>CatPhotoApp</h1>
    <main>
      <section>
       <h2>Cat Photos</h2>
       <!-- TODO: Add link to cat photos -->
       <p>Click here to view more <a target="_blank" href="https://freecatphotoapp.com">cat photos</a>.</p>
       <a href="https://freecatphotoapp.com"><img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/relaxing-cat.jpg" alt="A cute orange cat lying on its back."></a>
     </section>
     <section>
        <h2>Cat Lists</h2>
        <h3>Things cats love:</h3>
        <ul>
          <li>cat nip</li>
          <li>laser pointers</li>
          <li>lasagna</li>
        </ul>
        <figure>
         <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/lasagna.jpg" alt="A slice of lasagna on a plate.">
         <figcaption>Cats <em>love</em> lasagna.</figcaption>
        </figure>
        <h3>Top 3 things cats hate:</h3>
        <ol>
          <li>flea treatment</li>
          <li>thunder</li>
          <li>other cats</li>
        </ol>
        <figure>
          <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/cats.jpg" alt="Five cats looking around a field.">
          <figcaption>Cats <strong>hate</strong> other cats.</figcaption>
        </figure>
     </section>
     <section>
        <h2>Cat Form</h2>
        <form action="https://freecatphotoapp.com/submit-cat-photo">
        <fieldset>
            <legend>Is your cat an indoor or outdoor cat?</legend>
            <label><input id="indoor" type="radio" name="indoor-outdoor" value="indoor" checked> Indoor</label>
            <label><input id="outdoor" type="radio" name="indoor-outdoor" value="outdoor"> Outdoor</label>
        </fieldset>
        <fieldset>
            <legend>What's your cat's personality?</legend>
            <input id="loving" type="checkbox" name="personality" value="loving" checked> <label for="loving">Loving</label>
            <input id="lazy" type="checkbox" name="personality" value="lazy"> <label for="lazy">Lazy</label>
            <input id="energetic" type="checkbox" name="personality" value="energetic"> <label for="energetic">Energetic</label>
        </fieldset>
            <input type="text" name="catphotourl" placeholder="cat photo URL" required>
            <button type="submit">Submit</button>
        </form>
     </section>
    </main>
```
```html    
    <footer>
        <p>No Copyright - freeCodeCamp.org</p>
    </footer>
```
```html  
  </body>
</html>
```
> **Step 63** <br>
Make the text `freeCodeCamp.org` into a link by enclosing it in an anchor (`a`) element. The `href` attribute should be set to `https://www.freecodecamp.org`.

```html
<html>
  <body>
    <h1>CatPhotoApp</h1>
    <main>
      <section>
       <h2>Cat Photos</h2>
       <!-- TODO: Add link to cat photos -->
       <p>Click here to view more <a target="_blank" href="https://freecatphotoapp.com">cat photos</a>.</p>
       <a href="https://freecatphotoapp.com"><img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/relaxing-cat.jpg" alt="A cute orange cat lying on its back."></a>
     </section>
     <section>
        <h2>Cat Lists</h2>
        <h3>Things cats love:</h3>
        <ul>
          <li>cat nip</li>
          <li>laser pointers</li>
          <li>lasagna</li>
        </ul>
        <figure>
         <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/lasagna.jpg" alt="A slice of lasagna on a plate.">
         <figcaption>Cats <em>love</em> lasagna.</figcaption>
        </figure>
        <h3>Top 3 things cats hate:</h3>
        <ol>
          <li>flea treatment</li>
          <li>thunder</li>
          <li>other cats</li>
        </ol>
        <figure>
          <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/cats.jpg" alt="Five cats looking around a field.">
          <figcaption>Cats <strong>hate</strong> other cats.</figcaption>
        </figure>
     </section>
     <section>
        <h2>Cat Form</h2>
        <form action="https://freecatphotoapp.com/submit-cat-photo">
        <fieldset>
            <legend>Is your cat an indoor or outdoor cat?</legend>
            <label><input id="indoor" type="radio" name="indoor-outdoor" value="indoor" checked> Indoor</label>
            <label><input id="outdoor" type="radio" name="indoor-outdoor" value="outdoor"> Outdoor</label>
        </fieldset>
        <fieldset>
            <legend>What's your cat's personality?</legend>
            <input id="loving" type="checkbox" name="personality" value="loving" checked> <label for="loving">Loving</label>
            <input id="lazy" type="checkbox" name="personality" value="lazy"> <label for="lazy">Lazy</label>
            <input id="energetic" type="checkbox" name="personality" value="energetic"> <label for="energetic">Energetic</label>
        </fieldset>
            <input type="text" name="catphotourl" placeholder="cat photo URL" required>
            <button type="submit">Submit</button>
        </form>
     </section>
    </main>
    <footer>
        <p>
```
```html  

        No Copyright - <a href="https://www.freecodecamp.org">freeCodeCamp.org</a>

```
```html
        </p>
    </footer>  
  </body>
</html>
```
> **Step 64** <br>
Notice that everything you've added to the page so far is inside the `body` element. All page content elements that should be rendered to the page go inside the `body` element. However, other important information goes inside the `head` element.<br>
Add a `head` element just above the `body` element.

```html
<html>
```
```html

    <head></head>

```
```html
  <body>
    <h1>CatPhotoApp</h1>
    <main>
      <section>
       <h2>Cat Photos</h2>
       <!-- TODO: Add link to cat photos -->
       <p>Click here to view more <a target="_blank" href="https://freecatphotoapp.com">cat photos</a>.</p>
       <a href="https://freecatphotoapp.com"><img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/relaxing-cat.jpg" alt="A cute orange cat lying on its back."></a>
     </section>
     <section>
        <h2>Cat Lists</h2>
        <h3>Things cats love:</h3>
        <ul>
          <li>cat nip</li>
          <li>laser pointers</li>
          <li>lasagna</li>
        </ul>
        <figure>
         <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/lasagna.jpg" alt="A slice of lasagna on a plate.">
         <figcaption>Cats <em>love</em> lasagna.</figcaption>
        </figure>
        <h3>Top 3 things cats hate:</h3>
        <ol>
          <li>flea treatment</li>
          <li>thunder</li>
          <li>other cats</li>
        </ol>
        <figure>
          <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/cats.jpg" alt="Five cats looking around a field.">
          <figcaption>Cats <strong>hate</strong> other cats.</figcaption>
        </figure>
     </section>
     <section>
        <h2>Cat Form</h2>
        <form action="https://freecatphotoapp.com/submit-cat-photo">
        <fieldset>
            <legend>Is your cat an indoor or outdoor cat?</legend>
            <label><input id="indoor" type="radio" name="indoor-outdoor" value="indoor" checked> Indoor</label>
            <label><input id="outdoor" type="radio" name="indoor-outdoor" value="outdoor"> Outdoor</label>
        </fieldset>
        <fieldset>
            <legend>What's your cat's personality?</legend>
            <input id="loving" type="checkbox" name="personality" value="loving" checked> <label for="loving">Loving</label>
            <input id="lazy" type="checkbox" name="personality" value="lazy"> <label for="lazy">Lazy</label>
            <input id="energetic" type="checkbox" name="personality" value="energetic"> <label for="energetic">Energetic</label>
        </fieldset>
            <input type="text" name="catphotourl" placeholder="cat photo URL" required>
            <button type="submit">Submit</button>
        </form>
     </section>
    </main>
    <footer>
        <p>
        No Copyright - <a href="https://www.freecodecamp.org">freeCodeCamp.org</a>
        </p>
    </footer>  
  </body>
```
```html
</html>
```
> **Step 65** <br>
The `title` element determines what browsers show in the title bar or tab for the page.<br>
Add a `title` element within the `head` element using the text below:<br>
`CatPhotoApp`

```html
<html>
```
```html

    <head>
        <title>CatPhotoApp</title>
    </head>

```
```html
  <body>
    <h1>CatPhotoApp</h1>
    <main>
      <section>
       <h2>Cat Photos</h2>
       <!-- TODO: Add link to cat photos -->
       <p>Click here to view more <a target="_blank" href="https://freecatphotoapp.com">cat photos</a>.</p>
       <a href="https://freecatphotoapp.com"><img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/relaxing-cat.jpg" alt="A cute orange cat lying on its back."></a>
     </section>
     <section>
        <h2>Cat Lists</h2>
        <h3>Things cats love:</h3>
        <ul>
          <li>cat nip</li>
          <li>laser pointers</li>
          <li>lasagna</li>
        </ul>
        <figure>
         <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/lasagna.jpg" alt="A slice of lasagna on a plate.">
         <figcaption>Cats <em>love</em> lasagna.</figcaption>
        </figure>
        <h3>Top 3 things cats hate:</h3>
        <ol>
          <li>flea treatment</li>
          <li>thunder</li>
          <li>other cats</li>
        </ol>
        <figure>
          <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/cats.jpg" alt="Five cats looking around a field.">
          <figcaption>Cats <strong>hate</strong> other cats.</figcaption>
        </figure>
     </section>
     <section>
        <h2>Cat Form</h2>
        <form action="https://freecatphotoapp.com/submit-cat-photo">
        <fieldset>
            <legend>Is your cat an indoor or outdoor cat?</legend>
            <label><input id="indoor" type="radio" name="indoor-outdoor" value="indoor" checked> Indoor</label>
            <label><input id="outdoor" type="radio" name="indoor-outdoor" value="outdoor"> Outdoor</label>
        </fieldset>
        <fieldset>
            <legend>What's your cat's personality?</legend>
            <input id="loving" type="checkbox" name="personality" value="loving" checked> <label for="loving">Loving</label>
            <input id="lazy" type="checkbox" name="personality" value="lazy"> <label for="lazy">Lazy</label>
            <input id="energetic" type="checkbox" name="personality" value="energetic"> <label for="energetic">Energetic</label>
        </fieldset>
            <input type="text" name="catphotourl" placeholder="cat photo URL" required>
            <button type="submit">Submit</button>
        </form>
     </section>
    </main>
    <footer>
        <p>
        No Copyright - <a href="https://www.freecodecamp.org">freeCodeCamp.org</a>
        </p>
    </footer>  
  </body>
</html>
```
> **Step 66** <br>
Notice that the entire contents of the page are nested within an `html` element. All other elements must be descendants of this `html` element.<br>
Add the `lang` attribute with the value `en` to the opening `html` tag to specify that the language of the page is English.

```html
<html lang="en">
```
```html
  <head>
    <title>CatPhotoApp</title>
  </head>
  <body>
    <h1>CatPhotoApp</h1>
    <main>
      <section>
       <h2>Cat Photos</h2>
       <!-- TODO: Add link to cat photos -->
       <p>Click here to view more <a target="_blank" href="https://freecatphotoapp.com">cat photos</a>.</p>
       <a href="https://freecatphotoapp.com"><img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/relaxing-cat.jpg" alt="A cute orange cat lying on its back."></a>
     </section>
     <section>
        <h2>Cat Lists</h2>
        <h3>Things cats love:</h3>
        <ul>
          <li>cat nip</li>
          <li>laser pointers</li>
          <li>lasagna</li>
        </ul>
        <figure>
         <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/lasagna.jpg" alt="A slice of lasagna on a plate.">
         <figcaption>Cats <em>love</em> lasagna.</figcaption>
        </figure>
        <h3>Top 3 things cats hate:</h3>
        <ol>
          <li>flea treatment</li>
          <li>thunder</li>
          <li>other cats</li>
        </ol>
        <figure>
          <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/cats.jpg" alt="Five cats looking around a field.">
          <figcaption>Cats <strong>hate</strong> other cats.</figcaption>
        </figure>
     </section>
     <section>
        <h2>Cat Form</h2>
        <form action="https://freecatphotoapp.com/submit-cat-photo">
        <fieldset>
            <legend>Is your cat an indoor or outdoor cat?</legend>
            <label><input id="indoor" type="radio" name="indoor-outdoor" value="indoor" checked> Indoor</label>
            <label><input id="outdoor" type="radio" name="indoor-outdoor" value="outdoor"> Outdoor</label>
        </fieldset>
        <fieldset>
            <legend>What's your cat's personality?</legend>
            <input id="loving" type="checkbox" name="personality" value="loving" checked> <label for="loving">Loving</label>
            <input id="lazy" type="checkbox" name="personality" value="lazy"> <label for="lazy">Lazy</label>
            <input id="energetic" type="checkbox" name="personality" value="energetic"> <label for="energetic">Energetic</label>
        </fieldset>
            <input type="text" name="catphotourl" placeholder="cat photo URL" required>
            <button type="submit">Submit</button>
        </form>
     </section>
    </main>
    <footer>
        <p>
        No Copyright - <a href="https://www.freecodecamp.org">freeCodeCamp.org</a>
        </p>
    </footer>  
  </body>
</html>
```
> **Step 67** <br>
All pages should begin with `<!DOCTYPE html>`. This special string is known as a declaration and ensures the browser tries to meet industry-wide specifications.<br>
Add this declaration as the first line of the code.

```html
<!DOCTYPE html>
```
```html
<html lang="en">
  <head>
    <title>CatPhotoApp</title>
  </head>
```
```html
  <body>
    <h1>CatPhotoApp</h1>
    <main>
      <section>
       <h2>Cat Photos</h2>
       <!-- TODO: Add link to cat photos -->
       <p>Click here to view more <a target="_blank" href="https://freecatphotoapp.com">cat photos</a>.</p>
       <a href="https://freecatphotoapp.com"><img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/relaxing-cat.jpg" alt="A cute orange cat lying on its back."></a>
     </section>
     <section>
        <h2>Cat Lists</h2>
        <h3>Things cats love:</h3>
        <ul>
          <li>cat nip</li>
          <li>laser pointers</li>
          <li>lasagna</li>
        </ul>
        <figure>
         <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/lasagna.jpg" alt="A slice of lasagna on a plate.">
         <figcaption>Cats <em>love</em> lasagna.</figcaption>
        </figure>
        <h3>Top 3 things cats hate:</h3>
        <ol>
          <li>flea treatment</li>
          <li>thunder</li>
          <li>other cats</li>
        </ol>
        <figure>
          <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/cats.jpg" alt="Five cats looking around a field.">
          <figcaption>Cats <strong>hate</strong> other cats.</figcaption>
        </figure>
     </section>
     <section>
        <h2>Cat Form</h2>
        <form action="https://freecatphotoapp.com/submit-cat-photo">
        <fieldset>
            <legend>Is your cat an indoor or outdoor cat?</legend>
            <label><input id="indoor" type="radio" name="indoor-outdoor" value="indoor" checked> Indoor</label>
            <label><input id="outdoor" type="radio" name="indoor-outdoor" value="outdoor"> Outdoor</label>
        </fieldset>
        <fieldset>
            <legend>What's your cat's personality?</legend>
            <input id="loving" type="checkbox" name="personality" value="loving" checked> <label for="loving">Loving</label>
            <input id="lazy" type="checkbox" name="personality" value="lazy"> <label for="lazy">Lazy</label>
            <input id="energetic" type="checkbox" name="personality" value="energetic"> <label for="energetic">Energetic</label>
        </fieldset>
            <input type="text" name="catphotourl" placeholder="cat photo URL" required>
            <button type="submit">Submit</button>
        </form>
     </section>
    </main>
    <footer>
        <p>
        No Copyright - <a href="https://www.freecodecamp.org">freeCodeCamp.org</a>
        </p>
    </footer>  
  </body>
</html>
```
> **Step 68** <br>
One more thing. You should allow people to use their native language. Tell the browser to encode multiple languages by adding a `meta` element as a child of the `head` element. Set its `charset` attribute to `UTF-8`.

```html
<!DOCTYPE html>
<html lang="en">
```
```html
  <head>
    <meta charset="UTF-8">
    <title>CatPhotoApp</title>
  </head>
```
```html
  <body>
    <h1>CatPhotoApp</h1>
    <main>
      <section>
       <h2>Cat Photos</h2>
       <!-- TODO: Add link to cat photos -->
       <p>Click here to view more <a target="_blank" href="https://freecatphotoapp.com">cat photos</a>.</p>
       <a href="https://freecatphotoapp.com"><img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/relaxing-cat.jpg" alt="A cute orange cat lying on its back."></a>
     </section>
     <section>
        <h2>Cat Lists</h2>
        <h3>Things cats love:</h3>
        <ul>
          <li>cat nip</li>
          <li>laser pointers</li>
          <li>lasagna</li>
        </ul>
        <figure>
         <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/lasagna.jpg" alt="A slice of lasagna on a plate.">
         <figcaption>Cats <em>love</em> lasagna.</figcaption>
        </figure>
        <h3>Top 3 things cats hate:</h3>
        <ol>
          <li>flea treatment</li>
          <li>thunder</li>
          <li>other cats</li>
        </ol>
        <figure>
          <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/cats.jpg" alt="Five cats looking around a field.">
          <figcaption>Cats <strong>hate</strong> other cats.</figcaption>
        </figure>
     </section>
     <section>
        <h2>Cat Form</h2>
        <form action="https://freecatphotoapp.com/submit-cat-photo">
        <fieldset>
            <legend>Is your cat an indoor or outdoor cat?</legend>
            <label><input id="indoor" type="radio" name="indoor-outdoor" value="indoor" checked> Indoor</label>
            <label><input id="outdoor" type="radio" name="indoor-outdoor" value="outdoor"> Outdoor</label>
        </fieldset>
        <fieldset>
            <legend>What's your cat's personality?</legend>
            <input id="loving" type="checkbox" name="personality" value="loving" checked> <label for="loving">Loving</label>
            <input id="lazy" type="checkbox" name="personality" value="lazy"> <label for="lazy">Lazy</label>
            <input id="energetic" type="checkbox" name="personality" value="energetic"> <label for="energetic">Energetic</label>
        </fieldset>
            <input type="text" name="catphotourl" placeholder="cat photo URL" required>
            <button type="submit">Submit</button>
        </form>
     </section>
    </main>
    <footer>
        <p>
        No Copyright - <a href="https://www.freecodecamp.org">freeCodeCamp.org</a>
        </p>
    </footer>  
  </body>
</html>
```