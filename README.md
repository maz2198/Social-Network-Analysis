# Social Network Analysis


This repo represents our main project completed during the Social Network Analysis course which was completed with Diego Cuartas and Nisrine Ferahi. 

## Refugee Migration Network Analysis
 

The journey of a refugee is often untold, and if told, it is never heard. Often in western mainstream media, the refugee journey is either termed as a “crisis” and expand to questions on “how this will effect our economy.” However, using various social network analysis techniques, we will debunk the stereotypical notion of a Eurocentric refugee network, and bring light to the stories of the untold.

![Unweighted Migration](/images/Unweighted_Migration.jpg)

This first map is a “blind” data visualization of the migrants social network. As you can see in the first map, the flows are unweighted so it gives a misleading representation of the flow of the migrants around the globe. This is the case for most of the maps online created by famous journalists trying to show the flow of refugees around the globe; however not depicting the reality of the refugees social network. This is why we decided to first start by creating another map you can see below with weighted edges.

![Weighted Migration](/images/Weighted_Migration.jpg)

This map is ambiguous and does not provide valuable insights to the reality of the migrants social network. The reason behind this is that we are trying to plot a complex society in a simple graph, which does not give the social network justice. This is why we are dug deeper into the analysis by dividing our refugees into three types: Refugees, Asylum seekers, Internally Displaced Persons.

In the full report we presented different centrality measures to detect transitory countries and asylum safe heavens. We also applied community detection to identify characteristics of the communities that have been broken but are subsequently rebuilt.

![Community Detection](/images/ComDetection.jpeg)

With this social network analysis of the forced migrants, we have been able to dispell the eurocentric notion of the refugee crisis. Moreover, it is about rethinking our humanity.

This project was made possible with the help of my colleagues Diego Cuartas and Nisrine Ferahi. The tools used for the project are the following:

- R for data transformation, the analysis and the report in a Markdown format;
- Gephi for some of the visualizations of our networks and community detection
- www.flowmap.blue for mapping the networks on mapped backgrounds (very intuitive tool that easily allows to map in and out degrees for geographical data)

