GENERAL INFORMATION
Title: Data from: Network analysis of sea turtle movements and connectivity: a tool for conservation prioritization

Author and Contact: Connie Y. Kot, Duke University (connie.kot@duke.edu)

Data of data collection: 1996-2018

Geographic location of data: Global, Atlantic Ocean, Indian Ocean, Mediterranean Sea, Pacific Ocean

Keywords: betweenness, Centrality, closeness, graph theory, marine turtle, migratory, satellite telemetry, tracking

Language: English

Funding sources for study: Primary support was from the Global Ocean Biodiversity Initiative (GOBI) grant from the International Climate Initiative (IKI). The German Federal Ministry for the Environment, Nature Conservation and Nuclear Safety (BMU) supports this initiative based on a decision adopted by the German Bundestag.

Abstract:
Aim: Understanding the spatial ecology of animal movements is a critical element in conserving long-lived, highly mobile marine species. Analysing networks developed from movements of six sea turtle species reveals marine connectivity and can help prioritize conservation efforts.

Location: Global.

Methods: We collated telemetry data from 1,235 individuals and reviewed the literature to determine our dataset’s representativeness. We used the telemetry data to develop spatial networks at different scales to examine areas, connections, and their geographic arrangement. We used graph theory metrics to compare networks across regions and species and to identify the role of important areas and connections.

Results: Relevant literature and citations for data used in this study had very little overlap. Network analysis showed that sampling effort influenced network structure and the arrangement of areas and connections for most networks was complex. However, important areas and connections identified by graph theory metrics can be different than areas of high data density. For the global network, marine regions in the Mediterranean had high closeness while links with high betweenness among marine regions in the South Atlantic were critical for maintaining connectivity. Comparisons among species-specific networks showed that functional connectivity was related to movement ecology, resulting in networks composed of different areas and links.

Main conclusions: Network analysis identified the structure and functional connectivity of the sea turtles in our sample at multiple scales. These network characteristics could help guide the coordination of management strategies for wide-ranging animals throughout their geographic extent. Most networks had complex structures that can contribute to greater robustness, but may be more difficult to manage changes when compared to simpler forms. Area-based conservation measures would benefit sea turtle populations when directed towards areas with high closeness dominating network function. Promoting seascape connectivity of links with high betweenness would decrease network vulnerability.

DATA & FILE OVERVIEW:
1) Supplementary Materials: Kot_SeaTurtleNetwork_supp.pdf: supplementary file from Kot et al. Network analysis of sea turtle movements and connectivity: a tool for conservation prioritization.
- Appendix S1. Literature on sea turtle movements and connectivity
- Figure S1.1. Summary of relevant references from first literature search
- Table S1.2. Summary of the relevant references, by source, species, and method
- Table S.1.3. Bibliography for sea turtle movements and connectivity
- Appendix S2. Summary of all sea turtle telemetry data included in the current study
- Table S2.4. Primary data providers for the sea turtle tracking data used in this study
- Table S2.5. Details for each telemetry tagged sea turtle with tracking data
- Figure S2.6. Frequency histograms of the number of individuals and days tracked
- Figure S2.7. Frequency histograms of the number of individuals and marine regions
- Appendix S3. Marine region node details for each network
 -Table S3.8. Summary of tracking data and centrality metrics for each marine region node
- Appendix S4. Link details for each network
- Table S4.9. Summary of tracking data and centrality metrics for each link
- Appendix S5. Select network metrics explored in this study
- Table S5.10. Select network metrics calculated for 14 networks
- Figure S5.11. Box plots of regional network metrics created with tracking data
- Figure S5.12. Box plots of metrics for regional networks created with tracking data and based on neighbouring marine regions
- Figure S5.13 Box plots of metrics for species networks created with tracking data

2) Geographic Information System Files: Kot_SeaTurtNetwork_GIS.zip
Details for layers and fields:
- Polygon layers: summarized tracking data within a hexagonal grid using all six sea turtle species with data (all) and by species (name of layer = species). Fields: hex_id = hexagon id; sum_pt = number of points; species = sea turtle species data included.
- Polyline layers: links between the centroids of marine regions, used as edges within network diagrams for all six sea turtle species with data (all) and by species (name of layer = species). Fields: link_id = link unique ID; sum_rte = total number of routes; bet_tn = link betweenness metric calculated for the tracking data network; bet_nn = link betweenness metric calculated for the neighbours network; bet_sp = link betweenness metric calculated for the individual species network; species = sea turtle species data included.
- Points: centroids of the marine regions where sea turtles were tracked, used as nodes within network diagrams for all six sea turtle species with data (all) and by species (name of layer = species). Fields: marreg = marine region name; marreg_id = marine region unique ID; sum_ani = total number of animals; close_tn = node closeness (all) metric calculated for the tracking data network; close_nn = node closeness (all) metric calculated for the neighbours network; close_sp = node closeness (out) metric calculated for the individual species network; species = sea turtle species data included.

Use limitations: Please cite Kot et al. 2022 or contact the authors directly for more information.