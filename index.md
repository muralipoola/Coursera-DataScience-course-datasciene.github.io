---
title       : Strom Database Explorer
subtitle    : 
author      : Murali Poola
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Between 1950 and 2011 severe weather events caused at least
* 14834 deaths
* 139445 jnjuries
* $358 billion worth of damage

---

## Now you can prepare yourself using Storm Database Explorer
* state of the art user interface*
* high quality data**
* fast and reliable***
* 100% open source


\*If you really determined there is a chance you'll find worse.<br/>
\*\*There is small chance it could be worse.<br/>
\*\*\*It works. Most of the time.<br/>

---

## and it can generate cool plots

<!-- BarChart generated in R 3.2.3 by googleVis 0.5.10 package -->
<!-- Sat Feb 27 14:59:37 2016 -->


<!-- jsHeader -->
<script type="text/javascript">
 
// jsData 
function gvisDataBarChartID40dc56497cc4 () {
var data = new google.visualization.DataTable();
var datajson =
[
 [
 "US",
1,
23 
],
[
 "GB",
3,
12 
],
[
 "BR",
4,
32 
] 
];
data.addColumn('string','country');
data.addColumn('number','val1');
data.addColumn('number','val2');
data.addRows(datajson);
return(data);
}
 
// jsDrawChart
function drawChartBarChartID40dc56497cc4() {
var data = gvisDataBarChartID40dc56497cc4();
var options = {};
options["allowHtml"] = true;

    var chart = new google.visualization.BarChart(
    document.getElementById('BarChartID40dc56497cc4')
    );
    chart.draw(data,options);
    

}
  
 
// jsDisplayChart
(function() {
var pkgs = window.__gvisPackages = window.__gvisPackages || [];
var callbacks = window.__gvisCallbacks = window.__gvisCallbacks || [];
var chartid = "corechart";
  
// Manually see if chartid is in pkgs (not all browsers support Array.indexOf)
var i, newPackage = true;
for (i = 0; newPackage && i < pkgs.length; i++) {
if (pkgs[i] === chartid)
newPackage = false;
}
if (newPackage)
  pkgs.push(chartid);
  
// Add the drawChart function to the global list of callbacks
callbacks.push(drawChartBarChartID40dc56497cc4);
})();
function displayChartBarChartID40dc56497cc4() {
  var pkgs = window.__gvisPackages = window.__gvisPackages || [];
  var callbacks = window.__gvisCallbacks = window.__gvisCallbacks || [];
  window.clearTimeout(window.__gvisLoad);
  // The timeout is set to 100 because otherwise the container div we are
  // targeting might not be part of the document yet
  window.__gvisLoad = setTimeout(function() {
  var pkgCount = pkgs.length;
  google.load("visualization", "1", { packages:pkgs, callback: function() {
  if (pkgCount != pkgs.length) {
  // Race condition where another setTimeout call snuck in after us; if
  // that call added a package, we must not shift its callback
  return;
}
while (callbacks.length > 0)
callbacks.shift()();
} });
}, 100);
}
 
// jsFooter
</script>
 
<!-- jsChart -->  
<script type="text/javascript" src="https://www.google.com/jsapi?callback=displayChartBarChartID40dc56497cc4"></script>
 
<!-- divChart -->
  
<div id="BarChartID40dc56497cc4" 
  style="width: 500; height: automatic;">
</div>

---

## are you interested?
* visit us on [shinyapps.io](https://muralipoola.shinyapps.io/developing-data-products-shiny/)
* fork on [GitHub](https://github.com/muralipoola/developing-data-products-shiny)
* enroll on [Coursera DataScience Specializaiton](https://www.coursera.org/specializations/jhu-data-science) and learn how to build your own



