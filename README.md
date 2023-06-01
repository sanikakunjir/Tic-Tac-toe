# Tic-Tac-toe
TIC-TAC-TOE two player game, using python, pusher, html, css.
software requirements-
Python
Flask
Pusher
HTML and CSS

Process-
pip install flask
pip install pusher

---Backend--
PUSHER:
-To integrate Pusher into your multiplayer game, you can follow these steps:
-Sign up or sign in to Pusher and go to the dashboard: Pusher Dashboard.
-Create a new Channels app by clicking on the "Create Channels app" button.
-Provide a name for your app and select the cluster closest to your location.
-Once your app is created, you'll be redirected to the app dashboard. Take note of the following information:
	App ID
	Key
	Secret
	Cluster
-To enable client events, click on "App settings" in the sidebar.
-Scroll down to the "Enable client events" section and toggle the switch to enable client events.
-Update the app settings by clicking on the "Update app settings" button.
-Now you have set up your Pusher Channels application and enabled client events. 
You can use the App ID, Key, Secret, and Cluster information to connect your 
client application to Pusher and start using its real-time capabilities.
- Create a file app.py and paste the code into it.

--Frontend--
-create a folder templates and create two file play.html and index.html and paste the code in it.

--testing--
- now you can test the code by runing it on the terminal by:
	python -m venv env
	env\Scripts\activate 
	set FLASK_APP=app.py
	flask run 
- to deactivate:
	deactivate
