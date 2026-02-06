#  Answers - Visualiztion  A

    > What software did you use to create your data visualization?

    Python (in a Jupyter notebook)

    > Who is your intended audience? 
    
    My visualization aims to inform manergers and policy makers in the Toronto's Shelters and Support Servises (TSSS), as well as social workers,
    shelters' manergers, and academics.

    > What information or message are you trying to convey with your visualization? 
    
    The purpose of this visualization is to reflect the need to build more emergency shelters. Shelters, both room-based and bed-based, have an average monthly occupancy of over 95%.
    These findings go beyond each shelter's daily occupancy rate, demonstrating the crisis in Toronto's shelter system and debunking the myth that it is winter- or seasonal-related.
    Additionally, the high occupancy rates in both room- and bed-based shelters indicate a broader housing crisis in the city. The fact that room-based shelters for families are almost 
    fully occupied year-round underscores the need to build public housing (since the shelter system should be an emergency solution).

    > What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots? 
    
    Firstly, I combined both bar and line plots to clearly represent my two y-variables (room-based shelter occupancy rate and bed-based occupancy rate). 
    Secondly, I planned my visualization so that the line plot appears above the bar plot to reflect the differences between room-based shelter occupancy
    and the bed-based shelter occupancy rate. I use two different colours, ensuring that one is darker than the other (see accessibility considerations).
    Thirdly, I placed the legend at the bottom right of the figure so it would not interrupt the interpretability of the visualization. Fourthly, I renamed and redefined 
    the x-axis ticks to include all month names, making the reading of the visualization easier. In this regard, I also enlarged the figure 
    size and inserted more ticks in the y axis to underscore the fact that the average monthly occupancy rates are higher than 95% throughout the year.
    Finally, I used a succinct and self-explanatory title, making the visualization easy to understand. 


    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 
    
    I employed several strategies to ensure reproducibility. First, I downloaded and saved the original dataset as a CSV file on my local machine. 
    Secondly, I used Panda's read.csv method to inquire the dataset and code old variables into new ones without transforming
    it (reusability). Thirdly, I commented on my code and provided a detailed description of the dataset. Lastly, I included the reference (URL address) 
    for the dataset as part of the dataset description.

    > How did you ensure that your data visualization is accessible?  
    
    I employed several methods to make my visualization accessible. Firstly, I used different colours for the bar and line plots. The colours are also different
    from one another in their darkness level (deeppink versus skyblue), making the visualization accessible for people with colour vision deficiencies. 
    Secondly, I embellished the line with triangular markers to make the minor differences between the room-based shelters' monthly occupancy rates 
    more visible. The triangular markers also make it easier to interpret the legend (i.e., by differentiating the line plot legend from the bar plot).
    Thirdly, I used an accessible font family ('DejaVu Sans') for the title, axes labels, axes ticks, and legend.
    Finally, I used "seaborn-v0_8-colorblind style" from Python's Matplotlib/Seaborn library to make data visualizations accessible 
    to individuals with common colour vision deficiencies. 

    > Who are the individuals and communities who might be impacted by your visualization?  
    
    My visualization will impact both shelter residents and workers. It aims to alleviate the overcrowding in Toronto's shelter system
    by debunking the idea that the overoccupancy is only a winter-related phenomenon. This, I hope, will encourage the municipality to build
    more shelters, and long-term housing solutions. 


    > How did you choose which features of your chosen dataset to include or exclude from your visualization? 
    
    My motivation was to show that monthly average occupancy rates in both bed and room shrelters (the only two occupancy rates calculated in
    this dataset) are nearing 100% in all months of the year. The dataset includes only daily occupancy rate culcualtions. However, I wanted
    to show the broader picture that the focus on individuals shelters/observation can easily mask.

    > What ‘underwater labour’ contributed to your final data visualization product?

    Underwater labour, with relation to my data visualization, includes the municipality shelter system workers (e.g., social service workers, social workers, 
    guides) who collected and documented these data as part of their daily work. In addition, workers in Toronto's Shelters and Support Services (TSSS) compiled 
    and cleaned these data into one, yearly dataset and then published it on the municipality website- making it available and accessible to the public.
    In addition, IT (information technology) teams in Toronto's municipality ensure that the website works and keep the data available. 
    In addition, data activists work to make social service data available. Python programmers/othersoftware engineers also contributed their knowledge
    to enhance Python's libraries' capacity to create better visualizations. 

