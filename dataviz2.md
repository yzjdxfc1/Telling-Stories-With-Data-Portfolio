# Assignment 2: Visualizing Debt
## Data Source 
“General Government - General Government Debt - OECD Data,” theOECD, n.d., https://data.oecd.org/gga/general-government-debt.htm.
The data consists of three major parts: location(country), Debt to GDP ratio, and year. 

## Part I: Government Debt Bar Chart
The first chart is a bar chart of government debt from OECD.  
It provides a snapshot data of year 2020; yeah, some information, but not meaningful enough.
<iframe src="https://data.oecd.org/chart/7krk" width="860" height="645" style="border: 0" mozallowfullscreen="true"
        webkitallowfullscreen="true" allowfullscreen="true">
    <a href="https://data.oecd.org/chart/7krk" target="_blank">
        OECD Chart: General government debt, Total, % of GDP, Annual, 2020
    </a>
</iframe>

## Part II: Heat Map
The second graph is a heat map of government debt data collected by OECD since 1995.  
It uses blue and orange to contast the Debt-to-GDP ratio.  
Notice that there are still many missing data for some countries.   
<div class='tableauPlaceholder' id='viz1706579610194' style='position: relative'>
    <noscript><a href='#'><img
            alt='Government Debt Ranked by Average Debt-to-GDP Ratio (1995 to 2022)Source: theOECD. “General Government - General Government Debt - OECD Data,” n.d. https:&#47;&#47;data.oecd.org&#47;gga&#47;general-government-debt.htm. '
            src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;da&#47;dataviz2_17065794852280&#47;GovernmentDebt&#47;1_rss.png'
            style='border: none'/></a></noscript>
    <object class='tableauViz' style='display:none;'>
        <param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F'/>
        <param name='embed_code_version' value='3'/>
        <param name='site_root' value=''/>
        <param name='name' value='dataviz2_17065794852280&#47;GovernmentDebt'/>
        <param name='tabs' value='no'/>
        <param name='toolbar' value='yes'/>
        <param name='static_image'
               value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;da&#47;dataviz2_17065794852280&#47;GovernmentDebt&#47;1.png'/>
        <param name='animate_transition' value='yes'/>
        <param name='display_static_image' value='yes'/>
        <param name='display_spinner' value='yes'/>
        <param name='display_overlay' value='yes'/>
        <param name='display_count' value='yes'/>
        <param name='language' value='en-US'/>
        <param name='filter' value='publish=yes'/>
    </object>
</div>
<script type='text/javascript'>
    var divElement = document.getElementById('viz1706579610194');
    var vizElement = divElement.getElementsByTagName('object')[0];
    vizElement.style.width = '100%';
    vizElement.style.height = (divElement.offsetWidth * 0.75) + 'px';
    var scriptElement = document.createElement('script');
    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
    vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>

## Part III: Forecasted Debt-to-GDP Ratio of USA
The third graph is the forecasted Debt-to-GDP Ratio of USA among top 5 countries.  
This graph only uses a subset of original data and tries answer a specific question: 
"How is Debt-to-GDP Ratio of USA going to be?"
<div class='tableauPlaceholder' id='viz1706587089366' style='position: relative'>
    <noscript><a href='#'><img
            alt='Forecasted Debt-to-GDP Ratio of USA Among Top 5 Highest CountriesReference: theOECD. “General Government - General Government Debt - OECD Data,” n.d. https:&#47;&#47;data.oecd.org&#47;gga&#47;general-government-debt.htm. '
            src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;da&#47;dataviz2_17065794852280&#47;USADebt&#47;1_rss.png'
            style='border: none'/></a></noscript>
    <object class='tableauViz' style='display:none;'>
        <param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F'/>
        <param name='embed_code_version' value='3'/>
        <param name='site_root' value=''/>
        <param name='name' value='dataviz2_17065794852280&#47;USADebt'/>
        <param name='tabs' value='no'/>
        <param name='toolbar' value='yes'/>
        <param name='static_image'
               value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;da&#47;dataviz2_17065794852280&#47;USADebt&#47;1.png'/>
        <param name='animate_transition' value='yes'/>
        <param name='display_static_image' value='yes'/>
        <param name='display_spinner' value='yes'/>
        <param name='display_overlay' value='yes'/>
        <param name='display_count' value='yes'/>
        <param name='language' value='en-US'/>
        <param name='filter' value='publish=yes'/>
    </object>
</div>
<script type='text/javascript'>
    var divElement = document.getElementById('viz1706587089366');
    var vizElement = divElement.getElementsByTagName('object')[0];
    vizElement.style.width = '100%';
    vizElement.style.height = (divElement.offsetWidth * 0.75) + 'px';
    var scriptElement = document.createElement('script');
    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
    vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>

## Part IV: Summary
Data source and data information available in introduction.   
These two graphs focuses on two different purposes.   
The heat map aims to help reader understand the overall debt condition for countries over time while the trend graph focuses on one specific country, USA, and tries to analyze its debt in the following 3 years.   
Design wise, the heat map could be overwhelimg at the beginning as it contains a lot of information, but it organizes well by allocating contrast colors, blue and orange, in a spectrum to give user a high level sense of the debt.   
The trend graph aims for an extremely simple and interactive experience. It grays other countries and only colored the ODEC average and the United States to draw attention from readers. Also, it use a gradient of color to display forecasted years in light color for better user understanding.  
In addition, these two graph uses different data ranges. The heat map includes all data all the way back 1995, when data of many other countries are still missing, hence users will see white blocks in it. On the other hand, the trend graph only focus on data since 2007, a year right before the financial crisis, and reserve more for future years. 
