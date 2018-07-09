## A simulation study of the sensitivity of mediation analysis to various underlying causal scenarios ##

In response to our study entitled **DNA methylation as a mediator of the association between prenatal adversity and risk factors for metabolic disease in adulthood** ([**Tobi et al. Sci Adv 2018**](http://advances.sciencemag.org/content/4/1/eaao4364)), Richmond, Relton and Davey Smith from the University of Bristol wrote an eLetter in which they argue that while we report methylation at specific CpGs as mediator of the impact of prenatal famine on metabolic traits, the underlying mechanisms likely is reverse-causation, where famine-induced metabolic traits drive changes in DNA methylation.

Here, we provide a set of _R_ scripts to explore the impact of four scenarios proposed by Richmond et al on the outcome of a statistical test of mediation. These simulations rebut the criticism that reverse-causation is a plausible explanation of our results, and support our original interpretation that the CpGs we identified as candidate mediators are either mediators themselves or a proxy for a causal underlying change in epigenetic regulation.

### Simulation of 4 scenarios (mediation, reverse-causation, driver, and confounding) ###
* [html version](http://htmlpreview.github.io/?https://github.com/molepi/SimulationStudy-Mediation/blob/master/simulation_2018_07_02.html)
* [R mark-down version](simulation%202018%2007%2002.rmd)


We provide a full description of our simulation studies in a manuscript posted on [**BioRxiv**](https://www.biorxiv.org/content/early/2018/07/05/362392), the abstract of which is: 
### Why mediation analysis trumps Mendelian randomization in population epigenomics studies of the Dutch Famine ###
Elmar W. Tobi, Erik W. van Zwet, L.H. Lumey, Bastiaan T. Heijmans

Our recent analysis of genome-wide DNA methylation data in men and women exposed to the Dutch Famine met passionate criticism by several researchers active on Twitter. It also prompted a more reasoned letter by Richmond and colleagues. At the core of the debate is the proper interpretation of findings from a mediation analysis. We used this method to identify specific DNA methylation changes that statistically provide a link between prenatal exposure to famine and adult metabolic traits. Our critics first argue that our results do not suggest mediation but reverse-causation, where famine-induced metabolic traits drive changes in DNA methylation. We rebut this scenario in a simulation study showing that our test of mediation was unlikely to become statistically significant in the case of reverse-causation. Some critics then argue that Mendelian randomization provides the sole path to correct inference. This belief misses a crucial point: DNA methylation, especially when measured in peripheral blood, is not likely to be a causal mediator from a biological point of view. It could however be a proxy of epigenetic regulation changes in specific tissues, for example at the level of transcription factor binding. If so, a Mendelian randomization approach using genetic variants affecting local DNA methylation in blood will be disconnected from the underlying biological mechanism and is bound to yield false-negative results. Our new simulation studies strengthen the original reasoning that the relationship between prenatal famine and metabolic traits is statistically mediated by specific DNA methylation changes while the specific molecular mechanism awaits elucidation.


_Appendix_
Richmond et al only considered scenarios of complete mediation and complete reverse-causation. For completeness sake, we also provide scripts simulating a partial mediation scenario and a partial reverse-causation scenario where famine also has an effect on DNA methylation through a independent mechanism. 

* [Appendix html: simulation of partial mediation and partial reverse-causation](http://htmlpreview.github.io/?https://github.com/molepi/SimulationStudy-Mediation/blob/master/simulation_2018_07_02_appendix.html)
* [Appendix R mark-down: simulation of partial mediation and partial reverse-causation](simulation%202018%2007%2002%20appendix.rmd)
