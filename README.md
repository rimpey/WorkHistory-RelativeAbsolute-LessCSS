![alt text](http://docs.rhondaimpey.com/img/workhistory.jpg "Work History")


WorkHistory-RelativeAbsolute-LessCSS
====================================

Graphical representation of work history and education.

This is part of a wider project, a website, and explores relative and absolute positioning along with Less CSS for 
styling. The idea being to graphically present my work and education in summary form associated with timeframe, 
further details are available upon a hover event. Less CSS is used and specificity touched upon in the context
of this project.

The outer div id="workeducyear" is position relative and contains div id="year" position absolute with a width of
10% along with div id="workeduc" also position absolute with a width of 90% starting left 10%.

The height of each year paragraph is reflective of a fixed 12 month period whereas the heihgt of workeduc divs are 
variable and based on time served on a course or in employment.

A div id="worksubflow" is contained inside the div id="workeduc" to enable an overlay of boxes on top of msc where 
lecturing and study took place simultaneously and over the top of the cert Ed for the same reason.

Divs contained within both id="workeduc" and id="worksubflow" are relative for which aside's are absolute used to 
display a more detailed account of employment and education upon hover.

CSS .less files have been used and automatically compile into .css files during development, via the include
of a less javascript file, however will need to be manually compiled prior to project release.

CSS Less is a more efficient way to write CSS without duplication, keeping code modular - possible through
mixins, variables, functions and nested code.


