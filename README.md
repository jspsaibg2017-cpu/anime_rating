# Anime Ratings Case Study

## Supervised Learning Regression Project: Anime Rating

**Problem Statement**

**Business Context**



Streamist is a streaming company that streams web series and movies for a worldwide audience. Every content on their portal is rated by the viewers, and the portal also provides other information for the content like the number of people who have watched it, the number of people who want to watch it, the number of episodes, duration of an episode, etc.



They are currently focusing on the anime available in their portal, and want to identify the most important factors involved in rating an anime. You as a data scientist at Streamist are tasked with identifying the important factors and building a predictive model to predict the rating on an anime.



Objective

To analyze the data and build a linear regression model to predict the ratings of anime.



Key Questions

What are the key factors influencing the rating of an anime?

Is there a good predictive model for the rating of an anime? What does the performance assessment look like for such a model?

Data Description

Each record in the database provides a description of an anime. A detailed data dictionary can be found below.



Data Dictionary



title - the title of anime

description - the synopsis of the plot

mediaType - format of publication

eps - number of episodes (movies are considered 1 episode)

duration - duration of an episode in minutes

ongoing - whether it is ongoing

sznOfRelease - the season of release (Winter, Spring, Fall)

years\_running - number of years the anime ran/is running

studio\_primary - primary studio of production

studios\_colab - whether there was a collaboration between studios to produce the anime

contentWarn - whether anime has a content warning

watched - number of users that completed it

watching - number of users that are watching it

wantWatch - number of users that want to watch it

dropped - number of users that dropped it before completion

rating - average user rating

votes - number of votes that contribute to rating

tag\_Based\_on\_a\_Manga - whether the anime is based on a manga

tag\_Comedy - whether the anime is of Comedy genre

tag\_Action - whether the anime is of Action genre

tag\_Fantasy - whether the anime is of Fantasy genre

tag\_Sci\_Fi - whether the anime is of Sci-Fi genre

tag\_Shounen - whether the anime has a tag Shounen

tag\_Original\_Work - whether the anime is an original work

tag\_Non\_Human\_Protagonists - whether the anime has any non-human protagonists

tag\_Drama - whether the anime is of Drama genre

tag\_Adventure - whether the anime is of Adventure genre

tag\_Family\_Friendly - whether the anime is family-friendly

tag\_Short\_Episodes - whether the anime has short episodes

tag\_School\_Life - whether the anime is regarding school life

tag\_Romance - whether the anime is of Romance genre

tag\_Shorts - whether the anime has a tag Shorts

tag\_Slice\_of\_Life - whether the anime has a tag Slice of Life

tag\_Seinen - whether the anime has a tag Seinen

tag\_Supernatural - whether the anime has a tag Supernatural

tag\_Magic - whether the anime has a tag Magic

tag\_Animal\_Protagonists - whether the anime has animal protagonists

tag\_Ecchi - whether the anime has a tag Ecchi

tag\_Mecha - whether the anime has a tag Mecha

tag\_Based\_on\_a\_Light\_Novel - whether the anime is based on a light novel

tag\_CG\_Animation - whether the anime has a tag CG Animation

tag\_Superpowers - whether the anime has a tag Superpowers

tag\_Others - whether the anime has other tags

tag\_is\_missing - whether tag is missing or not

