---
layout: post
title: test
---
# Introduction
## Motivation
<p style='text-align: justify;'> It is not news to anyone that gender inequalities persist in modern society. This is due to centuries of oppression of the "weaker sex" in western cultures, by systematically denying women political, economic and intellectual power. Women have been stereotyped as caring and nurturing by nature to be relegated to housework and childcare, while men had access to higher education and financial independence. Although Women's Rights Movements have greatly improved women's conditions, inequalities subsist. Men still occupy most positions of power, whether it be in politics or private companies. This can be explained not only by the huge difference in the number of women versus men pursuing higher education (very noticeable even at EFPL) but also by implicit bias, through which women are seen as less competent than their male counterpart. </p>

<p style='text-align: justify;'> As differential treatment and stereotypes lead to differences in self-assessment and behavior, it is no surprise that researchers have found women tend to underestimate their abilities more than men and frequently experience "Imposter Syndrome", wherein they feel as though they are not qualified for their position and fear they will be discovered as such. </p>

<p style='text-align: justify;'> We are interested in the difference in self-confidence between men and women. Have oppression and stereotypes lead to women being less confident? If so, is this asymmetry noticeable through the way people express themselves? Furthermore, we would like to see how being a public figure such as politician, making a living by speaking in front of crowds, would influence self-confidence. Does being of a specific gender influence the percieved confidence of politicians? </p>

## Method

<p style='text-align: justify;'> 
  We used the Quotebank dataset from the year 2020, <b>ACHANGER SELON LE DATA SET QU'ON UTILISE</b> which consists of quotes taken from English speaking newspaper articles and web domains, with the speaker attributed to the quote by the Quobert framework. We assigned a confidence score to speakers, using BERT text similarity to compare the quotes to a phrases taken from <a href="https://www.researchgate.net/publication/26877357_Verbal_Expressions_of_Confidence_and_Doubt">"Verbal Expressions of Confidence and Doubt"</a>, a psychology paper published in 2009, which rated the percieved self-confidence of speakers through their expression. </p>
<p style='text-align: justify;'> The personal information of quoted persons such as their gender, birthyear and occupation was retrieved from the speaker attribute files provided by TAs. </p>

### Some statistics on the Speakers:
<p style='text-align: justify;'> 
  Let's start by looking at the gender distribution of speakers: 
  
  <img src = "https://user-images.githubusercontent.com/57099519/146043704-032417fc-0b6d-44a7-813b-252dbbff940f.png" alt = "gender distribution among speakers" >

  We can see above that a vast majority of the speakers are "females" and "males" (these categories include cis-gender and unspecified females and males), but speakers of other genders figure in our dataset as well. As our analysis is mainly focused of the difference between men and women we will exlude other genders from our study. 
  </p>
