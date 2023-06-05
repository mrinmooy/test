ABOUT MY WEB APPLICATION:

I have used the streamlit library and speech_recognition library in python. This web application converts Audio to text in real time as we speak and displays the text on screen. It makes use of the Google Speech-to-text API for this.

HOW TO RUN IT:

You do not need any special environment to run this web app. A simple internet connection and installing the streamlit and speech_recognition packages in python is sufficient. 
 use commands
 - pip install streamlit
 - pip install speechrecognition
in your command prompt if you are using Windows OS as i have used.

In order to start the app use the command "streamlit run app.py" in the terminal at your file's location or you can also type it in the terminal section if you are using VS code.

HOW TO USE IT:

You will see a button with the microphone emoji. Click on it to for the web page to start listening to you. Now you can speak. After you are done speaking your sentence the page will display your speech in text as "You said - (whatever you said)". If you want to run the application again, press the 'R' button on your keyboard and follow the same instructions as above.

ISSUES:

There are some issues with this application as it is a basic one.
1 - Sometimes it doesn't recognise your words and may skip some while displaying the text.
2 - It stops listening on its own after a few seconds. You cannot go on forever.
3 - It cannot recognise punctuations.