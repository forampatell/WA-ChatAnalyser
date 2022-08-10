
# WhatsApp-ChatAnalyser




## Description
Get an instant analysis of WhatsApp chats using WhatsApp Chat Analyser.You cannot only analyse the chats between you and your friend but also the chat of a group can be analysed using this tool.Basically, it is a Streamlit App deployed on Heroku platform.

## Libraries
pandas

numpy

matplotlib

streamlit

seaborn

urlextract

wordcloud

regex

## Implementation
Steps taken to implement the program-

- The first step we perform is to collect the data of chat/group chat and save the file in a project folder.
- From the data collected, we can now preprocess the data and extract important features from it.
- Perform text analysis by visualising the data.
- Plotting the graph of various quantities showcasing the text analysis , once visualising is done.
- Integrate the analysis with User Interface made on the Streamlit app.
- Finally, then the app can be deployed on Heroku cloud platform.


## Analysis
Stats Analysis that app provides for a group chat-

- Total No. of Messages.
- Total No. of words.
- Total No. of Media shared.
- Total No. of links shared.
- Most Busy Users.
- Wordcloud- An image of composed of words in which the size of a word defines frequency of that word.
- Most common words.
- Monthly Timeline. 
- Activity Maps- Most busy day, Most busy month.
## Steps to Run

- Run the following command in the terminal with python installed in your system to install every dependencies/libraries for this project.
```bash
  cd WA-chatAnalyser
  pip install -r requirements.txt
```
- To download the chat/group chat file, open WhatsApp application and then open the chat/group chat that you want to analyse. After doing so, click on the three dotted vertical line on the top-right corner of the chat and perform the following opertions-
```bash
  More-->Export chat-->without media-->share
```
- Click on the following link that will direct you to the app(already deployed on Heroku)-

    https://wa-analyser.herokuapp.com/
- Once the app is opened , upload the chat file in .txt format and browse it to analyse the chats.

## Deployment

##### Steps to deploy an app on Heroku-

```bash
  heroku login
```
```bash
  cd my project/
  git init
  heroku git:remote -a wa-analyser
```
```bash
  git add .
  git commit -am "make it better"
  git push heroku master

```
## Features

- Light/dark mode toggle
- Fullscreen mode


