# Belly_Button_Biodiversity 🕺
OSU Challenge #12 - Plotly.js

![](belly_dancer.jpg)

Using Plotly.js to create bar charts:

```javascript
var trace = {
      x: sample_values,
      y: OTU_name,
      text: otu_labels,
      name: "Bacteria",
      type: "bar",
      orientation: "h"
    };
      console.log(yticks);
    // 8. Create the trace for the bar chart. 
    var barData = [trace];


    // 9. Create the layout for the bar chart. 
    var barLayout = {
      title: `Top 10 Bacteria Strains for ${sample}`,
      yaxis: {autorange : 'reversed'},
      xaxis: {title: 'Bacteria Count'}
    };
    // 10. Use Plotly to plot the data with the layout. 
    Plotly.newPlot("bar", barData, barLayout);
```
