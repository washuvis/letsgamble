# Let's Gamble

This repo contains the experiment data, stimuli, and setup analysis scripts from our Let's Gamble project. The goal is to *uncovering the impact of visualization on risk perception and decision-making*.

**Synopsis**

Data visualizations are standard tools for assessing and communicating risks. However, it is not always clear which designs are optimal or how encoding choices might influence risk perception and decision-making. This project reports the findings of a large-scale gambling game that immersed participants in an environment where their actions impacted their bonuses. Our study participants chose to either enter a draw or receive a guaranteed amount of money based on a visualization that showed the likelihood of winning. For each experiment, participants played 25 lottery sheets and were eligible to win prizes of up to \$10. 
* Experiment 1 focused on a proportion judgment task, where participants estimated the probability depicted by the visualization. Each participant was assigned one of five different types of widely used visualizations before entering their lottery choice. 

* In Experiment 2, we removed the proportion judgment task to focus on the direct impact of visualization on lottery decisions. We also included a text condition for comparison and evaluation.

By measuring risk perception and observing decision-making, we showed that icon arrays tended to elicit economically sound behavior. We also found that people were more likely to gamble when presented area proportioned triangle and circle designs. Using our results, we model risk perception and discuss how our findings can improve visualization selection.


## Data
The are a total three data files:
* Experiment 1: Graphical Perception using the lottery game for the IEEE InfoVis 2019 Poster [**Icons are Best: Ranking  Visualizations for Proportion  Estimation.**](https://github.com/washuvis/letsgamble/blob/master/VIS2019_poster.pdf) Zhengliang Liu, Melanie Bancilhon, and Alvitta Ottley. The data were collected in two rounds and combined for the poster submission:
  * Exp1-round1.csv (105 participants)
  * Exp1-round2.csv (300 participants)
  
  **Paper Correction** The poster write up includeed a typographic error. It states "We analyzed 406 participants' decisions over real monetary gains, resulting in 10,150 observations". However, there was a total of 405 participants with 25 observations each (405 x 25 = 10,150). 

* Experiment 2: Decision-Making using the lottery game for the IEEE InfoVis Short Paper Submission **Let's Gamble: How a Poor Visualization Can Elicit Risky Behavior** Melanie Bancilhon, Zhengliang Liu, and Alvitta Ottley.
  * Exp2.csv (300 participants) 

## Stumili
The 5 visualization designs we used in the experiments can be found in [stimuli.pdf](https://washuvis.github.io/letsgamble/stimuli.pdf).

## Analysis
A script for the analyses can be found in [analysis/](https://github.com/washuvis/letsgamble/blob/master/analysis/).
* [IEEE InfoVis Short Paper Submission Analysis Script](https://washuvis.github.io/letsgamble/analysis/short_paper_analysis.html) 


