# Proposal for Semester Project

**Patterns & Trends in Environmental Data / Computational Movement
Analysis Geo 880**

| Semester:      | FS22                              |
|----------------|---------------------------------- |
| **Data:**      | Wild Boar Movement Data           |
| **Title:**     | Investigation of effects of scare-off measures on wild boars       |
| **Student 1:** | Valerie Arnaldi                 |
| **Student 2:** | Wenke Zimmermann                 |

## Abstract 
Wild boars cause great damage to agricultural crops. To prevent this, novel methods have been developed to deter the animals from entering the fields. In order to test the effect of one of these methods, an acoustic scare-off measure, wild boars in the Bernese Seeland were fitted with GPS collars and their space-time behavior was analyzed. The data collected with this method are investigated in the present work on the following questions.

## Research Questions
1.	Does habituation take place due to the scare-off measures aka do they leave the area or do they stay?
2.	If they get scared/when they are alarmed, do they escape in the same direction/move on as a "rotte" or do they spread?

## Results / products
We expect the wild boars to not stay longer in the field over time. And we expect them to stay together. One product will be a numeric evaluation. Another will be a map where the wild boar locations are shown.

## Data
We will use the data provided by ZHAW, Wildlife Managment Research Group. The dataset about wild boar locations including time stamps, overlapping observations as well as the agenda of the scare-off measure should suffice for the task.

## Analytical concepts
1.	First of all, we examine only the months in which the wild boar scare-off measure ran (i.e. April-October). And we will determine if a wild boar stays in the field or not. During the study period, we will compare the average duration per month and over all years the wild boars stayed. If they stay longer in the field over time, it indicates habituation to the scare-off.
2.	We determine at what speed and distance we can speak of 'fleeing'. Likewise, we have to find wild boars that escape in the same time window. Finally we calculate if all these escape in the same directions.

## R concepts
•	Filter and remove unneeded data
•	Detect wild boar locations within fields
•	Compute duration of stay
•	Detect indivuals belonging to a "rotte"
•	Check for trajectory similarity measures
•	Compute direction by azimut value

## Risk analysis
•	No exact calculations because of lacking granularity of the scare-off measure.

## Questions? 
<!-- Which questions would you like to discuss at the coaching session? -->
