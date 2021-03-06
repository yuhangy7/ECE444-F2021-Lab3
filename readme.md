Yuhang Yan

This repo is a clone of https://github.com/nelaturuk/education_pathways

## Activity 1
![alt text](https://github.com/Hoowolf/ECE444-F2021-Lab3/blob/main/pictures/act1.jpg)

## Activity 2
![alt text](https://github.com/Hoowolf/ECE444-F2021-Lab3/blob/main/pictures/act2.jpg)

## Activity 3
![alt text](https://github.com/Hoowolf/ECE444-F2021-Lab3/blob/main/pictures/act3.jpg)

## Activity 4
![alt text](https://github.com/Hoowolf/ECE444-F2021-Lab3/blob/main/pictures/act41.jpg)

![alt text](https://github.com/Hoowolf/ECE444-F2021-Lab3/blob/main/pictures/act42.jpg)


## Functional Requirement

Users should be able to search courses by instructor's name.

**Improvement:** Change the current search tool to include instructor's name as a search keyword. 



## Non-Functional Requirement

(Performance) Users should get the result of a search fast.

**Improvement**: Make sure courses related information are stored appropriately in a database, so we can get information from database quickly.




# CARTE Education Pathways

## Description
Welcome to CARTE's in-development tool for course selection at UofT. Education Pathways allows for more intelligent course searching, by matching not just the terms you search, but ones relevant to them. The more terms you search for, the more relevant your results will be! Even try searching across disciplines for the courses that best cover each.

Whatever year you are looking for, Education Pathways will also suggest courses in earlier years that will best help you to prepare. To get the most out of this, try searching for courses in a later year and see what is suggested for your current one.

We are looking for feedback to improve Education Pathways and make it more useful for students. If you have ideas or suggestions, please email us!

## Setup Instructions

### With Docker



## Repository files:

`./Procfile ./wsgi.py` *tells gunicorn how to run the program*

`./environment.yml  ./requirements.txt` *specifies python requirements for anaconda and pip respectively*

`./__init__.py` *main flask code*

`./readme.md` *this file*

`./resources:` *contains datasets used in the program*

`course_vectorizer.pickle df_processed.pickle`

`course_vectors.npz       graph.pickle`

`./static:` *contains any static elements of the webpage, in this case just the CARTE logo*
`CARTE_logo.jpg`

`./templates:` *contains flask templates for rendering HTML*

`_formhelpers.html course.html       index.html        results.html`
