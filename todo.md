### To Do
-   Clean up style function
-   functional styling
    -   setStyle/getStyle functions
    -   auto update
-   Conditional Rendering
    -   check on render
        -   if false, do nothing
        -   if true, render
    -   check on 'something' periodically
        -   same rules as above
    -   self control?
        -   render, but 'display: none;'?
-   JSON creation and parsing functions
    -   currently work for non-self reference functions
    -   how to get setHas/getHas reference correct
    -   must query componants NOT jsut the compiled 'app'
    -   static pages will work with just the app componant stored as JSON
    -   any dynamic pieces must have correct references to final object