---
title: "PairAssignment 02: Research Proposal"
authors: "Björn Boening, Laurence Hendry, Cody Koebnick"
date: "20. Oktober 2015"
output: ioslides_presentation
---

## 1. Introduction: 
## 1.A Research Question

My topic is about global anti-piracy measures. Thereof, my broad research question is: What is the influence of predictive models on piracy?

A yet provisionally, but more specific research question is: Do predictive models have a 
greater impact on anti-piracy measures when a hot spot for piracy can be identified (1), or do 
predictive models impact naval forces deployment (2)?

Piracy as an act of robbery or criminal violence against vessels is the key concept of my 
research project. The United Nations’ International Law Commission has described piracy 
not only happening at High Sea, but also in the air. My project focuses on maritime piracy, 
and thus only takes into account vessels on water. The International Chamber of 
Commerce’s International Maritime Bureau (IMB) has defined in 1992 piracy as “the act of 
boarding any vessel with an intent to commit theft or any other crime, and with an intent or 
capacity to use force in furtherance of that act”. The United Nations Convention on the Law 
of the Sea (1982) has defined piracy as “any illegal acts of violence, detention, or any act of 
depredation’ committed for private ends, in a ship-to-ship conflict that occurs in the high 
seas.”

## 1.B Relevance of topic

The global shipping routes are highly important for trading. Even if piracy attacks so far were 
unable to stop global trade, they are a (potential) threat not only for the shipping crew but as 
well can bear high costs in case of ransom notes. The (cost intensive) deployment of 
international naval forces in Somalia show how serious the threat is for some countries.

## 2. Literature & theoretical approach
## 2.A Literature on the Topic - Gaps in Literature

Gladly some work has been done by other researchers already. Stephanie Hanson (2009) 
from the Council on Foreign Relations, for instance, published a piece which describes the 
nature and severity of piracy within the recent decades. She concludes that global piracy has 
been rising over the last decades. However, many authors agree that the deployment of 
naval forces has cut off this rising (Hanson 2009, Twyman-Ghoshal 2014, Kiourktsoglou
2011). We conclude, that depending on the spot and the pirates’ equipment the threat can be
tackled by maritime policing. As deployment of naval police and military forces is very 
expensive, the potential of prediction is very high. 

So far some researchers examine patterns of piracy in order to predict hotspots (Daxecker 
2015, Gurram 2015, Marchione 2014). We hope to enter this field of literature by adding 
valuable data and a solid model.

## 3. Methodological Approach
## 3.A How to Answer the Question

Among other reasons, for instance socio-economic factors, piracy can be best explained by 
variables describing the ship’s characteristics (for instance fully loaded with promising cargo), 
and presence of law enforcement (Twyman-Ghoshal 2014). Thereof, we assume that a 
hotspot will most likely evolve when the level of law enforcement is low and bypassing ships 
can be easily spotted before they reach the actual hotspot (distance to coast).

Furthermore we have to distinguish between local differences. The nature and severity of
piracy differs considerably around the globe. Over years South East Asia was known as the 
hotspot for piracy. Recently Somalia has emerged as a severe piracy hotspot.

## 3.B Which Data, Variables and Strategies will be used and why

We have time-series cross-sectional micro-level data from different sources. Since 1992 the 
IMB collects pirate attacks in its yearly reports with detailed information on the attack, the 
pirates and the vessel. Not at all time the quality is the same. To get the best picture 
available, we add data from the U.S. National Geospatial Intelligence Agency.

So far there is no real model developed. However, important variables can already be 
described. For instance we want to design several categorical variables, for instance ship 
class, type of attack (low intensity to high intensity), type of cargo (promising to less 
promising), distance to coast (close to far away), and variables for different regions in the 
world. Furthermore, continuous variables for location, time, and number of attacks will be 
provided. The more detailed the data we compile is, the better our prediction model can be. 
Furthermore we try to add data which is not correlated with other covariates, which can be 
weather data for instance.



## Slide with Bullets

- Bullet 1
- Bullet 2
- Bullet 3

## Slide with R Code and Output

```{r}
summary(cars)
```

## Slide with Plot

```{r, echo=FALSE}
plot(cars)
```

