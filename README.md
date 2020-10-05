
# INFOSYS SOI


## ABOUT THE PROJECT {Vi}

In the view of current pandemic where everything has been pushed to **Digitisation**, We bring you **Vi aka Virtual Interviewer** which was made for Talent Acquisition Managers who in the current pandemic are facing a lot of difficulties in hiring candidates for their respective roles.

## PROBLEM 

So in the current scenario of digitization, the recruiters in every sectors are facing problem in hiring candidates for their respective roles. The problems occurs due to the physical absence of candidates in the interview where the recruiters used to study and analyse the candidate's postures, body language, way of speaking and many more. Now the situation has been different where everything from classroom to industries have been forced to the virtual conference platforms. So the interviews are now taking place online where candidate's may have the utmost advantage with them.

## Solution

So in view of this we propose you a platform called **Vi aka Virtual Interviewer** which tends to observe and analyse the candidate's emotions or facial expressions and classifies it and further gives a statistical output of the candidate.

## How does it Work ?

 - So our platform was made with flask and runs on a local server. The candidate is properly guided throughout the site and then finally the candidate takes the 45s video analysis test in response to the recruiter's question. 
 - The model that our platform uses is the Xception Model which was developed by google researchers. It further uses the popular FER2013 kaggle challenge dataset.
 - The following emotions are identified 

| | Emotions |
|--|--|
| 1 | Displease |
| 2 | Nervous |
|3|Unsure|
| 4 | Happy |
| 5 | Disinterested |
|6| Neutral|
| 7 | Confused |

So from our platform the recruiter's could get the statistical output of the candidate in terms of probability of emotion being displayed in various intervals of time and the most common emotion displayed by the candidate.
The platform aims to make their task much easier and more accurate so as to get the best candidates suitable for their role's.

## FUTURE GOALS

So our future goals is to analyse the text as well audio of the candidate with the help of the best frameworks. 
For the text we could use the NLTK packages and along with web mining we could easily figure out if the candidate has been copying the answers from any site or we could find the most common usage of words and then again give out a statistical output for the recruiter.
The audio analysis can be done via deep learning or teachable machine by google to judge the candidate's audio while answering the recruiter's questions.

**..We tried to make a difference and hope you all like it..**

Make sure to download the models for the project to work.
1. face_landmarks 
2. padding.pickle
3. Personality_traits_NN.h5
4. Personality_traits_NN
5. Personality_traits_SVM
