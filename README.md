##Approach

Forcing to write '-and-above/below' removes ambiguity, allows for both mobile-first and desktop-first styling


##Examples

```
@include small-mobile-only {}
@include mobile-and-below {}
@include mobile-and-above {}
@include tablet-and-below {}
@include tablet-and-above {}
@include desktop-and-below {}
@include desktop-and-above {}
@include widedesktop-only {}
```

###For special breakpoints, use sparingly:

```
@include below(600) {}
@include above(600) {}
```

###For dealing with vertical space available (non-scrolling layouts): 

```
@include below-height(600) {}
@include above-height(1000) {}
```