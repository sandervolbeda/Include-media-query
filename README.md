# Included media queries
Basic structure for breakpoint setup to include in scss.

## Why should you use this?
Although I think it's best practise to __NOT__ work with solid breakpoints, but rather use breakpoints when things get ugly, the best way to use breakpoints is in variables.

## Step 1
Install Gulp, Grunt or any other compiler.

## Step 2 
Add the code from the file __breakpoint__ into your scss file.

## Step 3
Now in your css instead of __@media screen and (min-width: 1024px)__ you can use the following examples:

__EXAMPLE: Use the following code to get the breakpoints__ \
@include respond-to(xs) { ... } \
@include respond-to(sm) { ... } \
@include respond-to(md) { ... } \
@include respond-to(lg) { ... } \
@include respond-to(xl) { ... } 

or 

@include respond-to(xs-min) { ... } \
@include respond-to(sm-min) { ... } \
@include respond-to(md-min) { ... } \
@include respond-to(lg-min) { ... } \
@include respond-to(xl-min) { ... } 

## Step 4
If you want to have different breakpoint you can know just edit the variable in the breakpoints scss file. You're way more flexible now.
