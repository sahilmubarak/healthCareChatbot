(-*-)Steps I followed to Get the Project working on Windows 10------------------------------------------------

1. Go to the directory of the project

2. Open Git Bash Terminal there.

3. Install needed dependencies and plugins

4. cd to the "\rasabot" directory in the same Terminal

5. Run the model with "rasa run -m models --endpoints endpoints.yml --port 5002 --credentials credentials.yml"

6. Open a new Bash Terminal in "\web_app"

7. Run the Flask app there using "flask run"

8. Wait for both the terminals to finish loading

(-*-)Then after the RASA server and flask app are online.-----------------------------------------------------

9. Copy the port on which the app is running (for me it was "http://127.0.0.1:5000/")

10. Open your browser and paste this in the URL

(-*-) Start Chatting------------------------------------------------------------------------------------------

--------------------------------------------------------------------------------------------------------------

*If there is any problem with the flask app, the webpage will not load*

*If there is any problem with the rasa server then the web page will load but you wont get any replies from the bot*

*I faced an issue with the server,
the rasa version of the trained model was not compatible with the one I had installed,
i re-trained the model with the new rasa version and everything was fine*
--------------------------------------------------------------------------------------------------------------