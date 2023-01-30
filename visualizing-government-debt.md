| [home page](https://cmustudent.github.io/tswd-portfolio-templates/) | [visualizing debt](visualizing-government-debt) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Part 1: Working with web-based visualization tools and data
The Organization for Economic Co-operation and Development (OECD) has intesting data sets on Government Debt. I vizualized ne such data set, "Government Debt by GDP" for the year 2019 on the OECD website. The bar chart comparing different countries is embedded below:

<iframe src="https://data.oecd.org/chart/6XS6" width="860" height="645" style="border: 0" mozallowfullscreen="true" webkitallowfullscreen="true" allowfullscreen="true"><a href="https://data.oecd.org/chart/6XS6" target="_blank">OECD Chart: General government debt, Total, % of GDP, Annual, 2019</a></iframe>

# Part 2: Working with Flourish
Data for the 'Debt to GDP' ratio between the years 1995-2019 from the OECD website was vizualied using an online Analytics software called 'Flourish'.

## Vizualization 1.1
Vizualization 1.1 is a grid of line graph, it helps readers understand the trends of increase/ decrease in the debt to GDP ratio of individual countries between the years 1996 and 2019 (inclusive). This vizualization also highlights the latest available data and the year it was published. This way of representation is a good way to convey the summary of a large data set. 

<div class="flourish-embed flourish-chart" data-src="visualisation/12561357"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

## Vizualization 1.2
To read the debt to GDP ratio of a particular year in greater detail, a graphic such as a radial heirarchy chart is better. Vizualization 1.2, displays individual debt to GDP ratios of each country in the order from highest to lowest for the selected year. This type of represntation helps comparison between countries across a smaller time period (In this case - a year) easy.

<div class="flourish-embed flourish-hierarchy" data-src="visualisation/12572983"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

# Part 2: Working with Tableau 

The same dataset from The Organization for Economic Co-operation and Development (OECD) was used to generate a heat map vizualization on Tableau. Tableau is a great software for analytics. 

## Vizualization 2.1
Visualization 2.1 combines the advantages of a grid of line chart and a radial heirarchy chart. It helps summarize all data between the years 1995-2019, assign a color gradient for easy understanding, and arrange the values in order. It also gives specific debt to GDP values for each year, thus making it just not a summary but also specific to the years. Vizualization 2.1 is an interactive graph that also allows the user to select individual rows/ columns and sort it in various ways to understand the data better. 

<div class='tableauPlaceholder' id='viz1675006969682' style='position: relative'><noscript><a href='#'><img alt='Government Debt to GDP Ratio  ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Go&#47;GovernmentDebttoGDPRatiosite&#47;Sheet1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='GovernmentDebttoGDPRatiosite&#47;Sheet1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Go&#47;GovernmentDebttoGDPRatiosite&#47;Sheet1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>  
<script type='text/javascript'>
  var divElement = document.getElementById('viz1675006969682');
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>   
