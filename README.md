# One Hit Wonder
 Kyle Icban's project for Professor Phil Chodrow in PIC16B

## Abstract
 This project will use sentiment analysis to explore musical trends over the decades. It will cover how to train a model to analyze the sentiment of a song (e.g. is a song happy or sad), how to acquire lyrical data from hundreds of songs, and how to graphical illustrate the patterns we hope to find. It will analyze trends in emotion from popular songs from different musical decades (70s, 80s, 90s, 00s, 10s, Present) to see how audience's taste in music has evolved over time. The goal from this project will be to answer questions like "What historical events could possibly explain these shifts (if any)?" and "How can artists use this information to produce music today?"

## Planned Deliverables
 There are two main deliverables: 1) a model that can determine the sentiment of a song based on its lyrics, 2) a visualization of how emotion in music has changed over time. Full success for the first point will be if we can achieve accuracy above 90% and for the second point will be to provide easily understandable analysis on musical trends. Its findings will be presented as a .pdf of a Jupyter Notebook and/or Powerpoint Presentation.

## Resources Required
 There will be two main datasets required: 1) an initial set of sentences to train a model on sentiment analysis in order to apply it music lyrics, 2) a database of songs, which decade their from, and their lyrics in the form of an array. For the first dataset, a potential dataset can be found https://www.kaggle.com/praveengovi/emotions-dataset-for-nlp. For the second database will have to be created by hand by looking up top songs from each decade, scraping it off the web, and then posting it to the database.

## Tools and Skills Required
 Machine learning, database management, and complex visualization are required for this project. Packages that could be used are `pandas`, `seaborn`, and `tensorflow`.

## What You Will Learn
 By completing this project, you will learn how to effectively acquire data and form a database, advanced machine learning techniques in `tensforflow`, and more advanced data visualization.

## Risks
 There are two main obstacles that could be worrisome. The first is easily acquiring the data of different songs. Ideally, this database will contain the top 50 songs from 6 different decades, so in total at least 300 songs. Finding a way to efficiently acquire the data will be the first issue. The second is to train a model that can accurately identify the emotion of a lyric. The idea is to use a preexisting dataset of sentences to train the model, and then applying this model to musical lyrics. However, lyrics are more nonsensical than formal sentences. The concern is how transferrable lyrics will be for the model in determining its emotion.

## Ethics
 1. ### What groups of people have the potential to benefit from the existence of our project?
     Historians and musicians could benefit from this project. For the sake of learning more about our world, it could be interesting for scholars to see how the world audience's music tastes respond to important events. Additionally, musicians could use these findings to tailor their music to suit the needs of the era. Whether it be appealing to a modern audience or targetting an older generations, musicians can learn what types of music their target audience enjoy the most.

 2. ### What groups of people have the potential to be harmed from the existence of our project?
     While it may not necessarily "harm" this group in the traditional sense, non-english speaking music listeners will not be able to use the findings from this project. It will be difficult to train the model in order to support different languages. In actuality, it would be better to make a different model to support different languages as to reduce complexity. This concern is particularly in response to the current trending popularity in the K-Pop genre. This something to keep in mind when interpreting the results of this project.

 3. ### Will the world become an overall better place because of the existence of our project?
     I would like to believe the world would be a better place because of this project. The goal of this project is to analyze the sentiment of songs over time. Learning more about history through a musical lens would only provide new perspective on our world. This project could be a great introduction for students and people to learn more about history through familiar musical terms. Additionally, rising musicians could use these findings to better tailor new songs to their audience. This project could potentially help create a rising star!
 
 ## Tentative Schedule
  - ### Two Week:
    - Acquire the data needed to complete the project.
  - ### Four Week:
    - Train the model and retrieve the sentiment of each song.
  - ### Six Week:
    - Perform data visualizations and finalize project details.