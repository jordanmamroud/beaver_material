# beaver_material
# The scss_customizable folder are examples of both the style.css for childthemes and the variable control sheet to manage all of the styles through out the project. 
# to use the the library with a child theme you just need to create a style.scss and variables_in_use.scss and turn on sass watch. Editing files besides these is unecessary unless you to add more styles and classes. 


#steps to setting up with child theme
# 1. Turn on sass watch ( sass --watch scss:css in command line );
# 2. Create a style.scss file under scss_customizable folder
# 3. Create a variables_in_use.scss  file under scss_customizable folder
# 4. open Filezilla and connect to the site you would like edit
# 5. navigate directory of remote site to where the style.css file should be in wp-content/themes/bb-theme-child
# 6. navigate directory of local site to where the style.css file should be in scss/scss_customizable
# 7. in style.scss copy the code from style_example.scss 
# 8. uncomment the imports you would like to use.
# 9. copy the code from the variables_example and paste it in variables_in_use.scss 
# 10. Save these changes so Sass preprocesses to the style.css file
# 11. Overwrite the style.css file at the remote site location




















# If editing the files please follow these conventions  


# bug tracking 
# bug on ie 10 with dual button module style 1 where it glitches a little gray underneath when leaving hover of first button