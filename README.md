## Ready for a career in data science with demonstrated ability to solve for real-world problems. 

Real world data was analysed with inferential statistical testing by k-means clustering. Each neighbourhood’s closest match within boroughs was 
sought by venues. [Machine Learning was used to cluster the neighbourhoods](https://github.com/lindangulopez/Coursera_Capstone/blob/master/LeafletMap.png) and a Tailor-Made Liveability Indicator was applied to the clusters to 
make recommendations on relocation options with Word Clouds, i.e. text clouds or tag clouds.  The Word Cloud were created with 640 words from the 
EIU’s Liveability Index and 360 words from the venue data sets, for each neighbourhood, borough and the cities of New York, Toronto and Paris. 
So, a list of 1000 words were used to generate the merged word clouds and 360 words for the venue only word clouds.

![Tailor-Made Liveability Indicator ](https://github.com/lindangulopez/Coursera_Capstone/blob/master/IBM_DSP.png?raw=true)

After much data mining, munging and visualizations the bias of the EIU’s index was revealed. It shows a clear preference for lower density and
less built up cities, like Toronto over the big buzz in the Big Apple. As he EIU's Liveability Index focus on the the challenges that are faced 
in a big city it rated Toronto, Paris and New York as 4th, 29th and 55th respectively, leagues apart!

![Leaflet Map](https://github.com/lindangulopez/Coursera_Capstone/blob/master/LeafletMap.png?raw=true)

PROCET: 
{
**A relocation adviser has to make recommendations to person who has two job offers, one in Manhattan, New York and another in York, Toronto. The client is Parisian and would like to maintain their lifestyle.

*** They want to keep the habit of taking walks in gardens and *** is picky eater (they only eat at French restaurants), *** wants to be in a crime free environment and *** most of all away from congestion and public transport problems!

They are undecided as both jobs are equally attractive and money is not a problem for them. In addition both cities are very diverse and are the financial capitals of their respective countries. Though attracted to the “big city buzz”, comparable with Paris, with their prestigious hubs, a treasure cases of recreational activities, global cities are also prone to have high levels of crime, congestion and public transport problems than are deemed uncomfortable by the client. So we will compare the both the types of venues their neighbourhoods have to offer to determine their similarity to Paris and as these results only look at recreational activities, use the EIU’s World’s Most Liveable City index to weight in on the choice of: ***Whether Manhattan, New York or York, Toronto be a better home away from home from Reuilly, Paris?

***Interested and Affected Parties, IAPs.

Although at a Beginner Level, these Data Science tools and the shared data set allow for a powerful virtual

play ground for data exploration, so please do fork on Gitbub and collaborate!!!

This notebook is approachable enough to be replicated it can be used for collaboration and not only to expand the business problem of relocation options, as demonstrated here, but also be the stem for approaching other problems/opportunity which depend on the share data and methods used here.

***Data Sources & Types https://github.com/lindangulopez/Coursera_Capstone

The stem data was sourced from two tables , both of which have been converted to pandas dataframes then manipulated in this Lab. The data generated in this lab as well as relevant data generated in two previous Labs have been cleaned and stored as csv files with geo-location coordinates, their corresponding IPython notebooks with dataframes, as well as csv and json files plus in html format can be forked at Github

The data to be used, in the second part of the assignment, to cluster and compare the three cities are available on Github. In prior labs these two cleaned data sets were created, you can download them from Github they have a list of the following neighbourhoods with their geo-ordinates as well as venues, gleaned with the Folium App.

**Manhattan, New York & **York, Toronto Neighbourhoods.

**Data from this notebook as well as the accompanying data sets and outputs is also available on this Github repository

**Stem Data Sources:

**A Wikipedia Table:

The city of Paris is divided into twenty, administrative districts, referred to as Arrondissements. The number of the Arrondissement, the equivalent of boroughs, is indicated by the last two digits in of its postal codes, from 75001 up to 75020. The client lives in the 12th Arrondissement of Paris close to ‘Parc de Bercy’ and is attached to its park and the nearby restaurants. This borough is called Reuilly and is situated on the right bank of the river Seine. Each of Paris’ 20 boroughs are divided into 4 quartiers, the equivalent of neighbourhoods. He lives in the 49th quarter, which is the Bercy neighbourhood.

**Global Liveability Index Report:

This index assesses which locations around the world provide the best or the worst living conditions by quantifying the challenges that might be presented to an individual’s lifestyle in 140 cities worldwide. Each city is assigned a score for over 30 qualitative and quantitative factors across five broad categories of, which I did some catching up on from these articles:

**Stability **Health-care **Culture and environment **Education and Infrastructure

The New York, Toronto and Paris ranking by Global Liveability Index Ranking are given and will be used to adjust the machine learnng outcome, by not more than 15%.

The following maps and data were generated from the stem data sources:

***A Wikipedia Table:

List of Paris’s Neighborhoods, csv file. Map of Paris’s Neighborhoods, html file. Map of Reuilly’s Neighborhoods, html file. List of Reuilly’s Nearby Venues, csv file. List of up to Top 100 Reuilly Venues, csv file. List of up to Reuilly Venues Sorted, csv file. **Global Liveability Index Report:

Global Liveability Index, csv file This IPython notebook contains code and is annotated to answer question from the first part of the above assignment. The focus is on how to search for, select, mine and upload potential data as well as store and clean dataframes with pandas and nympy, using python3. The outcome and notebook itself, will be used in the creation of a deliverable, a blog post. The blog post and other deliverables are part of the later half of the assignment and will be available a week after this submission.

——-> ——-> ——-> ——-> ——-> ——-> ——-> ——-> ——->}
