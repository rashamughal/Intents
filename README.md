This project is implementing Implicit Intent

Code Overview

MainActivity.java
Implicit Intent: The main logic for creating and sending the implicit intent is implemented in MainActivity.
Text Sharing: The text from the TextView is passed as extra data in the intent.

MainActivity2.java, MainActivity3.java, MainActivity4.java
Receiving Intent: These activities receive the intent and extract the shared text to display it.

AndroidManifest.xml
Intent Filters: Defines how each activity can respond to the implicit intent.


Usage
MainActivity:

Contains a TextView displaying the text to be shared.
A button that triggers an implicit intent to share the text.
Choose an Activity:

When the button is clicked, an activity chooser dialog appears, allowing the user to select one of the available activities (MainActivity2, MainActivity3, or MainActivity4).
Receiving Activity:

The selected activity will display the shared text from MainActivity.
