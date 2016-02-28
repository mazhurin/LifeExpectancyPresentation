---
title       : Life Expectancy Calculator
subtitle    : 
author      : Anton Mazhurin
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : [bootstrap, quiz]
ext_widgets : {rCharts: [libraries/nvd3]}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## What is Life Expectancy?

Life expectancy is a statistical measure of how long an organism may live, based on:


* the year of birth
* the current age 
* other demographic factors including sex.

---
## Online Life Expectancy Calculator

* You can try our Life Expectancy calculator online [here](https://greymemory.shinyapps.io/LifeExpectancy/)

* This Life expectancy calculator is base on the [data](http://apps.who.int/gho/data/node.main.688?lang=en) published by World Health Organization.

---
## Box sex life expectancy by Country


<div id = 'chart1' class = 'rChart nvd3'></div>
<script type='text/javascript'>
 $(document).ready(function(){
      drawchart1()
    });
    function drawchart1(){  
      var opts = {
 "dom": "chart1",
"width":    800,
"height":    400,
"x": "Year",
"y": "Both.sexes",
"type": "multiBarChart",
"group": "Country",
"id": "chart1" 
},
        data = [
 {
 "Country": "Australia",
"Year": 2013,
"Both.sexes": 83,
"Female": 85,
"Male": 80,
"Both.sexes.1": 25,
"Female.1": 27,
"Male.1": 24,
"Both.sexes.2": "73",
"Female.2": "74",
"Male.2": "71" 
},
{
 "Country": "Australia",
"Year": 2012,
"Both.sexes": 83,
"Female": 85,
"Male": 81,
"Both.sexes.1": 25,
"Female.1": 27,
"Male.1": 24,
"Both.sexes.2": "73",
"Female.2": "74",
"Male.2": "71" 
},
{
 "Country": "Australia",
"Year": 2000,
"Both.sexes": 80,
"Female": 83,
"Male": 77,
"Both.sexes.1": 23,
"Female.1": 25,
"Male.1": 21,
"Both.sexes.2": "70",
"Female.2": "72",
"Male.2": "68" 
},
{
 "Country": "Australia",
"Year": 1990,
"Both.sexes": 77,
"Female": 80,
"Male": 74,
"Both.sexes.1": 21,
"Female.1": 23,
"Male.1": 19,
"Both.sexes.2": "",
"Female.2": "",
"Male.2": "" 
},
{
 "Country": "Canada",
"Year": 2013,
"Both.sexes": 82,
"Female": 84,
"Male": 80,
"Both.sexes.1": 25,
"Female.1": 26,
"Male.1": 23,
"Both.sexes.2": "72",
"Female.2": "73",
"Male.2": "71" 
},
{
 "Country": "Canada",
"Year": 2012,
"Both.sexes": 82,
"Female": 84,
"Male": 80,
"Both.sexes.1": 25,
"Female.1": 26,
"Male.1": 23,
"Both.sexes.2": "72",
"Female.2": "73",
"Male.2": "70" 
},
{
 "Country": "Canada",
"Year": 2000,
"Both.sexes": 79,
"Female": 82,
"Male": 77,
"Both.sexes.1": 23,
"Female.1": 25,
"Male.1": 21,
"Both.sexes.2": "70",
"Female.2": "72",
"Male.2": "68" 
},
{
 "Country": "Canada",
"Year": 1990,
"Both.sexes": 77,
"Female": 81,
"Male": 74,
"Both.sexes.1": 22,
"Female.1": 24,
"Male.1": 19,
"Both.sexes.2": "",
"Female.2": "",
"Male.2": "" 
},
{
 "Country": "China",
"Year": 2013,
"Both.sexes": 75,
"Female": 77,
"Male": 74,
"Both.sexes.1": 19,
"Female.1": 21,
"Male.1": 18,
"Both.sexes.2": "68",
"Female.2": "69",
"Male.2": "67" 
},
{
 "Country": "China",
"Year": 2012,
"Both.sexes": 75,
"Female": 77,
"Male": 74,
"Both.sexes.1": 19,
"Female.1": 21,
"Male.1": 18,
"Both.sexes.2": "68",
"Female.2": "69",
"Male.2": "67" 
},
{
 "Country": "China",
"Year": 2000,
"Both.sexes": 71,
"Female": 73,
"Male": 70,
"Both.sexes.1": 18,
"Female.1": 20,
"Male.1": 17,
"Both.sexes.2": "64",
"Female.2": "66",
"Male.2": "62" 
},
{
 "Country": "China",
"Year": 1990,
"Both.sexes": 69,
"Female": 71,
"Male": 67,
"Both.sexes.1": 18,
"Female.1": 19,
"Male.1": 16,
"Both.sexes.2": "",
"Female.2": "",
"Male.2": "" 
},
{
 "Country": "France",
"Year": 2013,
"Both.sexes": 82,
"Female": 85,
"Male": 79,
"Both.sexes.1": 25,
"Female.1": 28,
"Male.1": 23,
"Both.sexes.2": "72",
"Female.2": "74",
"Male.2": "69" 
},
{
 "Country": "France",
"Year": 2012,
"Both.sexes": 82,
"Female": 85,
"Male": 79,
"Both.sexes.1": 25,
"Female.1": 27,
"Male.1": 23,
"Both.sexes.2": "72",
"Female.2": "74",
"Male.2": "69" 
},
{
 "Country": "France",
"Year": 2000,
"Both.sexes": 79,
"Female": 83,
"Male": 75,
"Both.sexes.1": 23,
"Female.1": 26,
"Male.1": 20,
"Both.sexes.2": "69",
"Female.2": "72",
"Male.2": "67" 
},
{
 "Country": "France",
"Year": 1990,
"Both.sexes": 78,
"Female": 82,
"Male": 73,
"Both.sexes.1": 22,
"Female.1": 25,
"Male.1": 20,
"Both.sexes.2": "",
"Female.2": "",
"Male.2": "" 
},
{
 "Country": "Germany",
"Year": 2013,
"Both.sexes": 81,
"Female": 83,
"Male": 79,
"Both.sexes.1": 24,
"Female.1": 25,
"Male.1": 22,
"Both.sexes.2": "71",
"Female.2": "73",
"Male.2": "69" 
},
{
 "Country": "Germany",
"Year": 2012,
"Both.sexes": 81,
"Female": 83,
"Male": 78,
"Both.sexes.1": 24,
"Female.1": 25,
"Male.1": 22,
"Both.sexes.2": "71",
"Female.2": "73",
"Male.2": "69" 
},
{
 "Country": "Germany",
"Year": 2000,
"Both.sexes": 78,
"Female": 81,
"Male": 75,
"Both.sexes.1": 22,
"Female.1": 24,
"Male.1": 20,
"Both.sexes.2": "69",
"Female.2": "71",
"Male.2": "67" 
},
{
 "Country": "Germany",
"Year": 1990,
"Both.sexes": 76,
"Female": 79,
"Male": 72,
"Both.sexes.1": 20,
"Female.1": 22,
"Male.1": 18,
"Both.sexes.2": "",
"Female.2": "",
"Male.2": "" 
},
{
 "Country": "India",
"Year": 2013,
"Both.sexes": 66,
"Female": 68,
"Male": 65,
"Both.sexes.1": 17,
"Female.1": 18,
"Male.1": 16,
"Both.sexes.2": "58",
"Female.2": "59",
"Male.2": "56" 
},
{
 "Country": "India",
"Year": 2012,
"Both.sexes": 66,
"Female": 68,
"Male": 64,
"Both.sexes.1": 17,
"Female.1": 18,
"Male.1": 16,
"Both.sexes.2": "57",
"Female.2": "58",
"Male.2": "56" 
},
{
 "Country": "India",
"Year": 2000,
"Both.sexes": 62,
"Female": 63,
"Male": 61,
"Both.sexes.1": 16,
"Female.1": 17,
"Male.1": 15,
"Both.sexes.2": "53",
"Female.2": "53",
"Male.2": "52" 
},
{
 "Country": "India",
"Year": 1990,
"Both.sexes": 58,
"Female": 58,
"Male": 57,
"Both.sexes.1": 15,
"Female.1": 16,
"Male.1": 14,
"Both.sexes.2": "",
"Female.2": "",
"Male.2": "" 
},
{
 "Country": "Japan",
"Year": 2013,
"Both.sexes": 84,
"Female": 87,
"Male": 80,
"Both.sexes.1": 26,
"Female.1": 29,
"Male.1": 23,
"Both.sexes.2": "75",
"Female.2": "78",
"Male.2": "72" 
},
{
 "Country": "Japan",
"Year": 2012,
"Both.sexes": 84,
"Female": 87,
"Male": 80,
"Both.sexes.1": 26,
"Female.1": 29,
"Male.1": 23,
"Both.sexes.2": "75",
"Female.2": "77",
"Male.2": "72" 
},
{
 "Country": "Japan",
"Year": 2000,
"Both.sexes": 81,
"Female": 85,
"Male": 78,
"Both.sexes.1": 25,
"Female.1": 27,
"Male.1": 22,
"Both.sexes.2": "73",
"Female.2": "76",
"Male.2": "70" 
},
{
 "Country": "Japan",
"Year": 1990,
"Both.sexes": 79,
"Female": 82,
"Male": 76,
"Both.sexes.1": 23,
"Female.1": 25,
"Male.1": 20,
"Both.sexes.2": "",
"Female.2": "",
"Male.2": "" 
},
{
 "Country": "Russian Federation",
"Year": 2013,
"Both.sexes": 69,
"Female": 75,
"Male": 63,
"Both.sexes.1": 17,
"Female.1": 20,
"Male.1": 14,
"Both.sexes.2": "61",
"Female.2": "66",
"Male.2": "55" 
},
{
 "Country": "Russian Federation",
"Year": 2012,
"Both.sexes": 69,
"Female": 75,
"Male": 63,
"Both.sexes.1": 17,
"Female.1": 20,
"Male.1": 14,
"Both.sexes.2": "60",
"Female.2": "66",
"Male.2": "55" 
},
{
 "Country": "Russian Federation",
"Year": 2000,
"Both.sexes": 65,
"Female": 72,
"Male": 59,
"Both.sexes.1": 17,
"Female.1": 19,
"Male.1": 13,
"Both.sexes.2": "57",
"Female.2": "63",
"Male.2": "51" 
},
{
 "Country": "Russian Federation",
"Year": 1990,
"Both.sexes": 69,
"Female": 74,
"Male": 63,
"Both.sexes.1": 18,
"Female.1": 20,
"Male.1": 15,
"Both.sexes.2": "",
"Female.2": "",
"Male.2": "" 
},
{
 "Country": "Rwanda",
"Year": 2013,
"Both.sexes": 65,
"Female": 67,
"Male": 64,
"Both.sexes.1": 18,
"Female.1": 19,
"Male.1": 17,
"Both.sexes.2": "56",
"Female.2": "57",
"Male.2": "55" 
},
{
 "Country": "Rwanda",
"Year": 2012,
"Both.sexes": 65,
"Female": 66,
"Male": 63,
"Both.sexes.1": 18,
"Female.1": 19,
"Male.1": 17,
"Both.sexes.2": "55",
"Female.2": "56",
"Male.2": "54" 
},
{
 "Country": "Rwanda",
"Year": 2000,
"Both.sexes": 46,
"Female": 47,
"Male": 46,
"Both.sexes.1": 15,
"Female.1": 16,
"Male.1": 15,
"Both.sexes.2": "40",
"Female.2": "40",
"Male.2": "39" 
},
{
 "Country": "Rwanda",
"Year": 1990,
"Both.sexes": 48,
"Female": 50,
"Male": 46,
"Both.sexes.1": 15,
"Female.1": 15,
"Male.1": 14,
"Both.sexes.2": "",
"Female.2": "",
"Male.2": "" 
},
{
 "Country": "United States of America",
"Year": 2013,
"Both.sexes": 79,
"Female": 81,
"Male": 76,
"Both.sexes.1": 23,
"Female.1": 24,
"Male.1": 22,
"Both.sexes.2": "69",
"Female.2": "71",
"Male.2": "68" 
},
{
 "Country": "United States of America",
"Year": 2012,
"Both.sexes": 79,
"Female": 81,
"Male": 76,
"Both.sexes.1": 23,
"Female.1": 24,
"Male.1": 21,
"Both.sexes.2": "69",
"Female.2": "71",
"Male.2": "67" 
},
{
 "Country": "United States of America",
"Year": 2000,
"Both.sexes": 77,
"Female": 80,
"Male": 74,
"Both.sexes.1": 22,
"Female.1": 23,
"Male.1": 20,
"Both.sexes.2": "68",
"Female.2": "70",
"Male.2": "66" 
},
{
 "Country": "United States of America",
"Year": 1990,
"Both.sexes": 75,
"Female": 79,
"Male": 72,
"Both.sexes.1": 21,
"Female.1": 23,
"Male.1": 19,
"Both.sexes.2": "",
"Female.2": "",
"Male.2": "" 
} 
]
  
      if(!(opts.type==="pieChart" || opts.type==="sparklinePlus" || opts.type==="bulletChart")) {
        var data = d3.nest()
          .key(function(d){
            //return opts.group === undefined ? 'main' : d[opts.group]
            //instead of main would think a better default is opts.x
            return opts.group === undefined ? opts.y : d[opts.group];
          })
          .entries(data);
      }
      
      if (opts.disabled != undefined){
        data.map(function(d, i){
          d.disabled = opts.disabled[i]
        })
      }
      
      nv.addGraph(function() {
        var chart = nv.models[opts.type]()
          .width(opts.width)
          .height(opts.height)
          
        if (opts.type != "bulletChart"){
          chart
            .x(function(d) { return d[opts.x] })
            .y(function(d) { return d[opts.y] })
        }
          
         
        
          
        

        
        
        
      
       d3.select("#" + opts.id)
        .append('svg')
        .datum(data)
        .transition().duration(500)
        .call(chart);

       nv.utils.windowResize(chart.update);
       return chart;
      });
    };
</script>

---
## Why Life Expectancy matters?

* The dramatic increase in average life expectancy during the 20th century ranks as one of society's greatest achievements. 

* For the reason that life expectancy is rising, the number of people aged *60 years and above* have tripled from its number in 1950 to **600 million** in 2000, in 2006 it has surpassed to **700 million**, and is projected that the population will reach around the **2 billion** by 2050.

*  For the entirety of recorded human history, the world has never seen as aged a population as currently exists globally

