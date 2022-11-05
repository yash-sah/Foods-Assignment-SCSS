# Foods Assignment Using SCSS

One HTML file named index.html is used for HTML Code Purposes.

Images Folder is used for storing all the Images.

One CSS file is used.

One main SCSS file is used and there are 3 other SCSS files imported from the main SCSS file.

Base SCSS file is used for Variables usage, Custom Properties, Interpolation, Mixins and uses functions usage as well.

Component SCSS file is used for specific CSS Styles.

Layout SCSS file is used to incorporate nesting usage.

## List of all the SCSS/SASS features implemented -

Variables => Created all the Variables in a separate SCSS file. 

Custom Properties => Aslo known as CSS Variables. Used in base.scss file for declaring global styles.

Nesting => Used to nest CSS selectors. In componenets and layout scss files. In contactMe.scss file used nesting in nav, card, social, location and footer selectors. In aboutMe.scss file used nesting in nav, carousel and footer.

Interpolation => Used in a Sass stylesheet to embed the result of a SassScript expression into a chunk of CSS. Used @extend and @include Interpolation in components and layout file.

Placeholder Selectors => It is a class selector, but it starts with a % and it's not included in the CSS output. Used in body selector in components.scss. Defined a %pseudoBody Placeholder selector and used @extend to use it inside body selector.

Mixins => @mixin lets us create reusable css code. Created two separate header and footer scss files. They contain mixins which contain multiple css Properties. Used @import to import header & footer scss files in index.scss , contactMe.scss & aboutMe.scss files. Used @include inside base.scss , components.scss files under html selector to call the mixins. 

Functions => It allow to define complex operations on SassScript values that we can re-use throughout your stylesheet.
