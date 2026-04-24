# Investigating anuran biodiversity across latitude bands

## Background
Amphibians are one of the most threatened classes of organisms in the animal kingdom, with the list of species at risk of extinction continuing to grow (Stuart et al., 2004, IUCN, 2004, IUCN, 2023). As habitat loss and climate change continue to alter ecosystems, amphibians are increasingly exposed to suboptimal conditions, including drier environments that push species to their physiological limits across the globe (Wu et al., 2024) Anurans are the largest amphibian order, comprising approximately 88% of all recorded amphibian species (IUCN, 2023). As indicator species, frogs serve as markers for ecosystem health, making their distribution patterns of particular interest (Simon et al., 2011)

To assess biodiversity patterns of anurans, the current analysis primarily aims to determine whether anuran species follow the latitudinal diversity gradient (LDG). To explore this question, barcode index numbers (BIN) from  The Barcode of Life Data Systems (BOLD) are used as a proxy for species. Prior to determining BIN richness, an important prerequisite analysis explores sampling completeness of anurans across different latitude bands. 

The latitudinal diversity gradient describes a widespread pattern in global species richness, where biodiversity peaks in the tropics and declines with increasing distance from the equator (Hawkins, 2001). This pattern has been observed in anurans as well, supporting the prediction that if species richness is highest at the equator, there will be a negative relationship between species richness and distance from the equator (Wiens et al., 2009). If this pattern is not observed, it may be due to incomplete sampling data reported in BOLD, or an indication of a change in typical diversity patterns for anuran species that warrants further investigation.

## Methods
![Figure 0](figs/figure_0)

## Results

### Analysis results reveal insights about sampling and species richness patterns at different latitudes

![Figure 1](figs/figure_1)
Figure 1. Distribution pattern of all recorded anuran specimens in BOLD, by latitude band. The figure indicates global sampling of anurans. Specimen counts are higher near the equator and in the southern hemisphere, particularly in South America. Additionally, specimens decline moving away from the equator, especially in the northern hemisphere. 

![Figure 2](figs/figure_2)
Figure 2. Rarefaction curves for the median of each latitude band. The number of samples per latitude band is uneven, shown by the extreme differences in the curves. Latitudes 62.7°, 53.4°, and 42.6° have very little sampling coverage, while 38.0°, 33.3°, and 43.0° seem to reach almost complete coverage. 

![Figure_3](figs/figure_3)
Figure 3. Linear regression where estimated species richness was log-transformed. A non-significant (p = 0.279) negative relationship between estimated asymptotic species richness and distance from the equator. 

## Discussion

### Low sampling coverage and latitude band widths may explain the weak association
Although the trend was not significant, the relationship between estimated asymptotic richness and distance from the equator followed the negative relationship that was predicted. A limitation of the analysis was the incomplete sampling in many of the latitude bands, which may have led to an unreliable estimate of asymptotic species richness. Of the 42,000 records in the original data, many records were missing geographical data. If latitude and longitude data were imputed, it may be sufficient for rarefaction, or estimating asymptotic richness. Additionally, the latitude band of 10° was arbitrarily chosen for this analysis. An interesting subsequent analysis may look at the ideal latitude band-width to use in a similar study.

### Geographic range shifts of anurans due to habitat loss and climate change may explain the weak association
As habitat fragmentation and climate change continue to threaten anuran species’ existence, it may be the case that the weak association between latitude and anuran species richness is due to expanding geographic ranges. Colletta and Vasconcelos (2025) describe possible changes in geographic range that may occur for some Brachycephalidae anurans. They predict that while many species will likely go extinct due to ecosystem changes, some may have the capacity to expand into other regions. An investigation of ranges leveraging predictive models could be used to explore whether anuran species-richness patterns are deviating from the expected LDG, and determine whether species are more likely to expand their ranges or go extinct.

## Acknowledgements
I would like to thank the following peers for their valuable feedback, insights, and support throughout the development of this analysis. Their thoughtful suggestions helped shape both the direction of the analysis and the clarity with which it was presented: Eva, Cyrus, Liona, Sharon, Sabrina and Rebekah.

## References
Coletta, B. B. D., & Vasconcelos, T.S. (2025). Climate change implications on the potential distribution ranges of direct-development anurans (Brachycephalidae) in the Brazilian Atlantic forest. Austral Ecology, 50, e70112. https://doi.org/10.1111/aec.70112 

IUCN. (2023). State of the World’s Amphibians 2023: Second Global Amphibian Assessment (GAA2). https://nc.iucnredlist.org/redlist/resources/files/1696400756-SOTWA_GAA2_04Oct2023.pdf 

Simon N. Stuart et al., (2004). Status and Trends of Amphibian Declines and Extinctions Worldwide. Science (306). 1783-1786. https://www.science.org/doi/10.1126/science.1103538 

Hawkins, B. A., (2001). Ecology’s oldest pattern? Trends in Ecology & Evolution, 16(8), 470. https://www.cell.com/trends/ecology-evolution/fulltext/S0169-5347(01)02197-8

Wu, N.C., Bovo, R.P., Enriquez-Urzelai, U. et al. (2024). Global exposure risk of frogs to increasing environmental dryness. Nat. Clim. Chang. 14, 1314–1322. https://doi.org/10.1038/s41558-024-02167-z 

Simon, E., Puky, M., Braun, M., & Tóthmérész, B. (2011). Frogs and toads as biological indicators in environmental assessment. In J. L. Murray (Ed.), Frogs: Biology, ecology and uses. https://radfordphenology.weebly.com/uploads/1/1/6/6/116681661/14-simon-et-al-2011b.pdf

Wiens, J. J., Sukumaran, J, Pyron, R. A, Brown, R. M. (2009). Evolutionary and biogeographic origins of high tropical diversity in old world frogs (ranidae). Evolution, 63(5), 1217 - 1231. https://doi.org/10.1111/j.1558-5646.2009.00610.x 




