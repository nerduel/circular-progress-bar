# Circular Progressbar Add-on for Vaadin 8

circular-progressbar is a UI component add-on for Vaadin 8.

## Demo

![Alt Text](https://github.com/appreciated/blob/blob/master/progress-bar-demo.gif)

## Download release

Official releases of this add-on are available at Vaadin Directory. For Maven instructions, download and reviews, go to http://vaadin.com/addon/circular-progressbar

## Building and running demo

git clone <url of the CircularProgressbar repository>
mvn clean install
cd demo
mvn jetty:run

To see the demo, navigate to http://localhost:8080/

## Issue tracking

The issues for this add-on are tracked on its github.com page. All bug reports and feature requests are appreciated. 

## Contributions

Contributions are welcome, but there are no guarantees that they are accepted as such. Process for contributing is the following:
- Fork this project
- Create an issue to this project about the contribution (bug or feature) if there is no such issue about it already. Try to keep the scope minimal.
- Develop and test the fix or functionality carefully. Only include minimum amount of code needed to fix the issue.
- Refer to the fixed issue in commit
- Send a pull request for the original project
- Comment on the original issue that you have implemented a fix for it

## License & Author

Add-on is distributed under Apache License 2.0. For license terms, see LICENSE.txt.

CircularProgressbar is written by Appreciated 

## Features

A Circular Progressbar Component for Vaadin with animated Progress. Realized with SVG, and JavaScript.

## API

```
// Provide a double value between 0 and 100   

CircularProgressBar::setProgress(double)  

double CircularProgressBar::getProgress() 
```
