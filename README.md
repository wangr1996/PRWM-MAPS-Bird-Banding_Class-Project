

---
title: "ReadMe"
author: "Rebecca Wang"
date: "December 7, 2018"
output: html_document
---
# PRWM-MAPS-Bird-Banding_Class-Project
Pearl River Wildlife Management MAPS (Monitoring Avian Productivity and Survivorship) Program


**Data Description** 
   In the face of climate change, habitat destruction, and deforestation, land bird populations across the biosphere are being challenged to adapt to ever-changing habitats and seek new ones that provide them with the resources they need to survive (Brown, 1991). Many monitoring programs have already been put in place to provide annual information on populations of landbirds, which show that there has been a significant decrease in many species. While such programs have helped to show general population trends, they do not offer information about primary demographic parameters such as productivity and survivorship of landbirds. Without this information, it is difficult to determine to what extent habitat destruction and degradation play a role in these declining populations, making it therefore difficult to determine the causal agents driving these population changes. In 1989, the Institute of Bird Populations (IBP) established the Monitoring Avian Productivity and Survivorship (MAPS) Program to provide primary demographic parameters (productivity and survivorship) of landbirds as well as monitor how habitat destruction and degradation such as deforestation and forest fragmentation have affected population trends in Neotropical migratory landbirds (2017 MAPS Manual pg. 6). 
	 Hurricane Katrina, which made landfall in August 2005 with category 2 winds, severely damaged the bottomland hardwood forest in the Pearl River basin.  The bird community changed drastically following the hurricane mainly due to the regrowth of dense understory, which led to an increased density of bird species that preferred that kind of habitat, including breeding migrants such as the Hooded Warbler (Brown et al., 2011).  Northern Cardinals (Cardinalis cardinalis) are birds abundant in the Southeast whose foraging behavior involves hopping on the ground or low bushes and sometimes higher in trees for seeds, insects and berries. Females have 2-3 broods per year and both parents feed nestlings (Kaufman). Northern Cardinal nests are typically well hidden in dense shrubs, vines or low trees (3’-10’) above ground. Hooded Warblers (Setophaga citrina) prefer forest undergrowth, nesting close to the ground and foraging for insects in low shrubs and bushes in the shadowy understory. Males typically return to occupy the same nesting territory as previous years whereas females move to different territories. Nest sites are chosen based on patches of deciduous shrubs within forest or along edge and usually 1-4’ above ground. Both parents feed nestlings and females usually have 2 broods per year (Kaufman). 
	 The two species I chose to focus on are the Hooded Warbler and Northern Cardinal as a subset of a larger dataset compiled by Dr. Donata Henry. In Louisiana, which is part of  the South-Central MAPS region (2017 MAPS Manual, p. 5), Hooded Warblers are considered breeding migrant species whereas Northern Cardinals represent resident species (Brown et al., 2011). 
   The data presented includes information about Hooded Warblers (HOWA) and Northern Cardinals (NOCA) that were captured in mist nets at a MAPS banding station in Honey Island Swamp. The column C indicates if it is a new capture (N) or recapture (R). The BAND number is the individual band number assigned to each individual. Many band numbers reappear as rows as duplicates because they were captured in multiple years or are recaptured the same year multiple times. SEX is male or female, BP is presence of absence of brooding patch. NET number ranges from 1-10. AGE, has numbers 1, 2, 4, 5, and 6, each indicating different stages of maturity. According to the MAPS manual, the number codes are as follows:
   4 - Local (L): A young bird incapable of sustained flight. 
   2 - Hatching Year (H): A bird capable of sustained flight and known to have hatched during the calendar year in which it is captured. 
   1- After Hatching Year (A): A bird known to have hatched before the calendar year in which it is captured: year of hatching otherwise unknown. 
   5 - Second Year (S): A bird known to have hatched in the calendar year preceding the year in which it is captured (known to be in its second calendar year of life).
   6 - After Second Year (O): A bird known to have hatched earlier than the calendar year preceding the year in which it is captured (known to be a tleast in its third calendar year); year of hatching otherwise unknown. 
  For the purpose of my analyses, I grouped these number codes into two categories, Juveniles and Adults. 4-Local and 2- Hatching Year are considered Juveniles or First Cycle Formative (FCF) and 1-After Hatching Year, 5-Second Year, and 6-After Second Year are grouped under Adults, or Definitive Cycle Basic (DCB). Adults. In summary, Juveniles (FCF) = 4 & 2 and Adults (DCB) = 1, 5, & 6. 
  
#*Goals and Hypotheses* 
Using this data set, I hope to answer the following two questions by first examining if patterns exist. 
1) What are the population trends between Male and Females of HOWA and NOCA over time (Year 2005-2014)? 
    I will examine general population trends first at the species level, then look population        trends at the sex level.
2) Are there differences in proportions of juveniles and adults over time for each species? 

**Hypotheses: Who Leaves? Who Comes Back?**
 Hatch Year Birds (2) in the Juvenile category could be predicted to leave the site on which they were born and disperse to other areas, in which case they would not be recaptured. 
 
 After Second Year birds (6) or Adults, on the other hand, may be well-established on the site and one might expect to recapture them at least once. Whether a bird is caught once or recaptured over multiple years is interesting and could provide us with different kinds of information. For one, it could indicate territoriality, site-dependence, or habitat quality. For example, if a bird that had been recaptured multiple years consecutively suddenly is not recaptured another year, habitat quality and availability of resources could be called into question. If we have background knowledge that following a disturbance such as Hurricane Katrina, that habitat quality declined, we might expect to see an absence of previous recaptured birds. 