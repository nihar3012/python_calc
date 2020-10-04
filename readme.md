MVC is a software approach that separates application logic from presentation. In practice, it permits your web pages to contain minimal scripting since the presentation is separate from the PHP scripting.

1> Model

The Model represents your data structures. Typically, your model classes will contain functions that help you retrieve, insert and update information in your database.

The model is responsible for managing the data of the application. It responds to the request from the view and it also responds to instructions from the controller to update itself.

2> View

The View is information that is being presented to a user.

It displays all the records fetched within the model. View never interacts with model; controller does this work (communicating with model and view).

3> Controller

The Controller serves as an intermediary between the Model, the View, and any other resources needed to process the HTTP request and generate a web page.

The controller is responsible for responding to the user input and perform interactions on the data model objects. The controller receives the input, it validates the input and then performs the business operation that modifies the state of the data model.

Controller interacts with model through the getAll() method which fetches all the records displayed to the end user.

4> What is PyQt5?


PyQt is a library that lets you use the Qt GUI framework from Python. Qt itself is written in C++. By using it from Python, you can build applications much more quickly while not sacrificing much of the speed of C++.


Steps

* pip3 install pyqt5

* The user performs an action or request (event) on the view (GUI).

* The view notifies the controller about the user’s action.

* The model processes the controller query, performs the required operations, and returns an answer or result.

* The controller gets the user’s request and queries the model for a response.The controller receives the model’s answer and updates the view accordingly.
  The user finally sees the requested result on the view




