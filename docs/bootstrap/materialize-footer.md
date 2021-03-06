---
title: "Materialize Footer"
path: "/bootstrap/footer"
id: "/bootstrap/footer"

description: "Breadcrumbs are a good way to display your current location. This is usually used when you have multiple layers of content."
---

Footers are a great way to organize a lot of site navigation and information at the end of a page. This is where the user will look once they have finished scrolling through the current page or are looking for additional information about your website.

<div class="note"><strong>Note:</strong> We use flexbox to structure our html so that the footer is always on the bottom of the page. It is important to keep the structure of your page within the 3 HTML5 tags: <code>&lt;header&gt;</code>, <code>&lt;main&gt;</code>, <code>&lt;footer&gt;</code>.

<a href="#" class="run">Run code</a>

```html
<footer class="page-footer">
   <div class="container">
      <div class="row">
         <div class="col l6 s12">
            <h5 class="white-text">Footer Content</h5>
            <p class="grey-text text-lighten-4">You can use rows and columns here to organize your footer content.</p>
         </div>
         <div class="col l4 offset-l2 s12">
            <h5 class="white-text">Links</h5>
            <ul>
               <li><a class="grey-text text-lighten-3" href="#!">Link 1</a></li>
               <li><a class="grey-text text-lighten-3" href="#!">Link 2</a></li>
               <li><a class="grey-text text-lighten-3" href="#!">Link 3</a></li>
               <li><a class="grey-text text-lighten-3" href="#!">Link 4</a></li>
            </ul>
         </div>
      </div>
   </div>
   <div class="footer-copyright">
      <div class="container">
         © 2014 Copyright Text
         <a class="grey-text text-lighten-4 right" href="#!">More Links</a>
      </div>
   </div>
</footer>
```
 
### Sticky Footer

A sticky footer always stays on the bottom of the page regardless of how little content is on the page. However, this footer will be pushed down if there is a lot of content, so it is different from a fixed footer. Add the following code to your CSS file.

Note: This may cause issues in Internet Explorer which has weak support for flexbox.

```css
body {
display: flex;
min-height: 100vh;
flex-direction: column;
}
main {
flex: 1 0 auto;
}
```   

>See something that can be improved on the docs site? [Make a suggestion](/programs/edit-the-doc-site.html)!
