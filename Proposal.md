DSC 190 C01 Project Proposal<br>
Names: Jill Nomura (A17317360) & Ashley Chu (A16678105)<br>
Domain: Global Human Migration<br>

Motivation: Why do we care about this Network to study?<br>
Global Human Migration is essential to analyze because it provides various insights about the world from dynamic relationships between countries, each country's economic conditions, political factors, climate disasters, the list goes on. These complex topics are intertwined which results in human migration on different scales. 
Our group is interested in how global historical events like wars and treaties affect human migration across the world, as current events continue to change global populations in the present day (such as climate disaster). 
<br>
Events of interest (explore further to see which are best to study):
- Cold War (1947-1991): Cuban Migration
- Chinese Diaspora following Cultural Revolution (mid 1960s-mid 1970s), as well as after Britain transferred sovereignty of Hong Kong to the PRC
- Vietnam War (1955-1975)
- Cambodian Civil War, Cambodian genocide (1970-1979)
- Israel-Palestine Conflict, Arab-Israeli Conflict (1948-Present Day)

<br><br>
Data:<br>
What are the nodes and :<br>
Each node will represent a country/region (including regions like Hong Kong and Taiwan) from around the world (232 total), and each link will be a directed link that points from an origin country to a destination country. 
<br><br>
How will you collect data, or which dataset will you study?<br>
We are collecting data from the World Bank DataBank’s Global Bilateral Migration dataset. This dataset gives a matrix of migrant flow from each country to every other country, and is already in tabular format, so simple data cleaning will be sufficient to prepare it for analysis. The values in the matrix are bilateral flow estimates made by Guy J Abel (a statistical demographer at the Hong Kong University Department of Sociology) using global bilateral stock tables from the World Bank between 1960 and 2000 over four ten-year periods.<Br><br>
Expected size of the network:<br>
The expected number of nodes of the network is 232, as we have 232 countries/regions in the dataset. The expected number of edges per decade is 186,138,527 (1960), 211,575,204 (1970), 240,352,241 (1980), 283,712,017 (1990), and 334,130,928 edges (2000), as those are the total number of links in each network by decade.<br><br>

Detail on the dataset: <Br>
The World Bank Databank presents data on Global Bilateral Migration flows from 1960-2000, disaggregated by country of origin, country of destination, gender and year. Researchers have also developed their own estimates of (bilateral) global migration flows based on 5-year intervals (see  Abel and Cohen, 2019; Raymer et al., 2013). These estimates are based on UN and World Bank statistics on changes in migrant stocks over time. https://databank.worldbank.org/source/global-bilateral-migration#
<br>Additional, more detailed datasets (UN DESA, OECD, Eurostat) – these are smaller subsets (~40 countries), but have more detailed demographics, etc. https://www.migrationdataportal.org/themes/international-migration-flow<br><br>

Question to ask: <br>
Can we observe historical events on a global scale and relationships between countries by analyzing global human migration data over time from 1960 to 2000?
Idea on how to approach this question: What analysis to use?<br>
<br>
Structural Analysis: Degree/eigenvector centrality and degree distribution to identify hubs and sinks of migration during different historical events.<br><br>
Community Detection: Clustering coefficient to identify which countries are most closely linked, analyze which subset of nodes can create a small world to see which countries are most connected or easiest to migrate to and from.


